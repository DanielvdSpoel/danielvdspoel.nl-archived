<template>
    <div>
        <div class="relative bg-gray-50 overflow-hidden min-h-screen">
            <div class="hidden sm:block sm:absolute sm:inset-y-0 sm:h-screen sm:w-full" aria-hidden="true">
                <div class="relative h-full max-w-7xl mx-auto">
                    <svg class="absolute right-full transform translate-y-1/4 translate-x-1/4 lg:translate-x-1/2" width="404" height="784" fill="none" viewBox="0 0 404 784">
                        <defs>
                            <pattern id="f210dbf6-a58d-4871-961e-36d5016a0f49" x="0" y="0" width="20" height="20" patternUnits="userSpaceOnUse">
                                <rect x="0" y="0" width="4" height="4" class="text-gray-200" fill="currentColor" />
                            </pattern>
                        </defs>
                        <rect width="404" height="784" fill="url(#f210dbf6-a58d-4871-961e-36d5016a0f49)" />
                    </svg>
                    <svg class="absolute left-full transform -translate-y-3/4 -translate-x-1/4 md:-translate-y-1/2 lg:-translate-x-1/2" width="404" height="784" fill="none" viewBox="0 0 404 784">
                        <defs>
                            <pattern id="5d0dd344-b041-4d26-bec4-8d33ea57ec9b" x="0" y="0" width="20" height="20" patternUnits="userSpaceOnUse">
                                <rect x="0" y="0" width="4" height="4" class="text-gray-200" fill="currentColor" />
                            </pattern>
                        </defs>
                        <rect width="404" height="784" fill="url(#5d0dd344-b041-4d26-bec4-8d33ea57ec9b)" />
                    </svg>
                </div>
            </div>

            <div class="relative pt-6 pb-16 sm:pb-24">
                <Navbar/>
                <main class="mt-8 mx-auto max-w-7xl px-4 md:px-16 sm:mt-32">
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-16">
                        <div class="text-left md:mt-16">
                            <h1 class="text-4xl tracking-tight font-extrabold text-gray-900 sm:text-5xl md:text-4xl">
                                <span class="block inline">Goedemorgen, ik ben</span>
                                {{ ' ' }}
                                <span class="block text-cyan-400 inline">Daniël van der Spoel</span>
                            </h1>
                            <p class="mt-3 max-w-md text-base text-gray-500 sm:text-lg md:mt-5 md:text-xl md:max-w-3xl">Anim aute id magna aliqua ad ad non deserunt sunt. Qui irure qui lorem cupidatat commodo. Elit sunt amet fugiat veniam occaecat fugiat aliqua.</p>
                            <div class="flex gap-4 mt-6">
                                <button type="button" class="inline-flex items-center px-6 py-3 border border-transparent text-base font-medium rounded-md shadow-sm text-white bg-cyan-400 hover:bg-cyan-500 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-cyan-300">Meer over mij</button>
                                <button type="button" class="inline-flex items-center px-6 py-3 border border-2 border-gray-200 text-lg font-medium rounded-md text-cyan-400 hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-cyan-500">Contact</button>
                            </div>
                        </div>
                        <div class="grid grid-cols-1 content-center">
                            <HomeAnimation/>
                        </div>
                    </div>
                    <div class="flex justify-center mt-16">
                        <button type="button" class="animate-bounce inline-flex items-center p-3 border border-transparent rounded-full shadow-sm text-white bg-cyan-400 hover:bg-cyan-500 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-cyan-300">
                            <ArrowDownIcon class="h-6 w-6" aria-hidden="true" />
                        </button>
                    </div>
                </main>
            </div>
        </div>
        <section class="mx-auto max-w-7xl px-4 md:px-16 grid grid-cols-1 md:grid-cols-2 gap-4 bg-gray-100 py-8">
            <div class="mt-14">
                <div class="flex gap-2">
                    <img src="/images/hand_waving.png" class="h-8 mt-0.5" alt="A waving hand emoji">
                    <h1 class="text-xl tracking-tight font-bold text-gray-900 md:text-2xl">
                        Aangenaam kennis te maken, ik ben Daniël.
                    </h1>
                </div>
                <p class="mt-2 max-w-md text-base text-gray-500 sm:text-lg md:max-w-3xl">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam sollicitudin, diam eget fermentum rutrum, neque erat dapibus arcu, vitae varius lectus sem dictum ex. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Nam dapibus dolor a orci semper, nec elementum arcu porta. Vestibulum ultrices rutrum sapien. Pellentesque cursus elit ut mi tincidunt, vel lacinia magna tincidunt.
                </p>
                <h2 class="text-xl tracking-tight font-bold text-gray-900 md:text-2xl mt-5">
                    Mijn hobby's
                </h2>
                <p class="mt-2 max-w-md text-base text-gray-500 sm:text-lg md:max-w-3xl">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam sollicitudin, diam eget fermentum rutrum, neque erat dapibus arcu, vitae varius lectus sem dictum ex. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Nam dapibus dolor a orci semper, nec elementum arcu porta.
                </p>
            </div>
            <div class="grid grid-cols-1 content-center">
                <img src="/images/personal_picture.jpg" alt="Picture of Daniël van der Spoel" class="shadow-lg rounded-lg">
            </div>
        </section>
        <section class="mx-auto max-w-7xl px-4 md:px-16 py-8">
            <h1 class="text-xl tracking-tight font-bold text-gray-900 md:text-2xl">
                Wat kan ik allemaal?
            </h1>
            <p class="mt-2 max-w-md text-base text-gray-500 sm:text-lg md:max-w-3xl">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam sollicitudin, diam eget fermentum rutrum, neque erat dapibus arcu, vitae varius lectus sem dictum ex.
            </p>
            <div class="grid grid-cols-4 gap-4 mt-4">
                <div class="bg-white shadow rounded-md p-4">
                    <div class="inline-flex items-center p-3 border border-transparent rounded-full shadow-sm text-white bg-cyan-400">
                        <!-- h-6 w-6 -->
                    </div>
                    <h3 class="text-xl font-semibold text-gray-900 mt-2 ">Laravel websites (PHP)</h3>
                    <p class="mt-2 text-base text-gray-500">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam sollicitudin, diam eget fermentum rutrum, neque erat dapibus arcu, vitae varius lectus sem dictum ex.
                    </p>
                    <div class="mt-2">
                        <a class="text-cyan-400 font-semibold hover:text-cyan-600 cursor-pointer">
                            Projecten bekijken
                        </a>
                    </div>
                </div>

            </div>
        </section>
    </div>
</template>

<script>
import Navbar from "../components/Navbar";
import HomeAnimation from "../components/HomeAnimation";
import { ArrowDownIcon, } from '@heroicons/vue/outline'

export default {
    name: "Home",
    components: {HomeAnimation, Navbar, ArrowDownIcon}
}
</script>

<style scoped>

</style>
