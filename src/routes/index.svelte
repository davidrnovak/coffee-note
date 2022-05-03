<script>
  import RecipeList from "../components/recipeList/recipeList.svelte";
  import RecipeDisplay from "../components/recipeDisplay.svelte";
</script>

<div class="grid--coffee p-2">
  <RecipeList/>
  <RecipeDisplay/>
</div>

<style>
  .grid--coffee {
    display: grid;
    grid-template-columns: 1fr;
  }

  @media (min-width: 30rem) {
    .grid--coffee {
      grid-template-columns: 0.4fr 1fr;
      padding: 2rem;
    }
  }
</style>