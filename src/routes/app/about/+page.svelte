<script>
    import { Header, Footer } from "/src/lib/components"

    let skillsText = `
      - HTML, CSS, JavaScript
      - Svelte and SvelteKit
      - Tailwind CSS
      - Responsive Web Design
      - Web Accessibility
    `;


</script>

<style>
    .about-section {
        background-color: rgba(0, 0, 255, 0.1);
    }
    .image-card {
        display: flex;
        flex-wrap: wrap;
        gap: 20px;
    }

    .image-card img {
        width: 300px; /* 25% width with 10px gap between images */
        height: auto;
    }
</style>

  
<div>
    <Header />
</div>

<div class="container mx-auto py-10 text-gray-800 ">
    <h1 class="text-4xl font-semibold mb-8 text-white text-center">About Me</h1>

    <!-- Introduction -->
    <div class="grid grid-cols-1 md:grid-cols-1 gap-8 text-white">
        <div class="about-section p-6 rounded-lg shadow-lg">
            <h2 class="text-2xl font-semibold mb-4 text-center">Hobbies</h2>
            <p class="text-center">The majority of people see gaming as a hobby that is entertaining, sociable and a way to wind down. <b/></p>
            <p class="mb-4 text-center">It is one of my several interests and activities in my life alongside spending time with friends and family, going to school or work, and my daily responsibilities.</p>
            <div class="w-content flex items-center justify-center">
                <img src="/img/hobby1.jpg" alt="Group of Friends playing online game">
            </div>
        </div>
    </div>

    <!-- Hobbies and Travels -->
    <div class="grid grid-cols-1 md:grid-cols-2 gap-8 mt-8 text-white">
        <div class="about-section p-6 rounded-lg shadow-lg">
            <h2 class="text-2xl font-semibold mb-4">I LOVE CATS</h2>
            <div class="image-card flex flex-row items-center justify-center">
                <img src="/img/cat1.jpg" alt="Hobbies 1">
                <img src="/img/cat2.jpg" alt="Hobbies 2">
                <img src="/img/cat3.jpg" alt="Hobbies 3">
                <img src="/img/cat4.jpg" alt="Hobbies 4">
            </div>
        </div>

        <div class="about-section p-6 rounded-lg shadow-lg">
            <h2 class="text-2xl font-semibold mb-4">I LOVE TO TRAVEL</h2>
            <div class="image-card flex flex-row items-center justify-center">
                <img src="/img/travel1.jpg" alt="Blue sky and ocean with bended coconut tree">
                <img src="/img/travel2.jpg" alt="Tiffany's back">
                <img src="/img/travel3.jpg" alt="Blue sky and ocean with coconut trees">
                <img src="/img/travel4.jpg" alt="Blue sky and ocean with coconut trees">
            </div>
        </div>
    </div>

    <!-- Work Environment -->
    <div class="about-section p-6 mt-8 rounded-lg shadow-lg text-white">
        <h2 class="text-2xl font-semibold mb-4">Work Environment and Teammates</h2>
        <p class="text-center">
            My ideal work environment is one that fosters creativity and collaboration with my teammates. I thrive in a dynamic and agile setting, where I can brainstorm ideas, share insights, and work together with my team to bring them to life using the latest web technologies.
            Whether it's a cozy co-working space or a bustling agency, I'm always eager to adapt and learn from my surroundings, and I value the input and support of my teammates. A collaborative environment is where innovative solutions are born, and I believe that the work environment plays a crucial role in shaping the quality of our work and our ability to innovate.
        </p>
        <div class="w-content flex items-center justify-center">
            <img src="/img/team1.png" alt="Dev Team group pic">
        </div>
    </div>
</div>

<div>
    <Footer />
</div>