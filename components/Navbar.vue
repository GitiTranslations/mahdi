<template>
    <nav class="fixed top-0 w-full bg-transparent py-5 text-slate-100 bg-sky-800 opacity-80 z-50">
        <div class="w-11/12 sm:w-8/12  mx-auto flex justify-between">
            <NuxtLink to="/" class="text-2xl font-bold">Mahdi Translations</NuxtLink>
            <ul class="flex space-x-5">
                <li>
                    <NuxtLink to="/">Home</NuxtLink>
                </li>
                <li>
                    <NuxtLink to="#about">About</NuxtLink>
                </li>
                <li>
                    <NuxtLink to="#services">Services</NuxtLink>
                </li>
                <li>
                    <NuxtLink to="#pricing">Pricing</NuxtLink>
                </li>
                <li>
                    <NuxtLink to="#contact">Contact</NuxtLink>
                </li>
            </ul>
        </div>
    </nav>
</template>