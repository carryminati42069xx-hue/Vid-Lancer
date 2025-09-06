# Vid-Lancer<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vid Lancer | Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #121212;
            color: #E0E0E0;
        }
        .container {
            max-width: 1200px;
        }
        .card {
            background-color: #1E1E1E;
            border: 1px solid #333;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
        }
        .portfolio-image {
            transition: transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
            cursor: pointer;
        }
        .portfolio-image:hover {
            transform: scale(1.05);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.5);
        }
    </style>
</head>
<body class="flex flex-col items-center p-4 md:p-8">

    <!-- Header and Bio Section -->
    <header class="w-full text-center py-12 md:py-16">
        <div class="inline-block p-4 rounded-full bg-gradient-to-r from-blue-500 to-purple-600 shadow-xl">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-16 w-16 md:h-24 md:w-24 text-white" viewBox="0 0 24 24" fill="currentColor">
                <path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm1 15h-2v-2h2v2zm0-4h-2V7h2v6z"/>
            </svg>
        </div>
        <h1 class="text-4xl md:text-6xl font-extrabold mt-6 text-white tracking-tight">Piyaus Sarkar</h1>
        <p class="text-lg md:text-xl text-gray-400 mt-2">@vid_lancer</p>
        <p class="text-xl md:text-2xl mt-4 font-semibold text-white">Your Go-To for Gaming Thumbnails & Logos</p>
        <p class="text-md md:text-lg text-gray-300 mt-3 max-w-2xl mx-auto">
            I specialize in crafting high-impact, professional graphics that help content creators build a strong brand and stand out from the crowd. I am proficient in both thumbnail and logo design, with a focus on delivering eye-catching and click-worthy visuals.
        </p>
    </header>

    <main class="w-full container px-4 md:px-8">

        <!-- Services Section -->
        <section class="mb-12">
            <h2 class="text-3xl md:text-4xl font-bold text-center text-white mb-6">My Services</h2>
            <div class="flex flex-col md:flex-row justify-center items-center gap-6">
                <div class="card p-6 md:p-8 rounded-xl w-full md:w-1/2">
                    <h3 class="text-2xl font-bold mb-2 text-white">Thumbnail Design</h3>
                    <p class="text-gray-400 mb-4">I design custom thumbnails that are optimized for high click-through rates, using bold fonts and engaging visuals to attract viewers.</p>
                    <p class="text-lg font-bold text-white">Price: Depends on the project</p>
                </div>
                <div class="card p-6 md:p-8 rounded-xl w-full md:w-1/2">
                    <h3 class="text-2xl font-bold mb-2 text-white">Logo Design</h3>
                    <p class="text-gray-400 mb-4">I create professional, unique logos that serve as the foundation of a creator's brand identity. All logos are designed to be versatile and memorable.</p>
                    <p class="text-lg font-bold text-white">Price: Depends on the project</p>
                </div>
            </div>
        </section>

        <!-- Portfolio Section -->
        <section class="mb-12">
            <h2 class="text-3xl md:text-4xl font-bold text-center text-white mb-8">My Work</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Logos -->
                <div class="card p-4 rounded-xl text-center">
                    <h3 class="text-xl font-semibold mb-3 text-white">Logo Design</h3>
                    <img src="https://placehold.co/600x600/121212/E0E0E0?text=Logo+Design+1" alt="Sample Logo 1" class="w-full h-auto rounded-lg mb-4 portfolio-image">
                    <p class="text-sm text-gray-400">Created a versatile logo for a gaming channel, focusing on a clean and professional look.</p>
                </div>
                <div class="card p-4 rounded-xl text-center">
                    <h3 class="text-xl font-semibold mb-3 text-white">Logo Design</h3>
                    <img src="https://placehold.co/600x600/121212/E0E0E0?text=Logo+Design+2" alt="Sample Logo 2" class="w-full h-auto rounded-lg mb-4 portfolio-image">
                    <p class="text-sm text-gray-400">Designed a bold and memorable logo that works well across all social media platforms.</p>
                </div>

                <!-- Thumbnails -->
                <div class="card p-4 rounded-xl text-center">
                    <h3 class="text-xl font-semibold mb-3 text-white">Thumbnail Design</h3>
                    <img src="https://placehold.co/600x338/121212/E0E0E0?text=Thumbnail+Design+1" alt="Sample Thumbnail 1" class="w-full h-auto rounded-lg mb-4 portfolio-image">
                    <p class="text-sm text-gray-400">Designed a high-contrast thumbnail for a fast-paced game, drawing the viewer's eye to key elements.</p>
                </div>
                <div class="card p-4 rounded-xl text-center">
                    <h3 class="text-xl font-semibold mb-3 text-white">Thumbnail Design</h3>
                    <img src="https://placehold.co/600x338/121212/E0E0E0?text=Thumbnail+Design+2" alt="Sample Thumbnail 2" class="w-full h-auto rounded-lg mb-4 portfolio-image">
                    <p class="text-sm text-gray-400">Created an eye-catching thumbnail to increase clicks and viewer curiosity for a YouTube video.</p>
                </div>
                <div class="card p-4 rounded-xl text-center">
                    <h3 class="text-xl font-semibold mb-3 text-white">Thumbnail Design</h3>
                    <img src="https://placehold.co/600x338/121212/E0E0E0?text=Thumbnail+Design+3" alt="Sample Thumbnail 3" class="w-full h-auto rounded-lg mb-4 portfolio-image">
                    <p class="text-sm text-gray-400">Designed a vibrant thumbnail with custom text effects to match the video's energetic theme.</p>
                </div>
                <div class="card p-4 rounded-xl text-center">
                    <h3 class="text-xl font-semibold mb-3 text-white">Thumbnail Design</h3>
                    <img src="https://placehold.co/600x338/121212/E0E0E0?text=Thumbnail+Design+4" alt="Sample Thumbnail 4" class="w-full h-auto rounded-lg mb-4 portfolio-image">
                    <p class="text-sm text-gray-400">This thumbnail was designed to create intrigue and encourage viewers to watch the full video.</p>
                </div>

            </div>
        </section>

        <!-- Contact Form Section -->
        <section class="mb-12">
            <h2 class="text-3xl md:text-4xl font-bold text-center text-white mb-6">Let's Work Together</h2>
            <div class="card p-6 md:p-10 rounded-xl max-w-2xl mx-auto">
                <p class="text-center text-gray-300 mb-6">Ready to level up your brand? Fill out the form below or DM me on Instagram to get started.</p>
                <form action="#" method="post" class="space-y-4">
                    <div>
                        <label for="name" class="block text-sm font-medium text-gray-400">Name</label>
                        <input type="text" id="name" name="name" class="mt-1 block w-full rounded-md border-gray-600 shadow-sm focus:border-purple-500 focus:ring-purple-500 bg-[#2A2A2A] text-white">
                    </div>
                    <div>
                        <label for="email" class="block text-sm font-medium text-gray-400">Email</label>
                        <input type="email" id="email" name="email" class="mt-1 block w-full rounded-md border-gray-600 shadow-sm focus:border-purple-500 focus:ring-purple-500 bg-[#2A2A2A] text-white">
                    </div>
                    <div>
                        <label for="message" class="block text-sm font-medium text-gray-400">Your Project Details</label>
                        <textarea id="message" name="message" rows="4" class="mt-1 block w-full rounded-md border-gray-600 shadow-sm focus:border-purple-500 focus:ring-purple-500 bg-[#2A2A2A] text-white"></textarea>
                    </div>
                    <button type="submit" class="w-full py-3 px-4 rounded-md font-semibold text-white bg-gradient-to-r from-blue-500 to-purple-600 hover:from-blue-600 hover:to-purple-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-purple-500 transition-transform transform hover:scale-105">
                        Send Message
                    </button>
                </form>
                <p class="text-center text-sm text-gray-500 mt-4">This form is for demonstration. For a live version, you would connect it to a service like Formspree or Netlify Forms.</p>
            </div>
        </section>

    </main>

    <footer class="text-center text-gray-500 text-sm py-8">
        © 2025 Piyaus Sarkar. All Rights Reserved.
    </footer>

</body>
</html>

