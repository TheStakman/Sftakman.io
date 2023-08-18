<script>
  import Navbar from '../lib/components/+navbar.svelte';
</script>
<main>
  <Navbar />
  <section class="flex flex-col shrink-0 video-container">
    <video class="-z-10 responsive-video" muted autoplay loop playsinline disablePictureInPicture>
      <source src="/dreamytemple.webm" type="video/webm"/>
    </video>
    <h1 class="text-6xl">Welcome to my website</h1>
    <button class="text-4xl">Learn More</button>
  </section>
</main>

<!-- css styling -->
<style lang="postcss">
  :global(html) {
    background-color: theme(colors.zinc.950);
  }
  .video-container {
    position: relative;
    width: 100%;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    overflow: hidden;
  }
  .responsive-video {
    position: absolute;
    width: 100%;
    height: 100%;
    object-fit: cover;
  }

  /* tablet styles */
  @media (max-width: 1024px) {
    .responsive-video {
      width: 100%;
      height: 100%;
      transform: translateX(-15%) scale(1.5);
      transform-origin: left center;
    }
  }

  /* mobile styles */
  @media (max-width: 768px) {
    .responsive-video {
      width: 100%;
      height: 100%;
      transform: translateX(-15%) scale(1.5); 
      transform-origin: left center; 
    }
  }
</style>