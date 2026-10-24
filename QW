<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>QUIRK TECHNOLOGY - Engineering &amp; Facilities</title>

    <!-- Google Fonts: Syne, Plus Jakarta Sans & JetBrains Mono -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;500;600&family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&family=Syne:wght@600;700;800&display=swap" rel="stylesheet">

    <!-- Font Awesome 6 Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        dark: {
                            950: '#04070D',
                            900: '#080C14',
                            850: '#0C121E',
                            800: '#111827',
                            750: '#172236',
                            700: '#1F293D',
                        },
                        brand: {
                            blue: '#0066FF',
                            cyan: '#00D2FF',
                            neon: '#10B981',
                            amber: '#F59E0B',
                        }
                    },
                    fontFamily: {
                        display: ['Syne', 'sans-serif'],
                        sans: ['"Plus Jakarta Sans"', 'sans-serif'],
                        mono: ['"JetBrains Mono"', 'monospace'],
                    },
                    animation: {
                        'pulse-glow': 'pulseGlow 5s ease-in-out infinite',
                        'float': 'float 6s ease-in-out infinite',
                    },
                    keyframes: {
                        pulseGlow: {
                            '0%, 100%': { opacity: '0.3', transform: 'scale(1)' },
                            '50%': { opacity: '0.65', transform: 'scale(1.08)' },
                        },
                        float: {
                            '0%, 100%': { transform: 'translateY(0px)' },
                            '50%': { transform: 'translateY(-8px)' },
                        }
                    }
                }
            }
        }
    </script>

    <style>
        html {
            overflow-x: hidden;
        }

        body {
            background-color: #060911;
            color: #E2E8F0;
            overflow-x: hidden;
            font-family: 'Plus Jakarta Sans', sans-serif;
            -webkit-tap-highlight-color: transparent;
        }

        ::selection {
            background-color: #0066FF;
            color: #ffffff;
        }

        .grid-pattern {
            background-size: 48px 48px;
            background-image: 
                linear-gradient(to right, rgba(255, 255, 255, 0.03) 1px, transparent 1px),
                linear-gradient(to bottom, rgba(255, 255, 255, 0.03) 1px, transparent 1px);
        }

        .glass-panel {
            background: rgba(12, 18, 30, 0.75);
            backdrop-filter: blur(18px);
            -webkit-backdrop-filter: blur(18px);
            border: 1px solid rgba(255, 255, 255, 0.08);
        }

        .glass-card {
            background: linear-gradient(135deg, rgba(17, 24, 39, 0.6) 0%, rgba(8, 12, 20, 0.75) 100%);
            backdrop-filter: blur(14px);
            -webkit-backdrop-filter: blur(14px);
            border: 1px solid rgba(255, 255, 255, 0.07);
            transition: all 0.3s cubic-bezier(0.16, 1, 0.3, 1);
        }

        .glass-card:hover {
            border-color: rgba(0, 210, 255, 0.35);
            transform: translateY(-4px);
            box-shadow: 0 16px 36px -10px rgba(0, 102, 255, 0.2);
        }

        .hero-title-gradient {
            background: linear-gradient(135deg, #FFFFFF 15%, #CBD5E1 55%, #00D2FF 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .accent-gradient-text {
            background: linear-gradient(90deg, #00D2FF, #0066FF);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        /* Hide scrollbars for cleaner mobile tab sliding */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }

        ::-webkit-scrollbar {
            width: 7px;
            height: 7px;
        }
        ::-webkit-scrollbar-track {
            background: #080C14;
        }
        ::-webkit-scrollbar-thumb {
            background: #1E293B;
            border-radius: 4px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #0066FF;
        }
    </style>
</head>
<body class="relative min-h-screen">

<!-- Ambient Glowing Orbs Background -->
<div class="fixed inset-0 pointer-events-none z-0 overflow-hidden">
    <div class="absolute -top-[10%] -left-[10%] w-[350px] sm:w-[650px] h-[350px] sm:h-[650px] bg-brand-blue/15 rounded-full blur-[100px] sm:blur-[140px] animate-pulse-glow"></div>
    <div class="absolute top-[35%] -right-[15%] w-[320px] sm:w-[600px] h-[320px] sm:h-[600px] bg-brand-cyan/10 rounded-full blur-[100px] sm:blur-[160px] animate-pulse-glow" style="animation-delay: 2s;"></div>
    <div class="absolute -bottom-[10%] left-[10%] sm:left-[25%] w-[350px] sm:w-[700px] h-[350px] sm:h-[700px] bg-brand-blue/10 rounded-full blur-[120px] sm:blur-[180px]"></div>
    <div class="absolute inset-0 grid-pattern opacity-60"></div>
</div>

<!-- Live Telemetry Status Bar -->
<aside aria-label="Facility status" class="relative z-50 bg-dark-950/90 border-b border-white/5 py-2 px-3 sm:px-4 text-xs font-mono text-slate-400">
    <div class="max-w-7xl mx-auto flex flex-wrap items-center justify-between gap-2">
        <div class="flex items-center gap-2">
            <span class="inline-block w-2 h-2 rounded-full bg-emerald-400 animate-ping"></span>
            <span class="text-slate-300 font-semibold tracking-wider uppercase text-[10px] sm:text-[11px]">System Status:</span>
            <span class="text-emerald-400 font-medium text-[10px] sm:text-xs">On-Ground Engineering Teams Active Across Central India</span>
        </div>
        <div class="hidden md:flex items-center gap-6 text-[11px]">
            <span><i class="fa-solid fa-clock mr-1.5 text-brand-cyan"></i> Emergency SLA: &lt;60 Mins</span>
            <span><i class="fa-solid fa-phone mr-1.5 text-brand-blue"></i> Direct: +91 9425991996</span>
            <span><i class="fa-solid fa-location-dot mr-1.5 text-brand-cyan"></i> HQ: Scheme 114, Indore, MP</span>
        </div>
    </div>
</aside>

<!-- Floating Two-Tier Header Navigation -->
<header class="sticky top-2 sm:top-3 z-40 px-3 sm:px-6 lg:px-8 max-w-7xl mx-auto">
    <nav class="glass-panel rounded-2xl p-3 sm:p-4 shadow-2xl shadow-black/40 border border-white/10 flex flex-col gap-2.5 sm:gap-3">
        
        <!-- Row 1 (Top Line): Logo & Primary Navigation Links -->
        <div class="flex items-center justify-between gap-2 sm:gap-4">
            <!-- Brand Logo -->
            <a href="#home" class="flex items-center gap-2.5 sm:gap-3 shrink-0 group">
                <div class="w-10 h-10 sm:w-11 sm:h-11 rounded-xl bg-black border border-white/15 p-1 flex items-center justify-center overflow-hidden shadow-md group-hover:border-brand-cyan/40 transition-all">
                    <img src="QUIRK TECHNOLOGY logo.jpg" 
                         alt="QUIRK TECHNOLOGY" 
                         class="w-full h-full object-contain"
                         onerror="this.onerror=null; this.parentElement.innerHTML='<i class=\'fa-solid fa-bolt-lightning text-brand-cyan text-base sm:text-lg\'></i>';">
                </div>
                <div>
                    <span class="font-display font-extrabold text-sm sm:text-base lg:text-lg tracking-tight text-white flex items-center gap-1.5">
                        QUIRK <span class="text-[9px] sm:text-[10px] lg:text-xs px-1.5 sm:px-2 py-0.5 rounded-full bg-brand-blue/20 text-brand-cyan font-mono border border-brand-blue/30 font-semibold">TECH</span>
                    </span>
                    <p class="text-[9px] sm:text-[10px] uppercase tracking-wider sm:tracking-widest text-slate-400 -mt-0.5 font-medium">Engineering &amp; Facilities</p>
                </div>
            </a>

            <!-- Full Navigation Menu (Icons + Labels with whitespace-nowrap) -->
            <div class="hidden lg:flex items-center gap-4 xl:gap-6 text-xs xl:text-sm font-medium text-slate-300">
                <a href="#home" class="flex items-center gap-1.5 hover:text-brand-cyan transition-colors whitespace-nowrap">
                    <i class="fa-solid fa-house text-brand-cyan text-xs"></i>
                    <span>Home</span>
                </a>
                <a href="#about" class="flex items-center gap-1.5 hover:text-brand-cyan transition-colors whitespace-nowrap">
                    <i class="fa-solid fa-circle-info text-brand-cyan text-xs"></i>
                    <span>About</span>
                </a>
                <a href="#it-services" class="flex items-center gap-1.5 hover:text-brand-cyan transition-colors whitespace-nowrap">
                    <i class="fa-solid fa-microchip text-brand-cyan text-xs"></i>
                    <span>IT &amp; AI</span>
                </a>
                <a href="#engineering" class="flex items-center gap-1.5 hover:text-brand-cyan transition-colors whitespace-nowrap">
                    <i class="fa-solid fa-gears text-brand-cyan text-xs"></i>
                    <span>Engineering</span>
                </a>
                <a href="#construction" class="flex items-center gap-1.5 hover:text-brand-cyan transition-colors whitespace-nowrap">
                    <i class="fa-solid fa-trowel-bricks text-brand-cyan text-xs"></i>
                    <span>Construction</span>
                </a>
                <a href="#solutions" class="flex items-center gap-1.5 hover:text-brand-cyan transition-colors whitespace-nowrap">
                    <i class="fa-solid fa-sliders text-brand-cyan text-xs"></i>
                    <span>Tech Specs</span>
                </a>
                <a href="#calculator" class="flex items-center gap-1.5 hover:text-brand-cyan transition-colors whitespace-nowrap">
                    <i class="fa-solid fa-calculator text-brand-cyan text-xs"></i>
                    <span>AMC Estimator</span>
                </a>
                <a href="#contact" class="flex items-center gap-1.5 hover:text-brand-cyan transition-colors whitespace-nowrap">
                    <i class="fa-solid fa-envelope text-brand-cyan text-xs"></i>
                    <span>Contact</span>
                </a>
            </div>

            <!-- Quick WhatsApp link for mobile header + Hamburger Toggle -->
            <div class="flex items-center gap-2 lg:hidden">
                <a href="https://wa.me/919425991996?text=Hello%20Quirk%20Technology,%20I%20would%20like%20to%20inquire%20about%20your%20engineering%20services." 
                   target="_blank" 
                   rel="noopener"
                   class="w-10 h-10 rounded-xl bg-emerald-500/20 border border-emerald-500/30 flex items-center justify-center text-emerald-400 hover:text-emerald-300 transition-colors"
                   aria-label="WhatsApp">
                    <i class="fa-brands fa-whatsapp text-lg"></i>
                </a>
                <button id="mobileMenuToggle" 
                        class="w-10 h-10 rounded-xl bg-white/5 border border-white/10 flex items-center justify-center text-slate-300 hover:text-white transition-colors"
                        aria-label="Toggle Menu">
                    <i id="mobileMenuIcon" class="fa-solid fa-bars-staggered text-sm"></i>
                </button>
            </div>
        </div>

        <!-- Row 2 (Downside / 2nd Line): WhatsApp & Get Free Quote Action Bar -->
        <div class="hidden lg:flex items-center justify-between pt-2.5 border-t border-white/5">
            <!-- Left Status and Hotline -->
            <div class="flex items-center gap-4 text-[11px] font-mono text-slate-400">
                <span class="flex items-center gap-1.5 text-emerald-400">
                    <span class="w-1.5 h-1.5 rounded-full bg-emerald-400 animate-ping"></span>
                    Central India Rapid SLA &lt;60 Mins
                </span>
                <span class="text-white/20">|</span>
                <span><i class="fa-solid fa-headset mr-1 text-brand-cyan"></i> 24/7 Breakdown Desk: +91 9425991996</span>
            </div>

            <!-- Action CTAs -->
            <div class="flex items-center gap-3">
                <a href="https://wa.me/919425991996?text=Hello%20Quirk%20Technology,%20I%20would%20like%20to%20inquire%20about%20your%20engineering%20services." 
                   target="_blank" 
                   rel="noopener"
                   class="inline-flex items-center gap-2 px-4 py-2 rounded-xl bg-emerald-500/15 hover:bg-emerald-500/25 border border-emerald-500/30 text-emerald-300 hover:text-emerald-200 font-semibold text-xs tracking-wide shadow-lg shadow-emerald-500/10 hover:-translate-y-0.5 transition-all">
                    <i class="fa-brands fa-whatsapp text-sm text-emerald-400"></i>
                    <span>WhatsApp</span>
                </a>
                
                <a href="#calculator" 
                   class="inline-flex items-center gap-2 px-5 py-2 rounded-xl bg-gradient-to-r from-brand-blue to-brand-cyan text-white font-bold text-xs tracking-wide shadow-lg shadow-brand-blue/30 hover:shadow-brand-blue/50 hover:-translate-y-0.5 transition-all">
                    <span>Get a Free Quote</span>
                    <i class="fa-solid fa-arrow-right text-[11px]"></i>
                </a>
            </div>
        </div>

    </nav>

    <!-- Mobile Drawer Menu -->
    <div id="mobileDrawer" class="hidden lg:hidden mt-2 glass-panel rounded-2xl p-4 sm:p-5 shadow-2xl border border-white/10 max-h-[80vh] overflow-y-auto">
        <div class="flex flex-col gap-2 text-sm font-medium">
            <a href="#home" class="mobile-nav-link flex items-center gap-3 text-slate-300 hover:text-brand-cyan py-2.5 px-2 rounded-lg hover:bg-white/[0.03] border-b border-white/5">
                <i class="fa-solid fa-house text-brand-cyan text-xs w-4"></i> Home
            </a>
            <a href="#about" class="mobile-nav-link flex items-center gap-3 text-slate-300 hover:text-brand-cyan py-2.5 px-2 rounded-lg hover:bg-white/[0.03] border-b border-white/5">
                <i class="fa-solid fa-circle-info text-brand-cyan text-xs w-4"></i> About
            </a>
            <a href="#it-services" class="mobile-nav-link flex items-center gap-3 text-slate-300 hover:text-brand-cyan py-2.5 px-2 rounded-lg hover:bg-white/[0.03] border-b border-white/5">
                <i class="fa-solid fa-microchip text-brand-cyan text-xs w-4"></i> IT &amp; AI Services
            </a>
            <a href="#engineering" class="mobile-nav-link flex items-center gap-3 text-slate-300 hover:text-brand-cyan py-2.5 px-2 rounded-lg hover:bg-white/[0.03] border-b border-white/5">
                <i class="fa-solid fa-gears text-brand-cyan text-xs w-4"></i> Engineering Services
            </a>
            <a href="#construction" class="mobile-nav-link flex items-center gap-3 text-slate-300 hover:text-brand-cyan py-2.5 px-2 rounded-lg hover:bg-white/[0.03] border-b border-white/5">
                <i class="fa-solid fa-trowel-bricks text-brand-cyan text-xs w-4"></i> Construction Services
            </a>
            <a href="#solutions" class="mobile-nav-link flex items-center gap-3 text-slate-300 hover:text-brand-cyan py-2.5 px-2 rounded-lg hover:bg-white/[0.03] border-b border-white/5">
                <i class="fa-solid fa-sliders text-brand-cyan text-xs w-4"></i> Technical Specs
            </a>
            <a href="#why-us" class="mobile-nav-link flex items-center gap-3 text-slate-300 hover:text-brand-cyan py-2.5 px-2 rounded-lg hover:bg-white/[0.03] border-b border-white/5">
                <i class="fa-solid fa-award text-brand-cyan text-xs w-4"></i> Why Choose Us
            </a>
            <a href="#calculator" class="mobile-nav-link flex items-center gap-3 text-slate-300 hover:text-brand-cyan py-2.5 px-2 rounded-lg hover:bg-white/[0.03] border-b border-white/5">
                <i class="fa-solid fa-calculator text-brand-cyan text-xs w-4"></i> AMC Estimator
            </a>
            <a href="#contact" class="mobile-nav-link flex items-center gap-3 text-slate-300 hover:text-brand-cyan py-2.5 px-2 rounded-lg hover:bg-white/[0.03]">
                <i class="fa-solid fa-envelope text-brand-cyan text-xs w-4"></i> Contact
            </a>
            
            <div class="pt-3 border-t border-white/10 flex flex-col gap-2.5">
                <a href="https://wa.me/919425991996" target="_blank" class="flex items-center justify-center gap-2 w-full py-3 rounded-xl bg-emerald-500/20 text-emerald-400 border border-emerald-500/30 text-xs font-semibold">
                    <i class="fa-brands fa-whatsapp text-sm"></i> Chat on WhatsApp (+91 9425991996)
                </a>
                <a href="#calculator" class="mobile-nav-link flex items-center justify-center gap-2 w-full py-3 rounded-xl bg-gradient-to-r from-brand-blue to-brand-cyan text-white text-xs font-semibold">
                    Get a Free Quote <i class="fa-solid fa-arrow-right text-xs"></i>
                </a>
            </div>
        </div>
    </div>
</header>

<!-- Main Content Flow -->
<main class="relative z-10 overflow-hidden">

    <!-- 1. Hero Section -->
    <section id="home" class="pt-10 sm:pt-16 pb-14 sm:pb-20 lg:pt-24 lg:pb-32 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-10 sm:gap-12 lg:gap-8 items-center">
            
            <!-- Hero Left: Content -->
            <div class="lg:col-span-7 flex flex-col items-start text-left">
                <div class="inline-flex items-center gap-2 px-3 py-1.5 rounded-full bg-brand-blue/10 border border-brand-blue/30 text-brand-cyan text-[10px] sm:text-xs font-mono font-medium mb-5 sm:mb-6 backdrop-blur-md">
                    <span class="w-1.5 h-1.5 rounded-full bg-brand-cyan animate-ping shrink-0"></span>
                    <span class="truncate">ESTABLISHED 2012 • ENGINEERING, IT &amp; FACILITY INFRASTRUCTURE</span>
                </div>

                <h1 class="font-display text-3xl sm:text-5xl lg:text-5xl xl:text-6xl font-extrabold tracking-tight hero-title-gradient leading-[1.15] mb-5 sm:mb-6">
                    Next-Gen Engineering &amp; Intelligent <span class="accent-gradient-text">Facility Systems.</span>
                </h1>

                <p class="text-slate-400 text-sm sm:text-base lg:text-lg max-w-2xl leading-relaxed mb-6 sm:mb-8">
                    Central India's trusted single-window engineering authority since 2012. We modernize and maintain elevator lifelines, high-tonnage HVAC chiller plants, smart BMS architectures, and mission-critical IT &amp; AI networks with rapid SLA execution.
                </p>

                <!-- CTAs -->
                <div class="flex flex-col sm:flex-row items-stretch sm:items-center gap-3.5 sm:gap-4 w-full sm:w-auto mb-8 sm:mb-10">
                    <a href="#calculator" 
                       class="w-full sm:w-auto px-6 sm:px-7 py-3.5 sm:py-4 rounded-xl bg-gradient-to-r from-brand-blue to-brand-cyan text-white font-semibold text-xs sm:text-sm tracking-wide shadow-xl shadow-brand-blue/25 hover:shadow-brand-blue/40 hover:-translate-y-0.5 transition-all flex items-center justify-center gap-2.5">
                        <i class="fa-solid fa-calculator"></i>
                        <span>Get a Free Quote</span>
                    </a>

                    <a href="https://wa.me/919425991996" 
                       target="_blank"
                       class="w-full sm:w-auto px-6 sm:px-7 py-3.5 sm:py-4 rounded-xl bg-white/5 hover:bg-white/10 border border-white/10 text-white font-semibold text-xs sm:text-sm tracking-wide transition-all flex items-center justify-center gap-2.5 backdrop-blur-md">
                        <i class="fa-brands fa-whatsapp text-emerald-400 text-base"></i>
                        <span>WhatsApp Technical Desk</span>
                    </a>
                </div>

                <!-- Trust Tags -->
                <div class="pt-5 sm:pt-6 border-t border-white/10 w-full flex flex-col sm:flex-row sm:flex-wrap items-start sm:items-center gap-3 sm:gap-6 text-xs text-slate-400 font-mono">
                    <div class="flex items-center gap-2">
                        <i class="fa-solid fa-shield-halved text-brand-cyan shrink-0"></i>
                        <span>ISO Certified Field Engineers</span>
                    </div>
                    <div class="flex items-center gap-2">
                        <i class="fa-solid fa-microchip text-brand-cyan shrink-0"></i>
                        <span>Predictive Sensor Telemetry</span>
                    </div>
                    <div class="flex items-center gap-2">
                        <i class="fa-solid fa-headset text-emerald-400 shrink-0"></i>
                        <span>24/7 Rapid Response Unit</span>
                    </div>
                </div>
            </div>

            <!-- Hero Right: Photorealistic Visual & Telemetry Bento -->
            <div class="lg:col-span-5 relative w-full">
                <div class="absolute inset-0 bg-gradient-to-tr from-brand-blue/20 via-brand-cyan/20 to-transparent rounded-3xl blur-2xl -z-10"></div>
                
                <div class="relative space-y-4">
                    <!-- Photorealistic Engineering Visual Card -->
                    <div class="glass-card rounded-2xl overflow-hidden border border-white/10">
                        <div class="relative h-48 sm:h-56 w-full overflow-hidden">
                            <img src="https://images.unsplash.com/photo-1581092160607-ee22621dd758?auto=format&fit=crop&w=1000&q=80" 
                                 alt="Engineer inspecting facility infrastructure and control systems" 
                                 class="w-full h-full object-cover">
                            <div class="absolute inset-0 bg-gradient-to-t from-dark-950 via-dark-950/40 to-transparent"></div>
                            <div class="absolute bottom-3 left-3 sm:left-4 right-3 sm:right-4 flex items-center justify-between">
                                <div class="flex items-center gap-2 text-[10px] sm:text-xs font-mono text-white bg-dark-950/80 px-2.5 py-1 rounded-md border border-white/10 backdrop-blur-md">
                                    <i class="fa-solid fa-circle text-[7px] sm:text-[8px] text-emerald-400 animate-ping"></i>
                                    <span>Indore Central Operations</span>
                                </div>
                                <span class="text-[10px] font-mono bg-brand-blue/40 text-brand-cyan px-2 py-0.5 rounded border border-brand-cyan/30">Active</span>
                            </div>
                        </div>

                        <div class="p-4 sm:p-5">
                            <div class="flex items-center justify-between mb-3">
                                <div>
                                    <h2 class="text-xs sm:text-sm font-semibold text-white">Lift &amp; HVAC Real-Time Telemetry</h2>
                                    <p class="text-[11px] sm:text-xs text-slate-400 font-mono">Preventive Vibration &amp; Load Loops</p>
                                </div>
                                <span class="px-2 sm:px-2.5 py-0.5 sm:py-1 rounded-full text-[9px] sm:text-[10px] font-mono bg-emerald-500/15 text-emerald-400 border border-emerald-500/30 whitespace-nowrap">
                                    99.9% Uptime
                                </span>
                            </div>

                            <div class="space-y-2 mb-4">
                                <div class="flex justify-between text-xs text-slate-400 font-mono">
                                    <span>Governor &amp; Safety Diagnostics</span>
                                    <span class="text-brand-cyan font-semibold">Nominal 0.02g</span>
                                </div>
                                <div class="w-full h-2 rounded-full bg-dark-950 overflow-hidden">
                                    <div class="h-full bg-gradient-to-r from-brand-blue to-brand-cyan rounded-full w-[94%]"></div>
                                </div>
                            </div>

                            <div class="grid grid-cols-3 gap-2 pt-3 border-t border-white/5 text-center text-xs">
                                <div class="bg-dark-950/60 p-2 rounded-lg border border-white/5">
                                    <p class="text-[9px] sm:text-[10px] uppercase text-slate-400 font-mono">AMC Mode</p>
                                    <p class="text-[11px] sm:text-xs font-bold text-white mt-0.5">Turnkey</p>
                                </div>
                                <div class="bg-dark-950/60 p-2 rounded-lg border border-white/5">
                                    <p class="text-[9px] sm:text-[10px] uppercase text-slate-400 font-mono">Response</p>
                                    <p class="text-[11px] sm:text-xs font-bold text-brand-cyan mt-0.5">&lt;45 Min</p>
                                </div>
                                <div class="bg-dark-950/60 p-2 rounded-lg border border-white/5">
                                    <p class="text-[9px] sm:text-[10px] uppercase text-slate-400 font-mono">Standard</p>
                                    <p class="text-[11px] sm:text-xs font-bold text-emerald-400 mt-0.5">IS:14665</p>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Highlights Banner -->
                    <div class="grid grid-cols-2 gap-3 sm:gap-4">
                        <div class="glass-card rounded-2xl p-3.5 sm:p-4 border border-white/10">
                            <i class="fa-solid fa-snowflake text-brand-cyan text-base sm:text-lg mb-1"></i>
                            <p class="text-lg sm:text-xl font-display font-extrabold text-white">35%+</p>
                            <p class="text-[11px] sm:text-xs text-slate-400 font-medium">Energy Savings on Chiller Plants</p>
                        </div>
                        <div class="glass-card rounded-2xl p-3.5 sm:p-4 border border-white/10">
                            <i class="fa-solid fa-building-circle-check text-emerald-400 text-base sm:text-lg mb-1"></i>
                            <p class="text-lg sm:text-xl font-display font-extrabold text-white">250+</p>
                            <p class="text-[11px] sm:text-xs text-slate-400 font-medium">Commercial Facilities Managed</p>
                        </div>
                    </div>
                </div>
            </div>

        </div>
    </section>

    <!-- Metric Ribbon -->
    <section class="border-y border-white/10 bg-dark-900/60 backdrop-blur-md py-8 sm:py-10 px-4">
        <div class="max-w-7xl mx-auto grid grid-cols-2 lg:grid-cols-4 gap-6 sm:gap-8 text-center divide-x-0 sm:divide-x divide-white/10">
            <div class="px-2 sm:px-4">
                <p class="font-display text-3xl sm:text-4xl lg:text-5xl font-extrabold text-white tracking-tight">12+</p>
                <p class="text-[11px] sm:text-sm font-mono text-brand-cyan uppercase tracking-wider mt-1.5">Years of Excellence</p>
                <p class="text-[10px] sm:text-xs text-slate-400 mt-1">Established in 2012</p>
            </div>
            <div class="px-2 sm:px-4">
                <p class="font-display text-3xl sm:text-4xl lg:text-5xl font-extrabold text-white tracking-tight">250+</p>
                <p class="text-[11px] sm:text-sm font-mono text-brand-cyan uppercase tracking-wider mt-1.5">Deployments</p>
                <p class="text-[10px] sm:text-xs text-slate-400 mt-1">Commercial, Malls &amp; Hospitals</p>
            </div>
            <div class="px-2 sm:px-4">
                <p class="font-display text-3xl sm:text-4xl lg:text-5xl font-extrabold text-white tracking-tight">99.8%</p>
                <p class="text-[11px] sm:text-sm font-mono text-brand-cyan uppercase tracking-wider mt-1.5">Facility Uptime</p>
                <p class="text-[10px] sm:text-xs text-slate-400 mt-1">Preventive engineering protocols</p>
            </div>
            <div class="px-2 sm:px-4">
                <p class="font-display text-3xl sm:text-4xl lg:text-5xl font-extrabold text-emerald-400 tracking-tight">&lt;60m</p>
                <p class="text-[11px] sm:text-sm font-mono text-emerald-400 uppercase tracking-wider mt-1.5">Emergency SLA</p>
                <p class="text-[10px] sm:text-xs text-slate-400 mt-1">Rapid on-ground response</p>
            </div>
        </div>
    </section>

    <!-- 2. About Us Section -->
    <section id="about" class="py-14 sm:py-20 lg:py-24 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 sm:gap-12 items-center">
            
            <!-- Left: Photorealistic Visual -->
            <div class="lg:col-span-5 relative order-2 lg:order-1">
                <div class="glass-card rounded-3xl p-3 border border-white/10 overflow-hidden group">
                    <div class="relative h-72 sm:h-96 lg:h-[430px] rounded-2xl overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1486406146926-c627a92ad1ab?auto=format&fit=crop&w=1200&q=80" 
                             alt="Modern Commercial Towers and Complex Infrastructure Managed by Quirk Technology"
                             class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700">
                        <div class="absolute inset-0 bg-gradient-to-t from-dark-950 via-dark-950/40 to-transparent"></div>
                        
                        <div class="absolute bottom-3 sm:bottom-4 left-3 sm:left-4 right-3 sm:right-4 glass-panel rounded-xl p-3 sm:p-4 border border-white/15">
                            <div class="flex items-center gap-3">
                                <div class="w-8 h-8 sm:w-9 sm:h-9 rounded-lg bg-brand-blue flex items-center justify-center text-white shrink-0">
                                    <i class="fa-solid fa-map-location-dot text-sm"></i>
                                </div>
                                <div>
                                    <p class="text-xs font-semibold text-white">Central Operations Hub</p>
                                    <p class="text-[10px] sm:text-[11px] text-slate-300">Scheme No 114, Part I, Indore (MP)</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Right: Content Narrative -->
            <div class="lg:col-span-7 space-y-5 sm:space-y-6 order-1 lg:order-2">
                <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-white/5 border border-white/10 text-[10px] sm:text-xs font-mono text-slate-300">
                    <i class="fa-solid fa-compass-drafting text-brand-cyan"></i>
                    <span>OUR ENGINEERING HERITAGE</span>
                </div>

                <h2 class="font-display text-2xl sm:text-3xl lg:text-4xl font-extrabold text-white tracking-tight leading-tight">
                    Built for Zero-Downtime. <br class="hidden sm:inline">
                    Engineered for <span class="accent-gradient-text">Absolute Reliability.</span>
                </h2>

                <p class="text-slate-400 text-sm sm:text-base leading-relaxed">
                    Founded in 2012 in Indore, Madhya Pradesh, <strong class="text-white">QUIRK TECHNOLOGY SOLUTIONS</strong> has grown into the premier engineering authority for multi-tenant commercial towers, luxury hospitality hubs, manufacturing facilities, and healthcare campuses across Central India.
                </p>

                <p class="text-slate-400 text-sm sm:text-base leading-relaxed">
                    Instead of managing multiple conflicting contractors for HVAC, elevators, surveillance, and networking, leading enterprises partner with Quirk for cohesive, single-source operational excellence with transparent SLA accountability.
                </p>

                <div class="grid grid-cols-1 sm:grid-cols-2 gap-3 sm:gap-4 pt-2 sm:pt-4">
                    <div class="flex items-start gap-3 p-3.5 rounded-xl bg-white/[0.03] border border-white/5">
                        <div class="text-brand-cyan mt-0.5 shrink-0"><i class="fa-solid fa-check-double text-sm"></i></div>
                        <div>
                            <h3 class="text-xs sm:text-sm font-semibold text-white">OEM-Compliant Upgrades</h3>
                            <p class="text-[11px] sm:text-xs text-slate-400 mt-0.5">Compatible across Otis, Schindler, KONE, Daikin, Johnson Controls.</p>
                        </div>
                    </div>

                    <div class="flex items-start gap-3 p-3.5 rounded-xl bg-white/[0.03] border border-white/5">
                        <div class="text-brand-cyan mt-0.5 shrink-0"><i class="fa-solid fa-microchip text-sm"></i></div>
                        <div>
                            <h3 class="text-xs sm:text-sm font-semibold text-white">Predictive Diagnostics</h3>
                            <p class="text-[11px] sm:text-xs text-slate-400 mt-0.5">Vibration, thermal, and amperage tracking before breakdowns occur.</p>
                        </div>
                    </div>

                    <div class="flex items-start gap-3 p-3.5 rounded-xl bg-white/[0.03] border border-white/5">
                        <div class="text-brand-cyan mt-0.5 shrink-0"><i class="fa-solid fa-handshake-angle text-sm"></i></div>
                        <div>
                            <h3 class="text-xs sm:text-sm font-semibold text-white">Transparent AMC Contracts</h3>
                            <p class="text-[11px] sm:text-xs text-slate-400 mt-0.5">Clear scope definition without sudden hidden replacement costs.</p>
                        </div>
                    </div>

                    <div class="flex items-start gap-3 p-3.5 rounded-xl bg-white/[0.03] border border-white/5">
                        <div class="text-brand-cyan mt-0.5 shrink-0"><i class="fa-solid fa-certificate text-sm"></i></div>
                        <div>
                            <h3 class="text-xs sm:text-sm font-semibold text-white">Statutory Safety Compliance</h3>
                            <p class="text-[11px] sm:text-xs text-slate-400 mt-0.5">Strict adherence to Indian Standards (IS) and building safety codes.</p>
                        </div>
                    </div>
                </div>
            </div>

        </div>
    </section>

    <!-- 3. IT & AI Services Section -->
    <section id="it-services" class="py-14 sm:py-20 lg:py-24 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto border-t border-white/5">
        <div class="text-center max-w-3xl mx-auto mb-10 sm:mb-16">
            <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-brand-cyan/10 border border-brand-cyan/30 text-[10px] sm:text-xs font-mono text-brand-cyan mb-3 sm:mb-4">
                <i class="fa-solid fa-brain"></i>
                <span>DIGITAL INTELLIGENCE &amp; CONNECTIVITY</span>
            </div>
            <h2 class="font-display text-2xl sm:text-4xl lg:text-5xl font-extrabold text-white tracking-tight">
                IT &amp; AI Technology Services
            </h2>
            <p class="text-slate-400 text-xs sm:text-sm lg:text-base mt-3 sm:mt-4">
                From enterprise optical fiber backbones to smart AI automation, cybersecurity, and cloud portals.
            </p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-5 sm:gap-6">
            <!-- Service 1: AI Solutions -->
            <div class="glass-card rounded-3xl p-5 sm:p-7 border border-white/10 flex flex-col justify-between group">
                <div>
                    <div class="relative h-44 rounded-2xl overflow-hidden mb-5 sm:mb-6">
                        <img src="https://i.ibb.co/rKYbcDhm/AI-photo.jpg" 
                             alt="AI Neural Network and Automation Solutions" 
                             class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                        <div class="absolute inset-0 bg-gradient-to-t from-dark-950 via-dark-950/20 to-transparent"></div>
                        <span class="absolute top-3 right-3 text-[10px] font-mono px-2.5 py-1 rounded-full bg-dark-950/80 text-brand-cyan border border-brand-cyan/30">
                            AI &amp; ML
                        </span>
                    </div>
                    <h3 class="font-display text-lg sm:text-xl font-bold text-white group-hover:text-brand-cyan transition-colors">
                        AI Solutions &amp; Process Automation
                    </h3>
                    <p class="text-slate-400 text-xs sm:text-sm mt-2 sm:mt-3 leading-relaxed">
                        Intelligent computer vision, anomaly detectors, automated workflow triggers, and smart facility reporting bots.
                    </p>
                    <ul class="mt-4 space-y-2 text-xs text-slate-300 font-mono">
                        <li class="flex items-center gap-2"><i class="fa-solid fa-angle-right text-brand-cyan"></i> Predictive Maintenance AI</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-angle-right text-brand-cyan"></i> Optical Character &amp; ANPR Models</li>
                    </ul>
                </div>
            </div>

            <!-- Service 2: CCTV & Electronic Security -->
            <div class="glass-card rounded-3xl p-5 sm:p-7 border border-white/10 flex flex-col justify-between group">
                <div>
                    <div class="relative h-44 rounded-2xl overflow-hidden mb-5 sm:mb-6">
                        <img src="https://images.unsplash.com/photo-1557597774-9d273605dfa9?auto=format&fit=crop&w=700&q=80" 
                             alt="Photorealistic 4K IP CCTV Camera and Smart Surveillance" 
                             class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                        <div class="absolute inset-0 bg-gradient-to-t from-dark-950 via-dark-950/20 to-transparent"></div>
                        <span class="absolute top-3 right-3 text-[10px] font-mono px-2.5 py-1 rounded-full bg-dark-950/80 text-emerald-400 border border-emerald-500/30">
                            4K Vision
                        </span>
                    </div>
                    <h3 class="font-display text-lg sm:text-xl font-bold text-white group-hover:text-brand-cyan transition-colors">
                        CCTV Surveillance &amp; Electronic Security
                    </h3>
                    <p class="text-slate-400 text-xs sm:text-sm mt-2 sm:mt-3 leading-relaxed">
                        Ultra-HD IP surveillance architectures, biometric access turnstiles, perimeter laser barriers, and centralized control room setups.
                    </p>
                    <ul class="mt-4 space-y-2 text-xs text-slate-300 font-mono">
                        <li class="flex items-center gap-2"><i class="fa-solid fa-angle-right text-brand-cyan"></i> Cloud &amp; Local NVR RAID Arrays</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-angle-right text-brand-cyan"></i> Touchless Facial Recognition</li>
                    </ul>
                </div>
            </div>

            <!-- Service 3: Fiber Optics & Structured Networking -->
            <div class="glass-card rounded-3xl p-5 sm:p-7 border border-white/10 flex flex-col justify-between group">
                <div>
                    <div class="relative h-44 rounded-2xl overflow-hidden mb-5 sm:mb-6">
                        <img src="https://images.unsplash.com/photo-1544197150-b99a580bb7a8?auto=format&fit=crop&w=700&q=80" 
                             alt="Fiber Optic Cables and High Speed Telecommunications" 
                             class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                        <div class="absolute inset-0 bg-gradient-to-t from-dark-950 via-dark-950/20 to-transparent"></div>
                        <span class="absolute top-3 right-3 text-[10px] font-mono px-2.5 py-1 rounded-full bg-dark-950/80 text-sky-400 border border-sky-500/30">
                            10G/40G
                        </span>
                    </div>
                    <h3 class="font-display text-lg sm:text-xl font-bold text-white group-hover:text-brand-cyan transition-colors">
                        Fiber Optics &amp; Networking
                    </h3>
                    <p class="text-slate-400 text-xs sm:text-sm mt-2 sm:mt-3 leading-relaxed">
                        Structured optical fiber backbones, single-mode and multi-mode fusion splicing, OTDR validation, and Cat6A enterprise networks.
                    </p>
                    <ul class="mt-4 space-y-2 text-xs text-slate-300 font-mono">
                        <li class="flex items-center gap-2"><i class="fa-solid fa-angle-right text-brand-cyan"></i> Fluke-Certified Channel Testing</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-angle-right text-brand-cyan"></i> Low-Loss Optical Distribution</li>
                    </ul>
                </div>
            </div>

            <!-- Service 4: IT Infrastructure & Servers -->
            <div class="glass-card rounded-3xl p-5 sm:p-7 border border-white/10 flex flex-col justify-between group">
                <div>
                    <div class="relative h-44 rounded-2xl overflow-hidden mb-5 sm:mb-6">
                        <img src="https://images.unsplash.com/photo-1558494949-ef010cbdcc31?auto=format&fit=crop&w=700&q=80" 
                             alt="Enterprise Server Rack and Data Center Infrastructure" 
                             class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                        <div class="absolute inset-0 bg-gradient-to-t from-dark-950 via-dark-950/20 to-transparent"></div>
                        <span class="absolute top-3 right-3 text-[10px] font-mono px-2.5 py-1 rounded-full bg-dark-950/80 text-brand-cyan border border-brand-blue/30">
                            Server Hub
                        </span>
                    </div>
                    <h3 class="font-display text-lg sm:text-xl font-bold text-white group-hover:text-brand-cyan transition-colors">
                        IT Infrastructure &amp; Data Centers
                    </h3>
                    <p class="text-slate-400 text-xs sm:text-sm mt-2 sm:mt-3 leading-relaxed">
                        Server rack thermal management, redundant power supplies (UPS syncing), managed routing, enterprise switching, and cloud gateways.
                    </p>
                    <ul class="mt-4 space-y-2 text-xs text-slate-300 font-mono">
                        <li class="flex items-center gap-2"><i class="fa-solid fa-angle-right text-brand-cyan"></i> Tier-1/Tier-2 Server Room Builds</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-angle-right text-brand-cyan"></i> Dual Redundant ISP Failovers</li>
                    </ul>
                </div>
            </div>

            <!-- Service 5: Web & Mobile App Development -->
            <div class="glass-card rounded-3xl p-5 sm:p-7 border border-white/10 flex flex-col justify-between group">
                <div>
                    <div class="relative h-44 rounded-2xl overflow-hidden mb-5 sm:mb-6">
                        <img src="https://images.unsplash.com/photo-1555066931-4365d14bab8c?auto=format&fit=crop&w=700&q=80" 
                             alt="Custom Software, Web, and Mobile Application Development" 
                             class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                        <div class="absolute inset-0 bg-gradient-to-t from-dark-950 via-dark-950/20 to-transparent"></div>
                        <span class="absolute top-3 right-3 text-[10px] font-mono px-2.5 py-1 rounded-full bg-dark-950/80 text-emerald-400 border border-emerald-500/30">
                            Full Stack
                        </span>
                    </div>
                    <h3 class="font-display text-lg sm:text-xl font-bold text-white group-hover:text-brand-cyan transition-colors">
                        Web &amp; App Development
                    </h3>
                    <p class="text-slate-400 text-xs sm:text-sm mt-2 sm:mt-3 leading-relaxed">
                        Custom enterprise web portals, mobile workforce applications, real-time IoT monitoring dashboards, and facility booking software.
                    </p>
                    <ul class="mt-4 space-y-2 text-xs text-slate-300 font-mono">
                        <li class="flex items-center gap-2"><i class="fa-solid fa-angle-right text-brand-cyan"></i> Responsive Progressive Web Apps</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-angle-right text-brand-cyan"></i> Secure API Integrations &amp; Cloud</li>
                    </ul>
                </div>
            </div>

            <!-- Service 6: Turnkey Managed IT Desk -->
            <div class="glass-card rounded-3xl p-5 sm:p-7 border border-white/10 flex flex-col justify-between group">
                <div>
                    <div class="relative h-44 rounded-2xl overflow-hidden mb-5 sm:mb-6">
                        <img src="https://images.unsplash.com/photo-1531482615713-2afd69097998?auto=format&fit=crop&w=700&q=80" 
                             alt="IT Support Engineer and Helpdesk Assistance" 
                             class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                        <div class="absolute inset-0 bg-gradient-to-t from-dark-950 via-dark-950/20 to-transparent"></div>
                        <span class="absolute top-3 right-3 text-[10px] font-mono px-2.5 py-1 rounded-full bg-dark-950/80 text-amber-400 border border-amber-500/30">
                            24/7 SLA
                        </span>
                    </div>
                    <h3 class="font-display text-lg sm:text-xl font-bold text-white group-hover:text-brand-cyan transition-colors">
                        Managed IT &amp; Helpdesk AMC
                    </h3>
                    <p class="text-slate-400 text-xs sm:text-sm mt-2 sm:mt-3 leading-relaxed">
                        Complete workplace technology management, scheduled antivirus/firmware patching, asset lifecycle tracking, and SLA ticketing desks.
                    </p>
                    <ul class="mt-4 space-y-2 text-xs text-slate-300 font-mono">
                        <li class="flex items-center gap-2"><i class="fa-solid fa-angle-right text-brand-cyan"></i> Dedicated Resident Engineers</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-angle-right text-brand-cyan"></i> Complete IT Inventory Audits</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- 4. Engineering Services Section -->
    <section id="engineering" class="py-14 sm:py-20 lg:py-24 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto border-t border-white/5">
        <div class="text-center max-w-3xl mx-auto mb-10 sm:mb-16">
            <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-brand-blue/10 border border-brand-blue/30 text-[10px] sm:text-xs font-mono text-brand-cyan mb-3 sm:mb-4">
                <i class="fa-solid fa-gears"></i>
                <span>MISSION CRITICAL MEP &amp; LIFELINES</span>
            </div>
            <h2 class="font-display text-2xl sm:text-4xl lg:text-5xl font-extrabold text-white tracking-tight">
                Heavy Engineering &amp; Facility Operations
            </h2>
            <p class="text-slate-400 text-xs sm:text-sm lg:text-base mt-3 sm:mt-4">
                Precision maintenance, scheduled overhauls, and modernization for vital building electro-mechanical infrastructure.
            </p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-5 sm:gap-6">

            <!-- Lift & Elevator Care -->
            <div class="glass-card rounded-3xl p-5 sm:p-7 border border-white/10 flex flex-col justify-between group">
                <div>
                    <div class="relative h-44 rounded-2xl overflow-hidden mb-5 sm:mb-6 bg-dark-900">
                        <img src="https://i.ibb.co/svjFx9PB/elevtor.jpg" 
                             alt="Modern High Speed Glass Elevator Shaft Maintenance" 
                             class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500"
                             onerror="this.onerror=null; this.src='https://images.unsplash.com/photo-1541888946425-d0fbb186c5f9?auto=format&fit=crop&w=800&q=80';">
                        <div class="absolute inset-0 bg-gradient-to-t from-dark-950 via-dark-950/20 to-transparent"></div>
                        <span class="absolute top-3 right-3 text-[10px] font-mono px-2.5 py-1 rounded-full bg-dark-950/80 text-brand-cyan border border-brand-cyan/30">
                            IS:14665 Spec
                        </span>
                    </div>
                    <h3 class="font-display text-lg sm:text-xl font-bold text-white group-hover:text-brand-cyan transition-colors">
                        Lift &amp; Elevator Maintenance
                    </h3>
                    <p class="text-slate-400 text-xs sm:text-sm mt-2 sm:mt-3 leading-relaxed">
                        Hydraulic, traction, gearless, and machine-room-less (MRL) elevators. Includes 24/7 passenger rescue protocols, ARD calibration, and annual modernization.
                    </p>
                    <ul class="mt-4 space-y-2 text-xs text-slate-300 font-mono">
                        <li class="flex items-center gap-2"><i class="fa-solid fa-angle-right text-brand-cyan"></i> Emergency Passenger Rescue Hotline</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-angle-right text-brand-cyan"></i> Governor &amp; Brake Load Testing</li>
                    </ul>
                </div>
            </div>

            <!-- AC / VRF & Chiller Systems -->
            <div class="glass-card rounded-3xl p-5 sm:p-7 border border-white/10 flex flex-col justify-between group">
                <div>
                    <div class="relative h-44 rounded-2xl overflow-hidden mb-5 sm:mb-6 bg-dark-900">
                        <img src="https://images.unsplash.com/photo-1581092918056-0c4c3acd3789?auto=format&fit=crop&w=800&q=80" 
                             alt="Industrial Chiller and Commercial HVAC Systems" 
                             class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500"
                             onerror="this.onerror=null; this.src='https://images.unsplash.com/photo-1504384308090-c894fdcc538d?auto=format&fit=crop&w=800&q=80';">
                        <div class="absolute inset-0 bg-gradient-to-t from-dark-950 via-dark-950/20 to-transparent"></div>
                        <span class="absolute top-3 right-3 text-[10px] font-mono px-2.5 py-1 rounded-full bg-dark-950/80 text-emerald-400 border border-emerald-500/30">
                            Up to 35% Savings
                        </span>
                    </div>
                    <h3 class="font-display text-lg sm:text-xl font-bold text-white group-hover:text-brand-cyan transition-colors">
                        AC/VRF &amp; Chiller Systems
                    </h3>
                    <p class="text-slate-400 text-xs sm:text-sm mt-2 sm:mt-3 leading-relaxed">
                        Water-cooled &amp; air-cooled central chillers, VRV/VRF multi-splits, and AHU balancing. Precision compressor tuning and descaling to eliminate power waste.
                    </p>
                    <ul class="mt-4 space-y-2 text-xs text-slate-300 font-mono">
                        <li class="flex items-center gap-2"><i class="fa-solid fa-angle-right text-brand-cyan"></i> Refrigerant Balancing (R-410A, R-32)</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-angle-right text-brand-cyan"></i> Heat Exchanger Chemical Descaling</li>
                    </ul>
                </div>
            </div>

            <!-- Smart BMS Automation -->
            <div class="glass-card rounded-3xl p-5 sm:p-7 border border-white/10 flex flex-col justify-between group">
                <div>
                    <div class="relative h-44 rounded-2xl overflow-hidden mb-5 sm:mb-6 bg-dark-900">
                        <img src="https://images.unsplash.com/photo-1558002038-1055907df827?auto=format&fit=crop&w=800&q=80" 
                             alt="Smart Building Automation and BMS Control Systems" 
                             class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500"
                             onerror="this.onerror=null; this.src='https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=800&q=80';">
                        <div class="absolute inset-0 bg-gradient-to-t from-dark-950 via-dark-950/20 to-transparent"></div>
                        <span class="absolute top-3 right-3 text-[10px] font-mono px-2.5 py-1 rounded-full bg-dark-950/80 text-indigo-400 border border-indigo-500/30">
                            BACnet / Modbus
                        </span>
                    </div>
                    <h3 class="font-display text-lg sm:text-xl font-bold text-white group-hover:text-brand-cyan transition-colors">
                        BMS Automation &amp; SCADA
                    </h3>
                    <p class="text-slate-400 text-xs sm:text-sm mt-2 sm:mt-3 leading-relaxed">
                        Central Building Management Systems synchronizing ventilation, lighting schedules, water management, DG syncing, and power peak shaving.
                    </p>
                    <ul class="mt-4 space-y-2 text-xs text-slate-300 font-mono">
                        <li class="flex items-center gap-2"><i class="fa-solid fa-angle-right text-brand-cyan"></i> Live Telemetry &amp; Fault Alerts</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-angle-right text-brand-cyan"></i> Automated ESG Carbon Reports</li>
                    </ul>
                </div>
            </div>

            <!-- Electrical & Mechanical Maintenance -->
            <div class="glass-card rounded-3xl p-5 sm:p-7 border border-white/10 flex flex-col justify-between group">
                <div>
                    <div class="relative h-44 rounded-2xl overflow-hidden mb-5 sm:mb-6 bg-dark-900">
                        <img src="https://images.unsplash.com/photo-1621905251189-08b45d6a269e?auto=format&fit=crop&w=800&q=80" 
                             alt="Industrial Electrical Transformers and Mechanical Panels" 
                             class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500"
                             onerror="this.onerror=null; this.src='https://images.unsplash.com/photo-1581092160607-ee22621dd758?auto=format&fit=crop&w=800&q=80';">
                        <div class="absolute inset-0 bg-gradient-to-t from-dark-950 via-dark-950/20 to-transparent"></div>
                        <span class="absolute top-3 right-3 text-[10px] font-mono px-2.5 py-1 rounded-full bg-dark-950/80 text-amber-400 border border-amber-500/30">
                            HT / LT Panels
                        </span>
                    </div>
                    <h3 class="font-display text-lg sm:text-xl font-bold text-white group-hover:text-brand-cyan transition-colors">
                        Electrical &amp; Mechanical Systems
                    </h3>
                    <p class="text-slate-400 text-xs sm:text-sm mt-2 sm:mt-3 leading-relaxed">
                        HT/LT panels, capacitor banks, transformer servicing, diesel generator (DG) synchronizing, motor rewinding, and water booster pump upkeep.
                    </p>
                    <ul class="mt-4 space-y-2 text-xs text-slate-300 font-mono">
                        <li class="flex items-center gap-2"><i class="fa-solid fa-angle-right text-brand-cyan"></i> Thermographic Panel Scans</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-angle-right text-brand-cyan"></i> Earth Pit Resistance Verification</li>
                    </ul>
                </div>
            </div>

            <!-- Fire Fighting & Life Safety -->
            <div class="glass-card rounded-3xl p-5 sm:p-7 border border-white/10 flex flex-col justify-between group">
                <div>
                    <div class="relative h-44 rounded-2xl overflow-hidden mb-5 sm:mb-6 bg-dark-900">
                        <img src="https://i.ibb.co/XfZmpTDx/fireline.jpg" 
                             alt="Industrial Fire Fighting Hydrant System and Sprinkler Infrastructure" 
                             class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500"
                             onerror="this.onerror=null; this.src='https://images.unsplash.com/photo-1509783236416-c9ad59bae472?auto=format&fit=crop&w=800&q=80';">
                        <div class="absolute inset-0 bg-gradient-to-t from-dark-950 via-dark-950/20 to-transparent"></div>
                        <span class="absolute top-3 right-3 text-[10px] font-mono px-2.5 py-1 rounded-full bg-dark-950/80 text-rose-400 border border-rose-500/30">
                            Life Safety
                        </span>
                    </div>
                    <h3 class="font-display text-lg sm:text-xl font-bold text-white group-hover:text-brand-cyan transition-colors">
                        Fire Fighting &amp; Life Safety
                    </h3>
                    <p class="text-slate-400 text-xs sm:text-sm mt-2 sm:mt-3 leading-relaxed">
                        Hydrant lines, jockey pumps, smoke extraction dampers, addressable fire alarm loops, and statutory fire audit certifications.
                    </p>
                    <ul class="mt-4 space-y-2 text-xs text-slate-300 font-mono">
                        <li class="flex items-center gap-2"><i class="fa-solid fa-angle-right text-brand-cyan"></i> Hydro-Testing of Fire Mains</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-angle-right text-brand-cyan"></i> Quarterly Mock Drill Readiness</li>
                    </ul>
                </div>
            </div>

            <!-- Comprehensive Turnkey AMC Services -->
            <div class="glass-card rounded-3xl p-5 sm:p-7 border border-white/10 flex flex-col justify-between group">
                <div>
                    <div class="relative h-44 rounded-2xl overflow-hidden mb-5 sm:mb-6 bg-dark-900">
                        <img src="https://images.unsplash.com/photo-1504384308090-c894fdcc538d?auto=format&fit=crop&w=800&q=80" 
                             alt="Complete Facility Operations and High Tech Engineering Management" 
                             class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500"
                             onerror="this.onerror=null; this.src='https://images.unsplash.com/photo-1581092160607-ee22621dd758?auto=format&fit=crop&w=800&q=80';">
                        <div class="absolute inset-0 bg-gradient-to-t from-dark-950 via-dark-950/20 to-transparent"></div>
                        <span class="absolute top-3 right-3 text-[10px] font-mono px-2.5 py-1 rounded-full bg-dark-950/80 text-brand-cyan border border-brand-cyan/30">
                            Single Window
                        </span>
                    </div>
                    <h3 class="font-display text-lg sm:text-xl font-bold text-white group-hover:text-brand-cyan transition-colors">
                        Comprehensive Facility AMCs
                    </h3>
                    <p class="text-slate-400 text-xs sm:text-sm mt-2 sm:mt-3 leading-relaxed">
                        Total turnkey facility maintenance covering all electrical, mechanical, plumbing, and automation systems under unified accountability.
                    </p>
                    <ul class="mt-4 space-y-2 text-xs text-slate-300 font-mono">
                        <li class="flex items-center gap-2"><i class="fa-solid fa-angle-right text-brand-cyan"></i> Dedicated Resident Technicians</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-angle-right text-brand-cyan"></i> Guaranteed Response Time SLAs</li>
                    </ul>
                </div>
            </div>

        </div>
    </section>

    <!-- 5. Construction Services Section -->
    <section id="construction" class="py-14 sm:py-20 lg:py-24 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto border-t border-white/5">
        <div class="text-center max-w-3xl mx-auto mb-10 sm:mb-16">
            <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-brand-cyan/10 border border-brand-cyan/30 text-[10px] sm:text-xs font-mono text-brand-cyan mb-3 sm:mb-4">
                <i class="fa-solid fa-trowel-bricks"></i>
                <span>STRUCTURAL INTEGRITY &amp; CIVIL SOLUTIONS</span>
            </div>
            <h2 class="font-display text-2xl sm:text-4xl lg:text-5xl font-extrabold text-white tracking-tight">
                Construction &amp; Infrastructure Maintenance
            </h2>
            <p class="text-slate-400 text-xs sm:text-sm lg:text-base mt-3 sm:mt-4">
                Delivering precision building construction, retrofitting, civil restoration, and ongoing infrastructure upkeep.
            </p>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-5 sm:gap-6">
            <!-- Construction Item 1 -->
            <div class="glass-card rounded-2xl p-5 sm:p-6 border border-white/10 group">
                <div class="relative h-40 rounded-xl overflow-hidden mb-4">
                    <img src="https://images.unsplash.com/photo-1503387762-592deb58ef4e?auto=format&fit=crop&w=600&q=80" 
                         alt="Commercial Building Construction and Structural Framework" 
                         class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                    <div class="absolute inset-0 bg-dark-950/30"></div>
                </div>
                <h3 class="font-display text-base sm:text-lg font-bold text-white group-hover:text-brand-cyan transition-colors">
                    Building Construction
                </h3>
                <p class="text-slate-400 text-xs mt-2 leading-relaxed">
                    Commercial edifices, warehouse facilities, structural steel erection, and industrial plant development.
                </p>
            </div>

            <!-- Construction Item 2 -->
            <div class="glass-card rounded-2xl p-5 sm:p-6 border border-white/10 group">
                <div class="relative h-40 rounded-xl overflow-hidden mb-4">
                    <img src="https://images.unsplash.com/photo-1513694203232-719a280e022f?auto=format&fit=crop&w=600&q=80" 
                         alt="Renovation and Modern Architecture Remodeling" 
                         class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                    <div class="absolute inset-0 bg-dark-950/30"></div>
                </div>
                <h3 class="font-display text-base sm:text-lg font-bold text-white group-hover:text-brand-cyan transition-colors">
                    Renovation &amp; Remodeling
                </h3>
                <p class="text-slate-400 text-xs mt-2 leading-relaxed">
                    Corporate interior fit-outs, acoustic ceiling integration, facade modernization, and space layout retrofits.
                </p>
            </div>

            <!-- Construction Item 3 -->
            <div class="glass-card rounded-2xl p-5 sm:p-6 border border-white/10 group">
                <div class="relative h-40 rounded-xl overflow-hidden mb-4">
                    <img src="https://images.unsplash.com/photo-1590381105924-c72589b9ef3f?auto=format&fit=crop&w=600&q=80" 
                         alt="Structural Waterproofing and Building Restoration" 
                         class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                    <div class="absolute inset-0 bg-dark-950/30"></div>
                </div>
                <h3 class="font-display text-base sm:text-lg font-bold text-white group-hover:text-brand-cyan transition-colors">
                    Restoration &amp; Waterproofing
                </h3>
                <p class="text-slate-400 text-xs mt-2 leading-relaxed">
                    Advanced polymer waterproofing, concrete crack injections, structural load strengthening, and protective coatings.
                </p>
            </div>

            <!-- Construction Item 4 -->
            <div class="glass-card rounded-2xl p-5 sm:p-6 border border-white/10 group">
                <div class="relative h-40 rounded-xl overflow-hidden mb-4">
                    <img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=600&q=80" 
                         alt="Infrastructure Maintenance and Civil Upkeep" 
                         class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                    <div class="absolute inset-0 bg-dark-950/30"></div>
                </div>
                <h3 class="font-display text-base sm:text-lg font-bold text-white group-hover:text-brand-cyan transition-colors">
                    Infrastructure Upkeep
                </h3>
                <p class="text-slate-400 text-xs mt-2 leading-relaxed">
                    Heavy epoxy industrial flooring, drainage systems, perimeter security walls, and routine civil audits.
                </p>
            </div>
        </div>
    </section>

    <!-- 6. Technical Solutions & Specification Blueprint -->
    <section id="solutions" class="py-14 sm:py-20 lg:py-24 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto border-t border-white/5">
        <div class="glass-panel rounded-3xl p-5 sm:p-8 lg:p-10 border border-white/10">
            <div class="flex flex-col md:flex-row md:items-end justify-between gap-4 sm:gap-6 mb-8 sm:mb-10 pb-6 sm:pb-8 border-b border-white/10">
                <div>
                    <span class="text-[10px] sm:text-xs font-mono text-brand-cyan uppercase tracking-wider block mb-1.5 sm:mb-2">ENGINEERING SPECS &amp; STANDARDS</span>
                    <h2 class="font-display text-2xl sm:text-3xl lg:text-4xl font-extrabold text-white">
                        Technical Solutions Inspector
                    </h2>
                </div>
                <p class="text-slate-400 text-xs sm:text-sm max-w-md">
                    Review capabilities, operational thresholds, and compliance benchmarks across our technical divisions.
                </p>
            </div>

            <!-- Tab Headers (Scrollable on mobile) -->
            <div class="flex overflow-x-auto no-scrollbar gap-2 mb-6 sm:mb-8 pb-2 sm:pb-0" id="specTabHeaders">
                <button class="spec-tab-btn active shrink-0 px-3.5 sm:px-4 py-2 sm:py-2.5 rounded-xl font-mono text-xs transition-all bg-brand-blue text-white shadow-lg shadow-brand-blue/30" data-target="spec-elevator">
                    <i class="fa-solid fa-elevator mr-1.5"></i> Elevators
                </button>
                <button class="spec-tab-btn shrink-0 px-3.5 sm:px-4 py-2 sm:py-2.5 rounded-xl font-mono text-xs transition-all bg-white/5 text-slate-300 hover:bg-white/10 hover:text-white" data-target="spec-hvac">
                    <i class="fa-solid fa-fan mr-1.5"></i> HVAC &amp; Chillers
                </button>
                <button class="spec-tab-btn shrink-0 px-3.5 sm:px-4 py-2 sm:py-2.5 rounded-xl font-mono text-xs transition-all bg-white/5 text-slate-300 hover:bg-white/10 hover:text-white" data-target="spec-bms">
                    <i class="fa-solid fa-microchip mr-1.5"></i> Smart BMS
                </button>
                <button class="spec-tab-btn shrink-0 px-3.5 sm:px-4 py-2 sm:py-2.5 rounded-xl font-mono text-xs transition-all bg-white/5 text-slate-300 hover:bg-white/10 hover:text-white" data-target="spec-security">
                    <i class="fa-solid fa-shield-halved mr-1.5"></i> AI Security
                </button>
                <button class="spec-tab-btn shrink-0 px-3.5 sm:px-4 py-2 sm:py-2.5 rounded-xl font-mono text-xs transition-all bg-white/5 text-slate-300 hover:bg-white/10 hover:text-white" data-target="spec-network">
                    <i class="fa-solid fa-network-wired mr-1.5"></i> Fiber &amp; Network
                </button>
            </div>

            <!-- Tab Panes -->
            <div id="specTabPanes">
                <!-- Tab Pane 1: Elevators -->
                <div id="spec-elevator" class="spec-pane grid grid-cols-1 lg:grid-cols-12 gap-6 sm:gap-8 items-center">
                    <div class="lg:col-span-7 space-y-3 sm:space-y-4">
                        <h3 class="text-lg sm:text-xl font-bold text-white">Passenger, Freight &amp; Hospital Bed Elevators</h3>
                        <p class="text-slate-400 text-xs sm:text-sm leading-relaxed">
                            Our elevator specialists maintain rigorous mechanical precision. With central parts inventory in Indore, we service traction, gearless, and hydraulic models with quick turnarounds.
                        </p>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5 sm:gap-3 pt-2 text-xs font-mono">
                            <div class="p-3 rounded-lg bg-dark-950/60 border border-white/5">
                                <span class="text-slate-400 block text-[10px]">SPEED SPECIFICATION</span>
                                <span class="text-white font-semibold">Up to 4.0 m/sec</span>
                            </div>
                            <div class="p-3 rounded-lg bg-dark-950/60 border border-white/5">
                                <span class="text-slate-400 block text-[10px]">PAYLOAD CAPACITY</span>
                                <span class="text-brand-cyan font-semibold">320 kg to 5,000 kg</span>
                            </div>
                            <div class="p-3 rounded-lg bg-dark-950/60 border border-white/5">
                                <span class="text-slate-400 block text-[10px]">SAFETY PROTOCOL</span>
                                <span class="text-emerald-400 font-semibold">Automatic Rescue Device (ARD)</span>
                            </div>
                            <div class="p-3 rounded-lg bg-dark-950/60 border border-white/5">
                                <span class="text-slate-400 block text-[10px]">AVERAGE SLA</span>
                                <span class="text-amber-400 font-semibold">&lt; 45 Mins Rapid Dispatch</span>
                            </div>
                        </div>
                    </div>
                    <div class="lg:col-span-5">
                        <div class="relative h-56 sm:h-64 rounded-2xl overflow-hidden border border-white/10 bg-dark-900">
                            <img src="https://i.ibb.co/svjFx9PB/elevtor.jpg" 
                                 alt="Elevator Shaft Modern Engineering" 
                                 class="w-full h-full object-cover"
                                 onerror="this.onerror=null; this.src='https://images.unsplash.com/photo-1541888946425-d0fbb186c5f9?auto=format&fit=crop&w=800&q=80';">
                            <div class="absolute inset-0 bg-gradient-to-t from-dark-950/80 to-transparent flex items-end p-3 sm:p-4">
                                <span class="text-[10px] sm:text-xs font-mono text-brand-cyan bg-dark-950/80 px-2.5 sm:px-3 py-1 rounded-md border border-white/10">
                                    <i class="fa-solid fa-wrench mr-1"></i> Multi-Brand Support: Otis, Schindler, KONE
                                </span>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Tab Pane 2: HVAC -->
                <div id="spec-hvac" class="spec-pane hidden grid grid-cols-1 lg:grid-cols-12 gap-6 sm:gap-8 items-center">
                    <div class="lg:col-span-7 space-y-3 sm:space-y-4">
                        <h3 class="text-lg sm:text-xl font-bold text-white">Central Water-Cooled Chillers &amp; Inverter VRF Units</h3>
                        <p class="text-slate-400 text-xs sm:text-sm leading-relaxed">
                            From 5 TR ductables to 800 TR centrifugal chiller plants, we perform dynamic compressor tuning, refrigerant charge balancing, condenser descaling, and AHU coil sanitization.
                        </p>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5 sm:gap-3 pt-2 text-xs font-mono">
                            <div class="p-3 rounded-lg bg-dark-950/60 border border-white/5">
                                <span class="text-slate-400 block text-[10px]">TONNAGE RANGE</span>
                                <span class="text-white font-semibold">3.5 TR to 1200+ TR Plants</span>
                            </div>
                            <div class="p-3 rounded-lg bg-dark-950/60 border border-white/5">
                                <span class="text-slate-400 block text-[10px]">REFRIGERANT TYPES</span>
                                <span class="text-brand-cyan font-semibold">R-410A, R-32, R-134a Eco</span>
                            </div>
                            <div class="p-3 rounded-lg bg-dark-950/60 border border-white/5">
                                <span class="text-slate-400 block text-[10px]">ENERGY SAVING INDEX</span>
                                <span class="text-emerald-400 font-semibold">18% - 35% Measurable Gain</span>
                            </div>
                            <div class="p-3 rounded-lg bg-dark-950/60 border border-white/5">
                                <span class="text-slate-400 block text-[10px]">MAINTENANCE CADENCE</span>
                                <span class="text-amber-400 font-semibold">Monthly + On-Demand Emergency</span>
                            </div>
                        </div>
                    </div>
                    <div class="lg:col-span-5">
                        <div class="relative h-56 sm:h-64 rounded-2xl overflow-hidden border border-white/10 bg-dark-900">
                            <img src="https://images.unsplash.com/photo-1581092918056-0c4c3acd3789?auto=format&fit=crop&w=800&q=80" 
                                 alt="HVAC Chiller Plant Engineering" 
                                 class="w-full h-full object-cover"
                                 onerror="this.onerror=null; this.src='https://images.unsplash.com/photo-1504384308090-c894fdcc538d?auto=format&fit=crop&w=800&q=80';">
                            <div class="absolute inset-0 bg-gradient-to-t from-dark-950/80 to-transparent flex items-end p-3 sm:p-4">
                                <span class="text-[10px] sm:text-xs font-mono text-brand-cyan bg-dark-950/80 px-2.5 sm:px-3 py-1 rounded-md border border-white/10">
                                    <i class="fa-solid fa-droplet mr-1"></i> Descaling &amp; Indoor Air Quality (IAQ)
                                </span>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Tab Pane 3: BMS -->
                <div id="spec-bms" class="spec-pane hidden grid grid-cols-1 lg:grid-cols-12 gap-6 sm:gap-8 items-center">
                    <div class="lg:col-span-7 space-y-3 sm:space-y-4">
                        <h3 class="text-lg sm:text-xl font-bold text-white">Full-Stack Building Management &amp; SCADA Systems</h3>
                        <p class="text-slate-400 text-xs sm:text-sm leading-relaxed">
                            Automate whole building energy grids. Connect DG sets, water treatment, fire dampers, and ventilation systems directly to unified touchscreen command stations.
                        </p>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5 sm:gap-3 pt-2 text-xs font-mono">
                            <div class="p-3 rounded-lg bg-dark-950/60 border border-white/5">
                                <span class="text-slate-400 block text-[10px]">PROTOCOLS</span>
                                <span class="text-white font-semibold">BACnet, Modbus, KNX, MQTT</span>
                            </div>
                            <div class="p-3 rounded-lg bg-dark-950/60 border border-white/5">
                                <span class="text-slate-400 block text-[10px]">INTEGRATION NODES</span>
                                <span class="text-brand-cyan font-semibold">Up to 25,000 I/O Points</span>
                            </div>
                            <div class="p-3 rounded-lg bg-dark-950/60 border border-white/5">
                                <span class="text-slate-400 block text-[10px]">REPORTING</span>
                                <span class="text-emerald-400 font-semibold">Automated ESG Audits</span>
                            </div>
                            <div class="p-3 rounded-lg bg-dark-950/60 border border-white/5">
                                <span class="text-slate-400 block text-[10px]">FAILSAFE</span>
                                <span class="text-amber-400 font-semibold">Dual Hot-Standby Controllers</span>
                            </div>
                        </div>
                    </div>
                    <div class="lg:col-span-5">
                        <div class="relative h-56 sm:h-64 rounded-2xl overflow-hidden border border-white/10">
                            <img src="https://images.unsplash.com/photo-1558002038-1055907df827?auto=format&fit=crop&w=800&q=80" 
                                 alt="Smart BMS Automation Console" 
                                 class="w-full h-full object-cover">
                            <div class="absolute inset-0 bg-gradient-to-t from-dark-950/80 to-transparent flex items-end p-3 sm:p-4">
                                <span class="text-[10px] sm:text-xs font-mono text-brand-cyan bg-dark-950/80 px-2.5 sm:px-3 py-1 rounded-md border border-white/10">
                                    <i class="fa-solid fa-chart-line mr-1"></i> Live Power Telemetry
                                </span>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Tab Pane 4: Security -->
                <div id="spec-security" class="spec-pane hidden grid grid-cols-1 lg:grid-cols-12 gap-6 sm:gap-8 items-center">
                    <div class="lg:col-span-7 space-y-3 sm:space-y-4">
                        <h3 class="text-lg sm:text-xl font-bold text-white">AI Vision &amp; Perimeter Access Infrastructure</h3>
                        <p class="text-slate-400 text-xs sm:text-sm leading-relaxed">
                            Multi-layered facility security. We engineer high frame rate 4K optical setups, speed turnstiles, thermal imaging, and cloud-mirrored video management systems (VMS).
                        </p>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5 sm:gap-3 pt-2 text-xs font-mono">
                            <div class="p-3 rounded-lg bg-dark-950/60 border border-white/5">
                                <span class="text-slate-400 block text-[10px]">CAMERA RESOLUTIONS</span>
                                <span class="text-white font-semibold">4K / 8MP Starlight Infrared</span>
                            </div>
                            <div class="p-3 rounded-lg bg-dark-950/60 border border-white/5">
                                <span class="text-slate-400 block text-[10px]">AI CAPABILITIES</span>
                                <span class="text-brand-cyan font-semibold">ANPR, Crowd, Face &amp; Fire Detect</span>
                            </div>
                            <div class="p-3 rounded-lg bg-dark-950/60 border border-white/5">
                                <span class="text-slate-400 block text-[10px]">STORAGE RETENTION</span>
                                <span class="text-emerald-400 font-semibold">30 - 180 Days RAID-6</span>
                            </div>
                            <div class="p-3 rounded-lg bg-dark-950/60 border border-white/5">
                                <span class="text-slate-400 block text-[10px]">ACCESS LATENCY</span>
                                <span class="text-amber-400 font-semibold">&lt;0.2s Touchless Face Auth</span>
                            </div>
                        </div>
                    </div>
                    <div class="lg:col-span-5">
                        <div class="relative h-56 sm:h-64 rounded-2xl overflow-hidden border border-white/10">
                            <img src="https://images.unsplash.com/photo-1557597774-9d273605dfa9?auto=format&fit=crop&w=800&q=80" 
                                 alt="High End Surveillance Camera" 
                                 class="w-full h-full object-cover">
                            <div class="absolute inset-0 bg-gradient-to-t from-dark-950/80 to-transparent flex items-end p-3 sm:p-4">
                                <span class="text-[10px] sm:text-xs font-mono text-brand-cyan bg-dark-950/80 px-2.5 sm:px-3 py-1 rounded-md border border-white/10">
                                    <i class="fa-solid fa-shield-virus mr-1"></i> Cyber-Hardened Firmware
                                </span>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Tab Pane 5: Network -->
                <div id="spec-network" class="spec-pane hidden grid grid-cols-1 lg:grid-cols-12 gap-6 sm:gap-8 items-center">
                    <div class="lg:col-span-7 space-y-3 sm:space-y-4">
                        <h3 class="text-lg sm:text-xl font-bold text-white">Fiber Backbones &amp; High-Density Switching</h3>
                        <p class="text-slate-400 text-xs sm:text-sm leading-relaxed">
                            Build your facility on reliable connectivity. We install low-loss single-mode and multi-mode fiber trunks, redundant L2/L3 core switches, and enterprise-grade WiFi coverage.
                        </p>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5 sm:gap-3 pt-2 text-xs font-mono">
                            <div class="p-3 rounded-lg bg-dark-950/60 border border-white/5">
                                <span class="text-slate-400 block text-[10px]">FIBER STANDARDS</span>
                                <span class="text-white font-semibold">OM3, OM4 &amp; OS2 Single Mode</span>
                            </div>
                            <div class="p-3 rounded-lg bg-dark-950/60 border border-white/5">
                                <span class="text-slate-400 block text-[10px]">SWITCH FABRIC</span>
                                <span class="text-brand-cyan font-semibold">10G / 40G Uplink Stack</span>
                            </div>
                            <div class="p-3 rounded-lg bg-dark-950/60 border border-white/5">
                                <span class="text-slate-400 block text-[10px]">TESTING CRITERIA</span>
                                <span class="text-emerald-400 font-semibold">100% Channel Fluke Pass</span>
                            </div>
                            <div class="p-3 rounded-lg bg-dark-950/60 border border-white/5">
                                <span class="text-slate-400 block text-[10px]">WARRANTY LIFECYCLE</span>
                                <span class="text-amber-400 font-semibold">Up to 25 Years System Warranty</span>
                            </div>
                        </div>
                    </div>
                    <div class="lg:col-span-5">
                        <div class="relative h-56 sm:h-64 rounded-2xl overflow-hidden border border-white/10">
                            <img src="https://images.unsplash.com/photo-1558494949-ef010cbdcc31?auto=format&fit=crop&w=800&q=80" 
                                 alt="Enterprise Server and Rack Cabling" 
                                 class="w-full h-full object-cover">
                            <div class="absolute inset-0 bg-gradient-to-t from-dark-950/80 to-transparent flex items-end p-3 sm:p-4">
                                <span class="text-[10px] sm:text-xs font-mono text-brand-cyan bg-dark-950/80 px-2.5 sm:px-3 py-1 rounded-md border border-white/10">
                                    <i class="fa-solid fa-server mr-1"></i> Structured Server Rack Management
                                </span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

        </div>
    </section>

    <!-- 7. Why Choose Us Section -->
    <section id="why-us" class="py-14 sm:py-20 lg:py-24 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto border-t border-white/5">
        <div class="text-center max-w-3xl mx-auto mb-10 sm:mb-16">
            <span class="text-[10px] sm:text-xs font-mono text-brand-cyan uppercase tracking-wider block mb-1.5 sm:mb-2">BENCHMARK PERFORMANCE</span>
            <h2 class="font-display text-2xl sm:text-3xl lg:text-4xl font-extrabold text-white">
                Why Choose Quirk Technology Solutions?
            </h2>
            <p class="text-slate-400 text-xs sm:text-sm mt-2 sm:mt-3">
                A direct comparison of our engineering commitments versus unorganized regional vendors.
            </p>
        </div>

        <!-- Comparison Table Container -->
        <div class="glass-panel rounded-3xl overflow-hidden border border-white/10 shadow-2xl">
            <div class="overflow-x-auto">
                <table class="w-full min-w-[620px] text-left border-collapse text-xs sm:text-sm">
                    <thead>
                        <tr class="border-b border-white/10 bg-dark-950/60 font-mono text-[11px] sm:text-xs uppercase tracking-wider text-slate-400">
                            <th class="p-4 sm:p-5">Engineering Parameter</th>
                            <th class="p-4 sm:p-5 text-brand-cyan bg-brand-blue/10 border-x border-white/10">
                                <div class="flex items-center gap-2">
                                    <i class="fa-solid fa-bolt-lightning"></i>
                                    <span>QUIRK TECHNOLOGY SOLUTIONS</span>
                                </div>
                            </th>
                            <th class="p-4 sm:p-5 text-slate-400">Unorganized Local Vendors</th>
                        </tr>
                    </thead>
                    <tbody class="divide-y divide-white/5 text-slate-300">
                        <tr class="hover:bg-white/[0.02] transition-colors">
                            <td class="p-4 sm:p-5 font-medium text-white">Emergency Breakdown SLA</td>
                            <td class="p-4 sm:p-5 bg-brand-blue/[0.03] border-x border-white/10 text-emerald-400 font-semibold">
                                &lt; 45 to 60 Mins On-Site Fleet Response
                            </td>
                            <td class="p-4 sm:p-5 text-slate-400">Unpredictable (4 to 24+ Hours)</td>
                        </tr>
                        <tr class="hover:bg-white/[0.02] transition-colors">
                            <td class="p-4 sm:p-5 font-medium text-white">Engineering Experience</td>
                            <td class="p-4 sm:p-5 bg-brand-blue/[0.03] border-x border-white/10 text-white font-semibold">
                                Established 2012 (12+ Years Field-Tested Legacy)
                            </td>
                            <td class="p-4 sm:p-5 text-slate-400">Ad-hoc Subcontractors &amp; Frequent Turnover</td>
                        </tr>
                        <tr class="hover:bg-white/[0.02] transition-colors">
                            <td class="p-4 sm:p-5 font-medium text-white">Certified Technicians</td>
                            <td class="p-4 sm:p-5 bg-brand-blue/[0.03] border-x border-white/10 text-white font-semibold">
                                Certified Electrical, Mech, HVAC &amp; BMS Engineers
                            </td>
                            <td class="p-4 sm:p-5 text-slate-400">Informal Semi-Skilled Labor</td>
                        </tr>
                        <tr class="hover:bg-white/[0.02] transition-colors">
                            <td class="p-4 sm:p-5 font-medium text-white">Predictive Diagnostic Audits</td>
                            <td class="p-4 sm:p-5 bg-brand-blue/[0.03] border-x border-white/10 text-white font-semibold">
                                Digital Sensor Logging, Thermal &amp; Vibration Scans
                            </td>
                            <td class="p-4 sm:p-5 text-slate-400">Reactive Repairs Only After Breakdown</td>
                        </tr>
                        <tr class="hover:bg-white/[0.02] transition-colors">
                            <td class="p-4 sm:p-5 font-medium text-white">Service Ecosystem</td>
                            <td class="p-4 sm:p-5 bg-brand-blue/[0.03] border-x border-white/10 text-white font-semibold">
                                One-Stop (Elevator + HVAC + Civil + CCTV + IT)
                            </td>
                            <td class="p-4 sm:p-5 text-slate-400">Fragmented (5+ Conflicting Contractors)</td>
                        </tr>
                        <tr class="hover:bg-white/[0.02] transition-colors">
                            <td class="p-4 sm:p-5 font-medium text-white">Safety &amp; Compliance</td>
                            <td class="p-4 sm:p-5 bg-brand-blue/[0.03] border-x border-white/10 text-white font-semibold">
                                IS:14665 elevator standards, statutory fire logs
                            </td>
                            <td class="p-4 sm:p-5 text-slate-400">No Statutory Audit Trails</td>
                        </tr>
                    </tbody>
                </table>
            </div>
            <div class="px-4 py-2 bg-dark-950/80 border-t border-white/5 text-[10px] text-slate-500 font-mono text-center md:hidden">
                <i class="fa-solid fa-arrows-left-right mr-1"></i> Swipe table left and right to inspect comparison
            </div>
        </div>
    </section>

    <!-- Interactive AMC Cost & Proposal Estimator -->
    <section id="calculator" class="py-14 sm:py-20 lg:py-24 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto border-t border-white/5">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-10 sm:gap-12 items-center">
            
            <!-- Left: Instructions -->
            <div class="lg:col-span-5 space-y-4 sm:space-y-6">
                <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-brand-cyan/10 border border-brand-cyan/30 text-[10px] sm:text-xs font-mono text-brand-cyan">
                    <i class="fa-solid fa-calculator"></i>
                    <span>INSTANT ESTIMATOR</span>
                </div>

                <h2 class="font-display text-2xl sm:text-3xl lg:text-4xl font-extrabold text-white tracking-tight leading-tight">
                    Instant Facility <br class="hidden sm:inline">
                    <span class="accent-gradient-text">AMC Cost Estimator.</span>
                </h2>

                <p class="text-slate-400 text-xs sm:text-sm leading-relaxed">
                    Select your facility type, built-up area, and required engineering systems to calculate an instant ballpark monthly budget. Export directly to our senior engineer via WhatsApp for inspection scheduling.
                </p>

                <div class="space-y-3 sm:space-y-4 pt-2">
                    <div class="flex items-center gap-3 text-xs sm:text-sm text-slate-300">
                        <div class="w-6 h-6 rounded-full bg-emerald-500/20 text-emerald-400 flex items-center justify-center text-xs shrink-0">
                            <i class="fa-solid fa-check"></i>
                        </div>
                        <span>Zero hidden fees during routine preventive care</span>
                    </div>
                    <div class="flex items-center gap-3 text-xs sm:text-sm text-slate-300">
                        <div class="w-6 h-6 rounded-full bg-emerald-500/20 text-emerald-400 flex items-center justify-center text-xs shrink-0">
                            <i class="fa-solid fa-check"></i>
                        </div>
                        <span>Comprehensive and Non-Comprehensive contract options</span>
                    </div>
                    <div class="flex items-center gap-3 text-xs sm:text-sm text-slate-300">
                        <div class="w-6 h-6 rounded-full bg-emerald-500/20 text-emerald-400 flex items-center justify-center text-xs shrink-0">
                            <i class="fa-solid fa-check"></i>
                        </div>
                        <span>On-premise engineering survey within 24 hours</span>
                    </div>
                </div>
            </div>

            <!-- Right: Calculator Interface -->
            <div class="lg:col-span-7">
                <div class="glass-card rounded-3xl p-5 sm:p-8 border border-white/10 shadow-2xl relative">
                    <form id="amcCalculatorForm" class="space-y-5 sm:space-y-6">
                        
                        <!-- Facility Selector -->
                        <div>
                            <label class="block text-[11px] sm:text-xs font-mono uppercase text-slate-400 mb-2">1. Select Facility Type</label>
                            <div class="grid grid-cols-2 sm:grid-cols-4 gap-2 sm:gap-2.5">
                                <button type="button" class="facility-btn active p-2.5 sm:p-3 rounded-xl border border-brand-blue bg-brand-blue/20 text-[11px] sm:text-xs font-semibold text-white transition-all text-center" data-factor="1.0">
                                    <i class="fa-solid fa-briefcase block text-sm sm:text-base mb-1 text-brand-cyan"></i>
                                    Corporate Office
                                </button>
                                <button type="button" class="facility-btn p-2.5 sm:p-3 rounded-xl border border-white/10 bg-white/[0.02] text-[11px] sm:text-xs font-semibold text-slate-400 hover:text-white transition-all text-center" data-factor="1.25">
                                    <i class="fa-solid fa-hospital block text-sm sm:text-base mb-1 text-slate-400"></i>
                                    Hospital / Clinic
                                </button>
                                <button type="button" class="facility-btn p-2.5 sm:p-3 rounded-xl border border-white/10 bg-white/[0.02] text-[11px] sm:text-xs font-semibold text-slate-400 hover:text-white transition-all text-center" data-factor="1.35">
                                    <i class="fa-solid fa-industry block text-sm sm:text-base mb-1 text-slate-400"></i>
                                    Factory / Plant
                                </button>
                                <button type="button" class="facility-btn p-2.5 sm:p-3 rounded-xl border border-white/10 bg-white/[0.02] text-[11px] sm:text-xs font-semibold text-slate-400 hover:text-white transition-all text-center" data-factor="0.9">
                                    <i class="fa-solid fa-hotel block text-sm sm:text-base mb-1 text-slate-400"></i>
                                    Hotel / Complex
                                </button>
                            </div>
                        </div>

                        <!-- Area Slider -->
                        <div>
                            <div class="flex justify-between items-center text-xs font-mono mb-2">
                                <span class="text-slate-400 uppercase text-[11px]">2. Built-Up Footprint</span>
                                <span id="sqftDisplay" class="text-brand-cyan font-bold text-xs sm:text-sm">25,000 Sq. Ft.</span>
                            </div>
                            <input type="range" id="sqftSlider" min="5000" max="150000" step="5000" value="25000" 
                                   class="w-full h-2 bg-dark-950 rounded-lg appearance-none cursor-pointer accent-brand-blue">
                            <div class="flex justify-between text-[10px] text-slate-400 font-mono mt-1">
                                <span>5k Sq.Ft.</span>
                                <span>75k Sq.Ft.</span>
                                <span>150k+ Sq.Ft.</span>
                            </div>
                        </div>

                        <!-- Modules Checkboxes -->
                        <div>
                            <label class="block text-[11px] sm:text-xs font-mono uppercase text-slate-400 mb-2">3. Required Sub-Systems</label>
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-2 sm:gap-2.5 text-xs">
                                <label class="flex items-center gap-3 p-3 rounded-xl bg-dark-950/60 border border-white/5 cursor-pointer hover:border-brand-blue/30 transition-all">
                                    <input type="checkbox" class="sys-check rounded bg-dark-900 border-white/20 text-brand-blue focus:ring-0" value="12000" checked>
                                    <span class="text-slate-200 font-medium">Lift / Elevator Care (2+ Units)</span>
                                </label>

                                <label class="flex items-center gap-3 p-3 rounded-xl bg-dark-950/60 border border-white/5 cursor-pointer hover:border-brand-blue/30 transition-all">
                                    <input type="checkbox" class="sys-check rounded bg-dark-900 border-white/20 text-brand-blue focus:ring-0" value="15000" checked>
                                    <span class="text-slate-200 font-medium">VRF / Chiller Plant Tuning</span>
                                </label>

                                <label class="flex items-center gap-3 p-3 rounded-xl bg-dark-950/60 border border-white/5 cursor-pointer hover:border-brand-blue/30 transition-all">
                                    <input type="checkbox" class="sys-check rounded bg-dark-900 border-white/20 text-brand-blue focus:ring-0" value="8000" checked>
                                    <span class="text-slate-200 font-medium">CCTV &amp; Biometric Security</span>
                                </label>

                                <label class="flex items-center gap-3 p-3 rounded-xl bg-dark-950/60 border border-white/5 cursor-pointer hover:border-brand-blue/30 transition-all">
                                    <input type="checkbox" class="sys-check rounded bg-dark-900 border-white/20 text-brand-blue focus:ring-0" value="9500">
                                    <span class="text-slate-200 font-medium">Smart BMS Automation &amp; SCADA</span>
                                </label>
                            </div>
                        </div>

                        <!-- Live Price Summary Box -->
                        <div class="p-4 sm:p-5 rounded-2xl bg-gradient-to-r from-dark-950 to-dark-900 border border-brand-cyan/20 flex flex-col sm:flex-row items-stretch sm:items-center justify-between gap-4">
                            <div>
                                <span class="text-[10px] sm:text-[11px] font-mono uppercase text-slate-400">Estimated Operations Budget</span>
                                <div class="flex items-baseline gap-2 mt-0.5">
                                    <span class="text-xs text-slate-400">₹</span>
                                    <span id="calculatedEstimate" class="font-display text-2xl sm:text-3xl font-extrabold text-white">35,000</span>
                                    <span class="text-xs text-slate-400 font-mono">/ Month (Est.)</span>
                                </div>
                                <span class="text-[10px] text-emerald-400 block mt-0.5 font-mono">Includes preventative spares &amp; priority SLA</span>
                            </div>

                            <button type="button" id="sendQuoteWhatsApp" 
                                    class="w-full sm:w-auto px-5 py-3 rounded-xl bg-emerald-500 hover:bg-emerald-400 text-white font-bold text-xs tracking-wider uppercase flex items-center justify-center gap-2 shadow-lg shadow-emerald-500/20 transition-all">
                                <i class="fa-brands fa-whatsapp text-sm"></i>
                                <span>Send to Engineer</span>
                            </button>
                        </div>

                    </form>
                </div>
            </div>

        </div>
    </section>

    <!-- 8. Contact Section -->
    <section id="contact" class="py-14 sm:py-20 lg:py-24 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto border-t border-white/5">
        <div class="glass-panel rounded-3xl p-5 sm:p-8 lg:p-12 border border-white/10 shadow-2xl relative overflow-hidden">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 sm:gap-12">
                
                <!-- Left: Direct Info -->
                <div class="lg:col-span-5 space-y-5 sm:space-y-6">
                    <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-white/5 border border-white/10 text-[10px] sm:text-xs font-mono text-slate-300">
                        <i class="fa-solid fa-building text-brand-cyan"></i>
                        <span>HEADQUARTERS &amp; OPERATIONS</span>
                    </div>

                    <h2 class="font-display text-2xl sm:text-3xl lg:text-3xl font-extrabold text-white tracking-tight">
                        Connect Directly with our Engineering Office
                    </h2>

                    <p class="text-slate-400 text-xs sm:text-sm leading-relaxed">
                        Schedule a site inspection or invite our technical team for an on-premise infrastructure appraisal anywhere in Madhya Pradesh and Central India.
                    </p>

                    <div class="space-y-3.5 sm:space-y-4 pt-1 sm:pt-2">
                        <div class="flex items-start gap-3 sm:gap-4">
                            <div class="w-9 h-9 sm:w-10 sm:h-10 rounded-xl bg-brand-blue/15 text-brand-cyan flex items-center justify-center shrink-0 mt-0.5">
                                <i class="fa-solid fa-location-dot text-sm sm:text-base"></i>
                            </div>
                            <div>
                                <h3 class="text-[10px] sm:text-xs font-mono uppercase text-slate-400">Registered Office Address</h3>
                                <p class="text-xs sm:text-sm font-semibold text-white mt-0.5">
                                    1120, 2nd Floor, Part I, Scheme No 114, Indore, Madhya Pradesh 452010
                                </p>
                            </div>
                        </div>

                        <div class="flex items-start gap-3 sm:gap-4">
                            <div class="w-9 h-9 sm:w-10 sm:h-10 rounded-xl bg-brand-blue/15 text-brand-cyan flex items-center justify-center shrink-0 mt-0.5">
                                <i class="fa-solid fa-phone text-sm sm:text-base"></i>
                            </div>
                            <div>
                                <h3 class="text-[10px] sm:text-xs font-mono uppercase text-slate-400">Direct Engineering Line</h3>
                                <p class="text-xs sm:text-sm font-semibold text-white mt-0.5">
                                    <a href="tel:+919425991996" class="hover:text-brand-cyan transition-colors">+91 9425991996</a>
                                </p>
                            </div>
                        </div>

                        <div class="flex items-start gap-3 sm:gap-4">
                            <div class="w-9 h-9 sm:w-10 sm:h-10 rounded-xl bg-brand-blue/15 text-brand-cyan flex items-center justify-center shrink-0 mt-0.5">
                                <i class="fa-solid fa-envelope text-sm sm:text-base"></i>
                            </div>
                            <div>
                                <h3 class="text-[10px] sm:text-xs font-mono uppercase text-slate-400">Official Correspondence</h3>
                                <p class="text-xs sm:text-sm font-semibold text-white mt-0.5 break-all">
                                    <a href="mailto:quirktechnology@gmail.com" class="hover:text-brand-cyan transition-colors">quirktechnology@gmail.com</a>
                                </p>
                            </div>
                        </div>

                        <div class="flex items-start gap-3 sm:gap-4">
                            <div class="w-9 h-9 sm:w-10 sm:h-10 rounded-xl bg-brand-blue/15 text-brand-cyan flex items-center justify-center shrink-0 mt-0.5">
                                <i class="fa-solid fa-clock text-sm sm:text-base"></i>
                            </div>
                            <div>
                                <h3 class="text-[10px] sm:text-xs font-mono uppercase text-slate-400">Technical Working Hours</h3>
                                <p class="text-xs sm:text-sm font-semibold text-white mt-0.5">
                                    Mon - Sat: 9:00 AM - 6:00 PM <span class="text-[10px] sm:text-xs text-emerald-400 font-mono block sm:inline">(24/7 Breakdown Hotline)</span>
                                </p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Right: Fast Inquiry Form -->
                <div class="lg:col-span-7">
                    <div class="bg-dark-950/70 p-5 sm:p-8 rounded-2xl border border-white/10">
                        <h3 class="text-base sm:text-lg font-bold text-white mb-1.5 sm:mb-2">Request Technical Site Visit</h3>
                        <p class="text-xs text-slate-400 mb-5 sm:mb-6">Fill in your site specs and we will dispatch a senior engineering consultant.</p>
                        
                        <form id="contactForm" class="space-y-4">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5 sm:gap-4">
                                <div>
                                    <label class="block text-[11px] sm:text-xs font-mono text-slate-400 uppercase mb-1.5">Your Name *</label>
                                    <input type="text" id="contactName" required placeholder="e.g. Rajesh Sharma" 
                                           class="w-full px-3.5 sm:px-4 py-2.5 sm:py-3 rounded-xl bg-dark-900 border border-white/10 text-white text-xs sm:text-sm focus:border-brand-blue focus:outline-none transition-colors">
                                </div>
                                <div>
                                    <label class="block text-[11px] sm:text-xs font-mono text-slate-400 uppercase mb-1.5">Phone Number *</label>
                                    <input type="tel" id="contactPhone" required placeholder="e.g. +91 98765 43210" 
                                           class="w-full px-3.5 sm:px-4 py-2.5 sm:py-3 rounded-xl bg-dark-900 border border-white/10 text-white text-xs sm:text-sm focus:border-brand-blue focus:outline-none transition-colors">
                                </div>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5 sm:gap-4">
                                <div>
                                    <label class="block text-[11px] sm:text-xs font-mono text-slate-400 uppercase mb-1.5">Facility / City *</label>
                                    <input type="text" id="contactFacility" required placeholder="e.g. Office Complex in Indore" 
                                           class="w-full px-3.5 sm:px-4 py-2.5 sm:py-3 rounded-xl bg-dark-900 border border-white/10 text-white text-xs sm:text-sm focus:border-brand-blue focus:outline-none transition-colors">
                                </div>
                                <div>
                                    <label class="block text-[11px] sm:text-xs font-mono text-slate-400 uppercase mb-1.5">Primary Requirement *</label>
                                    <select id="contactService" class="w-full px-3.5 sm:px-4 py-2.5 sm:py-3 rounded-xl bg-dark-900 border border-white/10 text-white text-xs sm:text-sm focus:border-brand-blue focus:outline-none transition-colors">
                                        <option value="Elevator & Lift AMC">Elevator &amp; Lift AMC</option>
                                        <option value="AC / VRF & Chiller Systems">AC / VRF &amp; Chiller Systems</option>
                                        <option value="Smart BMS & Automation">Smart BMS &amp; Automation</option>
                                        <option value="Electronic Security & CCTV">Electronic Security &amp; CCTV</option>
                                        <option value="IT Infrastructure & Fiber Optics">IT Infrastructure &amp; Fiber Optics</option>
                                        <option value="Building Construction & Renovation">Building Construction &amp; Renovation</option>
                                        <option value="Turnkey MEP Comprehensive AMC">Turnkey MEP Comprehensive AMC</option>
                                    </select>
                                </div>
                            </div>

                            <div>
                                <label class="block text-[11px] sm:text-xs font-mono text-slate-400 uppercase mb-1.5">System Specs / Comments</label>
                                <textarea id="contactNotes" rows="3" placeholder="Describe number of elevator units, chiller tonnage, or current issues..." 
                                          class="w-full px-3.5 sm:px-4 py-2.5 sm:py-3 rounded-xl bg-dark-900 border border-white/10 text-white text-xs sm:text-sm focus:border-brand-blue focus:outline-none transition-colors"></textarea>
                            </div>

                            <button type="submit" class="w-full py-3.5 sm:py-4 rounded-xl bg-gradient-to-r from-brand-blue to-brand-cyan text-white font-bold text-xs uppercase tracking-wider shadow-lg shadow-brand-blue/30 hover:shadow-brand-blue/50 transition-all flex items-center justify-center gap-2">
                                <i class="fa-solid fa-paper-plane"></i>
                                <span>Schedule Site Assessment</span>
                            </button>
                        </form>
                    </div>
                </div>

            </div>
        </div>
    </section>

</main>

<!-- 9. Footer -->
<footer class="border-t border-white/10 bg-dark-950 pt-12 sm:pt-16 pb-10 sm:pb-12 px-4 sm:px-6 lg:px-8 text-slate-400 text-xs">
    <div class="max-w-7xl mx-auto grid grid-cols-1 sm:grid-cols-2 md:grid-cols-12 gap-8 sm:gap-10 pb-10 sm:pb-12 border-b border-white/10">
        
        <!-- Col 1: Brand Info with Provided Logo -->
        <div class="sm:col-span-2 md:col-span-4 space-y-4">
            <div class="flex items-center gap-3">
                <div class="w-9 h-9 sm:w-10 sm:h-10 rounded-xl bg-black border border-white/10 p-0.5 overflow-hidden flex items-center justify-center shrink-0">
                    <img src="QUIRK TECHNOLOGY logo.jpg" 
                         alt="QUIRK TECHNOLOGY Logo" 
                         class="w-full h-full object-contain"
                         onerror="this.onerror=null; this.parentElement.innerHTML='<i class=\'fa-solid fa-bolt-lightning text-brand-cyan text-base\'></i>';">
                </div>
                <span class="font-display font-extrabold text-base sm:text-lg text-white">
                    QUIRK TECHNOLOGY
                </span>
            </div>
            <p class="text-slate-400 text-xs leading-relaxed max-w-sm">
                Established in 2012. Premier engineering services company specializing in elevator lifecycle care, central HVAC chiller plants, smart BMS architectures, and turnkey infrastructure management.
            </p>
            <div class="flex items-center gap-3 pt-1">
                <a href="https://wa.me/919425991996" target="_blank" class="w-8 h-8 rounded-lg bg-white/5 hover:bg-emerald-500/20 hover:text-emerald-400 border border-white/10 flex items-center justify-center text-sm transition-colors" title="WhatsApp">
                    <i class="fa-brands fa-whatsapp"></i>
                </a>
                <a href="tel:+919425991996" class="w-8 h-8 rounded-lg bg-white/5 hover:bg-brand-blue/20 hover:text-brand-cyan border border-white/10 flex items-center justify-center text-sm transition-colors" title="Call Us">
                    <i class="fa-solid fa-phone"></i>
                </a>
                <a href="mailto:quirktechnology@gmail.com" class="w-8 h-8 rounded-lg bg-white/5 hover:bg-brand-blue/20 hover:text-brand-cyan border border-white/10 flex items-center justify-center text-sm transition-colors" title="Email">
                    <i class="fa-solid fa-envelope"></i>
                </a>
            </div>
        </div>

        <!-- Col 2: Engineering & IT Verticals -->
        <div class="md:col-span-3 space-y-3 font-mono">
            <p class="text-xs uppercase text-white font-bold tracking-wider">Service Verticals</p>
            <ul class="space-y-2 text-slate-400">
                <li><a href="#engineering" class="hover:text-brand-cyan transition-colors">Lift &amp; Elevator Care</a></li>
                <li><a href="#engineering" class="hover:text-brand-cyan transition-colors">AC VRF &amp; Chiller Systems</a></li>
                <li><a href="#engineering" class="hover:text-brand-cyan transition-colors">BMS Automation &amp; SCADA</a></li>
                <li><a href="#it-services" class="hover:text-brand-cyan transition-colors">CCTV &amp; AI Security</a></li>
                <li><a href="#it-services" class="hover:text-brand-cyan transition-colors">Fiber Optics &amp; Networking</a></li>
                <li><a href="#construction" class="hover:text-brand-cyan transition-colors">Construction &amp; Renovation</a></li>
            </ul>
        </div>

        <!-- Col 3: Quick Links -->
        <div class="md:col-span-2 space-y-3 font-mono">
            <p class="text-xs uppercase text-white font-bold tracking-wider">Navigation</p>
            <ul class="space-y-2 text-slate-400">
                <li><a href="#home" class="hover:text-brand-cyan transition-colors">Home Base</a></li>
                <li><a href="#about" class="hover:text-brand-cyan transition-colors">Company Legacy</a></li>
                <li><a href="#it-services" class="hover:text-brand-cyan transition-colors">IT &amp; AI</a></li>
                <li><a href="#engineering" class="hover:text-brand-cyan transition-colors">Engineering</a></li>
                <li><a href="#construction" class="hover:text-brand-cyan transition-colors">Construction</a></li>
                <li><a href="#calculator" class="hover:text-brand-cyan transition-colors">AMC Estimator</a></li>
                <li><a href="#contact" class="hover:text-brand-cyan transition-colors">Contact HQ</a></li>
            </ul>
        </div>

        <!-- Col 4: Regional Presence -->
        <div class="sm:col-span-2 md:col-span-3 space-y-3">
            <p class="text-xs font-mono uppercase text-white font-bold tracking-wider">Regional Operations</p>
            <div class="p-4 rounded-xl bg-white/[0.02] border border-white/5 space-y-2 text-xs">
                <p class="text-white font-semibold flex items-center gap-1.5">
                    <i class="fa-solid fa-building text-brand-cyan"></i>
                    Indore Operations Hub
                </p>
                <p class="text-slate-400 leading-relaxed">
                    1120, 2nd Floor, Part I, Scheme No 114, Indore, MP 452010
                </p>
                <p class="text-emerald-400 font-mono text-[11px] pt-1">
                    Active Coverage: Indore, Bhopal, Ujjain, Dewas &amp; Pithampur Industrial Belt.
                </p>
            </div>
        </div>

    </div>

    <!-- Copyright -->
    <div class="max-w-7xl mx-auto pt-6 flex flex-col sm:flex-row items-center justify-between gap-3 sm:gap-4 text-slate-400 text-[10px] sm:text-[11px] font-mono text-center sm:text-left">
        <p>&copy; 2012-2026 QUIRK TECHNOLOGY SOLUTIONS. All Rights Reserved.</p>
        <div class="flex items-center gap-4 sm:gap-6">
            <span>Central India Precision Engineering</span>
            <span>ISO &amp; Safety Standard Compliant</span>
        </div>
    </div>
</footer>

<!-- Notification Toast -->
<div id="toastNotification" class="fixed bottom-4 right-4 sm:bottom-6 sm:right-6 z-50 glass-panel px-4 sm:px-5 py-3 rounded-xl border border-white/15 text-white text-xs font-mono shadow-2xl flex items-center gap-3 translate-y-24 opacity-0 transition-all duration-300 max-w-[90vw]">
    <i id="toastIcon" class="fa-solid fa-circle-check text-emerald-400 text-base shrink-0"></i>
    <span id="toastMessage" class="truncate">Action completed successfully.</span>
</div>

<!-- Interactive Scripts -->
<script>
    document.addEventListener('DOMContentLoaded', () => {

        // --- 1. Mobile Menu Drawer Toggle & Icon Animation ---
        const mobileToggle = document.getElementById('mobileMenuToggle');
        const mobileDrawer = document.getElementById('mobileDrawer');
        const mobileMenuIcon = document.getElementById('mobileMenuIcon');
        const mobileLinks = document.querySelectorAll('.mobile-nav-link');

        if (mobileToggle && mobileDrawer) {
            mobileToggle.addEventListener('click', () => {
                const isHidden = mobileDrawer.classList.toggle('hidden');
                if (mobileMenuIcon) {
                    if (isHidden) {
                        mobileMenuIcon.classList.remove('fa-xmark');
                        mobileMenuIcon.classList.add('fa-bars-staggered');
                    } else {
                        mobileMenuIcon.classList.remove('fa-bars-staggered');
                        mobileMenuIcon.classList.add('fa-xmark');
                    }
                }
            });

            mobileLinks.forEach(link => {
                link.addEventListener('click', () => {
                    mobileDrawer.classList.add('hidden');
                    if (mobileMenuIcon) {
                        mobileMenuIcon.classList.remove('fa-xmark');
                        mobileMenuIcon.classList.add('fa-bars-staggered');
                    }
                });
            });
        }

        // --- 2. Technical Spec Blueprint Tab Switcher ---
        const tabButtons = document.querySelectorAll('.spec-tab-btn');
        const tabPanes = document.querySelectorAll('.spec-pane');

        tabButtons.forEach(btn => {
            btn.addEventListener('click', () => {
                tabButtons.forEach(b => {
                    b.classList.remove('bg-brand-blue', 'text-white', 'shadow-lg', 'shadow-brand-blue/30');
                    b.classList.add('bg-white/5', 'text-slate-300');
                });

                btn.classList.add('bg-brand-blue', 'text-white', 'shadow-lg', 'shadow-brand-blue/30');
                btn.classList.remove('bg-white/5', 'text-slate-300');

                const targetId = btn.getAttribute('data-target');
                tabPanes.forEach(pane => {
                    if (pane.id === targetId) {
                        pane.classList.remove('hidden');
                        pane.classList.add('grid');
                    } else {
                        pane.classList.add('hidden');
                        pane.classList.remove('grid');
                    }
                });
            });
        });

        // --- 3. Interactive AMC Cost Estimator Logic ---
        const facilityButtons = document.querySelectorAll('.facility-btn');
        const sqftSlider = document.getElementById('sqftSlider');
        const sqftDisplay = document.getElementById('sqftDisplay');
        const systemCheckboxes = document.querySelectorAll('.sys-check');
        const calculatedEstimate = document.getElementById('calculatedEstimate');
        const sendQuoteWhatsApp = document.getElementById('sendQuoteWhatsApp');

        let currentFacilityFactor = 1.0;
        let currentFacilityName = "Corporate Office";

        facilityButtons.forEach(btn => {
            btn.addEventListener('click', () => {
                facilityButtons.forEach(b => {
                    b.classList.remove('border-brand-blue', 'bg-brand-blue/20', 'text-white');
                    b.classList.add('border-white/10', 'bg-white/[0.02]', 'text-slate-400');
                    const icon = b.querySelector('i');
                    if (icon) icon.className = icon.className.replace('text-brand-cyan', 'text-slate-400');
                });

                btn.classList.add('border-brand-blue', 'bg-brand-blue/20', 'text-white');
                btn.classList.remove('border-white/10', 'bg-white/[0.02]', 'text-slate-400');
                const activeIcon = btn.querySelector('i');
                if (activeIcon) activeIcon.className = activeIcon.className.replace('text-slate-400', 'text-brand-cyan');

                currentFacilityFactor = parseFloat(btn.getAttribute('data-factor') || '1.0');
                currentFacilityName = btn.innerText.trim();
                recalculateAMC();
            });
        });

        function recalculateAMC() {
            if (!sqftSlider || !sqftDisplay || !calculatedEstimate) return;
            const sqft = parseInt(sqftSlider.value, 10);
            sqftDisplay.textContent = Number(sqft).toLocaleString('en-IN') + ' Sq. Ft.';

            let baseCost = 0;
            systemCheckboxes.forEach(cb => {
                if (cb.checked) {
                    baseCost += parseFloat(cb.value);
                }
            });

            const areaMultiplier = 1 + (sqft / 100000) * 0.75;
            const totalEstimatedMonthly = Math.round((baseCost * currentFacilityFactor * areaMultiplier) / 500) * 500;

            calculatedEstimate.textContent = Number(totalEstimatedMonthly).toLocaleString('en-IN');
        }

        if (sqftSlider) {
            sqftSlider.addEventListener('input', recalculateAMC);
        }
        systemCheckboxes.forEach(cb => cb.addEventListener('change', recalculateAMC));
        recalculateAMC();

        if (sendQuoteWhatsApp) {
            sendQuoteWhatsApp.addEventListener('click', () => {
                const sqft = sqftSlider.value;
                const estimatedPrice = calculatedEstimate.textContent;

                let selectedModules = [];
                systemCheckboxes.forEach(cb => {
                    if (cb.checked) {
                        selectedModules.push(cb.closest('label').querySelector('span').innerText);
                    }
                });

                const text = `Hello Quirk Technology Solutions!%0A%0AI used your online AMC Estimator:%0A- Facility Type: ${encodeURIComponent(currentFacilityName)}%0A- Area: ${Number(sqft).toLocaleString('en-IN')} Sq.Ft.%0A- Sub-systems: ${encodeURIComponent(selectedModules.join(', '))}%0A- Estimated Budget: ₹${estimatedPrice}/month%0A%0APlease schedule an engineering inspection for our site.`;
                window.open(`https://wa.me/919425991996?text=${text}`, '_blank');
            });
        }

        // --- 4. Contact Form Submission Handling ---
        const contactForm = document.getElementById('contactForm');
        if (contactForm) {
            contactForm.addEventListener('submit', (e) => {
                e.preventDefault();
                
                const name = document.getElementById('contactName').value;
                const phone = document.getElementById('contactPhone').value;
                const facility = document.getElementById('contactFacility').value;
                const service = document.getElementById('contactService').value;
                const notes = document.getElementById('contactNotes').value;

                const msg = `*New Engineering Site Request - Quirk Technology*%0A%0A*Name:* ${encodeURIComponent(name)}%0A*Phone:* ${encodeURIComponent(phone)}%0A*Facility/Location:* ${encodeURIComponent(facility)}%0A*Requirement:* ${encodeURIComponent(service)}%0A*Notes:* ${encodeURIComponent(notes || 'N/A')}`;

                showToast('Opening WhatsApp with your site details...', 'success');

                setTimeout(() => {
                    window.open(`https://wa.me/919425991996?text=${msg}`, '_blank');
                }, 500);
            });
        }

        // --- 5. Toast Feedback Function ---
        function showToast(message, type = 'success') {
            const toast = document.getElementById('toastNotification');
            const toastMsg = document.getElementById('toastMessage');
            const toastIcon = document.getElementById('toastIcon');

            if (!toast) return;

            toastMsg.textContent = message;
            if (type === 'success') {
                toastIcon.className = 'fa-solid fa-circle-check text-emerald-400 text-base shrink-0';
            } else {
                toastIcon.className = 'fa-solid fa-triangle-exclamation text-amber-400 text-base shrink-0';
            }

            toast.classList.remove('translate-y-24', 'opacity-0');
            toast.classList.add('translate-y-0', 'opacity-100');

            setTimeout(() => {
                toast.classList.remove('translate-y-0', 'opacity-100');
                toast.classList.add('translate-y-24', 'opacity-0');
            }, 4000);
        }

    });
</script>
</body>
</html>
