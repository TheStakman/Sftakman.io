<!-- <main>
<section class="flex h-[80vh] shrink-0 flex-col items-center justify-center bg-secondary-500">
    <video muted autoplay loop playsinline disablepictureinpicture>
        <source src="/umbrella.webm" type="video/webm"/> 
    </video> 
    <h1 class="text-6l">Moving Scapes</h1> 
    <button class="text-4xl">Subscribe</button>
</section>
</main> -->
<main>
  <section class="flex h-[80vh] shrink-0 flex-col items-center justify-center bg-secondary-800">
    <div class="video-container">
      <video class="responsive-video" muted autoplay loop playsinline disablepictureinpicture>
        <source src="/umbrella.webm" type="video/webm"/>
      </video>
      </div>
  </section>
</main>
  
<style>
  .video-container {
    position: relative;
    width: 100%;
    max-width: 2000px; /* Adjust as needed */
    padding-top: 56.25%; /* 16:9 aspect ratio */
    overflow: hidden;
  }

  .responsive-video {
    position: absolute;
    width: 100%;
    height: 80%;
    top: 0;
    left: 0;
    object-fit: cover;
  }
</style>