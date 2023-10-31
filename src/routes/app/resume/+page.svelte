<script>
    import { Header, Footer } from "/src/lib/components"
    import { Phone, Contact, AtSign, MapPin, Cog, BookOpenCheck, Codesandbox, HardDrive, BookHeart, Files, GraduationCap, Building2, CalendarRange, Medal, SearchCheck, Briefcase } from 'lucide-svelte'
</script>

<div>
    <Header />
</div>

<div class="grid grid-cols-1 md:grid-cols-2 gap-4 text-white px-4 md:px-64 mt-12 pb-14">
    <div class="items-center">
        <div class="flex flex-col items-center">
            <img src="/img/hans.png" alt="ME" class="w-40 h-40 rounded-full object-cover border-2 border-white">
        </div>
        <div class="mt-4 ml-4 flex flex-col items-center">
            <h1 class="text-5xl font-bold">HANNAH</h1>
            <h3 class="text-[26px]">WEB DEVELOPER</h3>
        </div>
        <div class="mt-8 ml-4">
            <div class="flex flex-col gap-4">
                <div class="flex items-center bg-gray-900 text-white p-2 rounded-full">
                    <div class="mr-2 pl-4">
                        <Contact class="w-10 h-10" />
                    </div>
                    <h3 class="text-[26px] font-bold">CONTACT</h3>
                </div>
                <div class="flex items-center">
                    <div class="mr-2 pl-14">
                        <MapPin />
                    </div>
                    <p>6000 Cebu City, Philippines</p>
                </div>
                <div class="flex items-center">
                    <div class="mr-2 pl-14">
                        <AtSign />
                    </div>
                    <p>hannahalsa04@gmail.com</p>
                </div>
                <div class="flex items-center">
                    <div class="mr-2 pl-14">
                        <Phone />
                    </div>
                    <p>+639 31006 4265</p>
                </div>
            </div>
        </div>
        <div class="mt-8 ml-4">
            <div class="flex flex-col gap-4">
                <div class="flex items-center bg-gray-900 text-white p-2 rounded-full">
                    <div class="mr-2 pl-4">
                        <Cog class="w-10 h-10" />
                    </div>
                    <h3 class="text-[26px] font-bold">SKILLS</h3>
                </div>
                <div class="flex items-center">
                    <div class="mr-2 pl-14">
                        <BookOpenCheck />
                    </div>
                    <p class="font-bold">HTML | CSS | BOOTSTRAP | SVELTEKIT | JAVASCRIPT</p>
                    
                </div>
                <div class="flex items-center">
                    <div class="mr-2 pl-14">
                        <Codesandbox />
                    </div>
                    <p>Microsoft 365: Word, Excel, Pttx</p>
                </div>
                <div class="flex items-center">
                    <div class="mr-2 pl-14">
                        <HardDrive />
                    </div>
                    <p>Google Drive | Outlook | Googlesheet</p>
                </div>
                <div class="flex items-center">
                    <div class="mr-2 pl-14">
                        <Files />
                    </div>
                    <p>Documentation | Email Support Management</p>
                </div>
                <div class="flex items-center">
                    <div class="mr-2 pl-14">
                        <BookHeart />
                    </div>
                    <p>Collaboration | Flexible | Detail-Oriented</p>
                </div>
            </div>
        </div>
        <div class="mt-8 ml-4">
            <div class="flex flex-col gap-4">
                <div class="flex items-center bg-gray-900 text-white p-2 rounded-full">
                    <div class="mr-2 pl-4">
                        <GraduationCap class="w-10 h-10" />
                    </div>
                    <h3 class="text-[26px] font-bold">EDUCATION</h3>
                </div>
                <div class="flex items-center">
                    <div class="mr-2 pl-14">
                        <Medal />
                    </div>
                    <p>Bachelor of Science in Information Technology</p>
                </div>
                <div class="flex items-center">
                    <div class="mr-2 pl-14">
                        <CalendarRange />
                    </div>
                    <p>2015 - 2019</p>
                </div>
                <div class="flex items-center">
                    <div class="mr-2 pl-14">
                        <Building2 />
                    </div>
                    <p>Asian College of Technology</p>
                </div>                
            </div>
        </div>
    </div>
    <div>
        <div class="mt-8 ml-4">
            <div class="flex flex-col gap-4">
                <div class="flex items-center bg-gray-900 text-white p-2 rounded-full">
                    <div class="mr-2 pl-4">
                        <SearchCheck class="w-10 h-10" />
                    </div>
                    <h3 class="text-[26px] font-bold">OVERVIEW</h3>
                </div>
                <div class="flex items-center">
                    <div class="mr-2 pl-14 flex flex-col items-center">
                        <p>Driven and detail-oriented developer with sufficient exposure to web development and a passion for continuous growth in both personal and professional aspects.
                            Eager to contribute my skills and enthusiasm to the team, while expanding my current knowledge, refining best practices, and staying current with the latest technological trends.
                            Committed to delivering quality output that drives business success
                        </p>
                    </div>
                    
                </div>
            </div>
        </div>
        <div class="mt-8 ml-4">
            <div class="flex flex-col gap-4">
                <div class="flex items-center bg-gray-900 text-white p-2 rounded-full">
                    <div class="mr-2 pl-4">
                        <Briefcase class="w-10 h-10" />
                    </div>
                    <h3 class="text-[26px] font-bold">WORK EXPERIENCE</h3>
                </div>
                <div class="flex items-center">
                    <div class="mr-2 pl-14 flex flex-col items-left">
                        <p class="font-bold">WEB DEVELOPER | RatesCalc</p>
                        <p>2021 - Present</p>
                        <ul class="list-disc pl-6">
                            <li>Implement front-end web pages based on Figma UX/UI designs</li>
                            <li>Collaborate with team lead in planning to ensure that feature specifications are achieved</li>
                            <li>Create and maintain specifications documentation for the assigned feature request</li>
                            <li>Assist in the development of reusable components for the web application software</li>
                            <li>Plan and create the database tables required for the assigned feature</li>
                            <li>Constant communication with the client for specification gathering and confirmation</li>
                            <li class="font-bold">Technologies: HTML, Javascript, CSS, SvelteKit, SQL, TailwindCSS, TypeScript, REST API, Git</li>
                        </ul>
                    </div>
                </div>
                <div class="flex items-center">
                    <div class="mr-2 pl-14 flex flex-col items-left">
                        <p class="font-bold">FRONT END DEVELOPER | AASIT Services</p>
                        <p>2019 - 2020</p>
                        <ul class="list-disc pl-6">
                            <li>Conceived and built optimized landing pages in HTML and CSS for integration and cross-browser compatibility.</li>
                            <li>Implement front-end web pages and maintain websites functionality.</li>
                            <li>Create and maintain user-friendly documentation for manual user process flows.</li>
                            <li>Develop visually appealing and easy-to-understand documentation, including diagrams, flowcharts, and step-by-step guides.</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

<div>
    <Footer />
</div>