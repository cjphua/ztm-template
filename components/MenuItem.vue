<template>
  <div class="text-center">
    <div><img src="crispy-chicken.jpg" class="border border-gray p-5" alt="" /></div>
    <h4 class="font-oswald uppercase text-2xl mt-5">Crispy Chicken</h4>
    <p class="font-light text-gray-500 my-2">
      Chicekn breast, Chili Sauce, Tomatoes, colesaw
    </p>
    <p class="mt-5 mb-8">
      <span
        class="rounded rounded-lg bg-amber-800 text-yellow-400 font-oswald font-bold text-xl px-5 py-2"
        >RM11.99</span
      >
    </p>
    <button class="font-oswald uppercase border py-2 px-3">Add To Cart</button>
  </div>
</template>

<script>
export default { props: ['item'] };
</script>
