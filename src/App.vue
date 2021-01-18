<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
  <div class="container mx-auto max-w-5xl p-8">
    <div class="flex flex-col md:flex-row mb-24 gap-12">
      <div class="w-full">
        <h3 class="text-4xl font-bold font-pt-serif">The creative crew</h3>
      </div>
      <div class="flex flex-col w-full text-lg font-poppins gap-2">
        <h4 class="font-bold">WHO WE ARE</h4>
        <p class="max-w-md">
          We are team of creatively diverse. driven. innovative individuals
          working in various locations from the world.
        </p>
      </div>
    </div>
    <div
      class="card-container grid grid-cols-2 md:grid-cols-3 grid-rows-3 md:grid-rows-2 gap-x-16"
    >
      <div class="block">
        <div
          class="transform transition-all ease-in-out duration-500 hover:scale-110 cursor-pointer"
        >
          <div class="card flex">
            <div class="flex-1 aspect-w-4 aspect-h-5">
              <img
                class="object-cover object-top"
                src="./assets/photo1.jpg"
                alt="user"
              />
            </div>
            <div class="card-position flex-shrink-0 pl-1">
              <span class="text-xs font-pt-serif uppercase">Product Owner</span>
            </div>
          </div>
          <h4 class="text-lg md:text-xl font-semibold mt-2">Bill Mahoney</h4>
        </div>
      </div>

      <div class="block">
        <div
          class="transform transition-all ease-in-out duration-500 hover:scale-110 cursor-pointer"
        >
          <div class="card flex">
            <div class="flex-1 aspect-w-4 aspect-h-5">
              <img
                class="object-cover object-top"
                src="./assets/photo2.jpg"
                alt="user"
              />
            </div>
            <div class="card-position flex-shrink-0 pl-1">
              <span class="text-xs font-pt-serif uppercase">Art Director</span>
            </div>
          </div>
          <h4 class="text-lg md:text-xl font-semibold mt-2">Saba Cabrera</h4>
        </div>
      </div>

      <div class="block">
        <div
          class="transform transition-all ease-in-out duration-500 hover:scale-110 cursor-pointer"
        >
          <div class="card flex">
            <div class="flex-1 aspect-w-4 aspect-h-5">
              <img
                class="object-cover object-top"
                src="./assets/photo3.jpg"
                alt="user"
              />
            </div>
            <div class="card-position flex-shrink-0 pl-1">
              <span class="text-xs font-pt-serif uppercase">Techlead</span>
            </div>
          </div>
          <h4 class="text-lg md:text-xl font-semibold mt-2">Shae Le</h4>
        </div>
      </div>

      <div class="block">
        <div
          class="transform transition-all ease-in-out duration-500 hover:scale-110 cursor-pointer"
        >
          <div class="card flex">
            <div class="flex-1 aspect-w-4 aspect-h-5">
              <img
                class="object-cover object-top"
                src="./assets/photo4.jpg"
                alt="user"
              />
            </div>
            <div class="card-position flex-shrink-0 pl-1">
              <span class="text-xs font-pt-serif uppercase">UX Designer</span>
            </div>
          </div>
          <h4 class="text-lg md:text-xl font-semibold mt-2">Skylah Lu</h4>
        </div>
      </div>

      <div class="block">
        <div
          class="transform transition-all ease-in-out duration-500 hover:scale-110 cursor-pointer"
        >
          <div class="card flex">
            <div class="flex-1 aspect-w-4 aspect-h-5">
              <img
                class="object-cover object-top"
                src="./assets/photo5.jpg"
                alt="user"
              />
            </div>
            <div class="card-position flex-shrink-0 pl-1">
              <span class="text-xs font-pt-serif uppercase">Developer</span>
            </div>
          </div>
          <h4 class="text-lg md:text-xl font-semibold mt-2">Griff Richards</h4>
        </div>
      </div>

      <div class="block">
        <div
          class="transform transition-all ease-in-out duration-500 hover:scale-110 cursor-pointer"
        >
          <div class="card flex">
            <div class="flex-1 aspect-w-4 aspect-h-5">
              <img
                class="object-cover object-top"
                src="./assets/photo6.jpg"
                alt="user"
              />
            </div>
            <div class="card-position flex-shrink-0 pl-1">
              <span class="text-xs font-pt-serif uppercase">Develoepr</span>
            </div>
          </div>
          <h4 class="text-lg md:text-xl font-semibold mt-2">Stan John</h4>
        </div>
      </div>
    </div>
    <div class="text-center pt-8" style="color: #a9a9a9">
      assoft@DevChallenges.io
    </div>
  </div>
</template>