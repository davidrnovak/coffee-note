<script>
  export let recipeItem;
</script>

<div class="mx-2">
  <ul>
    <li class="flex flex-col py-6 border-b border-dashed border-text-100 hover:bg-primary-300">
      <a href="Yay" class="flex justify-between items-center px-2">
        <p class="text-base">{recipeItem.name} - {recipeItem.brewer}</p>
        <svg width="32" height="18" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M.5 10h27.086l-6.293 6.293 1.414 1.414L31.414 9 22.707.293l-1.414 1.414L27.586 8H.5v2Z" fill="#242526"/></svg>
      </a>
    </li>
  </ul>
</div>
