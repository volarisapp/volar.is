<script>
  import { fade } from 'svelte/transition';
  import '$lib/global.css';
</script>

<style>
  .button-primary {
    background-color: #f35c78;
    color: #fff;
    padding: 1rem;
    border-radius: 0.5rem;
    font-weight: bold;
    text-decoration: none;
    transition: background-color 0.3s ease;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .button-primary:hover {
    background-color: #ff7363;
  }

  .button-icon {
    margin-right: 1rem;
  }

  .button-description {
    font-size: 0.9rem;
  }
</style>

<div class="min-h-screen flex items-center justify-center bg-gray-900 text-white">
  <div class="py-8 bg-gray-800 rounded-lg shadow-lg p-10 text-center hover:shadow-xl transition duration-300" transition:fade={{ duration: 250 }}>
    <h1 class="text-4xl font-bold mb-8" transition:fade={{ duration: 250 }}>Contact Us</h1>
    <div class="max-w-3xl mx-auto">
      <p class="text-lg mb-6" transition:fade={{ duration: 250 }}>
        If you have any questions, feedback, or need support, feel free to join our Discord server or create an issue on our GitHub repository.
      </p>
      <!-- add fitting logos -->
      <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-8">
        <a href="https://discord.com/invite/your-discord-server-link" class="button-primary" transition:fade={{ duration: 250 }}>
          <img src="/discord-icon.png" alt="Discord Icon" class="button-icon">
          <div>
            <div>Join our Discord</div>
            <div class="button-description">Connect with our community and get instant support</div>
          </div>
        </a>
        <a href="https://github.com/volarisapp/volar.is/issues" class="button-primary" transition:fade={{ duration: 250 }}>
          <img src="/github-icon.png" alt="GitHub Icon" class="button-icon">
          <div>
            <div>Create a GitHub Issue</div>
            <div class="button-description">Report bugs or suggest features directly on GitHub</div>
          </div>
        </a>
      </div>
      <div class="text-lg" transition:fade={{ duration: 250 }}>
        <a href="/about" class="text-pink-accent font-bold hover:underline transition duration-300">Return to about</a>
      </div>
    </div>
  </div>
</div>
