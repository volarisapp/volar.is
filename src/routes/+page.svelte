<script>
  import '$lib/global.css';
  import { fade } from 'svelte/transition';
</script>

<style>
  .background-animation {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: linear-gradient(135deg, #0000, #f35c78, #ff7363, #ffacbb, #f8627e);
    background-size: 1200% 1200%;
    animation: gradientAnimation 15s ease infinite;
  }

  @keyframes gradientAnimation {
    0% {
      background-position: 0% 50%;
    }
    50% {
      background-position: 100% 50%;
    }
    100% {
      background-position: 0% 50%;
    }
  }
</style>

<svelte:head>
  <title>Leo Hanney - Volaris</title>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
</svelte:head>

<div class="background-animation" transition:fade={{ duration: 250 }}></div>
  <div class="relative py-8" transition:fade={{ duration: 250 }}>
    <div class="container mx-auto relative z-10">
      <h1 class="text-5xl font-bold text-white mb-6" transition:fade={{ duration: 250 }}>Welcome to Volaris</h1>
      <p class="text-lg text-white mb-8" transition:fade={{ duration: 250 }}>Volaris is an encryption tool designed to prioritize privacy and security. Built using Rust, it offers a modern and efficient solution for securing your data across multiple platforms, including desktops, command-line interfaces (CLI), and mobile devices.</p>
      <a href="/about" class="bg-white text-pink-400 font-bold py-3 px-6 rounded-full transition duration-300 hover:bg-pink-400 hover:text-white" transition:fade={{ duration: 250 }}>Learn More</a>
    </div>
</div>

