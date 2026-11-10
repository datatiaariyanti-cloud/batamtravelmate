<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Batam Travelmate | Private Batam Weekend Escape</title>
    
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        cream: '#FDFBF7',
                        warmSand: '#F5EFE6',
                        terracotta: '#D97757',
                        terracottaDark: '#B8583B',
                        sage: '#8A9A86',
                        sageLight: '#E8EFE8',
                        charcoal: '#2D312E',
                        softGray: '#6E746F'
                    },
                    fontFamily: {
                        sans: ['Plus Jakarta Sans', 'sans-serif'],
                        serif: ['Playfair Display', 'serif']
                    }
                }
            }
        }
    </script>
    
    <!-- Google Fonts & FontAwesome Icons -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,600;0,700;1,400&family=Plus+Jakarta+Sans:wght@400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <style>
        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
            background-color: #FDFBF7;
            color: #2D312E;
        }
        .font-serif-title {
            font-family: 'Playfair Display', serif;
        }
        /* Custom scrollbar */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #F5EFE6;
        }
        ::-webkit-scrollbar-thumb {
            background: #D97757;
            border-radius: 4px;
        }
    </style>
</head>
<body class="antialiased selection:bg-terracotta selection:text-white">

    <!-- Navigation Header -->
    <header class="fixed top-0 left-0 right-0 z-50 bg-cream/90 backdrop-blur-md border-b border-warmSand transition-all duration-300">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            <a href="#" class="flex items-center gap-2">
                <div class="w-10 h-10 rounded-full bg-terracotta flex items-center justify-center text-white font-serif-title font-bold text-xl shadow-md">
                    TG
                </div>
                <div>
                    <span class="font-serif-title text-xl font-bold tracking-tight text-charcoal block leading-none">Batamtravelmate</span>
                    <span class="text-[10px] text-terracotta uppercase tracking-widest font-semibold">by Tia & Ghea</span>
                </div>
            </a>
            
            <nav class="hidden md:flex items-center gap-8 text-sm font-medium text-charcoal">
                <a href="#about" class="hover:text-terracotta transition-colors">Our Vibes</a>
                <a href="#package" class="hover:text-terracotta transition-colors">The Package</a>
                <a href="#itinerary" class="hover:text-terracotta transition-colors">Sample Day</a>
                <a href="#faq" class="hover:text-terracotta transition-colors">FAQ & Privacy</a>
            </nav>

            <a href="#booking" class="bg-terracotta hover:bg-terracottaDark text-white px-5 py-2.5 rounded-full text-sm font-semibold shadow-sm hover:shadow-md transition-all flex items-center gap-2">
                <i class="fa-brands font-normal fa-whatsapp text-lg"></i>
                <span>Book Escape</span>
            </a>
        </div>
    </header>

    <!-- Main Content Wrapper -->
    <main class="pt-20">

        <!-- Hero Section -->
        <section class="relative overflow-hidden pt-12 pb-20 md:pt-20 md:pb-32 bg-gradient-to-b from-warmSand/50 to-cream">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
                    
                    <div class="lg:col-span-7 space-y-6 text-center lg:text-left">
                        <!-- Badges -->
                        <div class="flex flex-wrap justify-center lg:justify-start gap-2.5">
                            <span class="inline-flex items-center gap-1.5 px-3.5 py-1.5 rounded-full text-xs font-semibold bg-sageLight text-sage border border-sage/20">
                                <i class="fa-regular fa-calendar-check text-xs"></i> Weekend Only (Sat & Sun)
                            </span>
                            <span class="inline-flex items-center gap-1.5 px-3.5 py-1.5 rounded-full text-xs font-semibold bg-terracotta/10 text-terracotta border border-terracotta/20">
                                <i class="fa-solid fa-user-group text-xs"></i> Small Groups (2-3 Pax)
                            </span>
                            <span class="inline-flex items-center gap-1.5 px-3.5 py-1.5 rounded-full text-xs font-semibold bg-warmSand text-charcoal border border-charcoal/10">
                                <i class="fa-solid fa-sliders text-xs"></i> 100% Custom Itinerary
                            </span>
                        </div>

                        <h1 class="text-4xl sm:text-5xl lg:text-6xl font-serif-title font-bold text-charcoal leading-tight">
                            Explore Batam at <span class="italic text-terracotta font-normal">Your Own Pace.</span>
                        </h1>

                        <p class="text-lg text-softGray max-w-2xl mx-auto lg:mx-0 font-normal leading-relaxed">
                            No rush, no boring tourist-trap shops, just pure relaxed vibes. Join <strong class="text-charcoal">Tia & Ghea</strong> for a curated boutique private city tour—tailored for Singapore & overseas weekend seekers.
                        </p>

                        <div class="pt-4 flex flex-col sm:flex-row items-center justify-center lg:justify-start gap-4">
                            <a href="#booking" class="w-full sm:w-auto px-8 py-4 rounded-full bg-terracotta hover:bg-terracottaDark text-white font-semibold text-center shadow-lg shadow-terracotta/20 transition-all flex items-center justify-center gap-3 group">
                                <span>Plan Your Trip Now</span>
                                <i class="fa-solid fa-arrow-right group-hover:translate-x-1 transition-transform"></i>
                            </a>
                            <a href="#itinerary" class="w-full sm:w-auto px-8 py-4 rounded-full bg-white hover:bg-warmSand text-charcoal font-semibold border border-warmSand text-center transition-all flex items-center justify-center gap-2">
                                <i class="fa-regular fa-compass"></i>
                                <span>See Sample Itinerary</span>
                            </a>
                        </div>

                        <div class="pt-6 border-t border-warmSand/80 flex items-center justify-center lg:justify-start gap-6 text-xs text-softGray">
                            <span class="flex items-center gap-1.5"><i class="fa-solid fa-check text-sage"></i> Direct Ferry Pick-Up</span>
                            <span class="flex items-center gap-1.5"><i class="fa-solid fa-check text-sage"></i> Local Food Included</span>
                            <span class="flex items-center gap-1.5"><i class="fa-solid fa-check text-sage"></i> Zero Forced Shopping</span>
                        </div>
                    </div>

                    <!-- Hero Visual Card / Mock Banner -->
                    <div class="lg:col-span-5 relative">
                        <div class="relative mx-auto max-w-md lg:max-w-none">
                            <div class="absolute -top-4 -left-4 w-72 h-72 bg-sage/20 rounded-full filter blur-3xl opacity-70"></div>
                            <div class="absolute -bottom-4 -right-4 w-72 h-72 bg-terracotta/20 rounded-full filter blur-3xl opacity-70"></div>

                            <div class="relative bg-white rounded-3xl p-6 shadow-xl border border-warmSand space-y-4">
                                <div class="relative h-64 rounded-2xl overflow-hidden bg-warmSand">
                                    <img src="https://images.unsplash.com/photo-1540555700478-4be289fbecef?auto=format&fit=crop&w=800&q=80" alt="Batam Chill Vibes" class="w-full h-full object-cover">
                                    <div class="absolute inset-0 bg-gradient-to-t from-black/60 via-transparent to-transparent flex items-end p-5">
                                        <div class="text-white">
                                            <span class="bg-terracotta text-white text-[10px] uppercase font-bold tracking-wider px-2 py-0.5 rounded">Weekend Highlight</span>
                                            <h3 class="font-serif-title text-xl font-semibold mt-1">Barelang & Sunset Cafe Hopping</h3>
                                        </div>
                                    </div>
                                </div>

                                <div class="grid grid-cols-3 gap-3 text-center pt-2">
                                    <div class="bg-cream p-3 rounded-xl border border-warmSand">
                                        <i class="fa-solid fa-mug-hot text-terracotta text-lg mb-1"></i>
                                        <div class="text-xs font-semibold text-charcoal">Cafe Hopping</div>
                                    </div>
                                    <div class="bg-cream p-3 rounded-xl border border-warmSand">
                                        <i class="fa-solid fa-spa text-sage text-lg mb-1"></i>
                                        <div class="text-xs font-semibold text-charcoal">Spa & Salon</div>
                                    </div>
                                    <div class="bg-cream p-3 rounded-xl border border-warmSand">
                                        <i class="fa-solid fa-utensils text-terracotta text-lg mb-1"></i>
                                        <div class="text-xs font-semibold text-charcoal">Local Eats</div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                </div>
            </div>
        </section>

        <!-- About Us & Core Promise -->
        <section id="about" class="py-20 bg-white">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                
                <div class="text-center max-w-3xl mx-auto mb-16 space-y-4">
                    <span class="text-terracotta uppercase text-xs tracking-widest font-bold">Meet Your Travel Mates</span>
                    <h2 class="text-3xl sm:text-4xl font-serif-title font-bold text-charcoal">
                        Hi! We are Tia & Ghea.
                    </h2>
                    <p class="text-softGray text-base sm:text-lg leading-relaxed">
                        We started <strong class="text-charcoal">Batamtravelmate</strong> because we were tired of generic tour packages that rush tourists from one crowded souvenir shop to another. We believe holidays should be <em class="text-terracotta font-serif-title">relaxing, aesthetic, and fun</em>!
                    </p>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <!-- Feature 1 -->
                    <div class="bg-cream p-8 rounded-3xl border border-warmSand hover:shadow-lg transition-all space-y-4">
                        <div class="w-14 h-14 rounded-2xl bg-terracotta/10 text-terracotta flex items-center justify-center text-2xl font-bold">
                            <i class="fa-solid fa-clock-rotate-left"></i>
                        </div>
                        <h3 class="text-xl font-bold font-serif-title text-charcoal">No Rushing Around</h3>
                        <p class="text-softGray text-sm leading-relaxed">
                            Wake up at your pace, sip your morning coffee without looking at the watch, and enjoy every destination without tour-guide stress.
                        </p>
                    </div>

                    <!-- Feature 2 -->
                    <div class="bg-cream p-8 rounded-3xl border border-warmSand hover:shadow-lg transition-all space-y-4">
                        <div class="w-14 h-14 rounded-2xl bg-sage/10 text-sage flex items-center justify-center text-2xl font-bold">
                            <i class="fa-solid fa-heart"></i>
                        </div>
                        <h3 class="text-xl font-bold font-serif-title text-charcoal">Self-Care & Pampering</h3>
                        <p class="text-softGray text-sm leading-relaxed">
                            Combine sightseeing with what young travelers actually love: relaxing foot reflexology, trendy nail art, or hair pampering.
                        </p>
                    </div>

                    <!-- Feature 3 -->
                    <div class="bg-cream p-8 rounded-3xl border border-warmSand hover:shadow-lg transition-all space-y-4">
                        <div class="w-14 h-14 rounded-2xl bg-terracotta/10 text-terracotta flex items-center justify-center text-2xl font-bold">
                            <i class="fa-solid fa-sliders"></i>
                        </div>
                        <h3 class="text-xl font-bold font-serif-title text-charcoal">100% Customized</h3>
                        <p class="text-softGray text-sm leading-relaxed">
                            Want to spend 3 hours at a oceanfront cafe? Or skip a venue? Just tell us—you control the itinerary, we manage the logistics.
                        </p>
                    </div>
                </div>

            </div>
        </section>

        <!-- Pricing & Package Details -->
        <section id="package" class="py-20 bg-warmSand/40">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                
                <div class="bg-white rounded-3xl border border-warmSand shadow-xl overflow-hidden">
                    <div class="grid grid-cols-1 lg:grid-cols-12">
                        
                        <!-- Left Package Promo Panel -->
                        <div class="lg:col-span-5 bg-charcoal text-white p-8 sm:p-12 flex flex-col justify-between">
                            <div class="space-y-6">
                                <span class="bg-terracotta text-white text-xs uppercase font-bold tracking-widest px-3 py-1 rounded-full inline-block">
                                    All-Inclusive Day Escape
                                </span>
                                <div>
                                    <h3 class="text-3xl font-serif-title font-bold">One-Day Batam Private Tour</h3>
                                    <p class="text-gray-400 text-sm mt-2">Available Saturday & Sunday Only</p>
                                </div>
                                
                                <div class="pt-4 border-t border-gray-700">
                                    <div class="text-xs text-gray-400 uppercase tracking-wider font-semibold">Fixed Rate</div>
                                    <div class="flex items-baseline gap-2 mt-1">
                                        <span class="text-4xl font-bold text-white font-serif-title">IDR 1,000,000</span>
                                        <span class="text-gray-400 text-sm">/ pax</span>
                                    </div>
                                    <div class="text-sage text-xs mt-1 font-medium">
                                        <i class="fa-solid fa-circle-info"></i> ~ SGD 85 / pax (Min 2 - Max 3 Pax)
                                    </div>
                                </div>
                            </div>

                            <div class="pt-8 space-y-3">
                                <div class="flex items-center gap-3 text-xs text-gray-300">
                                    <i class="fa-solid fa-user-check text-terracotta"></i>
                                    <span>Private & Intimate (Driver + Host Included)</span>
                                </div>
                                <div class="flex items-center gap-3 text-xs text-gray-300">
                                    <i class="fa-solid fa-van-shuttle text-terracotta"></i>
                                    <span>Pick-up direct from Ferry Port or Hotel</span>
                                </div>
                            </div>
                        </div>

                        <!-- Right Inclusions & Exclusions -->
                        <div class="lg:col-span-7 p-8 sm:p-12 space-y-8">
                            
                            <div>
                                <h4 class="text-lg font-bold font-serif-title text-charcoal mb-4 flex items-center gap-2">
                                    <i class="fa-solid fa-circle-check text-sage text-xl"></i>
                                    <span>What's Included (Inclusions)</span>
                                </h4>
                                <ul class="grid grid-cols-1 sm:grid-cols-2 gap-3 text-sm text-softGray">
                                    <li class="flex items-start gap-2.5">
                                        <i class="fa-solid fa-check text-sage mt-1"></i>
                                        <span>Private Car + Fuel + Driver & Guide Host</span>
                                    </li>
                                    <li class="flex items-start gap-2.5">
                                        <i class="fa-solid fa-check text-sage mt-1"></i>
                                        <span>Local Delicacy Lunch at top spot</span>
                                    </li>
                                    <li class="flex items-start gap-2.5">
                                        <i class="fa-solid fa-check text-sage mt-1"></i>
                                        <span>Morning & Afternoon Coffee / Snack</span>
                                    </li>
                                    <li class="flex items-start gap-2.5">
                                        <i class="fa-solid fa-check text-sage mt-1"></i>
                                        <span>Ferry Port / Hotel Transfers</span>
                                    </li>
                                </ul>
                            </div>

                            <div class="border-t border-warmSand pt-6">
                                <h4 class="text-lg font-bold font-serif-title text-charcoal mb-4 flex items-center gap-2">
                                    <i class="fa-solid fa-circle-xmark text-terracotta text-xl"></i>
                                    <span>What's Excluded (Exclusions)</span>
                                </h4>
                                <ul class="grid grid-cols-1 sm:grid-cols-2 gap-3 text-sm text-softGray">
                                    <li class="flex items-start gap-2.5">
                                        <i class="fa-solid fa-xmark text-terracotta mt-1"></i>
                                        <span>Personal Pampering Costs (Salon/Nail Art/Spa)</span>
                                    </li>
                                    <li class="flex items-start gap-2.5">
                                        <i class="fa-solid fa-xmark text-terracotta mt-1"></i>
                                        <span>Hotel Accommodation</span>
                                    </li>
                                    <li class="flex items-start gap-2.5">
                                        <i class="fa-solid fa-xmark text-terracotta mt-1"></i>
                                        <span>Ferry / Flight Tickets to Batam</span>
                                    </li>
                                    <li class="flex items-start gap-2.5">
                                        <i class="fa-solid fa-xmark text-terracotta mt-1"></i>
                                        <span>Personal Shopping Expenses</span>
                                    </li>
                                </ul>
                            </div>

                            <div class="pt-4 flex justify-end">
                                <a href="#booking" class="bg-terracotta hover:bg-terracottaDark text-white px-6 py-3 rounded-full text-sm font-semibold transition-all">
                                    Book This Package
                                </a>
                            </div>

                        </div>

                    </div>
                </div>

            </div>
        </section>

        <!-- Sample Itinerary Showcase -->
        <section id="itinerary" class="py-20 bg-cream">
            <div class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8">
                
                <div class="text-center space-y-4 mb-16">
                    <span class="text-terracotta uppercase text-xs tracking-widest font-bold">Suggested Route</span>
                    <h2 class="text-3xl sm:text-4xl font-serif-title font-bold text-charcoal">
                        The "Chill & Glow" Day Sample
                    </h2>
                    <p class="text-softGray text-sm sm:text-base max-w-2xl mx-auto">
                        This is a popular sample itinerary, but remember: <strong class="text-charcoal">it is 100% customizable</strong> based on what you and your friends want to do!
                    </p>
                </div>

                <!-- Timeline Container -->
                <div class="relative border-l-2 border-terracotta/30 ml-4 sm:ml-32 space-y-12">
                    
                    <!-- Item 1 -->
                    <div class="relative pl-8 sm:pl-10 group">
                        <div class="absolute -left-[9px] top-1.5 w-4 h-4 rounded-full bg-terracotta border-4 border-cream"></div>
                        <div class="hidden sm:block absolute -left-32 top-0 text-xs font-bold text-terracotta uppercase tracking-wider">
                            09.00 - 09.30 AM
                        </div>
                        <div class="bg-white p-6 rounded-2xl border border-warmSand shadow-sm hover:shadow-md transition-all">
                            <span class="sm:hidden inline-block text-xs font-bold text-terracotta uppercase tracking-wider mb-2">09.00 - 09.30 AM</span>
                            <h3 class="text-lg font-bold font-serif-title text-charcoal">Warm Welcome & Pick-Up</h3>
                            <p class="text-softGray text-sm mt-1">We pick you up directly from Harbour Bay / Batam Center Ferry Terminal or your hotel in a clean private car.</p>
                        </div>
                    </div>

                    <!-- Item 2 -->
                    <div class="relative pl-8 sm:pl-10 group">
                        <div class="absolute -left-[9px] top-1.5 w-4 h-4 rounded-full bg-terracotta border-4 border-cream"></div>
                        <div class="hidden sm:block absolute -left-32 top-0 text-xs font-bold text-terracotta uppercase tracking-wider">
                            09.30 - 11.00 AM
                        </div>
                        <div class="bg-white p-6 rounded-2xl border border-warmSand shadow-sm hover:shadow-md transition-all">
                            <span class="sm:hidden inline-block text-xs font-bold text-terracotta uppercase tracking-wider mb-2">09.30 - 11.00 AM</span>
                            <h3 class="text-lg font-bold font-serif-title text-charcoal"><i class="fa-solid fa-mug-hot text-terracotta mr-2"></i>Morning Coffee & Pastry</h3>
                            <p class="text-softGray text-sm mt-1">Kick off the morning at an aesthetic artisan cafe in Batam for quiet coffee, light snacks, and catch-up chats.</p>
                        </div>
                    </div>

                    <!-- Item 3 -->
                    <div class="relative pl-8 sm:pl-10 group">
                        <div class="absolute -left-[9px] top-1.5 w-4 h-4 rounded-full bg-terracotta border-4 border-cream"></div>
                        <div class="hidden sm:block absolute -left-32 top-0 text-xs font-bold text-terracotta uppercase tracking-wider">
                            11.00 - 01.00 PM
                        </div>
                        <div class="bg-white p-6 rounded-2xl border border-warmSand shadow-sm hover:shadow-md transition-all">
                            <span class="sm:hidden inline-block text-xs font-bold text-terracotta uppercase tracking-wider mb-2">11.00 - 01.00 PM</span>
                            <h3 class="text-lg font-bold font-serif-title text-charcoal"><i class="fa-solid fa-spa text-sage mr-2"></i>Self-Care & Pampering Session</h3>
                            <p class="text-softGray text-sm mt-1">Enjoy foot reflexology, trendy nail art, or hair treatment at curated local beauty salons (treatment fee paid direct).</p>
                        </div>
                    </div>

                    <!-- Item 4 -->
                    <div class="relative pl-8 sm:pl-10 group">
                        <div class="absolute -left-[9px] top-1.5 w-4 h-4 rounded-full bg-terracotta border-4 border-cream"></div>
                        <div class="hidden sm:block absolute -left-32 top-0 text-xs font-bold text-terracotta uppercase tracking-wider">
                            01.00 - 02.30 PM
                        </div>
                        <div class="bg-white p-6 rounded-2xl border border-warmSand shadow-sm hover:shadow-md transition-all">
                            <span class="sm:hidden inline-block text-xs font-bold text-terracotta uppercase tracking-wider mb-2">01.00 - 02.30 PM</span>
                            <h3 class="text-lg font-bold font-serif-title text-charcoal"><i class="fa-solid fa-utensils text-terracotta mr-2"></i>Local Culinary Lunch</h3>
                            <p class="text-softGray text-sm mt-1">Relaxed lunch featuring famous local delicacies (Seafood or authentic Indonesian dishes included in package).</p>
                        </div>
                    </div>

                    <!-- Item 5 -->
                    <div class="relative pl-8 sm:pl-10 group">
                        <div class="absolute -left-[9px] top-1.5 w-4 h-4 rounded-full bg-terracotta border-4 border-cream"></div>
                        <div class="hidden sm:block absolute -left-32 top-0 text-xs font-bold text-terracotta uppercase tracking-wider">
                            02.30 - 05.00 PM
                        </div>
                        <div class="bg-white p-6 rounded-2xl border border-warmSand shadow-sm hover:shadow-md transition-all">
                            <span class="sm:hidden inline-block text-xs font-bold text-terracotta uppercase tracking-wider mb-2">02.30 - 05.00 PM</span>
                            <h3 class="text-lg font-bold font-serif-title text-charcoal"><i class="fa-solid fa-camera-retro text-sage mr-2"></i>Barelang Bridge & Sightseeing</h3>
                            <p class="text-softGray text-sm mt-1">Drive through iconic Batam landmarks for photos, scenic sea breezes, and scenic viewpoints.</p>
                        </div>
                    </div>

                    <!-- Item 6 -->
                    <div class="relative pl-8 sm:pl-10 group">
                        <div class="absolute -left-[9px] top-1.5 w-4 h-4 rounded-full bg-terracotta border-4 border-cream"></div>
                        <div class="hidden sm:block absolute -left-32 top-0 text-xs font-bold text-terracotta uppercase tracking-wider">
                            05.00 - 06.30 PM
                        </div>
                        <div class="bg-white p-6 rounded-2xl border border-warmSand shadow-sm hover:shadow-md transition-all">
                            <span class="sm:hidden inline-block text-xs font-bold text-terracotta uppercase tracking-wider mb-2">05.00 - 06.30 PM</span>
                            <h3 class="text-lg font-bold font-serif-title text-charcoal"><i class="fa-solid fa-cloud-sun text-terracotta mr-2"></i>Sunset Cafe & Drop-off</h3>
                            <p class="text-softGray text-sm mt-1">Unwind with afternoon snacks at a sunset spot before smooth drop-off back to your Ferry Terminal or Hotel.</p>
                        </div>
                    </div>

                </div>

            </div>
        </section>

        <!-- Interactive Booking Form & Price Calculator -->
        <section id="booking" class="py-20 bg-warmSand/30">
            <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
                
                <div class="text-center space-y-4 mb-12">
                    <span class="text-terracotta uppercase text-xs tracking-widest font-bold">Reserve Your Slot</span>
                    <h2 class="text-3xl sm:text-4xl font-serif-title font-bold text-charcoal">
                        Book Your Weekend Escape
                    </h2>
                    <p class="text-softGray text-sm sm:text-base max-w-xl mx-auto">
                        Fill in your details below to calculate your package total and instantly send a pre-filled booking request via WhatsApp to Tia & Ghea.
                    </p>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-start">
                    
                    <!-- Form Input Fields (Left) -->
                    <div class="lg:col-span-7 bg-white p-6 sm:p-8 rounded-3xl border border-warmSand shadow-md space-y-6">
                        
                        <h3 class="text-lg font-bold font-serif-title text-charcoal border-b border-warmSand pb-3">
                            1. Trip & Guest Details
                        </h3>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <!-- Number of Pax -->
                            <div>
                                <label class="block text-xs font-semibold uppercase text-charcoal mb-2">Number of Guests</label>
                                <select id="inputPax" onchange="calculatePrice()" class="w-full bg-cream border border-warmSand rounded-xl p-3 text-sm focus:outline-none focus:border-terracotta">
                                    <option value="2">2 Guests (Min Pax)</option>
                                    <option value="3">3 Guests (Max Pax)</option>
                                </select>
                            </div>

                            <!-- Preferred Day -->
                            <div>
                                <label class="block text-xs font-semibold uppercase text-charcoal mb-2">Preferred Day (Weekend)</label>
                                <select id="inputDay" class="w-full bg-cream border border-warmSand rounded-xl p-3 text-sm focus:outline-none focus:border-terracotta">
                                    <option value="Saturday">Saturday</option>
                                    <option value="Sunday">Sunday</option>
                                </select>
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <!-- Full Name -->
                            <div>
                                <label class="block text-xs font-semibold uppercase text-charcoal mb-2">Lead Guest Name *</label>
                                <input type="text" id="inputName" placeholder="e.g. Sarah Tan" class="w-full bg-cream border border-warmSand rounded-xl p-3 text-sm focus:outline-none focus:border-terracotta">
                            </div>

                            <!-- Passport Number -->
                            <div>
                                <label class="block text-xs font-semibold uppercase text-charcoal mb-2">Passport No. (For Pickup ID) *</label>
                                <input type="text" id="inputPassport" placeholder="e.g. K1234567A" class="w-full bg-cream border border-warmSand rounded-xl p-3 text-sm focus:outline-none focus:border-terracotta">
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <!-- Nationality -->
                            <div>
                                <label class="block text-xs font-semibold uppercase text-charcoal mb-2">Nationality *</label>
                                <input type="text" id="inputNationality" placeholder="e.g. Singaporean" class="w-full bg-cream border border-warmSand rounded-xl p-3 text-sm focus:outline-none focus:border-terracotta">
                            </div>

                            <!-- WhatsApp Contact -->
                            <div>
                                <label class="block text-xs font-semibold uppercase text-charcoal mb-2">WhatsApp Number *</label>
                                <input type="text" id="inputWhatsapp" placeholder="e.g. +65 9123 4567" class="w-full bg-cream border border-warmSand rounded-xl p-3 text-sm focus:outline-none focus:border-terracotta">
                            </div>
                        </div>

                        <!-- Pick up location -->
                        <div>
                            <label class="block text-xs font-semibold uppercase text-charcoal mb-2">Pick-Up Location in Batam *</label>
                            <input type="text" id="inputPickup" placeholder="e.g. Harbour Bay Ferry Terminal / Hotel Name" class="w-full bg-cream border border-warmSand rounded-xl p-3 text-sm focus:outline-none focus:border-terracotta">
                        </div>

                        <!-- Emergency Contact -->
                        <div>
                            <label class="block text-xs font-semibold uppercase text-charcoal mb-2">Emergency Contact (Name & Phone)</label>
                            <input type="text" id="inputEmergency" placeholder="e.g. Alex Tan (+65 9876 5432)" class="w-full bg-cream border border-warmSand rounded-xl p-3 text-sm focus:outline-none focus:border-terracotta">
                        </div>

                        <!-- Special Requests -->
                        <div>
                            <label class="block text-xs font-semibold uppercase text-charcoal mb-2">Food Allergies / Custom Wishlist</label>
                            <textarea id="inputNotes" rows="3" placeholder="e.g. Seafood allergy, want to visit nail salon in Nagoya, etc." class="w-full bg-cream border border-warmSand rounded-xl p-3 text-sm focus:outline-none focus:border-terracotta"></textarea>
                        </div>

                    </div>

                   <!-- Live Summary & WhatsApp Button (Right) -->
<div class="lg:col-span-5 bg-charcoal text-white p-6 sm:p-8 rounded-3xl shadow-xl space-y-6 sticky top-28">
    <h3 class="text-lg font-bold font-serif-title border-b border-gray-700 pb-3 flex items-center justify-between">
        <span>Summary & Transfer Details</span>
        <span class="text-xs font-normal text-sage bg-sage/20 px-2 py-0.5 rounded">Live Calc</span>
    </h3>

    <div class="space-y-3 text-sm text-gray-300">
        <div class="flex justify-between">
            <span>Rate Per Pax:</span>
            <span>IDR 1,000,000</span>
        </div>
        <div class="flex justify-between">
            <span>Jumlah Tamu:</span>
            <span id="summaryPaxText" class="font-semibold text-white">2 Pax</span>
        </div>
        
        <div class="border-t border-gray-700 pt-3 space-y-1">
            <div class="flex justify-between items-baseline">
                <span class="font-semibold text-white">Total Harga (IDR):</span>
                <span id="summaryTotalIDR" class="text-xl font-bold font-serif-title text-terracotta">IDR 2,000,000</span>
            </div>
            <div class="flex justify-between text-xs text-gray-400">
                <span>Estimasi (SGD):</span>
                <span id="summaryTotalSGD">~ SGD 169.49</span>
            </div>
            <div class="flex justify-between text-xs text-gray-400">
                <span>Estimasi (MYR):</span>
                <span id="summaryTotalMYR">~ MYR 555.56</span>
            </div>
        </div>

        <!-- Rincian Transfer Di Awal (DP 30%) -->
        <div class="bg-gray-800/90 p-4 rounded-xl border border-terracotta/40 space-y-2 mt-4">
            <div class="text-xs font-bold text-terracotta uppercase tracking-wider flex items-center gap-1.5">
                <i class="fa-solid fa-wallet"></i> Transfer Di Awal (DP 30% Deposit)
            </div>
            <div class="text-xs text-gray-300 space-y-1">
                <div class="flex justify-between">
                    <span>Deposit (IDR):</span>
                    <strong id="dpIDR" class="text-white">IDR 600,000</strong>
                </div>
                <div class="flex justify-between">
                    <span>Deposit (SGD):</span>
                    <strong id="dpSGD" class="text-sage">~ SGD 50.85</strong>
                </div>
                <div class="flex justify-between">
                    <span>Deposit (MYR):</span>
                    <strong id="dpMYR" class="text-sage">~ MYR 166.67</strong>
                </div>
            </div>
        </div>
    </div>

    <div class="p-3 bg-gray-800/50 rounded-xl text-xs text-gray-400 space-y-1 border border-gray-700">
        <p class="flex items-center gap-1.5 text-sage">
            <i class="fa-solid fa-shield-halved"></i> Pembayaran DP dilakukan di awal via Transfer / PayNow / Wise untuk mengunci slot weekend. Sisa pelunasan dibayar saat kedatangan.
        </p>
    </div>

    <button onclick="sendToWhatsapp()" class="w-full py-4 bg-terracotta hover:bg-terracottaDark text-white font-semibold rounded-xl shadow-lg transition-all flex items-center justify-center gap-2">
        <i class="fa-brands fa-whatsapp text-xl"></i>
        <span>Kirim Booking & Transfer DP via WA</span>
    </button>

    <p class="text-[11px] text-center text-gray-400">
        Format rincian data & info transfer akan otomatis terkirim ke WhatsApp.
    </p>
</div>
        </section>

        <!-- FAQ & Data Privacy Guarantee -->
        <section id="faq" class="py-20 bg-white">
            <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
                
                <div class="text-center space-y-4 mb-14">
                    <span class="text-terracotta uppercase text-xs tracking-widest font-bold">Good to Know</span>
                    <h2 class="text-3xl font-serif-title font-bold text-charcoal">
                        Frequently Asked Questions & Privacy
                    </h2>
                </div>

                <div class="space-y-6">
                    
                    <!-- FAQ Item 1 -->
                    <div class="bg-cream p-6 rounded-2xl border border-warmSand space-y-2">
                        <h4 class="font-bold text-charcoal text-base flex items-center gap-2">
                            <i class="fa-solid fa-lock text-terracotta"></i>
                            <span>Why do you need my passport details? Is it safe?</span>
                        </h4>
                        <p class="text-softGray text-sm leading-relaxed pl-6">
                            Passport details (Name and Passport Number) are required solely for identity verification during port/hotel pick-ups and for guest safety during our private tour. We strictly follow data privacy guidelines: your data will never be shared, sold, or shown on social media.
                        </p>
                    </div>

                    <!-- FAQ Item 2 -->
                    <div class="bg-cream p-6 rounded-2xl border border-warmSand space-y-2">
                        <h4 class="font-bold text-charcoal text-base flex items-center gap-2">
                            <i class="fa-solid fa-arrows-rotate text-sage"></i>
                            <span>What is the Cancellation / Reschedule Policy?</span>
                        </h4>
                        <p class="text-softGray text-sm leading-relaxed pl-6">
                            Deposits are non-refundable if cancelled less than 48 hours before the tour. However, you can reschedule your weekend tour free of charge with at least 3 days' prior notice (subject to Tia & Ghea's availability).
                        </p>
                    </div>

                    <!-- FAQ Item 3 -->
                    <div class="bg-cream p-6 rounded-2xl border border-warmSand space-y-2">
                        <h4 class="font-bold text-charcoal text-base flex items-center gap-2">
                            <i class="fa-solid fa-wallet text-terracotta"></i>
                            <span>How do overseas guests pay the deposit?</span>
                        </h4>
                        <p class="text-softGray text-sm leading-relaxed pl-6">
                            For Singaporean / International guests, we accept Wise (TransferWise), PayNow (via partnered local accounts), or Direct Bank Transfer. Remaining balance can be paid in Cash (SGD/IDR) upon arrival.
                        </p>
                    </div>

                </div>

            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-charcoal text-white py-12 border-t border-gray-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center space-y-6">
            
            <div class="flex items-center justify-center gap-2">
                <div class="w-8 h-8 rounded-full bg-terracotta flex items-center justify-center text-white font-serif-title font-bold text-sm">
                    TG
                </div>
                <span class="font-serif-title text-lg font-bold">Batam Travelmate</span>
            </div>

            <p class="text-xs text-gray-400 max-w-md mx-auto">
                Boutique private city tours in Batam for weekend escapees. Designed with love for relaxed travel.
            </p>

            <div class="text-[11px] text-gray-500 pt-4 border-t border-gray-800">
                &copy; 2026 Batam Travelmate. All rights reserved.
            </div>
        </div>
    </footer>

    <!-- JavaScript Logic for Price Calculator & WhatsApp Generation -->
<script>
    // Konstanta Harga & Kurs Mata Uang (IDR, SGD, MYR)
    const IDR_PER_PAX = 1000000;
    const RATE_SGD = 14143; // 1 SGD = 14,143 IDR
    const RATE_MYR = 4461;  // 1 MYR = 4,461 IDR
    const DEPOSIT_PERCENTAGE = 0.30; // DP 30% di awal

    function calculatePrice() {
        const pax = parseInt(document.getElementById('inputPax').value) || 2;
        
        // Total Harga
        const totalIDR = pax * IDR_PER_PAX;
        const totalSGD = (totalIDR / RATE_SGD).toFixed(2);
        const totalMYR = (totalIDR / RATE_MYR).toFixed(2);

        // Jumlah DP 30% Transfer di Awal
        const dpIDR = totalIDR * DEPOSIT_PERCENTAGE;
        const dpSGD = (dpIDR / RATE_SGD).toFixed(2);
        const dpMYR = (dpIDR / RATE_MYR).toFixed(2);

        // Update Ringkasan UI
        document.getElementById('summaryPaxText').innerText = pax + ' Pax';
        document.getElementById('summaryTotalIDR').innerText = 'IDR ' + totalIDR.toLocaleString('id-ID');
        document.getElementById('summaryTotalSGD').innerText = '~ SGD ' + totalSGD;
        document.getElementById('summaryTotalMYR').innerText = '~ MYR ' + totalMYR;

        // Update Informasi DP Transfer
        document.getElementById('dpIDR').innerText = 'IDR ' + dpIDR.toLocaleString('id-ID');
        document.getElementById('dpSGD').innerText = '~ SGD ' + dpSGD;
        document.getElementById('dpMYR').innerText = '~ MYR ' + dpMYR;
    }

    function sendToWhatsapp() {
        const name = document.getElementById('inputName').value.trim();
        const passport = document.getElementById('inputPassport').value.trim();
        const nationality = document.getElementById('inputNationality').value.trim();
        const whatsapp = document.getElementById('inputWhatsapp').value.trim();
        const pickup = document.getElementById('inputPickup').value.trim();
        const emergency = document.getElementById('inputEmergency').value.trim();
        const notes = document.getElementById('inputNotes').value.trim();
        const pax = document.getElementById('inputPax').value;
        const day = document.getElementById('inputDay').value;

        // Validasi input wajib
        if (!name || !passport || !nationality || !whatsapp || !pickup) {
            alert('Mohon lengkapi semua kolom wajib (Nama, No. Paspor, Kewarganegaraan, WhatsApp, & Lokasi Penjemputan).');
            return;
        }

        const totalIDR = pax * IDR_PER_PAX;
        const totalSGD = (totalIDR / RATE_SGD).toFixed(2);
        const totalMYR = (totalIDR / RATE_MYR).toFixed(2);

        const dpIDR = totalIDR * DEPOSIT_PERCENTAGE;
        const dpSGD = (dpIDR / RATE_SGD).toFixed(2);
        const dpMYR = (dpIDR / RATE_MYR).toFixed(2);

        // Format Pesan WhatsApp
        const message = 
`*[PEMESANAN TOUR - BATAM TRAVELMATE]*\n` +
`----------------------------------------\n` +
`*DATA PEMESAN:* \n` +
`• Nama Lengkap: ${name}\n` +
`• No. Paspor: ${passport}\n` +
`• Kewarganegaraan: ${nationality}\n` +
`• No. WhatsApp: ${whatsapp}\n` +
`• Hari Pilihan: ${day}\n` +
`• Jumlah Peserta: ${pax} Pax\n` +
`• Lokasi Penjemputan: ${pickup}\n` +
`• Kontak Darurat: ${emergency || '-'}\n` +
`• Permintaan Khusus/Catatan: ${notes || '-'}\n\n` +
`*RINCIAN BIAYA & TOTAL:* \n` +
`• Total Paket (IDR): IDR ${totalIDR.toLocaleString('id-ID')}\n` +
`• Estimasi (SGD): SGD ${totalSGD}\n` +
`• Estimasi (MYR): MYR ${totalMYR}\n\n` +
`*INFO TRANSFER DP DI AWAL (30%):*\n` +
`• DP Rupiah (IDR): *IDR ${dpIDR.toLocaleString('id-ID')}*\n` +
`• DP Dollar SG (SGD): *SGD ${dpSGD}*\n` +
`• DP Ringgit MY (MYR): *MYR ${dpMYR}*\n` +
`----------------------------------------\n` +
`Halo Kak Tia & Ghea, saya ingin konfirmasi reservasi paket tour ini. Mohon info nomor rekening / PayNow untuk transfer DP di awal. Terima kasih!`;

        const encodedMessage = encodeURIComponent(message);
        const targetPhoneNumber = "6287867293391"; // Nomor WhatsApp Tujuan Anda

        // Redirection ke WA Anda
        window.open(`https://wa.me/${targetPhoneNumber}?text=${encodedMessage}`, '_blank');
    }

    // Jalankan kalkulasi otomatis saat halaman dimuat
    window.onload = function() {
        calculatePrice();
    };
</script>
</body>
</html>
