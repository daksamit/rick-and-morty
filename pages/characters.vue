<template>
  <hero class="bg-white font-serif">
    <header class="px-12 h-32 -mb-32 relative">
      <h1 class="text-center text-4xl px-6 py-12">Rick and Morty App</h1>
    </header>

    <div class="w-full flex flex-wrap md:h-screen pt-32">
      <div class="pt-6 md:pt-0 w-full md:flex-1 md:order-last">
        <img
          src="https://images.unsplash.com/photo-1547740105-f99661aef734?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=948&q=80"
          class="w-full h-full object-cover"
        />
      </div>
      <div
        class="
          w-full
          p-6
          pb-12
          md:p-12
          md:w-5/12
          flex
          justify-center
          items-center
          relative
        "
      >
        <div class="w-full relative text-center py-12 px-12 md:p-0">
          <h1 class="text-5xl mb-4">Character's lists</h1>
          <ul class="text-2xl list-decimal text-center">
            <li>Rick</li>
            <li>Morty</li>
            <li>Beth</li>
            <li>Sam</li>
            <li>Jerry</li>
          </ul>
        </div>
      </div>
    </div>

    <div
      class="
        w-full
        flex
        -mt-6
        pt-32
        pb-24
        px-12
        text-center
        bg-black
        text-white
      "
    >
      <div class="w-full items-center text-center pb-4 md:p-0">
        <input
          type="search"
          placeholder="Character's name..."
          class="bg-gray-300 border text-xl text-black p-2"
        />
      </div>
    </div>
  </hero>
</template>

<script></script>
