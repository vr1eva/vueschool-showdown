<template>
    <div class="relative z-40 md:px-[64px]">
        <h3 id="plans" class="font-bold text-[60px] leading-[71px] text-center mt-[140px] xl:max-w-[752px] xl:mx-auto">
            Discounted
            <span class="text-gradient">Corporate
                Training</span> Bundles
        </h3>
        <ul class="mt-[72px] flex flex-col gap-6 xl:flex-row px-[15px]">
            <!-- Basic -->
            <li class="w-full xl:w-[640px] rounded-[30px] border bg-[#2B2F44] p-[40px] xl:px-[24px] mx-auto">
                <h2 class="flex items-center gap-[16px]"> <nuxt-icon name="leaf" filled class="text-[32px]" />
                    <span class="text-[22px] leading-[30px] font-bold">Basic</span>
                </h2>
                <p class="text-green mt-[32px] text-[16px] leading-[24px] text-secondary">Includes 1 year access to:</p>
                <ul class="mt-[24px] flex flex-col gap-[16px]">
                    <li class="flex items-center"> <nuxt-icon name="done" filled /><span
                            class="w-full ml-[16px] text-[14px] leading-5">All Video
                            Courses</span>
                        <nuxt-icon name="info" filled />
                    </li>
                    <li class="flex items-center"> <nuxt-icon name="done" filled /><span
                            class="w-full ml-[16px] text-[14px] leading-5">Vue.Js
                            Master class</span>
                        <nuxt-icon name="info" filled />
                    </li>
                    <li class="flex items-center"> <nuxt-icon name="done" filled /><span
                            class="w-full ml-[16px] text-[14px] leading-5">Developer
                            assist Slack
                            channel</span> <nuxt-icon name="info" filled />
                    </li>
                    <li class="flex items-center opacity-25"> <nuxt-icon name="canceled" filled /><span
                            class="w-full ml-[16px] text-[14px] leading-5">Live
                            Weekly QnA</span>
                    </li>
                    <li class="flex items-center opacity-25"> <nuxt-icon name="canceled" filled /><span
                            class="w-full ml-[16px] text-[14px] leading-5">1 x ws
                            ticket per
                            license</span>
                    </li>
                </ul>

                <div class="mt-[24px] bg-[#212435] py-[24px] px-[41px] rounded-[16px]">
                    <p class="font-bold text-[40px] leading-[50px]">$50 <small
                            class="text-[16px] leading-[19px] text-grey font-extralight">/ seat / month</small></p>
                    <label for="seats" class="mt-[24px] block text-[16px] leading-[19px] font-bold">How many licenses do
                        you
                        need?
                    </label>
                    <input type="range" id="seats" name="seats" min="5" max="20" class="mt-[16px] range">
                    <div class="flex justify-between ">
                        <span class="text-plomo">5</span> <span class="text-plomo">20</span>
                    </div>
                    <div class="flex items-center gap-5 mt-4">
                        <span
                            class="flex bg-[#0E0E1033] py-[4px] gap-[10px] items-center px-[14px] rounded-[8px]"><nuxt-icon
                                name="seats" filled class="text-[20px]" /> <span
                                class="text-[26px] leading-[30px] font-bold">12</span>
                            <small class="font-regular text-[16px] leading-[19px] text-[#979FAD]">seats</small></span>
                        <span class="font-medium text-[16px] leading-[19px] text-secondary">26%
                            discount</span>
                    </div>
                </div>
                <button
                    class="bg-secondary text-[#212435] font-medium leading-[19px] text-[16px] w-full py-5 rounded-[10px] mt-8">Start
                    Learning</button>
                <p class="text-secondary text-center mt-6 font-medium leading-[19px] text-[16px]">Refer your manager</p>
            </li>

            <!-- Pro -->
            <li class="w-full xl:w-[640px] rounded-[30px] border bg-[#2B2F44] p-[40px] xl:px-[24px] mx-auto">
                <h2 class="flex items-center gap-[16px]"> <nuxt-icon name="rocket" filled class="text-[32px]" />
                    <span class="text-[22px] leading-[30px] font-bold">Professional</span>
                </h2>
                <p class="text-green mt-[32px] text-[16px] leading-[24px] text-secondary">Includes 1 year access to:</p>
                <ul class="mt-[24px] flex flex-col gap-[16px]">
                    <li class="flex items-center"> <nuxt-icon name="done" filled /><span
                            class="w-full ml-[16px] text-[14px] leading-5">All Video
                            Courses</span>
                        <nuxt-icon name="info" filled />
                    </li>
                    <li class="flex items-center"> <nuxt-icon name="done" filled /><span
                            class="w-full ml-[16px] text-[14px] leading-5">Vue.Js
                            Master class</span>
                        <nuxt-icon name="info" filled />
                    </li>
                    <li class="flex items-center"> <nuxt-icon name="done" filled /><span
                            class="w-full ml-[16px] text-[14px] leading-5">Developer
                            assist Slack
                            channel</span> <nuxt-icon name="info" filled />
                    </li>
                    <li class="flex items-center"> <nuxt-icon name="done" filled /><span
                            class="w-full ml-[16px] font-bold text-[14px] leading-5 text-white">Live
                            Weekly QnA</span> <nuxt-icon name="info" filled />
                    </li>
                    <li class="flex items-center"> <nuxt-icon name="done" filled /><span
                            class="w-full ml-[16px] font-bold text-[14px] leading-5 text-white">1 x ws
                            ticket per
                            license</span> <nuxt-icon name="info" filled />
                    </li>
                </ul>

                <div class="flex gap-4 bg-[#245052] px-6 py-4 rounded-[10px] mt-6">
                    <NuxtImg src="/course.png" width="48" height="48" />
                    <div class="flex flex-col">
                        <p class="text-[14px] text-grey leading-[24px] font-medium">Enough time to watch:</p>
                        <h6 class="text-[18px] leading-6 font-medium">The Vue 3 Masterclass</h6>
                    </div>
                </div>

                <div class="mt-[24px] bg-[#212435] py-[24px] px-[41px] rounded-[16px]">
                    <p class="font-bold text-[40px] leading-[50px]">$50 <small
                            class="text-[16px] leading-[19px] text-grey font-extralight">/ seat / month</small></p>
                    <label for="seats" class="mt-[24px] block text-[16px] leading-[19px] font-bold">How many licenses do
                        you
                        need?
                    </label>
                    <input type="range" id="seats" name="seats" min="5" max="20" class="mt-[16px] range">
                    <div class="flex justify-between ">
                        <span class="text-plomo">5</span> <span class="text-plomo">20</span>
                    </div>
                    <div class="flex items-center gap-5 mt-4">
                        <span
                            class="flex bg-[#0E0E1033] py-[4px] gap-[10px] items-center px-[14px] rounded-[8px]"><nuxt-icon
                                name="seats" filled class="text-[20px]" /> <span
                                class="text-[26px] leading-[30px] font-bold">12</span>
                            <small class="font-regular text-[16px] leading-[19px] text-[#979FAD]">seats</small></span>
                        <span class="font-medium text-[16px] leading-[19px] text-secondary">26% discount</span>
                    </div>
                </div>
                <button
                    class="bg-secondary text-[#212435] font-medium leading-[19px] text-[16px] w-full py-5 rounded-[10px] mt-8">Start
                    Learning</button>
                <p class="text-secondary text-center mt-6 font-medium leading-[19px] text-[16px]">Refer your manager</p>
            </li>

            <!-- 2 basic to pro -->
            <li class="w-full xl:w-[640px] rounded-[30px] border bg-[#2B2F44] p-[40px] mx-auto xl:px-[24px]">
                <h2 class="flex items-center gap-[16px]"> <nuxt-icon name="bolt" filled class="text-[32px]" />
                    <span class="text-[22px] leading-[30px] font-bold">Basic</span>
                </h2>
                <p class="text-green mt-[32px] text-[16px] leading-[24px] text-secondary">Includes 1 year access to:</p>
                <ul class="mt-[24px] flex flex-col gap-[16px]">
                    <li class="flex items-center"> <nuxt-icon name="done" filled /><span
                            class="w-full ml-[16px] text-[14px] leading-5">All Video
                            Courses</span>
                        <nuxt-icon name="info" filled />
                    </li>
                    <li class="flex items-center"> <nuxt-icon name="done" filled /><span
                            class="w-full ml-[16px] text-[14px] leading-5">Vue.Js
                            Master class</span>
                        <nuxt-icon name="info" filled />
                    </li>
                    <li class="flex items-center"> <nuxt-icon name="done" filled /><span
                            class="w-full ml-[16px] text-[14px] leading-5">Developer
                            assist Slack
                            channel</span> <nuxt-icon name="info" filled />
                    </li>
                    <li class="flex items-center"> <nuxt-icon name="done" filled /><span
                            class="w-full ml-[16px] text-[14px] leading-5 text-white">Live
                            Weekly QnA</span> <nuxt-icon name="info" filled />
                    </li>
                    <li class="flex items-center"> <nuxt-icon name="done" filled /><span
                            class="w-full ml-[16px] font-bold text-[14px] leading-5 text-white">4 x Virtual Workshops of
                            your
                            choice
                        </span> <nuxt-icon name="info" filled />
                    </li>
                </ul>

                <div class="mt-[24px] bg-[#212435] py-[24px] px-[41px] rounded-[16px]">
                    <p class="font-bold text-[40px] leading-[50px]">$50 <small
                            class="text-[16px] leading-[19px] text-grey font-extralight">/ seat / month</small></p>
                    <label for="seats" class="mt-[24px] block text-[16px] leading-[19px] font-bold">How many licenses do
                        you
                        need?
                    </label>
                    <input type="range" id="seats" name="seats" min="5" max="20" class="mt-[16px] range">
                    <div class="flex justify-between ">
                        <span class="text-plomo">5</span> <span class="text-plomo">20</span>
                    </div>
                    <div class="flex items-center gap-5 mt-4">
                        <span
                            class="flex bg-[#0E0E1033] py-[4px] gap-[10px] items-center px-[14px] rounded-[8px]"><nuxt-icon
                                name="seats" filled class="text-[20px]" /> <span
                                class="text-[26px] leading-[30px] font-bold">12</span>
                            <small class="font-regular text-[16px] leading-[19px] text-[#979FAD]">seats</small></span>
                        <span class="font-medium text-[16px] leading-[19px] text-secondary">26% discount</span>
                    </div>
                </div>
                <button
                    class="bg-secondary text-[#212435] font-medium leading-[19px] text-[16px] w-full py-5 rounded-[10px] mt-8">Start
                    Learning</button>
                <p class="text-secondary text-center mt-6 font-medium leading-[19px] text-[16px]">Refer your manager</p>
            </li>

        </ul>
    </div>
</template>

<style scoped>
.text-gradient {
    background: -webkit-linear-gradient(#0CD890, #01F0FD);
    -webkit-background-clip: text;
    background-clip: text;
    -webkit-text-fill-color: transparent;
}

.range {
    -webkit-appearance: none;
    appearance: none;
    background: transparent;
    cursor: pointer;
    width: 100%;
}

/* Removes default focus */
.range:focus {
    outline: none;
}

/***** Chrome, Safari, Opera and Edge Chromium styles *****/
/* slider track */
.range::-webkit-slider-runnable-track {
    background: #0bd88f;
    border-radius: 0.5rem;
    height: 4px
}

/* slider thumb */
.range::-webkit-slider-thumb {
    -webkit-appearance: none;
    /* Override default look */
    appearance: none;
    margin-top: -4px;
    /* Centers thumb on the track */

    /*custom styles*/
    background: #0bd88f;
    height: 14px;
    width: 14px;
    border-radius: 50%;
}

.range:focus::-webkit-slider-thumb {
    border: 1px solid #0bd88f;
    outline: 3px solid #053a5f;
}
</style>
