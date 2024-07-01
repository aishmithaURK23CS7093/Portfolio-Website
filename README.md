<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Software Engineer Portfolio</title>
    <!-- Include Tailwind CSS -->
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>

<body class="bg-gray-100">

    <!-- Navbar -->
    <nav class="bg-gray-800 text-white p-4">
        <div class="container mx-auto flex justify-between items-center">
            <span class="font-semibold text-xl">My Portfolio</span>
            <div>
                <a href="#" class="px-3 py-2 hover:text-gray-300">Home</a>
                <a href="#projects" class="px-3 py-2 hover:text-gray-300">Projects</a>
                <a href="#about" class="px-3 py-2 hover:text-gray-300">About</a>
                <a href="#contact" class="px-3 py-2 hover:text-gray-300">Contact</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="bg-gray-900 text-white flex items-center justify-center h-screen">
        <div class="text-center">
            <h1 class="text-4xl font-bold mb-4">Hi, I'm [Your Name]</h1>
            <p class="text-lg">Software Engineer with 1 year of experience in Java development</p>
        </div>
    </header>

    <!-- Projects Section -->
    <section id="projects" class="py-12 px-4">
        <div class="container mx-auto">
            <h2 class="text-2xl font-semibold mb-4">Projects</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <!-- Example Project Card -->
                <div class="bg-white rounded-lg shadow-md p-6">
                    <h3 class="font-semibold text-lg mb-2">Project Name</h3>
                    <p class="text-gray-700 mb-4">Description of the project. Lorem ipsum dolor sit amet,
                        consectetur adipiscing elit.</p>
                    <a href="#" class="text-blue-500 hover:underline">View Project</a>
                </div>
                <!-- Add more project cards as needed -->
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-12 px-4 bg-gray-200">
        <div class="container mx-auto">
            <h2 class="text-2xl font-semibold mb-4">About Me</h2>
            <p class="text-lg text-gray-700">
                Brief introduction about yourself. Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                Nullam nec porttitor ante. Praesent dignissim congue augue, vitae aliquam ex placerat sit amet.
            </p>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-12 px-4">
        <div class="container mx-auto">
            <h2 class="text-2xl font-semibold mb-4">Contact Me</h2>
            <form action="#" method="POST" class="max-w-lg mx-auto">
                <div class="mb-4">
                    <label for="name" class="block text-sm font-medium text-gray-700">Name</label>
                    <input type="text" id="name" name="name" required
                        class="mt-1 block w-full px-3 py-2 border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-indigo-500 focus:border-indigo-500 sm:text-sm">
                </div>
                <div class="mb-4">
                    <label for="email" class="block text-sm font-medium text-gray-700">Email</label>
                    <input type="email" id="email" name="email" required
                        class="mt-1 block w-full px-3 py-2 border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-indigo-500 focus:border-indigo-500 sm:text-sm">
                </div>
                <div class="mb-4">
                    <label for="message" class="block text-sm font-medium text-gray-700">Message</label>
                    <textarea id="message" name="message" rows="4"
                        class="mt-1 block w-full px-3 py-2 border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-indigo-500 focus:border-indigo-500 sm:text-sm"></textarea>
                </div>
                <button type="submit"
                    class="inline-block bg-blue-500 text-white px-4 py-2 rounded-md hover:bg-blue-600">Send</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white text-center py-4">
        <p>&copy; 2024 Your Name. All rights reserved.</p>
    </footer>

    <!-- Optional JavaScript -->
    <script>
        // Add your custom JavaScript here if needed
    </script>
</body>

</html>
