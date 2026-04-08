<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0">
    <title>10 Melbourne Suburbs Under $700k | High Growth Report</title>
    
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
        /* Force remove all default margins that cause 'borders' */
        html, body {
            margin: 0 !important;
            padding: 0 !important;
            width: 100% !important;
            overflow-x: hidden;
        }
        .blur-overlay {
            background: linear-gradient(to bottom, rgba(255,255,255,0) 0%, rgba(255,255,255,0.9) 60%, rgba(255,255,255,1) 100%);
        }
        input:focus {
            outline: none;
            box-shadow: 0 0 0 3px rgba(147, 51, 234, 0.2);
            border-color: #9333ea;
        }
        /* Smooth fade for the background pattern */
        .bg-grid {
            mask-image: linear-gradient(to bottom, black, transparent);
        }
    </style>
</head>
<body class="font-sans text-gray-800 bg-white antialiased">

    <!-- HERO SECTION -->
    <header class="relative min-h-[70vh] flex items-center pt-16 pb-20 overflow-hidden border-b border-gray-100 bg-white">
        <!-- Background Pattern - Fixed to be full width -->
        <div class="absolute inset-0 z-0 opacity-[0.05] pointer-events-none bg-grid" style="background-image: url('data:image/svg+xml,%3Csvg width=\'60\' height=\'60\' viewBox=\'0 0 60 60\' xmlns=\'http://www.w3.org/2000/svg\'%3E%3Cg fill=\'none\' fill-rule=\'evenodd\'%3E%3Cg fill=\'%23000000\' fill-opacity=\'1\'%3E%3Cpath d=\'M36 34v-4h-2v4h-4v2h4v4h2v-4h4v-2h-4zm0-30V0h-2v4h-4v2h4v4h2V6h4V4h-4zM6 34v-4H4v4H0v2h4v4h2v-4h4v-2H6zM6 4V0H4v4H0v2h4v4h2V6h4V4H6z\'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E');"></div>
        
        <div class="w-full px-4 md:px-8 relative z-10">
            <div class="max-w-6xl mx-auto text-center">
                <div class="inline-block px-4 py-1.5 mb-6 text-xs font-bold tracking-widest text-purple-600 uppercase bg-purple-50 rounded-full">
                    2024 Market Intelligence Report
                </div>
                <h1 class="text-4xl md:text-6xl lg:text-7xl font-extrabold text-gray-900 leading-[1.1] mb-8 tracking-tight">
                    10 Melbourne Suburbs Under $700k <br class="hidden lg:block">
                    <span class="text-purple-600">Outperforming The Market</span>
                </h1>
                <p class="text-lg md:text-2xl text-gray-600 mb-12 max-w-3xl mx-auto leading-relaxed font-light">
                    Stop overpaying in blue-chip areas. We've identified the high-yield corridors recording <span class="font-semibold text-gray-900">10%+ growth</span> in the last 12 months.
                </p>
                <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
                    <button onclick="document.getElementById('lead-capture').scrollIntoView({behavior:'smooth'})" class="w-full sm:w-auto inline-flex items-center justify-center bg-purple-600 hover:bg-purple-700 text-white font-bold py-5 px-12 rounded-2xl text-xl transition-all duration-300 shadow-[0_20px_50px_rgba(147,51,234,0.3)] hover:-translate-y-1">
                        Get The Full Breakdown
                        <i data-lucide="arrow-right" class="ml-2 w-6 h-6"></i>
                    </button>
                </div>
            </div>
        </div>
    </header>

    <!-- PROOF SECTION -->
    <section class="bg-gray-50 border-b border-gray-100 py-16">
        <div class="w-full px-6">
            <div class="max-w-7xl mx-auto flex flex-wrap justify-center items-center gap-12 md:gap-24 lg:gap-40 text-center">
                <div class="group">
                    <span class="block text-4xl md:text-5xl font-extrabold text-gray-900 mb-2 transition-transform group-hover:scale-105">$150M+</span>
                    <span class="text-xs font-bold text-gray-400 uppercase tracking-widest">Property Secured</span>
                </div>
                <div class="group">
                    <span class="block text-4xl md:text-5xl font-extrabold text-gray-900 mb-2 transition-transform group-hover:scale-105">170+</span>
                    <span class="text-xs font-bold text-gray-400 uppercase tracking-widest">Strategic Transactions</span>
                </div>
                <div class="group">
                    <span class="block text-4xl md:text-5xl font-extrabold text-gray-900 mb-2 transition-transform group-hover:scale-105">1,000+</span>
                    <span class="text-xs font-bold text-gray-400 uppercase tracking-widest">Inspections Conducted</span>
                </div>
            </div>
        </div>
    </section>

    <!-- PREVIEW TABLE -->
    <section class="py-24 bg-white overflow-hidden">
        <div class="w-full px-4 max-w-5xl mx-auto text-center">
            <h2 class="text-3xl md:text-5xl font-bold text-gray-900 mb-6 tracking-tight">Market Data Preview</h2>
            <p class="text-gray-500 mb-16 text-lg md:text-xl">Discover why these areas are currently the highest-performing value pockets in Victoria.</p>
            
            <div class="relative bg-white border border-gray-200 rounded-3xl shadow-[0_10px_40px_rgba(0,0,0,0.04)] overflow-hidden text-left">
                <div class="overflow-x-auto">
                    <table class="w-full min-w-[600px]">
                        <thead>
                            <tr class="bg-gray-50 border-b border-gray-200 text-gray-500 text-sm uppercase tracking-widest font-bold">
                                <th class="py-6 px-10">Suburb Location</th>
                                <th class="py-6 px-10">Current Median</th>
                                <th class="py-6 px-10">Annual Growth</th>
                            </tr>
                        </thead>
                        <tbody class="divide-y divide-gray-100 text-lg">
                            <tr class="hover:bg-gray-50 transition-colors">
                                <td class="py-6 px-10 font-semibold text-gray-900">Frankston North</td>
                                <td class="py-6 px-10 text-gray-600">$595,000</td>
                                <td class="py-6 px-10 text-green-600 font-bold">+11.2%</td>
                            </tr>
                            <tr class="hover:bg-gray-50 transition-colors">
                                <td class="py-6 px-10 font-semibold text-gray-900">Melton South</td>
                                <td class="py-6 px-10 text-gray-600">$510,000</td>
                                <td class="py-6 px-10 text-green-600 font-bold">+10.5%</td>
                            </tr>
                            <tr class="blur-[8px] opacity-30 select-none">
                                <td class="py-6 px-10 font-medium">Hidden Growth Pocket</td>
                                <td class="py-6 px-10">$640,000</td>
                                <td class="py-6 px-10 text-green-600 font-bold">+12.8%</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
                <!-- Blurred Cta Overlay -->
                <div class="absolute bottom-0 left-0 right-0 h-48 blur-overlay flex items-center justify-center pb-8 z-10">
                    <button onclick="document.getElementById('lead-capture').scrollIntoView({behavior:'smooth'})" class="bg-gray-900 hover:bg-black text-white font-bold py-4 px-12 rounded-full text-base transition-all shadow-2xl hover:scale-105 active:scale-95">
                        Unlock Remaining 8 Suburbs
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- LEAD CAPTURE SECTION -->
    <section id="lead-capture" class="py-24 bg-gray-50 border-y border-gray-100">
        <div class="w-full px-4">
            <div class="max-w-2xl mx-auto bg-white rounded-[2.5rem] shadow-[0_40px_80px_-15px_rgba(0,0,0,0.12)] border border-gray-100 p-8 md:p-16 relative z-20">
                <div class="text-center mb-12">
                    <div class="w-20 h-20 bg-purple-100 text-purple-600 rounded-3xl rotate-3 flex items-center justify-center mx-auto mb-8 transition-transform hover:rotate-0">
                        <i data-lucide="mail-check" class="w-10 h-10"></i>
                    </div>
                    <h2 class="text-3xl md:text-5xl font-bold text-gray-900 mb-4 tracking-tight">Access The Report</h2>
                    <p class="text-gray-500 text-lg md:text-xl">Receive the 10-suburb PDF instantly and access our strategic booking calendar.</p>
                </div>
                
                <iframe name="hidden_iframe" id="hidden_iframe" style="display:none;" onload="if(submitted){window.location.href='https://api.leadconnectorhq.com/widget/booking/WFDrmJtulBGxRVD7ZIDr';}"></iframe>

                <form 
                    action="https://docs.google.com/forms/d/e/1FAIpQLSeH8UOfB8X2P8Ff6O7eR0PZ7vVz5Y-G_S5jN6Kx5o8p8G0yAQ/formResponse" 
                    method="POST" 
                    target="hidden_iframe" 
                    onsubmit="submitted=true; document.getElementById('btn-text').innerHTML='Opening Calendar...';"
                    class="space-y-6"
                >
                    <div class="space-y-2">
                        <label class="block text-sm font-bold text-gray-700 ml-1">Full Name</label>
                        <input type="text" name="entry.12345" placeholder="John Doe" required class="w-full px-6 py-5 border border-gray-200 rounded-2xl bg-gray-50 transition-all focus:bg-white text-lg focus:ring-4 focus:ring-purple-100">
                    </div>
                    <div class="space-y-2">
                        <label class="block text-sm font-bold text-gray-700 ml-1">Email Address</label>
                        <input type="email" name="entry.67890" placeholder="john@example.com" required class="w-full px-6 py-5 border border-gray-200 rounded-2xl bg-gray-50 transition-all focus:bg-white text-lg focus:ring-4 focus:ring-purple-100">
                    </div>
                    <div class="space-y-2">
                        <label class="block text-sm font-bold text-gray-700 ml-1">Mobile Number</label>
                        <input type="tel" name="entry.11223" placeholder="0400 000 000" required class="w-full px-6 py-5 border border-gray-200 rounded-2xl bg-gray-50 transition-all focus:bg-white text-lg focus:ring-4 focus:ring-purple-100">
                    </div>

                    <button type="submit" class="w-full bg-purple-600 hover:bg-purple-700 text-white font-bold py-6 px-6 rounded-2xl text-xl transition-all shadow-2xl shadow-purple-200 flex justify-center items-center group mt-4">
                        <span id="btn-text">Get Access Now</span>
                        <i data-lucide="chevron-right" class="ml-2 w-7 h-7 group-hover:translate-x-1 transition-transform"></i>
                    </button>
                </form>
                <div class="flex items-center justify-center gap-4 mt-10">
                    <div class="flex -space-x-2">
                        <div class="w-8 h-8 rounded-full bg-gray-200 border-2 border-white flex items-center justify-center text-[10px] font-bold">JD</div>
                        <div class="w-8 h-8 rounded-full bg-purple-200 border-2 border-white flex items-center justify-center text-[10px] font-bold">TS</div>
                        <div class="w-8 h-8 rounded-full bg-gray-300 border-2 border-white flex items-center justify-center text-[10px] font-bold">MK</div>
                    </div>
                    <p class="text-xs text-gray-400 font-bold uppercase tracking-widest">Joined by 500+ investors this month</p>
                </div>
            </div>
        </div>
    </section>

    <!-- FINAL CTA / FOOTER -->
    <footer class="bg-gray-950 text-white py-32">
        <div class="w-full px-4 max-w-4xl mx-auto text-center">
            <h2 class="text-4xl md:text-6xl font-bold mb-10 tracking-tight">Ready to build your <br> <span class="text-purple-500">Melbourne Portfolio?</span></h2>
            <p class="text-xl text-gray-400 mb-14 leading-relaxed font-light">Stop guessing. Use institutional-grade data to acquire high-yield assets before the next rate cycle.</p>
            <a href="https://api.leadconnectorhq.com/widget/booking/WFDrmJtulBGxRVD7ZIDr" class="inline-block bg-white text-gray-900 font-extrabold py-6 px-16 rounded-2xl text-xl hover:bg-purple-50 transition-all shadow-2xl hover:scale-105">
                Book Free Strategy Session
            </a>
            <div class="mt-24 pt-10 border-t border-gray-900">
                <p class="text-gray-600 text-sm font-medium uppercase tracking-widest">© 2024 Melbourne Property Strategy | Data-Driven Acquisition</p>
            </div>
        </div>
    </footer>

    <script>
        var submitted = false;
        lucide.createIcons();
    </script>
</body>
</html>
