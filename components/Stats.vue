<template>
    <div class="px-[15px] relative z-40 mt-[140px] md:px-[99px] xl:flex xl:justify-between">
        <div>
            <h4 class="text-gradient uppercase font-medium text-[24px] leading-[28px] text-center xl:text-left">Your #1
                source of
                Vue.js
                courses</h4>
            <h2
                class="font-bold text-[60px] leading-[71px] text-center xl:text-left mt-[13px] w-full xl:w-[570px] mx-auto">
                Full
                Stack
                <span class="text-gradient">Vue
                    Training</span>
                Solutions
            </h2>
        </div>

        <ul class="flex gap-[26px] xl:gap-[61px] mt-[29px] justify-center">
            <li class="flex flex-col items-center">
                <p class="text-gradient text-[64px] md:text-[90px] leading-[106px] font-medium">763</p>
                <span class="flex items-center mt-[11px] gap-[10px]"><nuxt-icon name="play" /><small
                        class="text-[14px] leading-[16px]">Video
                        lessons</small></span>
            </li>
            <li class="flex flex-col items-center">
                <p class="text-gradient text-[64px] md:text-[90px] leading-[106px] font-medium">40</p>
                <span class="flex items-center mt-[11px] gap-[10px]"><nuxt-icon name="book" /><small
                        class="text-[14px] leading-[16px]">Courses</small></span>
            </li>
            <li class="flex flex-col items-center">
                <p class="text-gradient text-[64px] md:text-[90px] leading-[106px] font-medium">64</p>
                <span class="flex items-center mt-[11px] gap-[10px]"><nuxt-icon name="clock" /> <small
                        class="text-[14px] leading-[16px]">15
                        Hours</small></span>
            </li>
        </ul>
    </div>
</template>

<style>
.text-gradient {
    background: -webkit-linear-gradient(#0CD890, #01F0FD);
    -webkit-background-clip: text;
    background-clip: text;
    -webkit-text-fill-color: transparent;
}
</style>