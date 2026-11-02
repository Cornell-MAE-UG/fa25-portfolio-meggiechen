<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meggie Chen - Resume & Curriculum Vitae</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            50: '#f8fafc',
                            100: '#f1f5f9',
                            700: '#1e293b',
                            800: '#0f172a',
                            accent: '#2563eb',
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'system-ui', 'sans-serif'],
                        mono: ['JetBrains Mono', 'Menlo', 'monospace']
                    }
                }
            }
        }
    </script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc;
            color: #0f172a;
        }

        @media print {
            .no-print {
                display: none !important;
            }
            body {
                background: white !important;
            }
            .page-container {
                box-shadow: none !important;
                border: none !important;
                padding: 0 !important;
                margin: 0 !important;
                max-width: 100% !important;
            }
        }
    </style>
</head>
<body class="min-h-screen py-8 px-4 sm:px-6">

    <!-- JEKILL MARKDOWN SNIPPET SECTION (Helper for GitHub Pages) -->
    <div class="no-print max-w-4xl mx-auto mb-8 bg-slate-900 rounded-2xl shadow-xl overflow-hidden border border-slate-800">
        <div class="bg-slate-950 px-5 py-3 border-b border-slate-800 flex items-center justify-between">
            <div class="flex items-center gap-2">
                <span class="w-3 h-3 rounded-full bg-red-500"></span>
                <span class="w-3 h-3 rounded-full bg-yellow-500"></span>
                <span class="w-3 h-3 rounded-full bg-green-500"></span>
                <span class="ml-2 text-xs font-mono font-semibold text-slate-300">resume.md / cv.md (Jekyll GitHub Pages Template)</span>
            </div>
            <button onclick="copyJekyllCode()" id="copy-btn" class="text-xs bg-blue-600 hover:bg-blue-500 text-white font-medium px-3 py-1.5 rounded-lg transition flex items-center gap-1.5">
                <i class="fa-regular fa-copy"></i>
                <span id="copy-btn-text">Copy Code for GitHub Pages</span>
            </button>
        </div>
        <div class="p-4 bg-slate-900 overflow-x-auto max-h-56">
            <pre class="text-xs font-mono text-emerald-400 leading-relaxed"><code id="jekyll-snippet">---
layout: default
title: Resume - Meggie Chen
permalink: /resume/
---

<!-- Download Resume Button -->
<div style="margin-bottom: 25px; text-align: left;">
  <a href="{{ '/assets/Resume_FA26.pdf' | relative_url }}" download="Resume_FA26.pdf" style="display: inline-flex; align-items: center; gap: 8px; background-color: #2563eb; color: #ffffff; padding: 10px 20px; border-radius: 8px; font-weight: 600; text-decoration: none; box-shadow: 0 4px 6px -1px rgba(0,0,0,0.1);">
    <svg width="18" height="18" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 10v6m0 0l-3-3m3 3l3-3m2 8H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"></path></svg>
    Download Resume (PDF)
  </a>
</div>

<!-- Embedded PDF Viewer -->
<div style="margin-bottom: 35px; border-radius: 12px; overflow: hidden; border: 1px solid #e2e8f0; box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1);">
  <iframe src="{{ '/assets/Resume_FA26.pdf' | relative_url }}" width="100%" height="800px" style="border: none; display: block;">
    <p>Your browser does not support embedded PDFs. <a href="{{ '/assets/Resume_FA26.pdf' | relative_url }}">Download the PDF here</a>.</p>
  </iframe>
</div></code></pre>
        </div>
        <div class="px-5 py-2.5 bg-slate-950/70 border-t border-slate-800/80 text-[11px] text-slate-400 flex items-center justify-between">
            <span><i class="fa-solid fa-folder-tree text-blue-400 mr-1.5"></i>Save file location: Upload your PDF to <code class="text-blue-300 font-mono bg-slate-800 px-1 py-0.5 rounded">assets/Resume_FA26.pdf</code></span>
            <span class="text-slate-500">Page Preview Below &darr;</span>
        </div>
    </div>

    <!-- MAIN RESUME PAGE DISPLAY (Clean layout without top tabs) -->
    <main class="page-container max-w-4xl mx-auto bg-white rounded-2xl shadow-xl border border-slate-200/80 p-6 sm:p-12">
        
        <!-- TOP DOWNLOAD BAR & ACTIONS -->
        <div class="no-print mb-8 pb-6 border-b border-slate-100 flex flex-col sm:flex-row items-stretch sm:items-center justify-between gap-4">
            <div>
                <span class="text-xs font-bold uppercase tracking-wider text-blue-600 font-mono">Curriculum Vitae</span>
                <h2 class="text-xl font-bold text-slate-900">Meggie Chen Resume</h2>
            </div>
            
            <div class="flex items-center gap-3">
                <!-- PDF DOWNLOAD LINK -->
                <a href="assets/Resume_FA26.pdf" download="Resume_FA26.pdf" 
                   class="inline-flex items-center justify-center gap-2 bg-blue-600 hover:bg-blue-700 text-white font-semibold text-sm px-5 py-2.5 rounded-xl shadow-md shadow-blue-500/10 transition-all hover:scale-[1.02] active:scale-95">
                    <i class="fa-solid fa-file-arrow-down text-base"></i>
                    <span>Download PDF</span>
                </a>
                
                <button onclick="window.print()" class="inline-flex items-center justify-center gap-2 bg-slate-100 hover:bg-slate-200 text-slate-700 font-medium text-sm px-4 py-2.5 rounded-xl transition">
                    <i class="fa-solid fa-print"></i>
                    <span class="hidden sm:inline">Print</span>
                </button>
            </div>
        </div>

        <!-- EMBEDDED PDF PREVIEW -->
        <section class="no-print mb-10">
            <div class="flex items-center justify-between mb-3">
                <span class="text-xs font-bold uppercase tracking-wider text-slate-400 flex items-center gap-2">
                    <i class="fa-solid fa-file-pdf text-red-500"></i> PDF Document Preview
                </span>
                <span class="text-xs text-slate-400 font-mono">assets/Resume_FA26.pdf</span>
            </div>
            <div class="w-full h-[600px] bg-slate-900 rounded-xl overflow-hidden border border-slate-200 shadow-inner">
                <iframe src="assets/Resume_FA26.pdf" width="100%" height="100%" class="w-full h-full border-none">
                    <div class="flex flex-col items-center justify-center h-full text-slate-400 p-6 text-center">
                        <i class="fa-solid fa-file-pdf text-4xl mb-3 text-slate-500"></i>
                        <p class="text-sm font-medium text-slate-200 mb-2">PDF Preview</p>
                        <p class="text-xs max-w-sm mb-4">To enable embedded viewing, place your PDF at <code class="text-blue-400">assets/Resume_FA26.pdf</code>.</p>
                        <a href="assets/Resume_FA26.pdf" download class="text-xs bg-blue-600 text-white px-4 py-2 rounded-lg font-semibold">Download Resume_FA26.pdf</a>
                    </div>
                </iframe>
            </div>
        </section>

        <!-- FORMATTED HTML RESUME -->
        <article class="text-slate-800">
            
            <!-- HEADER -->
            <header class="border-b border-slate-200 pb-6 mb-8">
                <div class="flex flex-col sm:flex-row justify-between items-start sm:items-end gap-3">
                    <div>
                        <h1 class="text-3xl sm:text-4xl font-extrabold text-slate-900 tracking-tight">MEGGIE CHEN</h1>
                        <p class="text-blue-600 font-semibold text-base mt-1">Mechanical Engineering Student @ Cornell University</p>
                    </div>
                    <div class="text-xs sm:text-sm text-slate-600 font-mono space-y-1 sm:text-right">
                        <div><i class="fa-solid fa-location-dot text-slate-400 mr-1.5"></i>Ithaca, NY 14853</div>
                        <div><i class="fa-solid fa-phone text-slate-400 mr-1.5"></i>(650) 224-3189</div>
                        <div>
                            <a href="mailto:mc2894@cornell.edu" class="text-blue-600 hover:underline">
                                <i class="fa-solid fa-envelope text-slate-400 mr-1.5"></i>mc2894@cornell.edu
                            </a>
                        </div>
                        <div>
                            <a href="https://www.linkedin.com/in/meggierchen/" target="_blank" class="text-blue-600 hover:underline">
                                <i class="fa-brands fa-linkedin text-slate-400 mr-1.5"></i>linkedin.com/in/meggierchen
                            </a>
                        </div>
                    </div>
                </div>
            </header>

            <!-- EDUCATION -->
            <section class="mb-8">
                <h2 class="text-xs font-extrabold uppercase tracking-widest text-slate-400 mb-3 flex items-center gap-2">
                    <i class="fa-solid fa-graduation-cap text-blue-600"></i> Education
                </h2>
                
                <div class="bg-slate-50/80 rounded-xl p-5 border border-slate-200/80">
                    <div class="flex flex-col sm:flex-row sm:items-baseline justify-between gap-1">
                        <h3 class="text-lg font-bold text-slate-900">Cornell University</h3>
                        <span class="text-xs font-semibold text-slate-500 font-mono">Ithaca, NY</span>
                    </div>
                    
                    <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-1 mt-1">
                        <p class="text-sm font-semibold text-slate-800">
                            B.S. in Mechanical Engineering 
                            <span class="text-blue-700 font-bold ml-2 bg-blue-100 px-2 py-0.5 rounded text-xs">GPA: 3.98</span>
                        </p>
                        <span class="text-xs font-medium text-slate-600">Expected December 2027</span>
                    </div>

                    <div class="mt-4">
                        <p class="text-xs font-bold uppercase tracking-wider text-slate-500 mb-2">Relevant Coursework:</p>
                        <div class="flex flex-wrap gap-1.5">
                            <span class="text-xs font-medium bg-white text-slate-700 px-2.5 py-1 rounded-md border border-slate-200 shadow-xs">Statics & Mechanics of Solids</span>
                            <span class="text-xs font-medium bg-white text-slate-700 px-2.5 py-1 rounded-md border border-slate-200 shadow-xs">Mechanics of Engineering Materials</span>
                            <span class="text-xs font-medium bg-white text-slate-700 px-2.5 py-1 rounded-md border border-slate-200 shadow-xs">Dynamics</span>
                            <span class="text-xs font-medium bg-white text-slate-700 px-2.5 py-1 rounded-md border border-slate-200 shadow-xs">Flight Dynamics</span>
                            <span class="text-xs font-medium bg-white text-slate-700 px-2.5 py-1 rounded-md border border-slate-200 shadow-xs">System Dynamics</span>
                            <span class="text-xs font-medium bg-white text-slate-700 px-2.5 py-1 rounded-md border border-slate-200 shadow-xs">Mechatronics</span>
                            <span class="text-xs font-medium bg-white text-slate-700 px-2.5 py-1 rounded-md border border-slate-200 shadow-xs">Thermodynamics</span>
                            <span class="text-xs font-medium bg-white text-slate-700 px-2.5 py-1 rounded-md border border-slate-200 shadow-xs">Heat Transfer</span>
                            <span class="text-xs font-medium bg-white text-slate-700 px-2.5 py-1 rounded-md border border-slate-200 shadow-xs">Fluid Mechanics</span>
                            <span class="text-xs font-medium bg-white text-slate-700 px-2.5 py-1 rounded-md border border-slate-200 shadow-xs">Spacecraft Dynamics</span>
                        </div>
                    </div>
                </div>
            </section>

            <!-- EXPERIENCE -->
            <section class="mb-8">
                <h2 class="text-xs font-extrabold uppercase tracking-widest text-slate-400 mb-4 flex items-center gap-2">
                    <i class="fa-solid fa-briefcase text-blue-600"></i> Technical & Leadership Experience
                </h2>

                <div class="space-y-6">

                    <!-- SPACEX -->
                    <div class="border-l-2 border-blue-600 pl-4 sm:pl-5 py-1">
                        <div class="flex flex-col sm:flex-row sm:items-baseline justify-between gap-1">
                            <h3 class="text-base sm:text-lg font-extrabold text-slate-900 flex items-center gap-2">
                                SPACEX
                                <span class="text-[10px] uppercase font-bold tracking-wider bg-slate-900 text-slate-100 px-2 py-0.5 rounded">Incoming</span>
                            </h3>
                            <span class="text-xs font-bold text-blue-700 font-mono bg-blue-50 px-2.5 py-0.5 rounded border border-blue-100">Spring 2027</span>
                        </div>
                        <p class="text-sm font-semibold text-slate-700 mt-0.5">Incoming Engineering Intern &mdash; Launch Mechanisms and Structures</p>
                        <ul class="mt-2 text-xs sm:text-sm text-slate-600 list-disc list-outside ml-4 space-y-1">
                            <li>Supporting the development of ground support and pad infrastructure for Starship on the Launch Mechanisms and Structures team.</li>
                        </ul>
                    </div>

                    <!-- CORNELL AIR SYSTEMS -->
                    <div class="border-l-2 border-slate-200 hover:border-blue-500 transition-colors pl-4 sm:pl-5 py-1">
                        <div class="flex flex-col sm:flex-row sm:items-baseline justify-between gap-1">
                            <h3 class="text-base sm:text-lg font-extrabold text-slate-900">CORNELL UNIVERSITY UNMANNED AIR SYSTEMS</h3>
                            <span class="text-xs font-medium text-slate-500 font-mono">November 2024 &ndash; Present</span>
                        </div>
                        
                        <div class="mt-2">
                            <p class="text-xs sm:text-sm font-bold text-slate-800">Structures and Payloads Lead</p>
                            <ul class="mt-1 text-xs sm:text-sm text-slate-600 list-disc list-outside ml-4 space-y-1.5">
                                <li>Lead a 10-engineer structures and payloads subgroup on a 35 lb autonomous search-and-rescue VTOL aircraft (70+ person team, 2nd of 6 at CUASC), directing implementation of the team's first tilt-rotor VTOL system as an alternative to the 4-motor-plus-pusher layout; bench-tested and preparing for flight trials.</li>
                                <li>Supervise 6–8 concurrent projects (tilt rotors, airdrop, gimbal, landing gear, bay doors, imaging test platform) through four formal design reviews, coordinating mechanical interfaces with the electrical and software subteams.</li>
                            </ul>
                        </div>

                        <div class="mt-3.5 pt-3.5 border-t border-slate-100">
                            <p class="text-xs sm:text-sm font-bold text-slate-800">Structures and Payloads Mechanical Member</p>
                            <ul class="mt-1 text-xs sm:text-sm text-slate-600 list-disc list-outside ml-4 space-y-1.5">
                                <li>Evaluated landing gear concepts on weight, compliance, and manufacturability, then designed, fabricated, and validated a carbon-fiber leaf-spring gear using SolidWorks and Ansys FEA; verified a 36% weight reduction across physical drop trials (straight, tilted, sustained load) at 1 m/s landing velocity and 15° roll.</li>
                                <li>Characterized off-the-shelf strut suspension mechanics by executing static compression testing across incremental loads to extract effective spring stiffness, applying strain energy conservation models to predict peak dynamic deflection and boundary limits under free-fall conditions, giving a conservative upper limit safety margin.</li>
                                <li>Reworked a DJI drone airframe to integrate custom hardware mounts and reinforce structurally unsound elements within constrained central-bay geometry, collaborating with electrical and imaging subteams to resolve interface and wiring constraints.</li>
                            </ul>
                        </div>
                    </div>

                    <!-- INTUITIVE SURGICAL -->
                    <div class="border-l-2 border-slate-200 hover:border-blue-500 transition-colors pl-4 sm:pl-5 py-1">
                        <div class="flex flex-col sm:flex-row sm:items-baseline justify-between gap-1">
                            <h3 class="text-base sm:text-lg font-extrabold text-slate-900">INTUITIVE SURGICAL</h3>
                            <span class="text-xs font-medium text-slate-500 font-mono">June 2026 &ndash; August 2026</span>
                        </div>
                        <p class="text-xs sm:text-sm font-bold text-slate-800 mt-0.5">Manufacturing Process Engineering Intern</p>
                        <ul class="mt-2 text-xs sm:text-sm text-slate-600 list-disc list-outside ml-4 space-y-1.5">
                            <li>Engineered and deployed a custom manufacturing line fixture to resolve an active bottleneck, confirmed to cut per-unit build time by 55% (40 seconds saved per unit) via line time studies.</li>
                            <li>Executed a 132-run DoE and capability analysis in Minitab, using Cpk metrics and Pareto charts to isolate primary failure modes and reduce future testing scope by 50%.</li>
                            <li>Designed and modeled custom machining fixtures, producing shop-ready technical drawings to support fabrication.</li>
                            <li>Managed 5 ECOs and created and managed up to 20 parts and documents across Agile PLM and Windchill, maintaining CAD version control under regulated QMS standards.</li>
                        </ul>
                    </div>

                    <!-- SPACE SYSTEMS DESIGN STUDIO -->
                    <div class="border-l-2 border-slate-200 hover:border-blue-500 transition-colors pl-4 sm:pl-5 py-1">
                        <div class="flex flex-col sm:flex-row sm:items-baseline justify-between gap-1">
                            <h3 class="text-base sm:text-lg font-extrabold text-slate-900">SPACE SYSTEMS DESIGN STUDIO (SSDS)</h3>
                            <span class="text-xs font-medium text-slate-500 font-mono">January 2026 &ndash; July 2026</span>
                        </div>
                        <p class="text-xs sm:text-sm font-bold text-slate-800 mt-0.5">ASCENT Mechanical Subteam Member</p>
                        <ul class="mt-2 text-xs sm:text-sm text-slate-600 list-disc list-outside ml-4 space-y-1.5">
                            <li>Precision-machined a rocket bulkhead on a manual mill and lathe, holding ±0.005 in tolerances to ensure structural interface alignment, and fabricated custom 3D-printed mounting brackets.</li>
                            <li>Designed a compact four-bar linkage in Fusion 360 to synchronize dual valve actuation through a 90° sweep with a single servo for liquid bi-propellant rocket, resolving engine-bay clearance constraints and preventing component interference; the linkage survived 2 hot fires and a live takeoff.</li>
                        </ul>
                    </div>

                    <!-- ASTRA LAB -->
                    <div class="border-l-2 border-slate-200 hover:border-blue-500 transition-colors pl-4 sm:pl-5 py-1">
                        <div class="flex flex-col sm:flex-row sm:items-baseline justify-between gap-1">
                            <h3 class="text-base sm:text-lg font-extrabold text-slate-900">ADVANCED SPACE TECHNOLOGY RESEARCH AND ARCHITECTURES LAB</h3>
                            <span class="text-xs font-medium text-slate-500 font-mono">June 2025 &ndash; August 2025</span>
                        </div>
                        <p class="text-xs sm:text-sm font-bold text-slate-800 mt-0.5">Undergraduate Researcher</p>
                        <ul class="mt-2 text-xs sm:text-sm text-slate-600 list-disc list-outside ml-4 space-y-1.5">
                            <li>Ran 18 Density Functional Theory simulations in CP2K and 8 molecular dynamics simulations in LAMMPS, compiling binding-energy data for 16 ionic liquids to support a machine-learning model for predicting electric-propulsion fuel properties.</li>
                        </ul>
                    </div>

                </div>
            </section>

            <!-- SKILLS -->
            <section>
                <h2 class="text-xs font-extrabold uppercase tracking-widest text-slate-400 mb-3 flex items-center gap-2">
                    <i class="fa-solid fa-gears text-blue-600"></i> Skills
                </h2>

                <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                    <div class="bg-slate-50 rounded-xl p-4 border border-slate-200/80">
                        <h3 class="text-xs font-bold uppercase tracking-wider text-slate-700 mb-2">Fabrication</h3>
                        <div class="flex flex-wrap gap-1.5">
                            <span class="text-xs font-semibold bg-white text-slate-800 px-2.5 py-1 rounded-md border border-slate-200">Manual Mill</span>
                            <span class="text-xs font-semibold bg-white text-slate-800 px-2.5 py-1 rounded-md border border-slate-200">Manual Lathe</span>
                            <span class="text-xs font-semibold bg-white text-slate-800 px-2.5 py-1 rounded-md border border-slate-200">Wet Carbon-Fiber Layups</span>
                            <span class="text-xs font-semibold bg-white text-slate-800 px-2.5 py-1 rounded-md border border-slate-200">3D Printing</span>
                            <span class="text-xs font-semibold bg-white text-slate-800 px-2.5 py-1 rounded-md border border-slate-200">Rapid Prototyping</span>
                        </div>
                    </div>

                    <div class="bg-slate-50 rounded-xl p-4 border border-slate-200/80">
                        <h3 class="text-xs font-bold uppercase tracking-wider text-slate-700 mb-2">Software & Programming</h3>
                        <div class="flex flex-wrap gap-1.5">
                            <span class="text-xs font-semibold bg-white text-slate-800 px-2.5 py-1 rounded-md border border-slate-200">SolidWorks</span>
                            <span class="text-xs font-semibold bg-white text-slate-800 px-2.5 py-1 rounded-md border border-slate-200">Fusion 360</span>
                            <span class="text-xs font-semibold bg-white text-slate-800 px-2.5 py-1 rounded-md border border-slate-200">Ansys Mechanical</span>
                            <span class="text-xs font-semibold bg-white text-slate-800 px-2.5 py-1 rounded-md border border-slate-200">Python</span>
                            <span class="text-xs font-semibold bg-white text-slate-800 px-2.5 py-1 rounded-md border border-slate-200">MATLAB</span>
                            <span class="text-xs font-semibold bg-white text-slate-800 px-2.5 py-1 rounded-md border border-slate-200">Java</span>
                            <span class="text-xs font-semibold bg-white text-slate-800 px-2.5 py-1 rounded-md border border-slate-200">Agile PLM</span>
                            <span class="text-xs font-semibold bg-white text-slate-800 px-2.5 py-1 rounded-md border border-slate-200">Windchill</span>
                            <span class="text-xs font-semibold bg-white text-slate-800 px-2.5 py-1 rounded-md border border-slate-200">Confluence</span>
                        </div>
                    </div>
                </div>
            </section>

        </article>

    </main>

    <script>
        function copyJekyllCode() {
            const codeText = document.getElementById('jekyll-snippet').innerText;
            const tempTextArea = document.createElement('textarea');
            tempTextArea.value = codeText;
            document.body.appendChild(tempTextArea);
            tempTextArea.select();
            document.execCommand('copy');
            document.body.removeChild(tempTextArea);

            const btnText = document.getElementById('copy-btn-text');
            btnText.textContent = 'Copied!';
            setTimeout(() => {
                btnText.textContent = 'Copy Code for GitHub Pages';
            }, 2500);
        }
    </script>
</body>
</html>