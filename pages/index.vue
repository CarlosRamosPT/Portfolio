<!-- eslint-disable prettier/prettier -->
<template>
    <div class="h-full">
        <main>
            <div class="md:pt-16 lg:pt-32"></div>
            <section class="px-12 md:px-16 lg:px-48 xl:px-72 py-12 text-yellow-100">

                <h2 class="text-4xl" md:text-5xl>I'm Carlos <br /> — <br /> A learning Software Developer</h2>

                <h1 class="text-6xl md:text-[8rem] lg:text-[9rem]">Ambitious into
                     <span class="bg-gradient-to-r from-yellow-100 to-blue-900 bg-clip-text text-transparent font-extrabold tracking-wide">Delving

                     </span> 
                     <span class="bg-gradient-to-r from-yellow-100 to-blue-900 bg-clip-text text-transparent font-extrabold tracking-wide">Further

                     </span>
                </h1>
            </section>

            <section class="bg-[#000000] bg-[radial-gradient(#ffffff33_1px,#00091d_1px)] bg-[size:20px_20px] py-12">
                <h2 class="pb-6 text-4xl md:text-5xl ld:text-6xl text-yellow-100 text-center">About Me</h2>
                <p class="px-5 text-lg md:px-24 md:text-xl lg:px-48 lg:text-2xl xl:px-96  text-gray-300">I am currently coming from a different are being previously an <span class="font-extrabold text-yellow-200">Assistant General Manager</span> <br />Having been a <span class="font-extrabold text-yellow-200">trainer</span> for a team of <span class="font-extrabold text-yellow-200">50 people</span> leading the shifts from the front, and being part of the recruitment team. <br />With an keen interest in development since interacting for a <span class="font-extrabold text-yellow-200">game modding</span>, wanted to pursue the career in <span class="font-extrabold text-yellow-200">software development</span>.</p>
            </section>

            <section class="py-12">
                <h2 class="pb-6 text-5xl md:text-6xl ld:text-7xl text-yellow-600 text-center">Technical Skills</h2>
                    <progression />
                    <div class="grid grid-cols1 gap-2 lg:grid-cols-3">  
                        <div class=" grid pb-4 grid-cols-1 gap-4 ">
                            <div class="border-2 rounded-lg border-yellow-100 py-2 px-6 border-dashed bg-[#000000] bg-[radial-gradient(#ffffff33_1px,#00091d_1px)] bg-[size:20px_20px]">
                                <div class="flex h-fit flex-row items-center pb-6">
                                    <img class="w-8" src="/assets/images/code-2-svgrepo-com.svg" alt="code logo">
                                    <h3 class="pl-6 text-xl font-extrabold text-yellow-100">
                                        Languages and Frameworks
                                    </h3>
                                </div>
                                <div class="grid grid-cols-4 gap-2">
                                    <div class="flex flex-col justify-center items-center basic">
                                        <div>
                                            <img class="w-12" src="/assets/images/javascript-svgrepo-com.svg" alt="Javascript logo">
                                            <p>Javascript</p>
                                        </div>
                                    </div>
                                    <div class="flex flex-col justify-center items-center basic">
                                        <div>
                                            <img class="w-12" src="/assets/images/python-svgrepo-com.svg" alt="Python logo">
                                            <p>Python</p>
                                        </div>
                                    </div>
                                    <div class="flex flex-col items-center medium">
                                        <div>
                                            <img class="w-12" src="/assets/images/html-5-svgrepo-com.svg" alt="html logo">
                                            <p>HTML</p>
                                        </div>
                                    </div>
                                    <div class="flex flex-col justify-center items-center medium">
                                        <div>
                                            <img class="w-12" src="/assets/images/css-3-svgrepo-com.svg" alt="CSS logo">
                                            <p>CSS</p>
                                        </div>
                                    </div>
                                    <div class="flex flex-col justify-center items-center medium">
                                        <div>
                                            <img class="w-12" src="/assets/images/node-16-svgrepo-com.svg" alt="Node logo">
                                            <p>Node JS</p>
                                        </div>
                                    </div>
                                    <div class="flex flex-col items-center learning">
                                        <div>
                                            <img class="w-12" src="/assets/images/deno-svgrepo-com.svg" alt="Deno logo">
                                            <p>Deno</p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="grid pb-4 grid-cols-1 gap-4">
                            <div class="border-2 rounded-lg border-yellow-100 py-2 px-6 border-dashed bg-[#000000] bg-[radial-gradient(#ffffff33_1px,#00091d_1px)] bg-[size:20px_20px]">
                                <div class="flex flex-row items-center pb-6">
                                    <img class="w-8" src="/assets/images/database-svgrepo-com.svg" alt="Database Logo">
                                    <h3 class="pl-6 text-xl font-extrabold text-yellow-100">
                                        Databases and System Controls
                                    </h3>
                                </div>
                                <div class="grid grid-cols-4 gap-2">
                                    <div class="flex flex-col items-center basic">
                                        <img class="w-12 h-10" src="/assets/images/mysql-svgrepo-com.svg" alt="My Sql logo">
                                        <p>MY SQL</p>
                                    </div>
                                    <div class="flex flex-col items-center basic">
                                        <img class="w-12 h-10" src="/assets/images/git-svgrepo-com.svg" alt="Git logo">
                                        <p>Git</p>
                                    </div>
                                    <div class="flex flex-col items-center basic">
                                        <img class="w-12 h-10" src="/assets/images/github-142-svgrepo-com.svg" alt="Github logo">
                                        <p>Github</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="grid pb-4 grid-cols-1 gap-4">
                            <div class="border-2 rounded-lg border-yellow-100 py-2 px-6 border-dashed bg-[#000000] bg-[radial-gradient(#ffffff33_1px,#00091d_1px)] bg-[size:20px_20px]">
                                <div class="flex flex-row items-center pb-6">
                                    <img class="w-12 h-12" src="/assets/images/rust-svgrepo-com.svg" alt="Rust Logo">
                                    <h3 class="pl-6 text-xl font-extrabold text-yellow-100">
                                        Future Learnings
                                    </h3>
                                </div>
                                <div class="grid grid-cols-4 gap-2">
                                    <div class="flex flex-col items-center learning">
                                        <img class="w-12 h-10" src="/assets/images/java-svgrepo-com.svg" alt="Java logo">
                                        <p>Java</p>
                                    </div>
                                    <div class="flex flex-col items-center learning">
                                        <img class="w-12 h-10" src="/assets/images/cpp-svgrepo-com.svg" alt="CPP logo">
                                        <p>C++</p>
                                    </div>
                                    <div class="flex flex-col items-center">
                                        <img class="w-12 h-10" src="/assets/images/Carbon_logo.png" alt="Carbon logo">
                                        <p>Carbon</p>
                                    </div>
                                    <div class="flex flex-col items-center">
                                        <img class="w-12 h-10" src="/assets/images/rust-svgrepo-com.svg" alt="Rust logo">
                                        <p>Rust</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>


            </section>
            <section class="py-12">
                <h2 class="pb-6 text-5xl md:text-6xl ld:text-7xl text-yellow-600 text-center">Soft Skills</h2>
                    <progression />
                    <div class="grid grid-cols1 gap-2 lg:grid-cols-3">
                        <div class="grid pb-4 grid-cols-1 gap-4">
                            <div class="border-2 rounded-lg border-yellow-100 py-2 px-6 bg-[#000000] bg-[radial-gradient(#ffffff33_1px,#00091d_1px)] bg-[size:20px_20px] border-dashed">
                                <div class="flex flex-row items-center pb-6 ">
                                    <img class="w-8 bg-gray-500/50 rounded-xl "  src="/assets/images/leadership-svgrepo-com.svg" alt="Leadership logo">
                                    <h3 class="pl-6 text-xl font-extrabold text-yellow-100">
                                        Leadership skills
                                    </h3>
                                </div>
                                <div class="grid grid-cols-4 gap-2 ">
                                    <div class="flex flex-col items-center advanced">
                                        <img class="w-12" src="/assets/images/leadership-svgrepo-com.svg" alt="Leadership logo">
                                        <p>Leadership</p>
                                    </div>
                                    <div class="flex flex-col items-center advanced">
                                        <img class="w-12" src="/assets/images/search-for-staff-svgrepo-com.svg" alt="Search for staff logo">
                                        <p>Recruitment</p>
                                    </div>
                                    <div class="flex flex-col items-center advanced">
                                        <img class="w-12" src="/assets/images/training-class-svgrepo-com.svg" alt="Training logo">
                                        <p>Training</p>
                                    </div>
                                    <div class="flex flex-col items-center advanced">
                                        <img class="w-12" src="/assets/images/time-management-hourglass-svgrepo-com.svg" alt="Time Management logo">
                                        <p>Time Management</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="grid pb-4 grid-cols-1 gap-4">
                            <div class="border-2 rounded-lg border-yellow-100 py-2 px-6 border-dashed bg-[#000000] bg-[radial-gradient(#ffffff33_1px,#00091d_1px)] bg-[size:20px_20px]">
                                <div class="flex flex-row items-center pb-6">
                                    <img class="w-8" src="/assets/images/flag-for-flag-portugal-svgrepo-com.svg" alt="Portugal Logo">
                                    <h3 class="pl-6 text-xl font-extrabold text-yellow-100">
                                        Languages spoken
                                    </h3>
                                </div>
                                <div class="grid grid-cols-4 gap-2">
                                    <div class="flex flex-col items-center advanced">
                                        <img class="w-12" src="/assets/images/flag-for-flag-portugal-svgrepo-com.svg" alt="Portugal flag">
                                        <p>Portuguese</p>
                                    </div><div class="flex flex-col items-center advanced">
                                        <img class="w-12" src="/assets/images/flag-for-spain-svgrepo-com.svg" alt="Spain flag">
                                        <p>Spanish</p>
                                    </div>
                                    <div class="flex flex-col items-center advanced">
                                        <img class="w-12" src="/assets/images/united-kingdom-uk-svgrepo-com.svg" alt="United Kingdom flag">
                                        <p>English</p>
                                    </div>
                                    <div class="flex flex-col items-center basic">
                                        <img class="w-12" src="/assets/images/flag-for-flag-france-svgrepo-com.svg" alt="France Flag">
                                        <p>French</p>
                                    </div>
                                    <div class="flex flex-col items-center basic">
                                        <img class="w-12" src="/assets/images/italy-svgrepo-com.svg" alt="Italy Flag">
                                        <p>Italian</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="grid pb-4 grid-cols-1 gap-4">
                            <div class="border-2 rounded-lg border-yellow-100 py-2 px-6 border-dashed bg-[#000000] bg-[radial-gradient(#ffffff33_1px,#00091d_1px)] bg-[size:20px_20px]">
                                <div class="flex flex-row items-center pb-6">
                                    <img class="w-8" src="/assets/images/time-management-hourglass-svgrepo-com.svg" alt="time management logo">
                                    <h3 class="pl-6 text-xl font-extrabold text-yellow-100">
                                        Future Learnings
                                    </h3>
                                </div>
                                <div class="grid grid-cols-4 gap-2">
                                    <div class="flex flex-col items-center learning">
                                        <img class="w-12" src="/assets/images/japan-svgrepo-com.svg" alt="Japan Flag">
                                        <p>Japanese</p>
                                    </div>
                                    <div class="flex flex-col items-center learning">
                                        <img class="w-12" src="/assets/images/flag-for-flag-germany-svgrepo-com.svg" alt="German Flag">
                                        <p>German</p>
                                    </div>
                                    <div class="flex flex-col items-center learning">
                                        <img class="w-12" src="/assets/images/blender-svgrepo-com.svg" alt="Blender logo">
                                        <p>Blender</p>
                                    </div>
                                    <div class="flex flex-col items-center learning">
                                        <img class="w-12" src="/assets/images/unrealengine-svgrepo-com.svg" alt="unreal logo">
                                        <p>Unreal</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>


            </section>

        </main>
    </div>
</template>

<script setup lang="ts">
definePageMeta({
    layout: "home"
});
</script>

