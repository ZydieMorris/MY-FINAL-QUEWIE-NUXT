<script setup>
import FeatureSlot from './FeatureSlot.vue'
</script>

<template>
  <div class="p-28 ">

    <div class="mt-7">
        <p class="text-4xl text-[#272727] font-semibold leading-13">Features That Redefine<br></br>
         <span class="text-5xl text-[#469AF0]">Queue Management</span>
        </p>
        
    </div>

        <div class="mt-25 space-y-20">
        <FeatureSlot
        title="The Quewie Features"
        highlight="Smart Queue Management"
        description="QUEWIE enables users to conveniently book, line up, and monitor their spot digitally
        through the web, kiosk, or mobile app."
        link="/learnmore/smart-quewie-management"
        image="/images/firstpicfeature.png"
        />

        <FeatureSlot
        title="The Quewie Features"
        highlight=" Real-Time Notifications & Alerts"
        description="QUEWIE notifies users via SMS, mobile app, or on-screen display when their turn is approaching,
        ensuring they never miss their slot."
        link="/learnmore/real-time-notifications-alerts"
        image="/images/Group 17 (3).png"
        />

        <FeatureSlot
        title="The Quewie Features"
        highlight=" Centralized Dashboard"
        description="QUEWIE features a powerful admin dashboard that allows administrators to view and manage all
        queues across departments or branches in real time. "
        link="/learnmore/centalized-dashboard"
        image="/images/confident-teacher-explaining-lesson-pupils 1.png"
        />

        <FeatureSlot
        title="The Quewie Features"
        highlight=" Multi-Channel Access"
        description="QUEWIE is a versatile, web-based, mobile, and kiosk-ready platform designed for flexible use across sectors like hospitals, government offices, retail, and schools. "
        link="/learnmore/multi-channel-access"
        image="/images/Group 17 (4).png"
        />

        <FeatureSlot
        title="The Quewie Features"
        highlight="Smart Prioritization & Auto Routing"
        description="QUEWIE intelligently manages queues by dynamically assigning customers to available counters
        or service agents, ensuring faster and more efficient service delivery. "
        link="/learnmore/smart-prioritization-auto-routing"
        image="/images/Group 17 (5).png"
        />

        <FeatureSlot
        title="The Quewie Features"
        highlight=" Multi-Branch & Department Management"
        description="It offers centralized management for multiple branches, with customizable access for administrators to ensure secure and organized operations. "
        link="/learnmore/multi-branch-department-management"
        image="/images/Group 17 (6).png"
        />

        <FeatureSlot
        title="The Quewie Features"
        highlight="  Feedback & Service Rating"
        description="It includes a rating system for customer feedback, helping organizations assess satisfaction and improve services. "
        link="/learnmore/feedback-service-rating"
        image="/images/Group 17 (7).png"
        />

        </div>
    
  </div>
  
</template>
