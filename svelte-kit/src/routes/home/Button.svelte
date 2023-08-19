<script>
  // when the button is clicked it will call this function
  function redirectToAboutPage() {
    // this will redirect the user to the /about page
    window.location.href = "about";
  }
</script>

<!-- setting the button class and onclick function, as well as content of button -->
<button class="button" on:click={redirectToAboutPage}>Explore</button>

<!-- styling of button -->
<style lang="postcss">
.button {
    background-color: transparent;
    color: #6B46C1;
    font-weight: 600;
    border: 1px solid #6B46C1;
    border-radius: 0.25rem;
    padding: 0.5rem 1rem;
    cursor: pointer;
    transition: background-color 0.3s, color 0.3s, border-color 0.3s;
  }

  .button:hover {
      background-color: #6B46C1;
      color: white;
      border-color: transparent;
  }
</style>