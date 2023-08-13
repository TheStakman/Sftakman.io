<script>
  import Navbar from '../lib/components/+navbar.svelte'; // Adjust the path based on your project structure
</script>
<main>
  <Navbar />
  <section class="flex justify-center items-center bg-zinc-950">
    <div class="video-container">
      <video class="responsive-video" muted autoplay loop playsinline disablePictureInPicture>
        <source src="/umbrella.webm" type="video/webm"/>
      </video>
    </div>
  </section>
</main>
<style lang="postcss">
  :global(html) {
    background-color: theme(colors.zinc.950);
  }
  .video-container {
   width: 100%;
   height: 100%;
   display: flex;
   justify-content: center; /* Horizontal centering */
   align-items: center; /* Vertical centering */
  }
  .responsive-video {
    position: center;
    width: 98%;
    height: 30%;
    border-radius: 5px; /* Adjust the value to control the amount of rounding */ 
  }
</style>