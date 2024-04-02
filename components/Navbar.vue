<template>
    <nav class="flex items-center px-[48px] py-[21.5px] justify-end">
        <nuxt-icon name="menu" color="white" width="26" class="text-[26px] mr-[24px] xl:hidden cursor-pointer" />
        <NuxtImg src="/logoxl.png" width="170" height="56" class="mr-auto block" />
        <div class="xl:flex gap-[12px] items-center hidden">
            <a href="/courses" class="flex items-center gap-1">Courses<nuxt-icon name="chevron" color="white" width="20"
                    height="20" filled /></a>

            <a href="/#plans" class="text-[16px] leading-[19px]">Plans</a>
            <a href="/services" class="flex items-center gap-1">Business Service<nuxt-icon name="chevron" color="white"
                    width="20" height="20" filled /></a>
            <a href="/paths" class="flex items-center">Learning Paths</a>
            <a href="/hiring" class="flex items-center">Hiring</a>
            <a href="/articles" class="flex items-center">Articles</a>
            <a href="/services" class="flex items-center gap-1">Events<nuxt-icon name="chevron" color="white" width="20"
                    height="20" filled /></a>
            <a href="/certification" class="flex items-center">Get Certified</a>
        </div>
        <div class="hidden md:flex flex-end gap-[30px] ml-[42px] items-center">
            <a href="/login" class="text-[16px] leading-[19px]">Log in</a>
            <a class="border-2 border-[#0BD88F] border-e-[#00C2FF] rounded-[10px] text-secondary px-[40px] py-[13px]"
                href="/signup">Sign
                up</a>
        </div>
    </nav>
</template>
