<template>
    <div class="bg-dark-50 relative w-full py-12 px-4">
        <UContainer>
            <h2 class="text-dark-900 text-left text-4xl font-bold">
                Our Partners
            </h2>
            <p class="text-dark-900/60 mt-2 text-left text-lg font-normal">
                Explore the possibilities with us, trusted by over +5,000 companies
            </p>
            <div class="mt-12">
                <NuxtMarquee :pauseOnHover="true" direction="right" gradient gradientColor="var(--color-dark-50)">
                    <div class="flex items-center gap-x-8">
                        <div class="w-full flex h-24 items-center justify-center">
                            <UIcon name="i-logos-nuxt" class="text-3xl" />
                        </div>
                        <div class="w-full flex h-24 items-center justify-center">
                            <UIcon name="i-logos-supabase" class="text-3xl" />
                        </div>
                        <div class="w-full flex h-24 items-center justify-center">
                            <UIcon name="i-logos-tailwindcss" class="text-3xl" />
                        </div>
                        <div class="w-full flex h-24 items-center justify-center">
                            <UIcon name="i-logos-cloudflare" class="text-3xl" />
                        </div>
                        <div class="w-full flex h-24 items-center justify-center">
                            <UIcon name="i-logos-nuxt" class="text-3xl" />
                        </div>
                        <div class="w-full flex h-24 items-center justify-center">
                            <UIcon name="i-logos-supabase" class="text-3xl" />
                        </div>
                        <div class="w-full flex h-24 items-center justify-center">
                            <UIcon name="i-logos-tailwindcss" class="text-3xl" />
                        </div>
                        <div class="w-full flex h-24 items-center justify-center">
                            <UIcon name="i-logos-cloudflare" class="text-3xl" />
                        </div>
                    </div>
                </NuxtMarquee>
            </div>
            <div class="mt-4">
                <NuxtMarquee :pauseOnHover="true" direction="left" gradient gradientColor="var(--color-dark-50)">
                    <div class="flex items-center gap-x-8">
                        <div class="w-full flex h-24 items-center justify-center">
                            <UIcon name="i-logos-nuxt" class="text-3xl" />
                        </div>
                        <div class="w-full flex h-24 items-center justify-center">
                            <UIcon name="i-logos-supabase" class="text-3xl" />
                        </div>
                        <div class="w-full flex h-24 items-center justify-center">
                            <UIcon name="i-logos-tailwindcss" class="text-3xl" />
                        </div>
                        <div class="w-full flex h-24 items-center justify-center">
                            <UIcon name="i-logos-cloudflare" class="text-3xl" />
                        </div>
                        <div class="w-full flex h-24 items-center justify-center">
                            <UIcon name="i-logos-nuxt" class="text-3xl" />
                        </div>
                        <div class="w-full flex h-24 items-center justify-center">
                            <UIcon name="i-logos-supabase" class="text-3xl" />
                        </div>
                        <div class="w-full flex h-24 items-center justify-center">
                            <UIcon name="i-logos-tailwindcss" class="text-3xl" />
                        </div>
                        <div class="w-full flex h-24 items-center justify-center">
                            <UIcon name="i-logos-cloudflare" class="text-3xl" />
                        </div>
                    </div>
                </NuxtMarquee>
            </div>
        </UContainer>
    </div>
</template>