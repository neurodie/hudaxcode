<script lang="ts">
  import NavBar from '../lib/components/NavBar.svelte';
  import SocialMedia from '../lib/components/SocialMedia.svelte';
  import profile from '../lib/assets/profile.jpg';
</script>

<svelte:head>
  <link rel="preload" href="{profile}" as="image">
</svelte:head>

<NavBar isFixed={true} />

<div class="flex flex-col items-center justify-center h-screen flex-wrap">
  <img class="w-40 h-40 rounded-full" src={profile} alt="" />
  <h1 class="mt-5 text-4xl text-white font-bold">hudaxcode</h1>
  <div class="text-xs font-sans text-white">"Just A children who like technology"</div>
  <SocialMedia />
</div>
c<div class="flex flex-col items-cjustify-between px-4 text-gray-200 font-sans text-center">© 2024 hihuda.pw | Privacy Policy | Disclaimer | Status - Powered by Muhamad Huda</div>