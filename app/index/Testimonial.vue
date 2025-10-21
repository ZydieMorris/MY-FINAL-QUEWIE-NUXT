<template>
  <div class="pb-35">
    <div class="grid grid-cols-1 lg:grid-cols-3 h-auto lg:h-220">

      <!-- First Column (BLUE) -->
      <div class="bg-[#469AF0] pl-[40px] lg:pl-[81px] py-16 h-150 lg:h-199.75">
        <div class="space-y-7">
          <img src="/images/testimonialLogo.png" class="w-32 lg:w-auto" />

          <p class="text-3xl leading-10 tracking-[4%] text-white font-normal font-custom">
            WHAT THEY SAY<br />ABOUT US?
          </p>
        </div>

        <!-- QUOTE -->
        <img src="/images/Qotes.png" class="h-40 w-40 lg:h-56 lg:w-56 mt-10" />

        <!-- NAME + POSITION -->
        <div class="mt-5">
          <h1 class="font-extrabold text-[42px] lg:text-[64px] text-white">
            Anya Santos
          </h1>
          <p class="text-sm text-[#EAEAEA]">Senior Software Engineer</p>
        </div>
      </div>

      <!-- Second Column (IMAGE) -->
      <div class="h-150  lg:h-199.75 w-full">
        <img 
          src="/images/anyaya.png"
          class="h-full w-full object-cover object-center"
        />
      </div>

      <!-- Third Column (WHITE) -->
      <div class="relative h-130  bg-white lg:h-199.75 flex items-center justify-center">
        <img src="/images/righttestimonial.png" class="absolute right-0 top-10 hidden lg:block" />
        <img src="/images/Frame5.png" class="w-60 lg:w-auto" />
      </div>

    </div>
  </div>
</template>
