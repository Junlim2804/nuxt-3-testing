<template>
   <div class='shadow-2xl border-2 max-w-screen-xl font-sans md:mx-auto'>
        <div
            class='hidden box-border w-auto px-4 md:flex items-center flex-col h-full fixed bg-gradient-to-b from-indigo-300 via-green-300 to-white'>
            <img class='mx-10 my-20 h-48 border border-black' src='../images/profile_pic.jpg'>
            </img>
            <span class="text-2xl font-bold mb-2">Lim Tau Jun</span>
            <span class='nav-bar-text'><a href='#about'>About</a></span>
            <span class='nav-bar-text'><a href='#education'>Education</a></span>
            <span class='nav-bar-text'><a href='#skills'>Skills</a></span>
            <span class='nav-bar-text'><a href='#experience'>Experience</a></span>

            <div class='m-5 flex-col absolute bottom-0 space-x-3 justify-between'>
                <a href='https://www.facebook.com/profile.php?id=100001151920145'><span
                        class='text-3xl text-gray-400 hover:text-black transition-colors duration-600'><i
                            class="fab fa-facebook"></i></span></a>
                <a href='https://www.linkedin.com/in/junlim2804/'><span
                        class='text-3xl text-gray-400 hover:text-black transition-colors duration-600'><i
                            class="fab fa-linkedin"></i></span></a>
                <a href='https://www.github.com/junlim2804'><span
                        class='text-3xl text-gray-400 hover:text-black transition-colors duration-600'><i
                            class="fab fa-github "></i></span></a>
            </div>
        </div>
        <div class="md:ml-56 ">
            <section id="about" class='flex flex-col w-full p-10'>
                <span class='text-5xl font-semibold mb-5'>About</span>
                <div class="bg-indigo-700 flex flex-col p-4">
                    <span class="text-white text-xl">Name : <span class='text-2xl'>Lim Tau Jun</span></span>
                    <span class="text-white text-xl">Age : <span class='text-2xl'>24</span></span>
                    <span class="text-white text-xl">Email : <a href="mailto:junlim2804@gmail.com"><span
                                class='text-2xl'>junlim2804@gmail.com</span></a></span>
                </div>

                <div class='text-lg text-blacks mt-5'>
                    <h3 class="font-bold">Career Objective</h3>
                    Seeking position in Software developer that will allow me to explore career option in the IT sector
                    and further my knowledge in the IT domain and utilize my skills.
                </div>

            </section>
            <section id="education" class='flex flex-col px-10 justify-center '>
                <span class='text-5xl font-semibold mb-5'>Education</span>
                <div class="grid grid-cols-3 border-2 border-black">
                    <div class="border-r-2 flex auto-cols-min items-center justify-center"><span>2018-2020</span></div>
                    <div class="px-2 col-span-2">Tunku Abdul Rahman University College KL Branch,Malaysia</div>
                    <div class="col-span-3 border-y-2 p-2 justify-center"> Completed Bachelor’s in software
                        engineering. Courses include AI programming, android
                        development, web development and software engineering. Obtain a CGPA of 3.90.
                    </div>
                    <div class="border-r-2 flex items-center justify-center"><span>2016-2018</span></div>
                    <div class="px-2 col-span-2">Tunku Abdul Rahman University College Penang Branch,Malaysia</div>
                    <div class="col-span-3 border-y-2 p-2 justify-center">Completed Diploma in Computer Science
                        (Computer Science and
                        Computer Mathematics). Courses
                        include Database system, HTML development, Java Web and Object-Oriented programming.
                        Obtained a
                        CGPA of 3.89.
                    </div>
                    <div class="border-r-2 flex items-center justify-center"><span>2015</span></div>
                    <div class="px-2 col-span-2">Sekolah Menengah Kebangsaan Bukit Mertajam</div>
                    <div class="col-span-3 border-y-2 p-2 justify-center">
                        Have 7As in Sijil Pelajaran Malaysia 2015.
                    </div>
                </div>
            </section>
            <section id="skills" class='flex flex-col p-10 '>
                <span class='text-5xl font-semibold mb-5'>Skills</span>
                <div class="flex w-full flex-col md:flex-row items-baseline ">
                    <div class="flex-1 flex-col space-y-3 m-10">
                        <h2 class="font-semibold text-3xl">Language</h2>
                        <div class="mb-1 text-base font-medium ">Chinese</div>
                        <div class=" bg-gray-200 rounded-full h-1.5">
                            <div class="bg-blue-600 h-1.5 rounded-full" style="width: 80%"></div>
                        </div>
                        <div class="mb-1 text-base font-medium ">English</div>
                        <div class=" bg-gray-200 rounded-full h-1.5">
                            <div class="bg-blue-600 h-1.5 rounded-full" style="width: 70%"></div>
                        </div>
                        <div class="mb-1 text-base font-medium ">Bahasa Melayu</div>
                        <div class="bg-gray-200 rounded-full h-1.5">
                            <div class="bg-blue-600 h-1.5 rounded-full" style="width: 60%"></div>
                        </div>

                    </div>
                    <div class="flex-1 flex-col space-y-3 mx-10">

                        <h2 class="font-semibold text-3xl">Programming Skills</h2>
                        <div class="mb-1 text-base font-medium ">Vue</div>
                        <div class="bg-gray-200 rounded-full h-1.5">
                            <div class="bg-green-600 h-1.5 rounded-full" style="width: 60%"></div>
                        </div>
                        <div class="mb-1 text-base font-medium ">Javascript</div>
                        <div class=" bg-gray-200 rounded-full h-1.5">
                            <div class="bg-green-600 h-1.5 rounded-full" style="width: 75%"></div>
                        </div>
                        <div class="mb-1 text-base font-medium ">CSS</div>
                        <div class=" bg-gray-200 rounded-full h-1.5">
                            <div class="bg-green-600 h-1.5 rounded-full" style="width: 70%"></div>
                        </div>
                        <div class="mb-1 text-base font-medium ">MySQL</div>
                        <div class="bg-gray-200 rounded-full h-1.5">
                            <div class="bg-green-600 h-1.5 rounded-full" style="width: 70%"></div>
                        </div>
                        <div class="mb-1 text-base font-medium ">C# .Net Framework</div>
                        <div class="bg-gray-200 rounded-full h-1.5">
                            <div class="bg-green-600 h-1.5 rounded-full" style="width: 70%"></div>
                        </div>
                        <div class="mb-1 text-base font-medium ">PHP Laravel</div>
                        <div class="bg-gray-200 rounded-full h-1.5">
                            <div class="bg-green-600 h-1.5 rounded-full" style="width: 50%"></div>
                        </div>
                        <div class="mb-1 text-base font-medium ">Python</div>
                        <div class="bg-gray-200 rounded-full h-1.5">
                            <div class="bg-green-600 h-1.5 rounded-full" style="width: 80%"></div>
                        </div>
                    </div>
                </div>
            </section>
            <section id='experience' class='flex flex-col p-10 space-y-10 '>
                <span class='text-5xl font-semibold mb-5'>Experience</span>
                <ol class="relative border-l border-gray-200 dark:border-gray-700">
                    <li class="mb-10 ml-4">
                        <div
                            class="absolute w-3 h-3 bg-gray-200 rounded-full -left-1.5 border border-white dark:border-gray-900 dark:bg-gray-700">
                        </div>
                        <time class="mb-1 text-xl font-normal leading-none">May 2021 to Present</time>
                        <h3 class="text-lg font-semibold  ">Toga Limited Sdn Bhd
                        </h3>
                        <p class="text-base font-normal ">
                        <ul class="list-disc ml-2 gap-2">
                            <li>Being a front-end web developer for web development and mini program developement.
                            </li>
                            <li>Experience in using Vue Js and wechat mini program</li>
                        </ul>
                        </p>
                    </li>
                    <li class="ml-4">
                        <div
                            class="absolute w-3 h-3 bg-gray-200 rounded-full -left-1.5 border border-white dark:border-gray-900 dark:bg-gray-700">
                        </div>
                        <time class="mb-1 text-xl font-normal leading-none">Feb 2020</time>
                        <h3 class="text-lg font-semibold ">Webbytes Sdn Bhd</h3>
                        <p class="text-base font-normal">
                        <ul class="list-disc ml-2 gap-2">
                            <li>Being a backend developer in REST API to provide access to third party and another team.
                            </li>
                            <li>Experience in using .Net Framework and SQL Database.</li>
                            <li>Responsible to migrate old system and refactor it to new system.</li>
                            <li>Modify and update backend API to provide support to mobile team.</li>
                        </ul>

                        </p>
                    </li>
                </ol>
            </section>
        </div>
    </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage'
})
</script>
