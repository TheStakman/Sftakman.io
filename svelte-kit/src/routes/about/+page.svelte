<script>
    import Navbar from '../../lib/components/+navbar.svelte';
</script>
<main>
    <Navbar />
    <body>
        <div class="wrapper">
            <div class="banner">
                <img src="setup.jpg" alt="setup" class="rounded-md border border-pink-500">
            </div>
            <div class="about-area p-8 flex flex-col md:flex-row bg-zinc-950 mt-4 md:mt-0 md:ml-4 flex-1 text-white">
                <div class="description">
                    <h1 class="text-2xl border-b-2 border-pink-500 pb-2 mb-4"> About Me </h1>
                    <p>
                        Hey! I'm Lynnelle. Right now, I'm employed at Wildcard Corp. as a Jr. DevOps Engineer/Systems Administrator. 
                        My journey with the company started two years ago during my junior year at the University of Wisconsin - Stevens Point. 
                        I began as a Web Developer intern, fell in love with Kubernetes and DevOps work, and then smoothly transitioned 
                        into the roles I enjoy today.
                        <br>
                        <br> 
                        When I'm not at work, you'll still find me in front of my computer, except I'd be playing PC games.
                        Usually FPS, Battle Royales and MMORPGs catch my interest the most, with Overwatch 2 and Apex Legends being my
                        current favorites. If I'm away from my computer, you can find me watching anime, strumming my guitar, and making 
                        sure my dogs get their walks and playtime.
                    </p>
                </div>
                <div class="me-pic mx-auto p-10">
                    <img src="graduation.jpg" alt="lynn desu" class="rounded-md border-2 border-pink-500 max-w-xs">
                </div>
            </div>   
        </div>
    </body>
</main>


<style>

    /* set the background color to match the navbar */
    .wrapper {
        background-color: #09090b;
    }

    /* font color of my about description */
    .description {
        color: white;
    }

    /* line under "About Me" heading */
    .description h1 {
        width: 35%;
    }

    /* the banner image size */
    .banner img{
        width: 100%;
        height: 600px;
    }

    p {
        line-height: 2;
        font-size: 18px;
    }
</style>