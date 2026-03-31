<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dhrubajyoti Paul | Financial Analytics & Public Policy</title>
    <link rel="icon" type="image/x-icon" href="/static/favicon.ico">
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/feather-icons/dist/feather.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/animejs/lib/anime.iife.min.js"></script>
    <style>
        :root {
            --navy: #0a192f;
            --slate: #8892b0;
            --gold: #d4af37;
        }
        body {
            background-color: var(--navy);
            color: white;
            font-family: 'Inter', sans-serif;
        }
        .gold-accent {
            color: var(--gold);
        }
    </style>
</head>
<body class="min-h-screen">
    <!-- Hero Section -->
    <section class="relative h-screen flex items-center justify-center bg-gradient-to-b from-[#0a192f] to-[#112240] overflow-hidden">
        <div class="absolute inset-0 z-0">
            <div class="absolute top-0 left-0 w-full h-full opacity-20" style="background-image: url('http://static.photos/abstract/1200x630/42'); background-size: cover;"></div>
        </div>
        <div class="container mx-auto px-6 z-10 text-center" data-aos="fade-up">
            <h1 class="text-7xl md:text-8xl font-bold mb-6 tracking-tight gold-accent">DHRUBAJYOTI PAUL</h1>
            <h2 class="text-5xl md:text-6xl font-bold mb-4">Intersection of <span class="gold-accent">Financial Analytics</span>, <span class="gold-accent">AI Research</span>, and <span class="gold-accent">Public Policy</span></h2>
            <p class="text-xl md:text-2xl text-slate-300 mb-8">B.Com (Hons) Financial Analytics student at BIT Mesra Noida integrated with the National Stock Exchange (NSE)</p>
            <div class="flex justify-center space-x-4 mb-12">
                <span class="px-4 py-2 bg-gray-800 rounded-full text-sm">2x PMO Appreciation Awardee</span>
                <span class="px-4 py-2 bg-gray-800 rounded-full text-sm">State-Level Policy Finalist</span>
                <span class="px-4 py-2 bg-gray-800 rounded-full text-sm">AI Researcher</span>
            </div>
            <div class="flex justify-center space-x-6">
                <a href="#research" class="px-8 py-3 bg-transparent border border-gold text-gold rounded-md hover:bg-gold hover:text-navy transition duration-300">View Research</a>
                <a href="#" class="px-8 py-3 bg-gold text-navy rounded-md hover:bg-opacity-90 transition duration-300">Download CV</a>
            </div>
        </div>
        <div class="absolute bottom-10 left-0 right-0 flex justify-center">
            <a href="#about" class="animate-bounce">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-chevron-down text-gray-400 hover:text-gold transition duration-300">
                    <polyline points="6 9 12 15 18 9"></polyline>
                </svg>
            </a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-[#112240]">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold mb-12 text-center gold-accent" data-aos="fade-up">Education & Academic Excellence</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-[#0a192f] p-6 rounded-lg shadow-lg" data-aos="fade-up" data-aos-delay="100">
                    <h3 class="text-xl font-semibold mb-2">B.Com (Hons) Financial Analytics</h3>
                    <p class="text-slate-300 mb-2">Birla Institute of Technology, Mesra (Noida Off-Campus)</p>
                    <p class="text-gold">7.8 SGPA</p>
                </div>
                <div class="bg-[#0a192f] p-6 rounded-lg shadow-lg" data-aos="fade-up" data-aos-delay="200">
                    <h3 class="text-xl font-semibold mb-2">Senior Secondary</h3>
                    <p class="text-slate-300 mb-2">CBSE</p>
                    <p class="text-gold">60%</p>
                </div>
                <div class="bg-[#0a192f] p-6 rounded-lg shadow-lg" data-aos="fade-up" data-aos-delay="300">
                    <h3 class="text-xl font-semibold mb-2">Secondary</h3>
                    <p class="text-slate-300 mb-2">CBSE</p>
                    <p class="text-gold">57%</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Research Section -->
    <section id="research" class="py-20 bg-[#0a192f]">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold mb-12 text-center gold-accent" data-aos="fade-up">Featured Research & Projects</h2>
            <div class="grid md:grid-cols-2 gap-8">
                <div class="bg-[#112240] p-6 rounded-lg shadow-lg" data-aos="fade-right">
                    <h3 class="text-xl font-semibold mb-2 gold-accent">International Conference Presentation</h3>
                    <p class="text-slate-300 mb-4">"From Credit Gaps to Carbon Credits: AI-Driven Risk Assessment Models for Scaling Agri-Tech Startups in Tribal Belts" presented at ICIEM'26</p>
                    <a href="#" class="text-gold hover:underline">View Paper →</a>
                </div>
                <div class="bg-[#112240] p-6 rounded-lg shadow-lg" data-aos="fade-left">
                    <h3 class="text-xl font-semibold mb-2 gold-accent">Academic Training</h3>
                    <p class="text-slate-300 mb-4">Metvy Finance Cohort (Sept 2025) – Earned Certificate of Excellence and LOR for financial fundamentals and analytical thinking</p>
                    <a href="#" class="text-gold hover:underline">View Certificate →</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Impact Section -->
    <section class="py-20 bg-[#112240]">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold mb-12 text-center gold-accent" data-aos="fade-up">Policy & National Recognition</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-[#0a192f] p-6 rounded-lg shadow-lg" data-aos="fade-up">
                    <h3 class="text-xl font-semibold mb-2 gold-accent">Prime Minister's Recognition</h3>
                    <p class="text-slate-300">Received consecutive letters of appreciation from the Prime Minister of India (2023 & 2024) for ideas and confidence in the national student dialogue</p>
                </div>
                <div class="bg-[#0a192f] p-6 rounded-lg shadow-lg" data-aos="fade-up" data-aos-delay="100">
                    <h3 class="text-xl font-semibold mb-2 gold-accent">State-Level Finalist (Assam)</h3>
                    <p class="text-slate-300">Selected for the Viksit Bharat Youth Leadership Dialogue 2026 State Championship (Ministry of Youth Affairs & Sports)</p>
                </div>
                <div class="bg-[#0a192f] p-6 rounded-lg shadow-lg" data-aos="fade-up" data-aos-delay="200">
                    <h3 class="text-xl font-semibold mb-2 gold-accent">Budget Expert</h3>
                    <p class="text-slate-300">State Finalist in the MyBharat Budget Quest 2026, analyzing national frameworks and "Ease of Doing Business"</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Experience Section -->
    <section class="py-20 bg-[#0a192f]">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold mb-12 text-center gold-accent" data-aos="fade-up">Professional Experience</h2>
            <div class="grid md:grid-cols-2 gap-8">
                <div class="bg-[#112240] p-6 rounded-lg shadow-lg" data-aos="fade-right">
                    <h3 class="text-xl font-semibold mb-2 gold-accent">Marketing & Research Intern</h3>
                    <p class="text-slate-300 mb-2">Vijayash Foundation (Noida Management Association)</p>
                    <ul class="list-disc list-inside text-slate-300 space-y-2">
                        <li>Focused on sustainability events</li>
                        <li>Stakeholder engagement</li>
                        <li>Data analysis</li>
                    </ul>
                </div>
                <div class="bg-[#112240] p-6 rounded-lg shadow-lg" data-aos="fade-left">
                    <h3 class="text-xl font-semibold mb-2 gold-accent">Leadership</h3>
                    <p class="text-slate-300 mb-2">Campus Ambassador for Techfest'25, IIT Bombay</p>
                    <ul class="list-disc list-inside text-slate-300 space-y-2">
                        <li>Driving participation for Asia's largest science and tech festival</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section class="py-20 bg-[#112240]">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold mb-12 text-center gold-accent" data-aos="fade-up">Technical & Creative Skills</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-[#0a192f] p-6 rounded-lg shadow-lg" data-aos="fade-up">
                    <h3 class="text-xl font-semibold mb-4 gold-accent">Programming & Data</h3>
                    <ul class="space-y-2 text-slate-300">
                        <li>Python (Basics)</li>
                        <li>MySQL</li>
                        <li>MS Excel</li>
                        <li>Power BI</li>
                        <li>Technical Analysis for Equity Trading</li>
                    </ul>
                </div>
                <div class="bg-[#0a192f] p-6 rounded-lg shadow-lg" data-aos="fade-up" data-aos-delay="100">
                    <h3 class="text-xl font-semibold mb-4 gold-accent">Core Certifications</h3>
                    <ul class="space-y-2 text-slate-300">
                        <li>SEBI-Investor Certification</li>
                        <li>Google Digital Marketing</li>
                        <li>Intro to Gen AI & Prompting</li>
                        <li>Diploma in Tabla (Bangiya Sangeet Parishad)</li>
                    </ul>
                </div>
                <div class="bg-[#0a192f] p-6 rounded-lg shadow-lg" data-aos="fade-up" data-aos-delay="200">
                    <h3 class="text-xl font-semibold mb-4 gold-accent">Events</h3>
                    <ul class="space-y-2 text-slate-300">
                        <li>Finance & Budgeting Division for TEDxBIT Noida 2025</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="py-20 bg-[#0a192f]">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold mb-12 text-center gold-accent" data-aos="fade-up">Contact & Socials</h2>
            <div class="max-w-2xl mx-auto">
                <div class="bg-[#112240] p-8 rounded-lg shadow-lg" data-aos="fade-up">
                    <div class="mb-6">
                        <h3 class="text-xl font-semibold mb-2 gold-accent">Email</h3>
                        <p class="text-slate-300">pauldhrubajyoti12@gmail.com</p>
                    </div>
                    <div class="mb-6">
                        <h3 class="text-xl font-semibold mb-2 gold-accent">Socials</h3>
                        <div class="flex space-x-4">
                            <a href="https://x.com/dhruba_paul01" target="_blank" class="text-slate-300 hover:text-gold transition duration-300">
                                <i data-feather="twitter"></i>
                            </a>
                            <a href="https://www.linkedin.com/in/01dhrubajyotipaul/" target="_blank" class="text-slate-300 hover:text-gold transition duration-300">
                                <i data-feather="linkedin"></i>
                            </a>
                            <a href="https://github.com/dhrubajyotipaul" target="_blank" class="text-slate-300 hover:text-gold transition duration-300">
                                <i data-feather="github"></i>
                            </a>
                        </div>
                    </div>
                    <div>
                        <h3 class="text-xl font-semibold mb-2 gold-accent">Address</h3>
                        <p class="text-slate-300">BIT NOIDA | INDIA</p>
                        <p class="text-slate-300">Dholai Co-District, Silchar, Assam -14</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <footer class="py-6 bg-[#020c1b] text-center text-slate-400">
        <p>© 2024 Dhrubajyoti Paul. All rights reserved.</p>
    </footer>

    <script>
        AOS.init({
            duration: 800,
            easing: 'ease-in-out',
            once: true
        });
        feather.replace();
    </script>
</body>
</html>
