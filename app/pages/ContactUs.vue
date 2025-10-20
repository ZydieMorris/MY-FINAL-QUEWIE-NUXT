<template>
    <NuxtLayout name="marketing-layout">
        <div class="h-230 pt-40">
            <div class=" h-166.75 w-299  mx-auto p-2 flex justify-between">
                <!-- left side -->
                <div class="bg-[#3691EF] p-8 w-122.75 relative overflow-hidden rounded-xl">
                    <!-- Heading -->
                    <div class="space-y-3">
                        <h1 class="text-3xl text-white font-semibold">Contact Information</h1>
                        <p class="text-lg text-[#C9C9C9]">For inquiries, partnerships, and product
                            demonstrations, please reach out to us:</p>
                    </div>
                    <!--Links Info  -->
                    <div class="w-84.25 h-79.75    text-white mt-22">

                        <div class="space-y-8">
                            <!-- telephone -->
                            <div class="flex space-x-5">
                                <PhoneCall />
                                <p>+1012 3456 789</p>
                            </div>
                            <!-- Email -->
                            <div class="flex space-x-5">
                                <Mail />
                                <p>supporthomi@gmail.com<br>quewie@gmail.com</p>
                            </div>
                            <!-- Map -->
                            <div class="flex space-x-5">
                                <MapPin />
                                <p>Tacurong City, Sultan Kudarat</p>
                            </div>
                            <!-- Facebook -->
                            <div class="flex space-x-5">
                                <svg class="h-6 w-6" viewBox="0 0 666.667 666.667">
                                    <g clip-path="url(#facebook_icon__a)"
                                        transform="matrix(1.33333 0 0 -1.33333 -133.333 800)">
                                        <path
                                            d="M0 0c0 138.071-111.929 250-250 250S-500 138.071-500 0c0-117.245 80.715-215.622 189.606-242.638v166.242h-51.552V0h51.552v32.919c0 85.092 38.508 124.532 122.048 124.532 15.838 0 43.167-3.105 54.347-6.211V81.986c-5.901.621-16.149.932-28.882.932-40.993 0-56.832-15.528-56.832-55.9V0h81.659l-14.028-76.396h-67.631v-171.773C-95.927-233.218 0-127.818 0 0"
                                            style="fill:#0866ff;fill-opacity:1;fill-rule:nonzero;stroke:none"
                                            transform="translate(600 350)" />
                                        <path
                                            d="m0 0 14.029 76.396H-67.63v27.019c0 40.372 15.838 55.899 56.831 55.899 12.733 0 22.981-.31 28.882-.931v69.253c-11.18 3.106-38.509 6.212-54.347 6.212-83.539 0-122.048-39.441-122.048-124.533V76.396h-51.552V0h51.552v-166.242a250.559 250.559 0 0 1 60.394-7.362c10.254 0 20.358.632 30.288 1.831V0Z"
                                            style="fill:#fff;fill-opacity:1;fill-rule:nonzero;stroke:none"
                                            transform="translate(447.918 273.604)" />
                                    </g>
                                </svg>
                                <p>facebook.com/QUEWIE</p>
                            </div>

                            <!-- BusinessHours-->
                            <div class="flex space-x-5 z-20 relative">
                                <Clock2 />
                                <p>Business Hours: Monday to<br>Saturday, 8:00 AM – 5:00 PM<br> (GMT+8)</p>
                            </div>

                            <div class="flex space-x-5">
                                <img src="/images/twitter.png" class="h-7.5 w-7.5" />
                                <img src="/images/instagram.png" class="h-7.5 w-7.5" />
                                <img src="/images/discord.png" class="h-7.5 w-7.5" />

                            </div>

                            <div class="w-34 h-34 bg-[#48484880] rounded-full absolute bottom-10 right-22 z-10"></div>

                            <div class="w-67 h-67 rounded-full bg-[#1A1A1A] absolute -bottom-20 -right-23 "></div>
                        </div>
                    </div>
                </div>





                <!--Right Side -->
                <div class="bg-white flex-1  space-y-10 p-10 relative">
                    <!-- Name -->
                    <div class="flex justify-between">
                        <div class="flex-1 space-y-2">
                            <Label>First Name</Label>
                            <input class="w-69.5 h-10 border-0 border-b-1 outline-0" />
                        </div>
                        <div class="flex-1 space-y-2 ">
                            <Label>Last Name</Label>
                            <input class="w-full h-10 border-0 border-b-1 outline-0" />
                        </div>
                    </div>
                    <!-- Email -->
                    <div class="flex justify-between">
                        <div class="flex-1 space-y-2">
                            <Label>Email</Label>
                            <input class="w-69.5 h-10 border-0 border-b-1 outline-0" />
                        </div>
                        <div class="flex-1 space-y-2">
                            <Label>Phone Number</Label>
                            <input class="w-full h-10 border-0 border-b-1 outline-0" />
                        </div>
                    </div>

                    <div class="space-y-3">
                        <h1 class="font-semibold">Select Subject?</h1>


                        <RadioGroup default-value="General Inquiry" class="flex  space-x-4">
                            <div class="flex items-center space-x-2">
                                <RadioGroupItem id="r1" value="default" />
                                <Label for="r1" class="text-xs">General Inquiry</Label>
                            </div>
                            <div class="flex items-center space-x-2">
                                <RadioGroupItem id="r2" value="product_inquiry"/>
                                     
                                <Label for="r2" class="text-xs ">Product Inquiry</Label>
                            </div>
                            <div class="flex items-center space-x-2">
                                <RadioGroupItem id="r3" value="pricing and quotation" />
                                <Label for="r3" class="text-xs">Pricing and Quotation</Label>
                            </div>
                            <div class="flex items-center space-x-2">
                                <RadioGroupItem id="r4" value="technical support" />
                                <Label for="r4" class="text-xs">Technical Support</Label>
                            </div>
                        </RadioGroup>

                        <div class="mt-10 space-y-2">
                            <Label>Message</Label>
                            <Textarea class="border-b-2 w-full  placeholder:pl-2 outline-0"
                                placeholder="write your message.." />
                        </div>

                        <Button class="absolute right-10 bg-black text-white w-53.75 h-13.5 hover:bg-gray-600 mt-5">Send
                            Message
                        </Button>


                    </div>

                </div>



            </div>
        </div>

    </NuxtLayout>
</template>

<script setup lang="ts">
import { Clock2, Facebook, Mail, MapPin, PhoneCall } from 'lucide-vue-next';

import { Label } from "@/components/ui/label"
import { RadioGroup, RadioGroupItem } from "@/components/ui/radio-group"

</script>
