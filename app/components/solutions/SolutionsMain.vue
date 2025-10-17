<script setup lang="ts">
import SolutionProps from './SolutionProps.vue';


</script>

<template>
    <div class=" h-1220 flex justify-center items-center  pt-40">
    <div>
         <div class="flex flex-col space-y-3">
            <h1 class="text-center text-6xl">We’re Here to Help</h1>
            <p class="text-center text-[#696984] text-4xl ">Support that keeps your queues moving smoothly.</p>
        </div>
           
           <div class="mt-15 space-y-20 ">
            <SolutionProps
                image="/images/solution1.png" 
                highlight="CiviQ"
                title="Government Offices"
                description="streamlines citizen services through organized queue flow, enabling digital ticketing and real-time
                updates. By reducing overcrowding in public halls and minimizing wait-related frustrations, it
                enhances transparency, improves service efficiency, and significantly reduces the volume of
                complaints."
                link="#"
            />

            <SolutionProps
                 image="/images/hospital&clinics.png" 
                highlight="HealtiQ"
                title="Hospitals & Clinics"
                description="helps prioritize patients based on urgency and schedule, enabling smoother check-ins through
                kiosks or mobile devices. It minimizes physical waiting by providing real-time updates and
                integrates seamlessly with existing health systems. By improving patient flow and reducing
                congestion, enhances the overall care experience while supporting safety, privacy, and
                operational efficiency."
                link="#"
            />

            <SolutionProps
                 image="/images/joyq.png" 
                highlight="JoyQ"
                title="Amusement Parks & Attractions"
                description="Enhances guest experience by enabling mobile or kiosk ride bookings, reducing lines, and offering real-time updates. Supports VIP and express queues for efficient crowd management and greater satisfaction."
                link="#"
            />

             <SolutionProps
                 image="/images/finq.png" 
                highlight="FinQ"
                title="Banks & Financial Institutions"
                description="Optimizes customer flow by managing service-based queues with contactless ticketing, real-time updates, and dynamic teller assignments, ensuring faster and more organized banking transactions."
                link="#"
            />

                <SolutionProps
                image="/images/serviq.png" 
                highlight="ServiQ"
                title="Retail & Service Centers"
                description="Enhances customer experience through digital check-ins for services, real-time wait tracking, and queue analytics—enabling efficient staff allocation, reduced waiting time, and improved overall satisfaction."
                link="#"
            />

             <SolutionProps
                image="/images/eduq.png" 
                highlight="EduQ"
                title="Schools & Universities"
                description="simplifies student services by managing queues for registration, cashier, guidance, and other
                offices through a centralized system. It allows students to check in digitally and receive real-time
                notifications when it’s their turn, reducing idle time and congestion in service areas. By improving
                queue visibility and efficiency, enhances the overall student experience and supports smoother
                administrative operations."
                link="#"
            />

             <SolutionProps
                image="/images/exeq.png" 
                highlight="ExecuQ"
                title="Corporate & BPO Offices"
                description="Streamlines internal operations by managing queues for HR, IT support, facilities, and visitor appointments. Enables digital check-ins with real-time updates—improving response time, service visibility, and overall workplace efficiency."
                link="#"
            />
           </div>
    </div>
       
    </div>
</template>



