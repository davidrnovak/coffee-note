<script>
  import TopCardTitle from "./topCardTitle.svelte";

  export let itemLabel;
</script>

<TopCardTitle/>
<div class="flex flex-col justify-between gap-12 p-2 md:p-8 md:border-2 md:border-text-200 md:flex-row">
  <ul class="w-full flex flex-col gap-4">
    <li class="flex justify-between items-end w-full">
      <p class="font-bold no-white-space">Name:</p>
      <span class="w-full mx-2 border-b border-dashed border-text-100"></span>
      <p class="no-white-space bg-primary-300 px-2">Diego Bermudez {itemLabel.name}</p>
    </li>
    <li class="flex justify-between items-end w-full">
      <p class="font-bold no-white-space">Origin:</p>
      <span class="w-full mx-2 border-b border-dashed border-text-100"></span>
      <p class="no-white-space bg-primary-300 px-2">Colombia</p>
    </li>
    <li class="flex justify-between items-end w-full">
      <p class="font-bold no-white-space">Roast Date:</p>
      <span class="w-full mx-2 border-b border-dashed border-text-100"></span>
      <p class="no-white-space bg-primary-300 px-2">12/25/2022</p>
    </li>
    <li class="flex justify-between items-end w-full">
      <p class="font-bold no-white-space">Dose:</p>
      <span class="w-full mx-2 border-b border-dashed border-text-100"></span>
      <p class="no-white-space bg-primary-300 px-2">30g</p>
    </li>
    <li class="flex justify-between items-end w-full">
      <p class="font-bold no-white-space">Brewer:</p>
      <span class="w-full mx-2 border-b border-dashed border-text-100"></span>
      <p class="no-white-space bg-primary-300 px-2">April Brewer</p>
    </li>
    <li class="flex justify-between items-end w-full">
      <p class="font-bold no-white-space">Temperature:</p>
      <span class="w-full mx-2 border-b border-dashed border-text-100"></span>
      <p class="no-white-space bg-primary-300 px-2">94C</p>
    </li>
    <li class="flex justify-between items-end w-full">
      <p class="font-bold no-white-space">Grind Size:</p>
      <span class="w-full mx-2 border-b border-dashed border-text-100"></span>
      <p class="no-white-space bg-primary-300 px-2">Coarse</p>
    </li>
    <li class="flex justify-between items-end w-full">
      <p class="font-bold no-white-space">Additional:</p>
      <span class="w-full mx-2 border-b border-dashed border-text-100"></span>
      <p class="no-white-space bg-primary-300 px-2">28 clicks</p>
    </li>
  </ul>
  <ul class="w-full flex flex-col gap-4">
    <li class="flex justify-between items-end w-full">
      <p class="font-bold no-white-space">Roaster:</p>
      <span class="w-full mx-2 border-b border-dashed border-text-100"></span>
      <p class="no-white-space bg-primary-300 px-2">Manhattan Coffee Roaster</p>
    </li>
    <li class="flex justify-between items-end w-full">
      <p class="font-bold no-white-space">Process:</p>
      <span class="w-full mx-2 border-b border-dashed border-text-100"></span>
      <p class="no-white-space bg-primary-300 px-2">Washed thermal shock</p>
    </li>
    <li class="flex justify-between items-end w-full">
      <p class="font-bold no-white-space">Off Roast:</p>
      <span class="w-full mx-2 border-b border-dashed border-text-100"></span>
      <p class="no-white-space bg-primary-300 px-2">2 Weeks</p>
    </li>
    <li class="flex justify-between items-end w-full">
      <p class="font-bold no-white-space">Total:</p>
      <span class="w-full mx-2 border-b border-dashed border-text-100"></span>
      <p class="no-white-space bg-primary-300 px-2">500g/ml</p>
    </li>
    <li class="flex justify-between items-end w-full">
      <p class="font-bold no-white-space">Accessories:</p>
      <span class="w-full mx-2 border-b border-dashed border-text-100"></span>
      <p class="no-white-space bg-primary-300 px-2">None</p>
    </li>
    <li class="flex justify-between items-end w-full">
      <p class="font-bold no-white-space">Additional:</p>
      <span class="w-full mx-2 border-b border-dashed border-text-100"></span>
      <p class="no-white-space bg-primary-300 px-2">Third Wave Water</p>
    </li>
    <li class="flex justify-between items-end w-full">
      <p class="font-bold no-white-space">Grinder:</p>
      <span class="w-full mx-2 border-b border-dashed border-text-100"></span>
      <p class="no-white-space bg-primary-300 px-2">Comandante C40 MK4</p>
    </li>
  </ul>
</div>

<style>
  .no-white-space {
    white-space: nowrap;
  }
</style>