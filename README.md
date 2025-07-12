import React from "react";

export default function Home() { return ( <div className="relative min-h-screen bg-black text-white font-serif"> {/* Background Image */} <div className="absolute inset-0 z-0"> <img
src="/background-mystic.jpg"
alt="Mystic Blessing Background"
className="w-full h-full object-cover opacity-90"
/> <div className="absolute inset-0 bg-gradient-to-b from-black/70 to-black/90"></div> </div>

{/* Navigation */}
  <nav className="absolute top-0 left-0 w-full z-20 flex justify-between items-center px-6 py-4 bg-transparent text-gold">
    <h1 className="text-xl font-bold tracking-wide">House of Mystic Blessing</h1>
    <ul className="flex space-x-6 text-sm">
      <li className="hover:text-white cursor-pointer">Home</li>
      <li className="hover:text-white cursor-pointer">Features</li>
      <li className="hover:text-white cursor-pointer">Pricing</li>
      <li className="hover:text-white cursor-pointer">Login</li>
    </ul>
  </nav>

  {/* Hero Section */}
  <section className="relative z-10 flex flex-col items-center justify-center text-center min-h-screen px-4 pt-32">
    <h2 className="text-4xl md:text-6xl font-bold text-gold drop-shadow-lg mb-4">
      Welcome to the House of Mystic Blessing
    </h2>
    <p className="text-lg md:text-xl text-white/80 mb-6 max-w-2xl">
      Decode your Divine Blueprint. Awaken your soul’s astrology.
    </p>
    <div className="flex gap-4">
      <button className="bg-gold text-black px-6 py-3 rounded-full font-semibold hover:bg-white transition">
        Generate Your Chart
      </button>
      <button className="border border-gold text-gold px-6 py-3 rounded-full font-semibold hover:bg-gold hover:text-black transition">
        Join Premium
      </button>
    </div>
  </section>

  {/* Features Section */}
  <section className="relative z-10 py-16 px-6 bg-black text-white">
    <h3 className="text-3xl font-bold text-center text-gold mb-10">Explore Your Soul Tools</h3>
    <div className="grid md:grid-cols-3 gap-8 max-w-6xl mx-auto">
      <div className="bg-white/5 p-6 rounded-xl border border-gold">
        <h4 className="text-xl text-gold font-semibold mb-2">Birth Chart Generator</h4>
        <p>Enter your birth info and instantly receive your full natal chart and soul map.</p>
      </div>
      <div className="bg-white/5 p-6 rounded-xl border border-gold">
        <h4 className="text-xl text-gold font-semibold mb-2">Soul Path Reports</h4>
        <p>Detailed insights on your life purpose, karmic patterns, and hidden strengths.</p>
      </div>
      <div className="bg-white/5 p-6 rounded-xl border border-gold">
        <h4 className="text-xl text-gold font-semibold mb-2">Synastry Love Maps</h4>
        <p>Compare charts to understand love, harmony, and soul contracts with others.</p>
      </div>
      <div className="bg-white/5 p-6 rounded-xl border border-gold">
        <h4 className="text-xl text-gold font-semibold mb-2">Transit Forecasts</h4>
        <p>Stay aligned with daily, weekly, and monthly cosmic shifts in your personal chart.</p>
      </div>
      <div className="bg-white/5 p-6 rounded-xl border border-gold">
        <h4 className="text-xl text-gold font-semibold mb-2">Learn Astrology</h4>
        <p>Master your own blueprint through beginner to advanced courses and tools.</p>
      </div>
      <div className="bg-white/5 p-6 rounded-xl border border-gold">
        <h4 className="text-xl text-gold font-semibold mb-2">Abundance Dashboard</h4>
        <p>Track your wealth codes, manifestation days, and soul-aligned opportunities.</p>
      </div>
    </div>
  </section>
</div>

); }

const gold = "#d6a84f";

