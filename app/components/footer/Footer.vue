<script setup lang="ts">

</script>

<template>
    <div class="h-[357px] bg-[#2F2F2F] pl-[130px] pr-[130px] pt-[60px]">
        <h1 class="text-[50px] font-semibold text-white">QUE<span class="text-[#3691EF]">WIE</span></h1>
        <div class="flex justify-between -mt-4.5  ">
            <p class="text-[18px] text-[#A6A6A6] mt-9">Get started now try our product</p>
            <div class="relative ">
                <Input
                    class="w-[1301px] h-[60px] rounded-[70px]  font-medium px-10 placeholder:text-[#A6A6A6] placeholder:text-[18px] placeholder:font-medium"
                    placeholder="Enter your email here"
                />
                <div class="absolute right-3 top-2.5  ">
                <ArrowRight class="bg-[#388FF0] rounded-full h-10 w-10" :color="'white'" />
                </div>
            </div>     
        </div>
        <!-- Logo -->
            <div class="mt-5 flex justify-between">
                <img src="/images/footerlogo.png" class="h-[80px] w-[414px]" />
                <p class="text-white text-[18px] font-medium mt-12">
                    Terms and Conditions <span class="text-white">•</span> Privacy Policy
                </p>
            </div>

            <div class="flex justify-between ">
                 <p class="text-white text-[18px] font-medium leading-[20px] ml-2.5">Proudly supported by DOST-PCIEERD and the<br> Philippine Startup Ecosystem.</p>
                 <p class="text-white text-[18px] font-medium">© 2025 LinkNeX Solution. Copyright and rights reserved</p>
            </div>
           
    </div>
</template>





