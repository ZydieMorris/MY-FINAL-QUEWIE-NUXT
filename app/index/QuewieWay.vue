<template>
  <div class="p-5 lg:p-20">
    <div class="bg-white p-7 lg:p-10 rounded-3xl shadow-lg h-auto lg:h-[529px]">

      <!-- FLEX WRAPPER -->
      <div class="mt-5 lg:mt-13 flex flex-col lg:flex-row justify-between h-auto lg:h-89.5">

        <!-- LEFT (TEXT SECTION) -->
        <div class="flex-1 relative text-center lg:text-left">
          <div class="h-14 w-14 rounded-full bg-[#388FF0] flex mx-auto lg:mx-0">
            <h1 class="absolute lg:left-6.5 lg:top-0 text-2xl font-medium leading-9 mt-3 ml-16 lg:ml-0">
              The QUEWIE Way:
              <span class="text-[#388FF0]">
                Stress-Free Service,<br />Happier Customers
              </span>
            </h1>
          </div>

          <div class="space-y-7 pb-8 lg:pb-0">
            <p class="tracking-wide leading-6 lg:leading-9 text-[#696984] mt-13 lg:ml-6.5">
              QUEWIE simplifies workflows, eases employee stress,<br /><br />
              and ensures faster, smoother service for happier<br /><br />
              customers.
            </p>

            <!-- DOT (Desktop only) -->
            <div class="hidden lg:block h-5 w-5 rounded-full bg-[#388FF0] absolute top-43 left-150"></div>

            <a class="underline text-[#696984] block lg:ml-6.5">Learn More</a>
          </div>
        </div>

        <!-- RIGHT (IMAGE SECTION) -->
<div class="flex-1 relative flex items-end justify-center lg:justify-end mt-10 lg:mt-0">

  <!-- Black rectangle (tablet + desktop) -->
  <div class="absolute top-0 md:block hidden lg:right-118 rounded-3xl w-26.5 h-24 bg-[#272727] z-10"></div>

  <!-- Blue rectangle (tablet + desktop) -->
  <div class="absolute bottom-0 right-0 md:block hidden rounded-3xl bg-[#388FF0] h-40.25 w-44.5 z-10"></div>

  <!-- IMAGE -->
  <img 
    src="/images/videothumbnail.png"
    class="z-11 relative lg:absolute lg:top-3.5 lg:right-4 w-[90%] lg:w-136 h-auto"
  />
</div>


      </div>

    </div>
  </div>
</template>
