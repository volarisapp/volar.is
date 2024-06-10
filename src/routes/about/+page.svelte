<script>
  import { fade } from 'svelte/transition';
  import '$lib/global.css';
</script>

<svelte:head>
  <title>Leo Hanney - Volaris</title>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
</svelte:head>

<div class="min-h-screen flex items-center justify-center bg-gray-900 text-white">
  <div class="py-8 bg-gray-800 rounded-lg shadow-lg p-10 text-center hover:shadow-xl transition duration-300" transition:fade={{ duration: 250 }}>
    <h1 class="text-4xl font-bold mb-8" transition:fade={{ duration: 250 }}>About Volaris</h1>
    <div class="max-w-3xl mx-auto">
      <p class="text-lg mb-6" transition:fade={{ duration: 250 }}>
        Volaris is an encryption tool designed to prioritize privacy and security. Built using Rust, it offers a modern and efficient solution for securing your data across multiple platforms, including desktops, command-line interfaces (CLI), and mobile devices.
      </p>
      <p class="text-lg mb-6" transition:fade={{ duration: 250 }}>
        Volaris is currently in development. We are working hard to bring you a secure and user-friendly encryption tool. Stay tuned for updates and releases.
      </p>
      <h2 class="text-2xl font-bold mb-4" transition:fade={{ duration: 250 }}>Key Features</h2>
      <ul class="text-lg text-left mb-8 space-y-2">
        <li class="flex items-center"><span class="text-pink-accent mr-2">•</span>Cross-Platform Support: Available on desktop, CLI, and mobile devices.</li>
        <li class="flex items-center"><span class="text-pink-accent mr-2">•</span>Rust-Based Security: Leveraging Rust's safety and performance features.</li>
        <li class="flex items-center"><span class="text-pink-accent mr-2">•</span>Modern Encryption Standards: Uses the latest encryption algorithms to ensure data security.</li>
      </ul>
      <div class="flex justify-center mb-8" transition:fade={{ duration: 250 }}>
        <p class="bg-pink-accent text-white font-bold py-3 px-8 rounded-full transition duration-300 hover:bg-pink-accent hover:text-gray-900 mr-4 cursor-not-allowed grayscale relative group">
        <span class="group-hover:hidden">Explore Features</span>
        <span class="hidden group-hover:inline">Coming Soon</span>
        </p>
        <a href="/download" class="bg-transparent border border-pink-accent text-pink-accent font-bold py-3 px-8 rounded-full transition duration-300 hover:bg-pink-accent hover:text-white">Download Now</a>
      </div>
      <div class="text-lg" transition:fade={{ duration: 250 }}>
        <a href="/contact" class="text-pink-accent font-bold hover:underline transition duration-300">Contact Us</a> or
        <a href="/" class="text-pink-accent font-bold hover:underline transition duration-300">Return to Home</a>
      </div>
    </div>
  </div>
</div>
