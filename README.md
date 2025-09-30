<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jhanvi's Portfolio</title>
    <!-- Use the Plus Jakarta Sans font from Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;600;700&display=swap" rel="stylesheet">
    <!-- Load Tailwind CSS via CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
            background-color: #0d1117; /* Darker, more professional background */
            color: #c9d1d9; /* Lighter text for contrast */
            line-height: 1.6;
        }
        .container {
            max-width: 1200px;
        }
        .section-heading {
            position: relative;
            display: inline-block;
        }
        .section-heading::after {
            content: '';
            position: absolute;
            bottom: -8px;
            left: 50%;
            transform: translateX(-50%);
            width: 50px;
            height: 4px;
            background-color: #24b47e;
            border-radius: 9999px;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .animate-fade-in {
            animation: fadeIn 1s ease-out forwards;
        }
    </style>
</head>
<body class="antialiased">

    <!-- Header Section -->
    <header class="bg-[#010409] py-6 shadow-xl sticky top-0 z-50">
        <div class="container mx-auto px-6 flex justify-between items-center">
            <div class="text-2xl font-bold text-white">
                Jhanvi Jani
            </div>
            <nav>
                <ul class="flex space-x-6">
                    <li><a href="#about" class="text-gray-300 hover:text-cyan-400 transition-colors">About</a></li>
                    <li><a href="#skills" class="text-gray-300 hover:text-cyan-400 transition-colors">Skills</a></li>
                    <li><a href="#certs" class="text-gray-300 hover:text-cyan-400 transition-colors">Certifications</a></li>
                    <li><a href="#projects" class="text-gray-300 hover:text-cyan-400 transition-colors">Projects</a></li>
                    <li><a href="#contact" class="text-gray-300 hover:text-cyan-400 transition-colors">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="py-20 text-center bg-[#010409] min-h-screen flex items-center justify-center">
        <div class="container mx-auto px-6">
            <div class="animate-fade-in mb-8" style="animation-delay: 0.2s;">
                <!-- Placeholder for a professional headshot -->
                <img class="mx-auto rounded-full w-40 h-40 object-cover shadow-xl border-4 border-cyan-500" src="https://placehold.co/150x150/24b47e/ffffff?text=Jhanvi+Jani" alt="Jhanvi Jani Profile Picture">
            </div>
            <h1 class="text-5xl md:text-6xl lg:text-7xl font-extrabold text-white mb-4 leading-tight animate-fade-in">
    GRC Analyst & Security Implementer | NIS2 Readiness & Azure Security
</h1>
<p class="text-lg md:text-xl text-gray-400 max-w-3xl mx-auto mb-8 animate-fade-in" style="animation-delay: 0.4s;">
    "I translate complex regulatory demands (ISO 27001, NIS2) into actionable project deliverables, prioritizing risk mitigation and operational resilience through a finance-backed lens."
</p>
            <div class="flex flex-col md:flex-row justify-center space-y-4 md:space-y-0 md:space-x-4 animate-fade-in" style="animation-delay: 0.6s;">
                <!-- Connects directly to your LinkedIn profile -->
                <a href="https://linkedin.com/in/jhanvi-jani" target="_blank" class="bg-cyan-600 text-white font-bold py-3 px-8 rounded-full shadow-lg hover:bg-cyan-500 transition-all transform hover:scale-105">
                    Connect on LinkedIn
                </a>
                <!-- NOTE: For this link to work, you must rename your file 'CV Jhanvi Jani GRC.pdf' to 'jhanvi-jani-cv.pdf' in your GitHub repository. -->
                <a href="jhanvi-jani-cv.pdf" download class="bg-gray-700 text-white font-bold py-3 px-8 rounded-full shadow-lg hover:bg-gray-600 transition-all transform hover:scale-105">
                    Download CV
                </a>
            </div>
        </div>
    </section>

    <!-- About Me Section -->
    <section id="about" class="py-20 bg-[#0d1117]">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center mb-12 text-white section-heading">About Me</h2>
            <div class="max-w-4xl mx-auto text-gray-300 space-y-4">
    <p>I am a **Cybersecurity GRC Analyst** and Implementer focused on fortifying digital security for Danish businesses. My unique perspective is driven by a strong **Master’s background in Finance and a decade in business operations**, allowing me to approach security as a critical component of risk management and strategic growth.</p>
    
    <p>My expertise lies in **Governance, Risk, and Compliance (GRC)**, with hands-on experience in executing security audits against frameworks like **ISO 27001 and NIST**. I am a proven implementer, having managed security policy deployment and achieving a documented **15% reduction in phishing rates** through targeted awareness programs.</p>
    
    <p>I am actively seeking full-time roles in Copenhagen—particularly within the **BFSI or large enterprise sectors**—where I can leverage my technical certification (e.g., **AZ-500**) and business acumen to drive measurable improvements in compliance and operational resilience.</p>
</div>
                <p>As a cybersecurity analyst with a strong foundation in finance and business operations, I offer a unique perspective on managing and mitigating digital risk. My background in procurement and strategic business management allows me to bridge the gap between technical security controls and their real-world impact on an organization’s bottom line and strategic goals.</p>
                <p>I specialize in Governance, Risk, and Compliance (GRC), with hands-on experience in implementing frameworks such as ISO 27001 and NIST. In my recent internship, I led security audits that identified key vulnerabilities and contributed to a 15% reduction in phishing rates through targeted awareness programs. I also volunteer as a facilitator at the ReDI School of Digital Integration, helping adults learn foundational cybersecurity skills.</p>
                <p>I am actively seeking full-time opportunities in Copenhagen or elsewhere in Denmark where I can leverage my blended technical and business acumen to help companies build robust and resilient security postures.</p>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="py-20 bg-[#010409]">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center mb-12 text-white section-heading">Skills & Competencies</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Cybersecurity & IT Card -->
                <div class="bg-[#161b22] p-8 rounded-xl shadow-lg border-2 border-[#21262d] transition-all transform hover:scale-105 hover:border-cyan-600">
                    <div class="flex items-center space-x-4 mb-4">
                        <svg class="h-8 w-8 text-cyan-400" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-1 15.5h2v-2h-2v2zm0-4h2v-6h-2v6z"/></svg>
                        <h3 class="text-xl font-bold text-cyan-400">Cybersecurity & GRC</h3>
                    </div>
                    <ul class="list-disc list-inside space-y-2 text-gray-300">
                        <li>Security Auditing (ISO 27001, OWASP Top 10, NIST)</li>
                        <li>Vulnerability & Risk Assessment</li>
                        <li>Phishing Awareness & Digital Forensics</li>
                        <li>Identity & Access Management (IAM)</li>
                        <li>Network Security (TCP/IP)</li>
                        <li>Third-Party Risk Management</li>
                    </ul>
                </div>

                <!-- Technical Tools & Platforms Card -->
                <div class="bg-[#161b22] p-8 rounded-xl shadow-lg border-2 border-[#21262d] transition-all transform hover:scale-105 hover:border-cyan-600">
                    <div class="flex items-center space-x-4 mb-4">
                        <svg class="h-8 w-8 text-cyan-400" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true"><path d="M12 2.016c-.531 0-1.048.118-1.52.332L2.016 5.86c-.516.234-.848.749-.848 1.304v7.616c0 .555.332 1.069.848 1.303l8.464 3.512c.472.196.988.303 1.519.303s1.047-.107 1.52-.303l8.464-3.512c.516-.234.848-.748.848-1.303V7.164c0-.555-.332-1.069-.848-1.304L13.52 2.348c-.472-.214-.989-.332-1.52-.332zM12 4.5l6.464 2.688L12 9.875 5.536 7.188 12 4.5zm0 15.421l-6.464-2.688V8.125l6.464 2.688 6.464-2.688v9.112l-6.464 2.688z"/></svg>
                        <h3 class="text-xl font-bold text-cyan-400">Technical Tools & Platforms</h3>
                    </div>
                    <ul class="list-disc list-inside space-y-2 text-gray-300">
                        <li>Splunk</li>
                        <li>Metasploit</li>
                        <li>Microsoft Azure</li>
                        <li>Python & C (scripting)</li>
                        <li>SAP MM</li>
                        <li>Wireshark</li>
                    </ul>
                </div>

                <!-- Business & Professional Card -->
                <div class="bg-[#161b22] p-8 rounded-xl shadow-lg border-2 border-[#21262d] transition-all transform hover:scale-105 hover:border-cyan-600">
                    <div class="flex items-center space-x-4 mb-4">
                        <svg class="h-8 w-8 text-cyan-400" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true"><path d="M12 11a4 4 0 100-8 4 4 0 000 8zm8 6h-2v2h2v-2zm-2-2h2v2h-2v-2zm2-2h-2v2h2v-2zm-2-2h2v2h-2v-2zm2-2h-2v2h2v-2zm-2-2h2v2h-2v-2zm-2-2h2v2h-2v-2zM4 17h-2v2h2v-2zm2 0h-2v2h2v-2zm-2-2h2v2h-2v-2zm2-2h-2v2h2v-2zm-2-2h2v2h-2v-2zm2-2h-2v2h2v-2zm-2-2h2v2h-2v-2zm2-2h-2v2h2v-2zm-2-2h2v2h-2v-2z"/></svg>
                        <h3 class="text-xl font-bold text-cyan-400">Business & Professional</h3>
                    </div>
                    <ul class="list-disc list-inside space-y-2 text-gray-300">
                        <li>Project Management</li>
                        <li>Financial Analysis</li>
                        <li>Process Improvement</li>
                        <li>Data Analysis</li>
                        <li>Stakeholder Communication</li>
                        <li>Team Leadership</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Certifications Section -->
    <section id="certs" class="py-20 bg-[#0d1117]">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center mb-12 text-white section-heading">Certifications & Professional Development</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Certifications will be here -->
                <div class="bg-[#161b22] p-6 rounded-lg text-center transform hover:scale-105 transition-transform border border-[#21262d] hover:border-cyan-600">
                    <h3 class="font-semibold text-lg text-white">SANS SEC275: Foundations</h3>
                </div>
                <div class="bg-[#161b22] p-6 rounded-lg text-center transform hover:scale-105 transition-transform border border-[#21262d] hover:border-cyan-600">
                    <h3 class="font-semibold text-lg text-white">MS Azure Security Engineer Associate (AZ-500)</h3>
                </div>
                <div class="bg-[#161b22] p-6 rounded-lg text-center transform hover:scale-105 transition-transform border border-[#21262d] hover:border-cyan-600">
                    <h3 class="font-semibold text-lg text-white">MS Cybersecurity Fundamentals (SC-900)</h3>
                </div>
                <div class="bg-[#161b22] p-6 rounded-lg text-center transform hover:scale-105 transition-transform border border-[#21262d] hover:border-cyan-600">
                    <h3 class="font-semibold text-lg text-white">ISC2 Information Security Management</h3>
                </div>
                <div class="bg-[#161b22] p-6 rounded-lg text-center transform hover:scale-105 transition-transform border border-[#21262d] hover:border-cyan-600">
                    <h3 class="font-semibold text-lg text-white">Cisco Junior Cybersecurity Analyst</h3>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="py-20 bg-[#010409]">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center mb-12 text-white section-heading">Projects & Hands-on Experience</h2>
            <div class="max-w-4xl mx-auto space-y-8">
                <!-- Mastercard Project -->
                <div class="bg-[#161b22] p-8 rounded-xl shadow-lg border-2 border-[#21262d] space-y-6 transform transition-all hover:border-cyan-600">
                    <div class="flex items-center space-x-4">
                        <svg class="h-10 w-10 text-cyan-400" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true"><path d="M12 2.25c-5.385 0-9.75 4.365-9.75 9.75s4.365 9.75 9.75 9.75 9.75-4.365 9.75-9.75S17.385 2.25 12 2.25zM12.75 16.5h-1.5V12h-1.5V10.5h3v6zM12 8.25a.75.75 0 110-1.5.75.75 0 010 1.5z"/></svg>
                        <h3 class="text-2xl font-bold text-cyan-400">Mastercard Cybersecurity Job Simulation</h3>
                    </div>
                    <p class="text-gray-300">
                        This project involved identifying phishing emails and designing security awareness training courses. Through this job simulation, I built my skills in problem-solving, data analysis, and data presentation and practiced them in a real-world context. This program confirmed my passion for working in cybersecurity, and I am excited to apply these skills to a Security Awareness team.
                    </p>
                    <!-- Update with the actual certificate link -->
                    <a href="https://example.com/mastercard-certificate.pdf" target="_blank" class="text-white font-bold hover:underline transition-colors text-lg">View Certificate →</a>
                </div>

                <!-- TCS Project -->
                <div class="bg-[#161b22] p-8 rounded-xl shadow-lg border-2 border-[#21262d] space-y-6 transform transition-all hover:border-cyan-600">
                    <div class="flex items-center space-x-4">
                        <svg class="h-10 w-10 text-cyan-400" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true"><path d="M12 2.25c-5.385 0-9.75 4.365-9.75 9.75s4.365 9.75 9.75 9.75 9.75-4.365 9.75-9.75S17.385 2.25 12 2.25zM12.75 16.5h-1.5V12h-1.5V10.5h3v6zM12 8.25a.75.75 0 110-1.5.75.75 0 010 1.5z"/></svg>
                        <h3 class="text-2xl font-bold text-cyan-400">TCS: Identity & Access Management (IAM) Project</h3>
                    </div>
                    <p class="text-gray-300">
                        Completed a job simulation collaborating with a Cybersecurity Consulting team. I acquired expertise in IAM principles, cybersecurity best practices, and strategic alignment with business objectives. I also delivered comprehensive documentation and presentations, showcasing my ability to communicate complex technical concepts effectively.
                    </p>
                    <!-- Update with the actual certificate link -->
                    <a href="https://example.com/tcs-certificate.pdf" target="_blank" class="text-white font-bold hover:underline transition-colors text-lg">View Certificate →</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-[#0d1117]">
        <div class="container mx-auto px-6 text-center">
            <h2 class="text-3xl font-bold mb-4 text-white section-heading">Let's Connect</h2>
            <p class="text-gray-400 mb-8 max-w-2xl mx-auto">
                I'm actively seeking opportunities to apply my unique skill set to a challenging role in the Danish job market. Feel free to connect with me on LinkedIn.
            </p>
            <div class="flex flex-col md:flex-row justify-center items-center mt-4 md:space-x-4">
                <a href="https://linkedin.com/in/jhanvi-jani" target="_blank" class="bg-cyan-600 text-white font-bold py-3 px-8 rounded-full shadow-lg hover:bg-cyan-500 transition-all transform hover:scale-105">
                    LinkedIn
                </a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-[#010409] py-6 text-center text-gray-500 text-sm">
        &copy; 2025 Jhanvi Jani. All rights reserved.
    </footer>
</body>
</html>
