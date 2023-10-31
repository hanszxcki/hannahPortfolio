<script>

let tabs = [
    {
        name: "Home",
        link: "/",
    },
    {
        name: "About Me",
        link: "/app/about",
    },
    {
        name: "Resume",
        link: "/app/resume",
    },
]

</script>

<header class="sticky z-10 top-0 duration-200 px-4 sm:px-64 md:px-64 flex items-center justify-between bg-gray-900 w-full p-4 text-white font-noto-sans-jp">
    <h1>
        <b>Hannah</b> Alsa
    </h1>
    <div class="flex items-center gap-4">
        {#each tabs as tab}
        <ul class="font-mono">
            <li><a href={tab.link} class="text-gray-300 hover:bg-gray-700 hover:text-white rounded-md px-3 py-2 text-sm font-medium">{tab.name}</a></li>
        </ul>
        {/each}
    </div>
</header>
    