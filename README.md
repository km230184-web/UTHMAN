    <label for="edit-profile-pic">Profile Picture URL:</label>
    <input type="text" id="edit-profile-pic" value="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/f6ce4e70-f134-4e2f-a78e-6b8d5440330c.png" />

    <label for="edit-hero-text">Hero Section Text:</label>
    <textarea id="edit-hero-text" rows="3">A passionate full-stack developer creating innovative web solutions.</textarea>

    <label for="edit-about-text">About Me Text:</label>
    <textarea id="edit-about-text" rows="5">I'm a dedicated software engineer with over 5 years of experience building web applications. I specialize in React, Node.js, and cloud technologies. When I'm not coding, you can find me exploring new technologies or hiking in nature.</textarea>

    <div class="flex justify-end space-x-2">
        <button id="save-changes" class="btn btn-primary" aria-label="Save customization changes">Save Changes</button>
        <button id="reset" class="btn btn-danger" aria-label="Reset customization to default">Reset to Default</button>
        <button id="close-panel" class="btn btn-secondary" aria-label="Close customization panel">Close</button>
    </div>
</div>

<!-- Navigation -->
<nav class="bg-white dark:bg-gray-800 shadow-lg fixed top-0 w-full z-50">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="flex justify-between h-16">
            <div class="flex items-center">
                <h1 id="nav-name" class="text-xl font-bold cursor-pointer" title="Double-click to customize">Othman</h1>
            </div>
            <div class="flex items-center space-x-4">
                <a href="#about" class="hover:text-blue-500">About</a>
                <a href="#projects" class="hover:text-blue-500">Projects</a>
                <a href="#contact" class="hover:text-blue-500">Contact</a>
                <button id="theme-toggle" class="p-2 rounded-full bg-gray-200 dark:bg-gray-700" aria-label="Toggle theme">
                    <svg id="sun-icon" class="w-5 h-5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 3v1m0 16v1m9-9h-1M4 12H3m15.364 6.364l-.707-.707M6.343 6.343l-.707-.707m12.728 0l-.707.707M6.343 17.657l-.707.707M16 12a4 4 0 11-8 0 4 4 0 018 0z" />
                    </svg>
                    <svg id="moon-icon" class="hidden w-5 h-5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M20.354 15.354A9 9 0 018.646 3.646 9.003 9.003 0 0012 21a9.003 9.003 0 008.354-5.646z" />
                    </svg>
                </button>
            </div>
        </div>
    </div>
</nav>

<!-- Hero Section -->
<section class="hero-bg text-white py-20">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col md:flex-row items-center">
        <div class="md:w-1/2">
            <h2 id="hero-name" class="text-5xl font-bold mb-4">Hello, I'm Othman</h2>
            <p id="hero-text" class="text-xl mb-8">A passionate full-stack developer creating innovative web solutions.</p>
            <a href="#contact" class="bg-white text-blue-600 px-6 py-3 rounded-full font-semibold hover:bg-gray-100 transition">Get In Touch</a>
        </div>
        <div class="md:w-1/2 mt-8 md:mt-0">
            <img id="profile-pic" src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/f6ce4e70-f134-4e2f-a78e-6b8d5440330c.png" alt="Profile picture of a professional male software developer with short brown hair, wearing a casual shirt, smiling confidently against a blurred urban cityscape background with technology motifs" class="rounded-full mx-auto md:mx-0 shadow-lg w-64 h-64 object-cover" onerror="this.style.display='none';" />
        </div>
    </div>
</section>

<!-- About Section -->
<section id="about" class="py-20 bg-white dark:bg-gray-800">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <h2 class="text-3xl font-bold text-center mb-12">About Me</h2>
        <div class="grid md:grid-cols-2 gap-8 items-center">
            <div>
                <p id="about-text" class="text-lg mb-4">I'm a dedicated software engineer with over 5 years of experience building web applications. I specialize in React, Node.js, and cloud technologies. When I'm not coding, you can find me exploring new technologies or hiking in nature.</p>
                <div class="flex space-x-4">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/502c1720-026d-49b5-bc63-aff70abc12ab.png" alt="Icon representing JavaScript programming language with a yellow JS acronym in a black box" class="w-16 h-16" onerror="this.style.display='none';" />
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/7f2ad479-5dce-4430-ba4d-fcff2c8d7eca.png" alt="Icon representing React JavaScript library with white atoms orbiting around the React text" class="w-16 h-16" onerror="this.style.display='none';" />
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/6a63ec3f-ebf9-4eb6-929a-ba56c6b5ebc7.png" alt="Icon representing Node.js runtime with green hexagons forming the framework" class="w-16 h-16" onerror="this.style.display='none';" />
                </div>
            </div>
            <div>
                <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/b17c2443-c75e-4789-a680-fcdc0cabb551.png" alt="Cozy home office setup with dual monitors displaying code, ergonomic chair, plants, and city skyline view through large windows" class="rounded-lg shadow-lg" onerror="this.style.display='none';" />
            </div>
        </div>
    </div>
</section>

<!-- Projects Section -->
<section id="projects" class="py-20 bg-gray-100 dark:bg-gray-900">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <h2 class="text-3xl font-bold text-center mb-12">My Projects</h2>
        <div class="grid md:grid-cols-3 gap-8">
            <div class="project-card bg-white dark:bg-gray-800 rounded-lg shadow-lg p-6">
                <h3 class="text-xl font-semibold mb-4">E-commerce Platform</h3>
                <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/f7f682ed-85f8-46f0-9227-76fe5ed703dc.png" alt="Screenshot of an e-commerce website homepage showing product listings with shopping cart icon and colorful product images" class="w-full h-32 object-cover rounded mb-4" onerror="this.style.display='none';" />
                <p class="mb-4">A full-stack e-commerce solution with payment integration and inventory management.</p>
                <a href="#" class="text-blue-500 hover:text-blue-700">View Project</a>
            </div>
            <div class="project-card bg-white dark:bg-gray-800 rounded-lg shadow-lg p-6">
                <h3 class="text-xl font-semibold mb-4">Weather App</h3>
                <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/d448916e-3730-4c8f-ac41-8603c32c0dd4.png" alt="Mobile app interface displaying current weather with sunny cloud icons, temperature gauge, and location map" class="w-full h-32 object-cover rounded mb-4" onerror="this.style.display='none';" />
                <p class="mb-4">A responsive weather application using weather API with forecast and location features.</p>
                <a href="#" class="text-blue-500 hover:text-blue-700">View Project</a>
            </div>
            <div class="project-card bg-white dark:bg-gray-800 rounded-lg shadow-lg p-6">
                <h3 class="text-xl font-semibold mb-4">Task Manager</h3>
                <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/1e7c5a83-d0d9-4d3d-ab8f-ff2217f40ba7.png" alt="Desktop application showing task list with checkboxes, priorities, and calendar integration" class="w-full h-32 object-cover rounded mb-4" onerror="this.style.display='none';" />
                <p class="mb-4">A productivity app for managing tasks, projects, and deadlines with drag-and-drop functionality.</p>
                <a href="#" class="text-blue-500 hover:text-blue-700">View Project</a>
            </div>
        </div>
    </div>
</section>

<!-- Contact Section -->
<section id="contact" class="py-20 bg-white dark:bg-gray-800">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <h2 class="text-3xl font-bold text-center mb-12">Contact Me</h2>
        <form id="contact-form" class="space-y-4">
            <div>
                <label for="name">Name</label>
                <input type="text" id="name" name="name" class="w-full p-3 border rounded-lg dark:bg-gray-700 dark:border-gray-600" required />
            </div>
            <div>
                <label for="email">Email</label>
                <input type="email" id="email" name="email" class="w-full p-3 border rounded-lg dark:bg-gray-700 dark:border-gray-600" required />
            </div>
            <div>
                <label for="message">Message</label>
                <textarea id="message" name="message" rows="4" class="w-full p-3 border rounded-lg dark:bg-gray-700 dark:border-gray-600" required></textarea>
            </div>
            <button type="submit" class="w-full bg-blue-500 text-white p-3 rounded-lg hover:bg-blue-600 transition">Send Message</button>
        </form>
        <p id="form-message" class="text-center mt-4"></p>
    </div>
</section>

<!-- Scroll to Top Button -->
<button id="scroll-to-top" class="scroll-to-top" aria-label="Scroll to top">↑</button>

<!-- JavaScript -->
<script>
    // Theme Toggle
    const themeToggle = document.getElementById('theme-toggle');
    const sunIcon = document.getElementById('sun-icon');
    const moonIcon = document.getElementById('moon-icon');
    const body = document.body;

    themeToggle.addEventListener('click', () => {
        body.classList.toggle('dark');
        sunIcon.classList.toggle('hidden');
        moonIcon.classList.toggle('hidden');
    });

    // Scroll to Top
    const scrollToTopBtn = document.getElementById('scroll-to-top');

    window.addEventListener('scroll', () => {
        if (window.pageYOffset > 100) {
            scrollToTopBtn.style.display = 'block';
        } else {
            scrollToTopBtn.style.display = 'none';
        }
    });

    scrollToTopBtn.addEventListener('click', () => {
        window.scrollTo({ top: 0, behavior: 'smooth' });
    });

    // Contact Form Validation
    const contactForm = document.getElementById('contact-form');
    const formMessage = document.getElementById('form-message');

    contactForm.addEventListener('submit', (e) => {
        e.preventDefault();
        const name = document.getElementById('name').value;
        const email = document.getElementById('email').value;
        const message = document.getElementById('message').value;

        if (name && email && message) {
            const emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
            if (emailRegex.test(email)) {
                formMessage.textContent = "Thank you for your message! I'll get back to you soon.";
                formMessage.className = 'text-green-500';
                contactForm.reset();
            } else {
                formMessage.textContent = 'Please enter a valid email address.';
                formMessage
