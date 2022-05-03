<script>
  import supabase from "$lib/db";
  import { onMount } from "svelte";

  import TopCard from "./cards/topCard.svelte";
  import LowerCard from "./cards/lowerCard.svelte";

  let recipeItemLabels = [];

  onMount( async () => {
    let { data, error } = await supabase.from('recipes').select('*');
    recipeItemLabels = data;
    console.log(recipeItemLabels);
  });
</script>

<section class="md:pl-8">
    <TopCard itemLabel={recipeItemLabels}/>
  <LowerCard/>
</section>