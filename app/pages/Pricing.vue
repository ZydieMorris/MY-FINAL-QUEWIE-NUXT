<template>
    <NuxtLayout name="marketing-layout">
        <div class="h-250">
            <div class="bg-[#3691EF] h-102 pt-40">
                <div class="w-348.5 h-176.25 mx-auto  p-10">
                    <div class="grid grid-cols-4 gap-5 h-full text-center">
                        <!-- First Grid -->
                        <div class="col-span-1 bg-white">
                            <div class="bg-[#005684] h-5"></div>
                            <!-- Prices -->
                            <div class="border-b-1 pb-8 space-y-4">
                                <h1 class="text-2xl mt-5 font-bold text-[#005684]">
                                    BASIC<span class="font-thin"> Plan</span>
                                </h1>
                                <p class="text-[#222222] font-semibold">
                                    ₱6.00 /<span class="italic font-thin">Transaction</span>
                                </p>
                                <p class="text-[#005684] font-bold">
                                    500-3,999<span class="text-[#222222] font-semibold">
                                        transactions<br />
                                        per month</span>
                                </p>
                            </div>
                            <!-- Description -->
                            <div class="p-10 space-y-17">
                                <p class="text-[#3D3D3D] leading-7">
                                    Perfect for small offices or<br />
                                    startups seeking a simple<br />
                                    yet reliable queue<br />
                                    management<br />
                                    solution with all essential<br />
                                    features and support<br />
                                    included.
                                </p>

                                <Button class="w-full h-12 text-xl bg-[#005684] rounded-none">Subscribe Now!</Button>
                            </div>
                        </div>

                        <!-- Second Grid -->
                        <div class="col-span-1 bg-white">
                            <div class="bg-[#00CDEC] h-5"></div>
                            <!-- Prices -->
                            <div class="border-b-1 pb-8  space-y-4">
                                <h1 class="text-2xl mt-5 font-bold text-[#00CDEC]">
                                    STANDARD<span class="font-thin"> Plan</span>
                                </h1>
                                <p class="text-[#00CDEC] font-semibold">
                                    ₱5.00 /<span class="italic font-thin">Transaction</span>
                                </p>
                                <p class="text-[#005684] font-bold">
                                    4,000-5,999<span class="text-[#222222] font-semibold">
                                        transactions<br />
                                        per month</span>
                                </p>
                            </div>
                            <!-- Description -->
                            <div class="p-10 space-y-17">
                                <p class="text-[#3D3D3D] leading-7">
                                    Ideal for growing organizations<br />
                                    that need stable performance,<br />
                                    dependable maintenance,<br />
                                    and responsive technical<br />
                                    support.
                                </p>

                                <Button class="w-full h-12 text-xl bg-[#00CDEC] rounded-none">Subscribe Now!</Button>
                            </div>
                        </div>

                        <!-- Third Grid -->
                        <div class="col-span-1 bg-white">
                            <div class="bg-[#00E0B8] h-5"></div>
                            <!-- Prices -->
                            <div class="border-b-1 pb-8  space-y-4">
                                <h1 class="text-2xl mt-5 font-bold text-[#00E0B8]">
                                    PROFESSIONAL<span class="font-thin"> Plan</span>
                                </h1>
                                <p class="text-[#00E0B8] font-semibold">
                                    ₱4.00 /<span class="italic font-thin">Transaction</span>
                                </p>
                                <p class="text-[#005684] font-bold">
                                    6,000-6,999<span class="text-[#222222] font-semibold">
                                        transactions<br />
                                        per month</span>
                                </p>
                            </div>
                            <!-- Description -->
                            <div class="p-10">
                                <p class="text-[#3D3D3D] leading-7">
                                    Best suited for mid-sized<br />
                                    enterprises or institutions<br />
                                    handling moderate to high<br />
                                    service<br />
                                    demand, ensuring efficiency<br />
                                    through regular updates,<br />
                                    analytics, and system optimization
                                </p>

                                <Button class="w-full h-12 mt-10 text-xl bg-[#00E0B8] rounded-none">Subscribe
                                    Now!</Button>
                            </div>
                        </div>

                        <!-- Fourth Grid -->
                        <div class="col-span-1 bg-white">
                            <div class="bg-[#006FE0] h-5"></div>
                            <!-- Prices -->
                            <div class="border-b-1 pb-8  space-y-4">
                                <h1 class="text-2xl mt-5 font-bold text-[#006FE0]">
                                    ENTERPRISE<span class="font-thin"> Plan</span>
                                </h1>
                                <p class="text-[#222222] font-semibold">
                                    ₱3.00 /<span class="italic font-thin">Transaction</span>
                                </p>
                                <p class="text-[#006FE0] font-bold">
                                    7,000 and above<span class="text-[#222222] font-semibold">
                                        transactions<br />
                                        per month</span>
                                </p>
                            </div>
                            <!-- Description -->
                            <div class="p-10">
                                <p class="text-[#3D3D3D] leading-7">
                                      Tailored for large enterprise<br>and government institutions<br>
                                managing high transaction<br>
                                volumes. This plan provides the
                                most cost-effective rate while
                                maintaining premium<br>
                                reliability, advanced features,
                                and priority system support.</p>
                                <Button class="w-full h-12 mt-3 text-xl bg-[#006FE0] rounded-none">Subscribe Now!</Button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </NuxtLayout>
</template>

<script setup lang="ts"></script>
