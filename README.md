<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>VELORAÉ — Rituals that feel like you</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,500;0,600;1,400&family=Inter:wght@300;400;500&display=swap" rel="stylesheet">
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            cream: '#FDF9F3',
            blush: '#FBEAE0',
            coffee: '#3B271A',
            sand: '#EDE6DA',
            gold: '#C5A572',
          },
          fontFamily: {
            serif: ['"Cormorant Garamond"', 'serif'],
            sans: ['Inter', 'sans-serif'],
          }
        }
      }
    }
  </script>
</head>
<body class="bg-cream text-coffee font-sans antialiased">

  <!-- Top Bar -->
  <div class="bg-blush text-center py-2 px-4">
    <p class="text-[11px] md:text-xs tracking-wide font-medium">A little luxury, delivered</p>
  </div>

  <!-- Navbar -->
  <header class="sticky top-0 z-50 bg-cream/90 backdrop-blur border-b border-coffee/10">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-10 h-[68px] flex items-center justify-between gap-4">
      <!-- Logo -->
      <a href="#" class="font-serif text-[28px] md:text-[32px] leading-none tracking-[0.12em] font-medium">VELORAÉ</a>

      <!-- Desktop Nav -->
      <nav class="hidden lg:flex items-center gap-8 text-[14px] font-normal">
        <a href="#" class="hover:text-gold transition">Skincare</a>
        <a href="#" class="hover:text-gold transition">Makeup</a>
        <a href="#" class="hover:text-gold transition">Fragrance</a>
        <a href="#" class="hover:text-gold transition">Body</a>
        <a href="#" class="hover:text-gold transition">Our Story</a>
      </nav>

      <!-- Icons -->
      <div class="flex items-center gap-4 md:gap-5">
        <button aria-label="Search" class="hidden sm:block">
          <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="1.5" viewBox="0 0 24 24"><path stroke-linecap="round" d="M21 21l-4.35-4.35M17 10.5a6.5 6.5 0 11-13 0 6.5 6.5 0 0113 0z"/></svg>
        </button>
        <button aria-label="Account" class="hidden sm:block">
          <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="1.5" viewBox="0 0 24 24"><path stroke-linecap="round" d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14c-4 0-7 2-7 5h14c0-3-3-5-7-5z"/></svg>
        </button>
        <button aria-label="Bag" class="relative">
          <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="1.5" viewBox="0 0 24 24"><path stroke-linecap="round" d="M6 8h12l-1 12H7L6 8zM9 8V6a3 3 0 016 0v2"/></svg>
        </button>
        <!-- Mobile Menu -->
        <button class="lg:hidden" aria-label="Menu">
          <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="1.5" viewBox="0 0 24 24"><path stroke-linecap="round" d="M4 7h16M4 12h16M4 17h16"/></svg>
        </button>
      </div>
    </div>
  </header>

  <!-- HERO SECTION -->
  <section class="relative overflow-hidden">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-10">
      <div class="grid lg:grid-cols-2 items-center gap-8 lg:gap-0 py-8 md:py-12 lg:py-0 lg:min-h-[560px]">

        <!-- Left: Copy -->
        <div class="order-2 lg:order-1 text-center lg:text-left lg:pr-10 xl:pr-16 relative z-10">
          <h1 class="font-serif text-[42px] leading-[1.05] sm:text-[56px] md:text-[64px] lg:text-[68px] xl:text-[76px] font-medium">
            Rituals that<br />
            <span class="italic font-normal">feel like you.</span>
          </h1>

          <p class="mt-5 md:mt-6 text-[14px] md:text-[15px] leading-relaxed text-coffee/80 max-w-[420px] mx-auto lg:mx-0">
            Considered beauty essentials, thoughtfully crafted with high-performing ingredients to elevate your everyday.
          </p>

          <!-- Two Buttons -->
          <div class="mt-7 md:mt-8 flex flex-col sm:flex-row lg:flex-col xl:flex-row gap-3 sm:gap-4 sm:justify-center lg:justify-start">
            <!-- Primary Button -->
            <a href="#shop" class="inline-flex items-center justify-center bg-coffee text-cream text-[14px] font-medium px-7 py-3.5 rounded-[4px] hover:bg-[#2A1A10] hover:-translate-y-[1px] transition-all duration-300 shadow-sm">
              Shop the collection
            </a>
            <!-- Secondary Button -->
            <a href="#story" class="inline-flex items-center justify-center bg-transparent text-coffee text-[14px] font-medium px-7 py-3.5 rounded-[4px] border border-coffee/40 hover:border-coffee hover:bg-white/60 transition-all duration-300">
              Discover our approach
            </a>
          </div>
        </div>

        <!-- Right: Image -->
        <div class="order-1 lg:order-2 relative">
          <div class="relative aspect-[4/3] sm:aspect-[16/10] lg:aspect-auto lg:h-[560px] w-full overflow-hidden lg:rounded-none rounded-[12px]">
            <!-- Replace src with your image -->
            <img
              src="https://images.unsplash.com/photo-1620916566398-39f1143ab7be?q=80&w=1400&auto=format&fit=crop"
              alt="VELORAÉ Radiant Serum, Nourishing Cream and Balance Mist"
              class="w-full h-full object-cover object-center"
            />
            <!-- Soft gradient for text readability on mobile -->
            <div class="absolute inset-0 bg-gradient-to-t from-cream/40 via-transparent to-transparent lg:hidden"></div>
          </div>

          <!-- Floating Badge - Desktop only -->
          <div class="hidden lg:flex absolute bottom-6 left-6 bg-white/85 backdrop-blur px-4 py-3 rounded-full items-center gap-2 shadow-sm">
            <span class="w-2 h-2 rounded-full bg-gold"></span>
            <span class="text-xs tracking-wide">Clean • Vegan • Cruelty Free</span>
          </div>
        </div>

      </div>
    </div>
  </section>

</body>
</html>
