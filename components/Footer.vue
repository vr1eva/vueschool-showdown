<template>
    <div class="flex flex-col xl:flex-row xl:justify-between">
        <div class="px-[15px] xl:px-10 mt-[140px]">
            <NuxtImg src="/logoxl.png" width="268" height="88" class="mx-auto xl:mx-0" />
            <p class="text-base leading-6 text-center mt-10 xl:max-w-[470px] xl:text-left">Thanks to fine people like
                you, Vue School
                can proudly
                sponsor
                Evan
                and the future of Vue.js by being a
                Platinum Patreon</p>
            <h3 class="font-medium text-[22px] leading-[30px] text-center text-[#737B98] w-full mt-10 xl:text-left">
                FOLLOW US IN
                SOCIAL
                MEDIA
            </h3>
            <ul class="flex gap-[4px] md:gap-[42px] justify-center mt-[32px] w-full">
                <li class="w-[60px] h-[60px] bg-[#2B2F44] flex items-center justify-center rounded-[100px]">
                    <nuxt-icon name="fb" filled class="text-[26px]" />
                </li>
                <li class="shrink-0 w-[60px] h-[60px] bg-[#2B2F44] flex items-center justify-center rounded-[100px]">
                    <nuxt-icon name="twitter" filled class="text-[26px]" />
                </li>
                <li class="shrink-0 w-[60px] h-[60px] bg-[#2B2F44] flex items-center justify-center rounded-[100px]">
                    <nuxt-icon name="github" filled class="text-[26px]" />
                </li>
                <li class="shrink-0 w-[60px] h-[60px] bg-[#2B2F44] flex items-center justify-center rounded-[100px]">
                    <nuxt-icon name="linkedin" filled class="text-[26px]" />
                </li>
                <li class="shrink-0 w-[60px] h-[60px] bg-[#2B2F44] flex items-center justify-center rounded-[100px]">
                    <nuxt-icon name="youtube" filled class="text-[26px]" />
                </li>
            </ul>
        </div>
        <References />
    </div>
</template>