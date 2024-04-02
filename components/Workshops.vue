<template>
    <div class="relative z-40 mt-[140px]">
        <h3 class="font-bold text-[60px] leading-[71px] text-center">Available Workshops</h3>
        <section class="mt-[72px] flex overflow-clip gap-[30px] px-10">
            <article class="w-full md:w-[570px] bg-[#2a2e42] rounded-[30px] shrink-0">
                <div
                    class="rounded-t-[30px] flex bg-gradient-to-r from-[#4F08E6] to-[#FF4975] py-6 px-[35px] items-center gap-3">
                    <nuxt-icon name="calendar" />
                    <p class="font-medium text-base leading-[19px]">December 14th - 11:00 AM (GMT-3)</p>
                </div>
                <div class="flex flex-col px-[35px] py-[35px]">
                    <div class="flex gap-[35px]">
                        <p class="flex gap-3"><nuxt-icon name="muteplay" filled /><span
                                class="text-[#737B98] text-[14px] leading-[16px]">LIVE Training</span>
                        </p>
                        <p class="flex gap-3"><nuxt-icon name="muteclock" filled /><span
                                class="text-[#737B98] text-[14px] leading-[16px]">15 Hours</span></p>
                    </div>
                    <h3 class="mt-5 font-medium text-[24px] leading-[28px]">Vue.js Fundamentals</h3>
                    <p class="mt-3 font-regular text-[14px] leading-5 text-[#737B98]">A progressive framework for
                        building
                        user interfaces.
                        Unlike other monolithic
                        frameworks, Vue is
                        designed
                        from the ground up to be incrementally...</p>
                    <div class="flex gap-3 mt-[22px] items-center">
                        <NuxtImg src="/author.png" class="shrink-0" width="24" height="24" />
                        <p class="text-[#737B98] text-[14px] leading-5">Steve Popoola</p>
                    </div>
                </div>
            </article>

            <article class="w-full xl:w-[570px] bg-[#2a2e42] rounded-[30px] shrink-0">
                <div
                    class="rounded-t-[30px] flex bg-gradient-to-r from-[#4F08E6] to-[#FF4975] py-6 px-[35px] items-center gap-3">
                    <nuxt-icon name="calendar" />
                    <p class="font-medium text-base leading-[19px]">December 14th - 11:00 AM (GMT-3)</p>
                </div>
                <div class="flex flex-col px-[35px] py-[35px]">
                    <div class="flex gap-[35px]">
                        <p class="flex gap-3"><nuxt-icon name="muteplay" filled /><span
                                class="text-[#737B98] text-[14px] leading-[16px]">LIVE Training</span>
                        </p>
                        <p class="flex gap-3"><nuxt-icon name="muteclock" filled /><span
                                class="text-[#737B98] text-[14px] leading-[16px]">15 Hours</span></p>
                    </div>
                    <h3 class="mt-5 font-medium text-[24px] leading-[28px]">Vue 3 and Composition API</h3>
                    <p class="mt-3 font-regular text-[14px] leading-5 text-[#737B98]">Take a deep dive into the new and
                        exciting features of Vue 3. Learn about Portals, Suspense, Composition API, Fragments, and much
                        much
                        more...</p>
                    <div class="flex gap-3 mt-[22px] items-center">
                        <NuxtImg src="/author.png" class="shrink-0" width="24" height="24" />
                        <p class="text-[#737B98] text-[14px] leading-5">Steve Popoola</p>
                    </div>
                </div>
            </article>

            <article class="w-full xl:w-[570px] bg-[#2a2e42] rounded-[30px] shrink-0">
                <div
                    class="rounded-t-[30px] flex bg-gradient-to-r from-[#4F08E6] to-[#FF4975] py-6 px-[35px] items-center gap-3">
                    <nuxt-icon name="calendar" />
                    <p class="font-medium text-base leading-[19px]">December 14th - 11:00 AM (GMT-3)</p>
                </div>
                <div class="flex flex-col px-[35px] py-[35px]">
                    <div class="flex gap-[35px]">
                        <p class="flex gap-3"><nuxt-icon name="muteplay" filled /><span
                                class="text-[#737B98] text-[14px] leading-[16px]">LIVE Training</span>
                        </p>
                        <p class="flex gap-3"><nuxt-icon name="muteclock" filled /><span
                                class="text-[#737B98] text-[14px] leading-[16px]">15 Hours</span></p>
                    </div>
                    <h3 class="mt-5 font-medium text-[24px] leading-[28px]">Vue 3 and Composition API</h3>
                    <p class="mt-3 font-regular text-[14px] leading-5 text-[#737B98]">Take a deep dive into the new and
                        exciting features of Vue 3. Learn about Portals, Suspense, Composition API, Fragments, and much
                        much more...</p>
                    <div class="flex gap-3 mt-[22px] items-center">
                        <NuxtImg src="/author.png" class="shrink-0" width="24" height="24" />
                        <p class="text-[#737B98] text-[14px] leading-5">Steve Popoola</p>
                    </div>
                </div>
            </article>
        </section>
        <button class="bg-secondary mt-[56px] rounded-[10px] py-5 px-10 text-[#212435] font-medium mx-auto block">See
            all
            the
            workshops</button>
    </div>
</template>