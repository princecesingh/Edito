<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Edito - Video Editing Service</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    html {
      scroll-behavior: smooth;
    }
  </style>
</head>
<body class="bg-gray-100 text-gray-800 font-sans">

  <!-- Hero Section -->
  <section class="min-h-screen flex flex-col justify-center items-center bg-black text-white text-center p-6">
    <h1 class="text-4xl md:text-6xl font-bold mb-4">Edito</h1>
    <p class="text-lg md:text-xl max-w-xl mb-6">Professional video editing for everyone. Upload your video or just write a prompt, and I’ll turn it into something amazing!</p>
    <a href="#demo" class="bg-white text-black px-6 py-3 rounded-full font-semibold hover:bg-gray-200 transition">See Demo</a>
  </section>

  <!-- Demo Section -->
  <section id="demo" class="py-16 px-4 bg-white">
    <h2 class="text-3xl font-bold text-center mb-10">Demo Videos</h2>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-6 max-w-6xl mx-auto">
      <!-- Replace these video links with your own -->
      <video controls class="rounded-lg shadow" src="demo1.mp4"></video>
      <video controls class="rounded-lg shadow" src="demo2.mp4"></video>
      <video controls class="rounded-lg shadow" src="demo3.mp4"></video>
      <!-- Add up to 10 videos -->
    </div>
  </section>

  <!-- Request Section -->
  <section class="py-16 px-4 bg-gray-100">
    <h2 class="text-3xl font-bold text-center mb-10">Submit a Request</h2>
    <div class="max-w-4xl mx-auto grid md:grid-cols-2 gap-8">
      <div class="flex flex-col">
        <label class="mb-2 font-medium">Upload Your Video</label>
        <input type="file" class="p-3 rounded border border-gray-300" />
      </div>
      <div class="flex flex-col">
        <label class="mb-2 font-medium">Write Your Prompt</label>
        <textarea rows="5" class="p-3 rounded border border-gray-300" placeholder="Describe your idea..."></textarea>
      </div>
    </div>
  </section>

  <!-- Talk to Me Section -->
  <section class="py-16 px-4 bg-white text-center">
    <h2 class="text-3xl font-bold mb-6">Talk to Me</h2>
    <p class="text-lg mb-4">If you want to make an edit after here, go on Instagram and message me on 
      <a href="https://instagram.com/prince452935" class="text-blue-500 font-semibold" target="_blank">@prince452935</a>
    </p>
  </section>

  <!-- Pricing Section -->
  <section class="py-16 px-4 bg-gray-100 text-center">
    <h2 class="text-3xl font-bold mb-6">Pricing</h2>
    <p class="text-lg">INR 20 for people in India / $1 for other countries</p>
    <p class="text-sm mt-2">Payment via Google Pay (ID available on Instagram)</p>
  </section>

  <!-- Contact Section -->
  <section class="py-16 px-4 bg-black text-white text-center">
    <h2 class="text-3xl font-bold mb-6">Contact</h2>
    <p>Instagram: <a href="https://instagram.com/prince452935" target="_blank" class="text-blue-400">@prince452935</a></p>
    <p>Email: <a href="mailto:vaibhavsingh5266@gmail.com" class="text-blue-400">vaibhavsingh5266@gmail.com</a></p>
  </section>

</body>
</html>
