<template>
  <div class="w-full bg-[#2F2F2F] px-6 lg:px-[130px] pt-[60px] pb-10">
    <div class="max-w-[1920px] mx-auto">

      <!-- BRAND -->
      <h1 class="text-[38px] lg:text-[50px] font-semibold text-white">
        QUE<span class="text-[#3691EF]">WIE</span>
      </h1>

      <!-- SUBTEXT + INPUT -->
      <div class="mt-6 lg:flex lg:items-center lg:justify-between">
        <p class="text-[#A6A6A6] mb-5 lg:mb-0">
          Get started now try our product
        </p>

        <div class="relative w-full lg:w-[1100px]">
          <Input
            class="w-full h-[60px] rounded-[70px] font-medium px-10
                   placeholder:text-[#A6A6A6] placeholder:text-[18px] placeholder:font-medium"
            placeholder="Enter your email here"
          />
          <div class="absolute right-3 top-2.5">
            <ArrowRight class="bg-[#388FF0] rounded-full h-10 w-10" :color="'white'" />
          </div>
        </div>
      </div>

      <!-- LOGO + LINKS -->
      <div class="mt-10 lg:flex lg:items-center lg:justify-between">
        <img src="/images/footerlogo.png" class="h-[60px] lg:h-[80px] w-auto mb-6 lg:mb-0" />

        <p class="text-white font-medium">
          Terms and Conditions <span class="text-white">•</span> Privacy Policy
        </p>
      </div>

      <!-- BOTTOM TEXT -->
      <div class="mt-6 lg:flex lg:items-center lg:justify-between space-y-4 lg:space-y-0">
        <p class="text-white font-medium leading-[20px]">
          Proudly supported by DOST-PCIEERD and the<br />
          Philippine Startup Ecosystem.
        </p>

        <p class="text-white font-medium">
          © 2025 LinkNeX Solution. Copyright and rights reserved
        </p>
      </div>

    </div>
  </div>
</template>
