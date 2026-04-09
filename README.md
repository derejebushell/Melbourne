<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0">
    <title>High Growth Report | Melbourne Under $700k</title>
    
    <!-- Modern Sans-Serif Font -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Lucide Icons -->
    <script src="https://unpkg.com/lucide@latest"></script>

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: { sans: ['Inter', 'sans-serif'] },
                    colors: {
                        purple: {
                            50: '#faf5ff',
                            600: '#9333ea', 
                            700: '#7e22ce',
                        }
                    }
                }
            }
        }
    </script>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        
        html, body {
            margin: 0 !important;
            padding: 0 !important;
            width: 100% !important;
            overflow-x: hidden;
            position: relative;
            top: 0;
            background-color: white;
        }

        input:focus {
            outline: none;
            box-shadow: 0 0 0 3px rgba(147, 51, 234, 0.2);
            border-color: #9333ea;
        }
        .bg-grid {
            mask-image: linear-gradient(to bottom, black, transparent);
        }
        .data-card {
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }
        .data-card:hover {
            transform: translateY(-2px);
            box-shadow: 0 20px 40px -10px rgba(0,0,0,0.05);
            border-color: #9333ea;
        }
    </style>
</head>
<body class="font-sans text-gray-800 bg-white antialiased">
    <div id="top"></div>

    <!-- HERO SECTION -->
    <header class="relative min-h-[50vh] flex items-center pt-24 pb-20 overflow-hidden border-b border-gray-100 bg-white">
        <div class="absolute inset-0 z-0 opacity-[0.05] pointer-events-none bg-grid" style="background-image: url('data:image/svg+xml,%3Csvg width=\'60\' height=\'60\' viewBox=\'0 0 60 60\' xmlns=\'http://www.w3.org/2000/svg\'%3E%3Cg fill=\'none\' fill-rule=\'evenodd\'%3E%3Cg fill=\'%23000000\' fill-opacity=\'1\'%3E%3Cpath d=\'M36 34v-4h-2v4h-4v2h4v4h2v-4h4v-2h-4zm0-30V0h-2v4h-4v2h4v4h2V6h4V4h-4zM6 34v-4H4v4H0v2h4v4h2v-4h4v-2H6zM6 4V0H4v4H0v2h4v4h2V6h4V4H6z\'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E');"></div>
        
        <div class="w-full px-4 md:px-8 relative z-10">
            <div class="max-w-6xl mx-auto text-center">
                <div class="inline-block px-5 py-2 mb-6 text-sm font-black tracking-[0.4em] text-purple-600 uppercase bg-purple-50 rounded-full">
                    2026
                </div>
                <h1 class="text-4xl md:text-6xl lg:text-7xl font-extrabold text-gray-900 leading-[1.1] mb-8 tracking-tight">
                    10 Melbourne Suburbs Under $700k <br class="hidden lg:block">
                    <span class="text-purple-600">Outperforming The Market</span>
                </h1>
                <p class="text-lg md:text-2xl text-gray-600 mb-0 max-w-3xl mx-auto leading-relaxed font-light">
                    Stop overpaying in blue-chip areas. We've identified the high-yield corridors recording <span class="font-semibold text-gray-900">10%+ growth</span> in the last 12 months.
                </p>
            </div>
        </div>
    </header>

    <!-- MARKET DATA COMPONENT -->
    <section class="py-24 bg-white overflow-hidden">
        <div class="w-full px-4 max-w-5xl mx-auto">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-5xl font-bold text-gray-900 mb-6 tracking-tight">Market Intelligence Preview</h2>
                <p class="text-gray-500 text-lg md:text-xl">Each suburb has been vetted for infrastructure, yield, and historical capital growth.</p>
            </div>
            
            <div class="space-y-4">
                <div class="data-card bg-white border border-gray-100 p-6 md:p-8 rounded-2xl flex flex-col md:flex-row md:items-center justify-between gap-6 shadow-sm">
                    <div class="flex items-center gap-6">
                        <div class="w-14 h-14 bg-purple-50 rounded-xl flex items-center justify-center text-purple-600 flex-shrink-0">
                            <i data-lucide="map-pin" class="w-6 h-6"></i>
                        </div>
                        <div>
                            <h3 class="text-2xl font-bold text-gray-900 leading-none mb-1">Frankston North</h3>
                            <span class="text-xs font-bold text-gray-400 uppercase tracking-widest">Growth Corridor • SE Melbourne</span>
                        </div>
                    </div>
                    <div class="flex items-center gap-8 md:gap-16">
                        <div>
                            <p class="text-xs font-bold text-gray-400 uppercase tracking-widest mb-1">Median Price</p>
                            <p class="text-2xl font-extrabold text-gray-900 tabular-nums">$595,000</p>
                        </div>
                        <div class="text-right">
                            <p class="text-xs font-bold text-gray-400 uppercase tracking-widest mb-1">12M Growth</p>
                            <p class="text-2xl font-extrabold text-green-600 tabular-nums">+11.2%</p>
                        </div>
                    </div>
                </div>

                <div class="data-card bg-white border border-gray-100 p-6 md:p-8 rounded-2xl flex flex-col md:flex-row md:items-center justify-between gap-6 shadow-sm">
                    <div class="flex items-center gap-6">
                        <div class="w-14 h-14 bg-purple-50 rounded-xl flex items-center justify-center text-purple-600 flex-shrink-0">
                            <i data-lucide="map-pin" class="w-6 h-6"></i>
                        </div>
                        <div>
                            <h3 class="text-2xl font-bold text-gray-900 leading-none mb-1">Melton South</h3>
                            <span class="text-xs font-bold text-gray-400 uppercase tracking-widest">Growth Corridor • W Melbourne</span>
                        </div>
                    </div>
                    <div class="flex items-center gap-8 md:gap-16">
                        <div>
                            <p class="text-xs font-bold text-gray-400 uppercase tracking-widest mb-1">Median Price</p>
                            <p class="text-2xl font-extrabold text-gray-900 tabular-nums">$510,000</p>
                        </div>
                        <div class="text-right">
                            <p class="text-xs font-bold text-gray-400 uppercase tracking-widest mb-1">12M Growth</p>
                            <p class="text-2xl font-extrabold text-green-600 tabular-nums">+10.5%</p>
                        </div>
                    </div>
                </div>

                <div class="bg-gray-50/50 border border-dashed border-gray-200 p-6 md:p-8 rounded-2xl flex flex-col md:flex-row md:items-center justify-between gap-6 opacity-60">
                    <div class="flex items-center gap-6 blur-[4px]">
                        <div class="w-14 h-14 bg-gray-100 rounded-xl flex items-center justify-center text-gray-400 flex-shrink-0">
                            <i data-lucide="lock" class="w-6 h-6"></i>
                        </div>
                        <div>
                            <h3 class="text-2xl font-bold text-gray-900 leading-none">Confidential Location</h3>
                        </div>
                    </div>
                    <div class="hidden md:block blur-[4px]">
                        <p class="text-2xl font-extrabold text-gray-300 tabular-nums">$6XX,000</p>
                    </div>
                </div>

                <div class="pt-12 text-center">
                    <button onclick="document.getElementById('lead-capture').scrollIntoView({behavior:'smooth'})" class="w-full sm:w-auto inline-flex items-center justify-center bg-purple-600 hover:bg-purple-700 text-white font-bold py-5 px-12 rounded-2xl text-xl transition-all duration-300 shadow-[0_20px_50px_rgba(147,51,234,0.3)] hover:-translate-y-1">
                        Get The Full Breakdown
                        <i data-lucide="arrow-right" class="ml-2 w-6 h-6"></i>
                    </button>
                    <p class="mt-6 text-gray-400 font-medium text-sm flex items-center justify-center gap-2">
                        <i data-lucide="unlock" class="w-4 h-4"></i>
                        Unlock remaining 8 high-growth locations
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- LEAD CAPTURE SECTION -->
    <section id="lead-capture" class="py-24 bg-white relative">
        <div class="w-full px-4">
            <div class="max-w-2xl mx-auto bg-white rounded-[2.5rem] shadow-[0_40px_80px_-15px_rgba(0,0,0,0.12)] border border-gray-100 p-8 md:p-16 relative z-20 overflow-hidden">
                
                <!-- Success State Overlay -->
                <div id="success-overlay" class="absolute inset-0 bg-white z-30 flex flex-col items-center justify-center p-8 text-center hidden">
                    <div class="w-24 h-24 bg-green-100 text-green-600 rounded-full flex items-center justify-center mb-8">
                        <i data-lucide="check-circle" class="w-12 h-12"></i>
                    </div>
                    <h2 class="text-3xl font-bold text-gray-900 mb-4">You're All Set!</h2>
                    <p class="text-gray-500 text-lg mb-10">Access your high-growth report via the Google Drive link below.</p>
                    
                    <div class="flex flex-col gap-4 w-full">
                        <!-- UPDATED GOOGLE DRIVE LINK -->
                        <a href="https://drive.google.com/file/d/1tRJBrxo-MvqKAvFHN5LiHp-mJaUBgPj2/view?usp=sharing" target="_blank" class="w-full bg-purple-600 text-white font-bold py-5 rounded-2xl text-lg flex items-center justify-center gap-2 hover:bg-purple-700 transition-all">
                            <i data-lucide="external-link" class="w-5 h-5"></i>
                            Open Report in Drive
                        </a>
                        <a href="https://api.leadconnectorhq.com/widget/booking/WFDrmJtulBGxRVD7ZIDr" class="w-full bg-gray-50 text-purple-600 font-bold py-5 rounded-2xl text-lg flex items-center justify-center gap-2 hover:bg-gray-100 transition-all">
                            <i data-lucide="calendar" class="w-5 h-5"></i>
                            Book Strategy Session
                        </a>
                    </div>
                </div>

                <!-- Form Content -->
                <div id="form-content">
                    <div class="text-center mb-12">
                        <div class="w-20 h-20 bg-purple-100 text-purple-600 rounded-3xl rotate-3 flex items-center justify-center mx-auto mb-8 transition-transform hover:rotate-0">
                            <i data-lucide="mail-check" class="w-10 h-10"></i>
                        </div>
                        <h2 class="text-3xl md:text-5xl font-bold text-gray-900 mb-4 tracking-tight text-center">Access The Report</h2>
                        <p class="text-gray-500 text-lg md:text-xl text-center">Submit your details to receive the Google Drive access link instantly.</p>
                    </div>
                    
                    <form 
                        id="report-form"
                        action="https://formspree.io/f/mgopbadl" 
                        method="POST" 
                        class="space-y-6"
                    >
                        <input type="hidden" name="_subject" value="New Lead: Melbourne Growth Report">
                        
                        <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                            <div class="space-y-2">
                                <label class="block text-sm font-bold text-gray-700 ml-1">First Name</label>
                                <input type="text" name="first_name" placeholder="John" required class="w-full px-6 py-5 border border-gray-200 rounded-2xl bg-gray-50 transition-all focus:bg-white text-lg focus:ring-4 focus:ring-purple-100">
                            </div>
                            <div class="space-y-2">
                                <label class="block text-sm font-bold text-gray-700 ml-1">Last Name</label>
                                <input type="text" name="last_name" placeholder="Doe" required class="w-full px-6 py-5 border border-gray-200 rounded-2xl bg-gray-50 transition-all focus:bg-white text-lg focus:ring-4 focus:ring-purple-100">
                            </div>
                        </div>
                        <div class="space-y-2">
                            <label class="block text-sm font-bold text-gray-700 ml-1">Email Address</label>
                            <input type="email" name="email" placeholder="john@example.com" required class="w-full px-6 py-5 border border-gray-200 rounded-2xl bg-gray-50 transition-all focus:bg-white text-lg focus:ring-4 focus:ring-purple-100">
                        </div>
                        <div class="space-y-2">
                            <label class="block text-sm font-bold text-gray-700 ml-1">Mobile Number</label>
                            <input type="tel" name="phone" placeholder="0400 000 000" required class="w-full px-6 py-5 border border-gray-200 rounded-2xl bg-gray-50 transition-all focus:bg-white text-lg focus:ring-4 focus:ring-purple-100">
                        </div>

                        <button type="submit" class="w-full bg-purple-600 hover:bg-purple-700 text-white font-bold py-6 px-6 rounded-2xl text-xl transition-all shadow-2xl shadow-purple-200 flex justify-center items-center group mt-4">
                            <span id="btn-text">Get Instant Access</span>
                            <i data-lucide="chevron-right" class="ml-2 w-7 h-7 group-hover:translate-x-1 transition-transform"></i>
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer class="bg-gray-950 text-white pt-32 pb-16">
        <div class="w-full px-4 max-w-4xl mx-auto text-center">
            <h2 class="text-4xl md:text-6xl font-bold mb-10 tracking-tight text-center">Ready to build your <br> <span class="text-purple-500">Melbourne Portfolio?</span></h2>
            <p class="text-xl text-gray-400 mb-14 leading-relaxed font-light text-center">Stop guessing. Use institutional-grade data to acquire high-yield assets before the next rate cycle.</p>
            <a href="https://api.leadconnectorhq.com/widget/booking/WFDrmJtulBGxRVD7ZIDr" class="inline-block bg-white text-gray-900 font-extrabold py-6 px-16 rounded-2xl text-xl hover:bg-purple-50 transition-all shadow-2xl hover:scale-105 mb-16">
                Book Free Strategy Session
            </a>
            
            <!-- Instagram Link Section -->
            <div class="pt-8 border-t border-gray-800 flex flex-col items-center gap-6">
                <p class="text-gray-500 font-bold uppercase tracking-widest text-xs">Follow for market updates</p>
                <a href="https://www.instagram.com/djpropertypro?igsh=MWZxOWE1ZW4zaWhnZg%3D%3D&utm_source=qr" target="_blank" class="flex flex-col md:flex-row items-center gap-4 text-white hover:text-purple-400 transition-colors group">
                    <div class="relative">
                        <img src="https://lh3.googleusercontent.com/d/1cPMr-eyUQ6LkcuvrypkDWaYUrABVPrwF=s400" alt="DJ Property Pro" class="w-14 h-14 md:w-16 md:h-16 rounded-full border-2 border-gray-800 group-hover:border-purple-400 transition-colors object-cover shadow-lg">
                        <div class="absolute -bottom-1 -right-1 bg-purple-600 rounded-full p-1 border-2 border-gray-950">
                            <i data-lucide="instagram" class="w-3 h-3 md:w-4 md:h-4"></i>
                        </div>
                    </div>
                    <span class="text-lg md:text-xl font-bold tracking-tight">@djpropertypro</span>
                </a>
            </div>
        </div>
    </footer>

    <script>
        lucide.createIcons();

        const form = document.getElementById('report-form');
        const successOverlay = document.getElementById('success-overlay');
        const btnText = document.getElementById('btn-text');

        form.addEventListener('submit', async (e) => {
            e.preventDefault();
            btnText.innerText = 'Verifying...';
            
            const formData = new FormData(form);
            
            try {
                const response = await fetch(form.action, {
                    method: 'POST',
                    body: formData,
                    headers: { 'Accept': 'application/json' }
                });

                if (response.ok) {
                    successOverlay.classList.remove('hidden');
                    successOverlay.scrollIntoView({behavior: 'smooth', block: 'center'});
                } else {
                    alert('Submission error. Please check your details.');
                    btnText.innerText = 'Get Instant Access';
                }
            } catch (error) {
                alert('Connection error.');
                btnText.innerText = 'Get Instant Access';
            }
        });
    </script>
</body>
</html>
