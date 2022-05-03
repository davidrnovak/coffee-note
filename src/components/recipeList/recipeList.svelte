<script>
  import supabase from "$lib/db";
  import { onMount } from "svelte";
  import ListItem from "../recipeList/listItem.svelte";
  import ButtonPrimary from "../buttons/buttonPrimary.svelte";
  import ButtonSecondary from "../buttons/buttonSecondary.svelte";


  let listItemLabels = [];

  onMount( async () => {
    let { data, error } = await supabase.from('recipes').select('*');
    listItemLabels = data;
    console.log(listItemLabels);
  });
</script>

<section class="hidden w-full h-full md:border-r-2 border-dashed border-gray-dashed md:flex md:flex-col md:pr-8">
  <h2 class="mb-4">Recipes</h2>
  {#each listItemLabels as recipeItem }
    <ListItem recipeItem={recipeItem}/>
  {/each}
  <div class="flex flex-col gap-4 my-16 md:flex-row">
    <ButtonPrimary/>
    <ButtonSecondary/>
  </div>
</section>

<style>
  h2 {
    font-weight: 900;
    font-size: 2rem;
  }
</style>