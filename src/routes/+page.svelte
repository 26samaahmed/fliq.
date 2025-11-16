<svelte:head>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" />
  <link
    href="https://fonts.googleapis.com/css2?family=Aclonica&family=Aldrich&family=Arimo:ital,wght@0,400..700;1,400..700&display=swap"
    rel="stylesheet"
  />
</svelte:head>

<script>
  import frame1 from '$lib/assets/frame1.svg';
  import chatbotIcon from '$lib/assets/chatbot-icon.svg';
  import profileIcon from '$lib/assets/profile-icon.svg';
</script>


<main class="bg-[#333745] min-h-screen p-6">
  <div class="flex items-center justify-between mb-8">
    <p class="font-aclonica text-5xl text-[#FE5F56]">fliq.</p>
  
    <div class="flex items-center gap-12">
      <img src="{chatbotIcon}" alt="Chatbot Icon" class="w-8 h-8" />
      <img src="{profileIcon}" alt="Profile Icon" class="w-8 h-8" />
    </div>
  </div>
  

  <div class="text-center">
    <h1 class="font-aldrich text-4xl text-white">Welcome!</h1>
    <p class="font-arimo text-xl text-[#E8F1F2] mt-5 w-230 mx-auto">
      <i>Create and customize photo memories with your friends in real time as fliq. brings the photo booth experience to you wherever you are.</i>
    </p>
    <button class="bg-[#EFF5DC] text-[#333745] font-aldrich p-3 rounded-full mt-10">
      Start Taking Pictures
    </button>
  </div>
  

  <div class="mt-10">
    <img src="{frame1}" alt="Frame 1" class="mx-auto w-50 h-30 h-auto rounded-lg shadow-lg" />
  </div>
</main>


<style>
  .font-aldrich {
    font-family: 'Aldrich', sans-serif;
  }

  .font-arimo {
    font-family: 'Arimo', sans-serif;
  }

  .font-aclonica {
    font-family: 'Aclonica', sans-serif;
  }
</style>

