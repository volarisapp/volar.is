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
    <h1 class="text-4xl font-bold mb-8" transition:fade={{ duration: 250 }}>Download Volaris Mobile</h1>
    <div class="max-w-3xl mx-auto">
      <p class="text-lg mb-6" transition:fade={{ duration: 250 }}>
        Download the latest version of Volaris for your mobile device. Choose the appropriate version for your platform.
      </p>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-8">
        <a href="/downloads/volaris-mobile-android.apk" class="bg-pink-accent text-white font-bold py-3 px-8 rounded-full transition duration-300 hover:bg-pink-500" transition:fade={{ duration: 250 }}>Download for Android</a>
        <p class="bg-pink-accent text-white font-bold py-3 px-8 rounded-full transition duration-300 cursor-not-allowed grayscale relative group">
          <span class="group-hover:hidden">Download for iOS</span>
          <span class="hidden group-hover:inline">Coming Soon</span>
        </p>
      </div>
      <div class="text-lg" transition:fade={{ duration: 250 }}>
        <a href="/download" class="text-pink-accent font-bold hover:underline transition duration-300">Back to Downloads</a>
      </div>
    </div>
  </div>
</div>
  