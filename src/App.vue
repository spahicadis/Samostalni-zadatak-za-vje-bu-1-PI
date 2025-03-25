<script setup></script>

<template>
  <div class="min-h-[100vh] bg-linear-to-b from-blue-500 to-orange-400 dark:from-emerald-950 dark:to-indigo-950"
    ref="dark">
    <button @click="$refs.dark.classList.toggle('dark')"
      class="border rounded-md p-1.5 absolute top-2 right-2 cursor-pointer dark:border-amber-50">
      <span class="dark:text-amber-50">Promjeni temu</span>
    </button>
    <h1 class="dark:text-white text-center text-3xl md:text-6xl p-10 ">
      Pozdrav, ja sam <span class="dark:text-cyan-400 text-amber-300">Adis Spahić</span>
    </h1>
    <hr class="border-2 opacity-75 rounded-full mx-auto sm:w-md md:w-3xl lg:w-5xl xl:w-7xl" />
    <div class="container mx-auto">
      <h3 class="mt-5 text-center md:text-start text-2xl dark:text-teal-100/75 text-violet-100">
        Moji omiljeni filmovi
      </h3>
      <div class="container mx-auto flex flex-col md:flex-row justify-between items-center">
        <div class="w-[220px] lg:w-[320px] h-[480px] pt-5">
          <img class="object-fit rounded-md"
            src="https://encrypted-tbn1.gstatic.com/images?q=tbn:ANd9GcSUX_2arZYl22hAX0hY19pOhDk0XyYtODSkWYQ_m0GtUq5ACocX" />
          <h2 class="text-center text-white text-2xl mt-2 dark:text-amber-50">Spašavanje vojnika Ryana</h2>
        </div>
        <div class="w-[220px] lg:w-[320px] h-[480px] pt-5">
          <img class="object-fit rounded-md"
            src="https://encrypted-tbn2.gstatic.com/images?q=tbn:ANd9GcQmUZve5jOATMSYj-wqlh_5Jca446l83msaDJgwwi8KCeZQkzrI" />
          <h2 class="text-center text-white text-2xl mt-2 dark:text-amber-50">Midway</h2>
        </div>
        <div class="w-[220px] lg:w-[320px] h-[480px] pt-5">
          <img class="object-fit rounded-md"
            src="https://encrypted-tbn3.gstatic.com/images?q=tbn:ANd9GcQ7PRcrPXSy_xYkOl26n2C9LxEPos-53ECogYvBKWIAjq6Ank38" />
          <h2 class="text-center text-white text-2xl mt-2 dark:text-amber-50">Smisao života jednoga psa</h2>
        </div>
      </div>
    </div>
  </div>
</template>
