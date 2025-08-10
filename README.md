## Hi there 👋

<!--
**ashish45221/ashish45221** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Heat Transfer Study Resources</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        :root {
            --primary: #3b82f6;
            --secondary: #1e40af;
            --accent: #f59e0b;
        }
        
        .gradient-bg {
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
        }
        
        .card-hover:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
        }
        
        .search-box:focus {
            box-shadow: 0 0 0 3px rgba(59, 130, 246, 0.5);
        }
        
        .ribbon {
            clip-path: polygon(0 0, 100% 0, 100% 70%, 50% 100%, 0 70%);
        }
        
        @media (max-width: 768px) {
            .mobile-stack {
                flex-direction: column;
            }
        }
    </style>
</head>
<body class="bg-gray-50 font-sans">
    <!-- Header/Navigation -->
    <header class="gradient-bg text-white">
        <div class="container mx-auto px-4 py-6">
            <div class="flex justify-between items-center">
                <div class="flex items-center space-x-2">
                    <div class="bg-white p-2 rounded-lg">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-blue-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                        </svg>
                    </div>
                    <h1 class="text-2xl font-bold">HeatTransferEdu</h1>
                </div>
                <nav class="hidden md:flex space-x-6">
                    <a href="#topics" class="hover:text-amber-200 transition">Topics</a>
                    <a href="#resources" class="hover:text-amber-200 transition">Resources</a>
                    <a href="#tutorials" class="hover:text-amber-200 transition">Tutorials</a>
                    <a href="#about" class="hover:text-amber-200 transition">About</a>
                </nav>
                <button class="md:hidden text-white">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
                    </svg>
                </button>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="relative gradient-bg text-white py-20">
        <div class="ribbon absolute bottom-0 w-full h-24 bg-white"></div>
        <div class="container mx-auto px-4 text-center">
            <h1 class="text-4xl md:text-5xl font-bold mb-6">Heat Transfer Educational Resources</h1>
            <p class="text-xl md:text-2xl mb-8 max-w-3xl mx-auto">Free educational materials including PDF notes, solved examples, and interactive learning tools</p>
            
            <div class="max-w-2xl mx-auto bg-white rounded-lg shadow-lg p-4 relative">
                <div class="flex mobile-stack space-x-2">
                    <input type="text" placeholder="Search for lecture notes..." class="search-box flex-grow px-4 py-3 rounded-lg border border-gray-300 focus:outline-none focus:border-blue-500 text-gray-800">
                    <button class="bg-blue-600 hover:bg-blue-700 text-white px-6 py-3 rounded-lg transition flex items-center justify-center">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
                        </svg>
                        Search
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- Main Content -->
    <main class="container mx-auto px-4 py-12 -mt-12 relative z-10">
        <!-- Featured Topics -->
        <section id="topics" class="mb-16">
            <h2 class="text-3xl font-bold mb-8 text-center text-gray-800">Educational Topics</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Conduction -->
                <div class="bg-white rounded-lg shadow-lg overflow-hidden card-hover transition duration-300">
                    <div class="h-48 overflow-hidden">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/bbaa57d1-a77a-444b-b7e9-ee98f1198912.png" alt="Heat conduction visualization showing temperature gradient across a metal rod" />
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-3 text-gray-800">Conduction</h3>
                        <p class="text-gray-600 mb-4">Fourier's law, thermal conductivity, steady and transient conduction, and thermal resistance networks.</p>
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="bg-blue-100 text-blue-800 text-xs px-3 py-1 rounded-full">10 PDFs</span>
                            <span class="bg-green-100 text-green-800 text-xs px-3 py-1 rounded-full">Solved Problems</span>
                        </div>
                        <a href="#" class="text-blue-600 font-medium flex items-center">
                            View Resources
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 ml-1" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
                            </svg>
                        </a>
                    </div>
                </div>
                
                <!-- Convection -->
                <div class="bg-white rounded-lg shadow-lg overflow-hidden card-hover transition duration-300">
                    <div class="h-48 overflow-hidden">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/43c6f14e-8835-45d3-98ad-cc7dc1cf8624.png" alt="Fluid flow visualization demonstrating convection currents in a heated container" />
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-3 text-gray-800">Convection</h3>
                        <p class="text-gray-600 mb-4">Natural and forced convection, boundary layers, Nusselt number, and heat transfer coefficients.</p>
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="bg-blue-100 text-blue-800 text-xs px-3 py-1 rounded-full">8 PDFs</span>
                            <span class="bg-green-100 text-green-800 text-xs px-3 py-1 rounded-full">Case Studies</span>
                        </div>
                        <a href="#" class="text-blue-600 font-medium flex items-center">
                            View Resources
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 ml-1" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
                            </svg>
                        </a>
                    </div>
                </div>
                
                <!-- Radiation -->
                <div class="bg-white rounded-lg shadow-lg overflow-hidden card-hover transition duration-300">
                    <div class="h-48 overflow-hidden">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/45e1fe7c-23b5-4998-8509-c7c16fe2b9a2.png" alt="Thermal radiation visualization showing infrared emission from different surfaces" />
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-3 text-gray-800">Radiation</h3>
                        <p class="text-gray-600 mb-4">Blackbody radiation, emissivity, view factors, and radiative heat exchange between surfaces.</p>
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="bg-blue-100 text-blue-800 text-xs px-3 py-1 rounded-full">6 PDFs</span>
                            <span class="bg-purple-100 text-purple-800 text-xs px-3 py-1 rounded-full">Interactive</span>
                        </div>
                        <a href="#" class="text-blue-600 font-medium flex items-center">
                            View Resources
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 ml-1" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
                            </svg>
                        </a>
                    </div>
                </div>
            </div>
        </section>

        <!-- PDF Resources Section -->
        <section id="resources" class="mb-16">
            <h2 class="text-3xl font-bold mb-8 text-center text-gray-800">Learning Materials</h2>
            
            <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                <div class="grid grid-cols-1 md:grid-cols-3 divide-y md:divide-y-0 md:divide-x divide-gray-200">
                    <!-- Textbook Notes -->
                    <div class="p-6">
                        <div class="flex items-center mb-4">
                            <div class="bg-red-100 p-3 rounded-lg mr-4">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-red-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.747 0 3.332.477 4.5 1.253v13C19.832 18.477 18.247 18 16.5 18c-1.746 0-3.332.477-4.5 1.253" />
                                </svg>
                            </div>
                            <h3 class="text-xl font-bold text-gray-800">Textbook Notes</h3>
                        </div>
                        <ul class="space-y-3">
                            <li class="flex items-center justify-between">
                                <div class="flex items-center">
                                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-gray-500 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 21h10a2 2 0 002-2V9.414a1 1 0 00-.293-.707l-5.414-5.414A1 1 0 0012.586 3H7a2 2 0 00-2 2v14a2 2 0 002 2z" />
                                    </svg>
                                    <span class="text-gray-600">Fundamentals of Heat Transfer (PDF)</span>
                                </div>
                                <a href="#" class="text-blue-600 hover:underline">Download</a>
                            </li>
                            <li class="flex items-center justify-between">
                                <div class="flex items-center">
                                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-gray-500 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 21h10a2 2 0 002-2V9.414a1 1 0 00-.293-.707l-5.414-5.414A1 1 0 0012.586 3H7a2 2 0 00-2 2v14a2 2 0 002 2z" />
                                    </svg>
                                    <span class="text-gray-600">Heat Transfer Textbook Companion (PDF)</span>
                                </div>
                                <a href="#" class="text-blue-600 hover:underline">Download</a>
                            </li>
                            <li class="flex items-center justify-between">
                                <div class="flex items-center">
                                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-gray-500 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 21h10a2 2 0 002-2V9.414a1 1 0 00-.293-.707l-5.414-5.414A1 1 0 0012.586 3H7a2 2 0 00-2 2v14a2 2 0 002 2z" />
                                    </svg>
                                    <span class="text-gray-600">Complete Heat Transfer Formulas (PDF)</span>
                                </div>
                                <a href="#" class="text-blue-600 hover:underline">Download</a>
                            </li>
                        </ul>
                    </div>
                    
                    <!-- Lecture Notes -->
                    <div class="p-6">
                        <div class="flex items-center mb-4">
                            <div class="bg-blue-100 p-3 rounded-lg mr-4">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-blue-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z" />
                                </svg>
                            </div>
                            <h3 class="text-xl font-bold text-gray-800">Lecture Notes</h3>
                        </div>
                        <ul class="space-y-3">
                            <li class="flex items-center justify-between">
                                <div class="flex items-center">
                                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-gray-500 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 21h10a2 2 0 002-2V9.414a1 1 0 00-.293-.707l-5.414-5.414A1 1 0 0012.586 3H7a2 2 0 00-2 2v14a2 2 0 002 2z" />
                                    </svg>
                                    <span class="text-gray-600">Heat Transfer Course Slides (PDF)</span>
                                </div>
                                <a href="#" class="text-blue-600 hover:underline">Download</a>
                            </li>
                            <li class="flex items-center justify-between">
                                <div class="flex items-center">
                                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-gray-500 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 21h10a2 2 0 002-2V9.414a1 1 0 00-.293-.707l-5.414-5.414A1 1 0 0012.586 3H7a2 2 0 00-2 2v14a2 2 0 002 2z" />
                                    </svg>
                                    <span class="text-gray-600">Conduction Detailed Notes (PDF)</span>
                                </div>
                                <a href="#" class="text-blue-600 hover:underline">Download</a>
                            </li>
                            <li class="flex items-center justify-between">
                                <div class="flex items-center">
                                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-gray-500 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 21h10a2 2 0 002-2V9.414a1 1 0 00-.293-.707l-5.414-5.414A1 1 0 0012.586 3H7a2 2 0 00-2 2v14a2 2 0 002 2z" />
                                    </svg>
                                    <span class="text-gray-600">Heat Exchanger Design (PDF)</span>
                                </div>
                                <a href="#" class="text-blue-600 hover:underline">Download</a>
                            </li>
                        </ul>
                    </div>
                    
                    <!-- Problem Sets -->
                    <div class="p-6">
                        <div class="flex items-center mb-4">
                            <div class="bg-green-100 p-3 rounded-lg mr-4">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-green-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 17v-2m3 2v-4m3 4v-6m2 10H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z" />
                                </svg>
                            </div>
                            <h3 class="text-xl font-bold text-gray-800">Solved Problems</h3>
                        </div>
                        <ul class="space-y-3">
                            <li class="flex items-center justify-between">
                                <div class="flex items-center">
                                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-gray-500 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 21h10a2 2 0 002-2V9.414a1 1 0 00-.293-.707l-5.414-5.414A1 1 0 0012.586 3H7a2 2 0 00-2 2v14a2 2 0 002 2z" />
                                    </svg>
                                    <span class="text-gray-600">Heat Transfer Problem Bank (PDF)</span>
                                </div>
                                <a href="#" class="text-blue-600 hover:underline">Download</a>
                            </li>
                            <li class="flex items-center justify-between">
                                <div class="flex items-center">
                                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-gray-500 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 21h10a2 2 0 002-2V9.414a1 1 0 00-.293-.707l-5.414-5.414A1 1 0 0012.586 3H7a2 2 0 00-2 2v14a2 2 0 002 2z" />
                                    </svg>
                                    <span class="text-gray-600">Midterm Problems with Solutions (PDF)</span>
                                </div>
                                <a href="#" class="text-blue-600 hover:underline">Download</a>
                            </li>
                            <li class="flex items-center justify-between">
                                <div class="flex items-center">
                                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-gray-500 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 21h10a2 2 0 002-2V9.414a1 1 0 00-.293-.707l-5.414-5.414A1 1 0 0012.586 3H7a2 2 0 00-2 2v14a2 2 0 002 2z" />
                                    </svg>
                                    <span class="text-gray-600">Final Exam Soluti
