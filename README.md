<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>10 Melbourne Suburbs Under $700k Outperforming The Market</title>
    
    <!-- Modern Sans-Serif Font -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    
    <!-- Tailwind CSS for styling -->
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
        .blur-overlay {
            background: linear-gradient(to bottom, rgba(255,255,255,0) 0%, rgba(255,255,255,0.9) 60%, rgba(255,255,255,1) 100%);
        }
        input:focus {
            outline: none;
            box-shadow: 0 0 0 3px rgba(147, 51, 234, 0.2);
            border-color: #9333ea;
        }
    </style>
</head>
<body class="font-sans text-gray-800 bg-white antialiased">

    <!-- HERO SECTION -->
    <header class="relative pt-24 pb-16 md:pt-32 md:pb-24 overflow-hidden border-b border-gray-100">
        <div class="absolute inset-0 z-0 opacity-[0.03] pointer-events-none" style="background-image: url('data:image/svg+xml,%3Csvg width=\'60\' height=\'60\' viewBox=\'0 0 60 60\' xmlns=\'http://www.w3.org/2000/svg\'%3E%3Cg fill=\'none\' fill-rule=\'evenodd\'%3E%3Cg fill=\'%23000000\' fill-opacity=\'1\'%3E%3Cpath d=\'M36 34v-4h-2v4h-4v2h4v4h2v-4h4v-2h-4zm0-30V0h-2v4h-4v2h4v4h2V6h4V4h-4zM6 34v-4H4v4H0v2h4v4h2v-4h4v-2H6zM6 4V0H4v4H0v2h4v4h2V6h4V4H6z\'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E');"></div>
        
        <div class="container mx-auto px-4 relative z-10">
            <div class="max-w-4xl mx-auto text-center">
                <h1 class="text-4xl md:text-5xl lg:text-6xl font-extrabold text-gray-900 leading-tight mb-6 tracking-tight">
                    10 Melbourne Suburbs Under $700k <span class="text-purple-600 block sm:inline">Outperforming The Market</span>
                </h1>
                <p class="text-lg md:text-xl text-gray-600 mb-10 max-w-2xl mx-auto leading-relaxed">
                    These areas have recorded 10%+ growth in the last 12 months while most investors are still chasing the wrong locations.
                </p>
                <button onclick="document.getElementById('lead-capture').scrollIntoView({behavior:'smooth'})" class="inline-flex items-center justify-center bg-purple-600 hover:bg-purple-700 text-white font-semibold py-4 px-8 rounded-lg text-lg transition-all duration-200 shadow-lg hover:-translate-y-0.5">
                    Get The Full Breakdown
                    <i data-lucide="arrow-right" class="ml-2 w-5 h-5"></i>
                </button>
            </div>
        </div>
    </header>

    <!-- PROOF SECTION -->
    <section class="bg-gray-50 border-b border-gray-100 py-10">
        <div class="container mx-auto px-4">
            <div class="flex flex-wrap justify-center items-center gap-8 md:gap-20 text-center">
                <div>
                    <span class="block text-3xl font-bold text-purple-700">$150M+</span>
                    <span class="text-xs font-bold text-gray-400 uppercase tracking-widest">property secured</span>
                </div>
                <div>
                    <span class="block text-3xl font-bold text-purple-700">170+</span>
                    <span class="text-xs font-bold text-gray-400 uppercase tracking-widest">transactions</span>
                </div>
                <div>
                    <span class="block text-3xl font-bold text-purple-700">1,000+</span>
                    <span class="text-xs font-bold text-gray-400 uppercase tracking-widest">inspections</span>
                </div>
            </div>
        </div>
    </section>

    <!-- PREVIEW TABLE -->
    <section class="py-20 bg-white">
        <div class="container mx-auto px-4 max-w-4xl text-center">
            <h2 class="text-3xl font-bold text-gray-900 mb-2">Market Data Preview</h2>
            <p class="text-gray-500 mb-10 text-lg">Full 10-suburb breakdown available after access</p>
            
            <div class="relative bg-white border border-gray-200 rounded-xl shadow-sm overflow-hidden text-left">
                <div class="overflow-x-auto">
                    <table class="w-full min-w-[500px]">
                        <thead>
                            <tr class="bg-gray-50 border-b border-gray-200 text-gray-600 text-sm uppercase tracking-wider">
                                <th class="py-4 px-6 font-semibold">Suburb</th>
                                <th class="py-4 px-6 font-semibold">Median Price</th>
                                <th class="py-4 px-6 font-semibold">12m Growth</th>
                            </tr>
                        </thead>
                        <tbody class="divide-y divide-gray-100">
                            <tr>
                                <td class="py-4 px-6 font-medium text-gray-900">Frankston North</td>
                                <td class="py-4 px-6 text-gray-600">$595,000</td>
                                <td class="py-4 px-6 text-green-600 font-bold">+11.2%</td>
                            </tr>
                            <tr>
                                <td class="py-4 px-6 font-medium text-gray-900">Melton South</td>
                                <td class="py-4 px-6 text-gray-600">$510,000</td>
                                <td class="py-4 px-6 text-green-600 font-bold">+10.5%</td>
                            </tr>
                            <tr class="blur-[5px] opacity-50 select-none">
                                <td class="py-4 px-6 font-medium text-gray-900">Hidden Suburb</td>
                                <td class="py-4 px-6 text-gray-600">$620,000</td>
                                <td class="py-4 px-6 text-green-600 font-bold">+12.1%</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
                <div class="absolute bottom-0 left-0 right-0 h-32 blur-overlay flex items-center justify-center pb-4 z-10">
                    <button onclick="document.getElementById('lead-capture').scrollIntoView({behavior:'smooth'})" class="bg-gray-900 hover:bg-black text-white font-bold py-3 px-8 rounded-full text-sm transition-all shadow-xl">
                        Unlock Remaining 8 Suburbs
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- LEAD CAPTURE SECTION -->
    <section id="lead-capture" class="py-24 bg-gray-50 border-y border-gray-100">
        <div class="container mx-auto px-4">
            <div class="max-w-xl mx-auto bg-white rounded-2xl shadow-2xl border border-gray-100 p-8 md:p-12 relative z-20">
                <div class="text-center mb-10">
                    <div class="w-16 h-16 bg-purple-100 text-purple-600 rounded-full flex items-center justify-center mx-auto mb-6">
                        <i data-lucide="file-text" class="w-8 h-8"></i>
                    </div>
                    <h2 class="text-3xl font-bold text-gray-900 mb-3">Get The Full List</h2>
                    <p class="text-gray-500 text-lg">Enter your details to receive the report and access the booking calendar.</p>
                </div>
                
                <iframe name="hidden_iframe" id="hidden_iframe" style="display:none;" onload="if(submitted){window.location.href='https://api.leadconnectorhq.com/widget/booking/WFDrmJtulBGxRVD7ZIDr';}"></iframe>

                <form 
                    action="https://docs.google.com/forms/d/e/1FAIpQLSeH8UOfB8X2P8Ff6O7eR0PZ7vVz5Y-G_S5jN6Kx5o8p8G0yAQ/formResponse" 
                    method="POST" 
                    target="hidden_iframe" 
                    onsubmit="submitted=true; document.getElementById('btn-text').innerHTML='Processing...';"
                    class="space-y-6"
                >
                    <div>
                        <label class="block text-sm font-bold text-gray-700 mb-2">Full Name</label>
                        <input type="text" name="entry.12345" placeholder="John Doe" required class="w-full px-4 py-4 border border-gray-300 rounded-xl bg-gray-50 transition-all focus:bg-white">
                    </div>
                    <div>
                        <label class="block text-sm font-bold text-gray-700 mb-2">Email Address</label>
                        <input type="email" name="entry.67890" placeholder="john@example.com" required class="w-full px-4 py-4 border border-gray-300 rounded-xl bg-gray-50 transition-all focus:bg-white">
                    </div>
                    <div>
                        <label class="block text-sm font-bold text-gray-700 mb-2">Phone Number</label>
                        <input type="tel" name="entry.11223" placeholder="0400 000 000" required class="w-full px-4 py-4 border border-gray-300 rounded-xl bg-gray-50 transition-all focus:bg-white">
                    </div>

                    <button type="submit" class="w-full bg-purple-600 hover:bg-purple-700 text-white font-bold py-5 px-6 rounded-xl text-xl transition-all shadow-lg shadow-purple-200 flex justify-center items-center group">
                        <span id="btn-text">Get Access Now</span>
                        <i data-lucide="chevron-right" class="ml-2 w-6 h-6 group-hover:translate-x-1 transition-transform"></i>
                    </button>
                </form>
                <p class="text-center text-xs text-gray-400 mt-6 uppercase tracking-widest font-semibold">100% Privacy Protected</p>
            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer class="bg-gray-900 text-white py-20 border-t border-gray-800">
        <div class="container mx-auto px-4 max-w-3xl text-center">
            <h2 class="text-3xl font-bold mb-6">Want help finding the right property?</h2>
            <p class="text-lg text-gray-400 mb-10">We help investors identify and secure high-performing properties based on data, not guesswork.</p>
            <a href="https://api.leadconnectorhq.com/widget/booking/WFDrmJtulBGxRVD7ZIDr" class="inline-block bg-white text-gray-900 font-bold py-4 px-10 rounded-lg text-lg hover:bg-gray-100 transition-colors">
                Book Strategy Session
            </a>
            <p class="text-gray-600 text-sm mt-12">&copy; 2024 Property Investment Strategy. All rights reserved.</p>
        </div>
    </footer>

    <script>
        var submitted = false;
        lucide.createIcons();
    </script>
</body>
</html>
