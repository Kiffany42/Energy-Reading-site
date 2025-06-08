import React from "react";
import { CalendarDays, PhoneCall, Mail, Star } from "lucide-react";

export default function App() {
  return (
    <div className="min-h-screen bg-gradient-to-br from-purple-900 via-purple-700 to-purple-400 text-white p-6">
      <header className="text-center py-8">
        <h1 className="text-4xl font-bold">Awaken Within Energy Readings</h1>
        <p className="mt-2 text-lg italic">Tune into your inner power and guide others to theirs</p>
      </header>

      <main className="grid grid-cols-1 md:grid-cols-2 gap-6 max-w-5xl mx-auto">
        <div className="bg-purple-800 shadow-xl rounded-2xl p-6">
          <h2 className="text-2xl font-semibold mb-2 flex items-center gap-2">
            <CalendarDays /> Book an Energy Reading
          </h2>
          <p className="mb-4">
            General Reading – $40. Intuitive soul readings aligned with your spiritual energy. Gain clarity, healing, and personal guidance.
          </p>
          <button className="bg-purple-600 hover:bg-purple-500 text-white py-2 px-4 rounded-xl">Book a Session</button>
        </div>

        <div className="bg-purple-700 shadow-xl rounded-2xl p-6">
          <h2 className="text-2xl font-semibold mb-2 flex items-center gap-2">
            <Star /> Join My Free Self-Help Seminar
          </h2>
          <p className="mb-4">
            Empower yourself and others with this heart-centered workshop on healing, purpose, and manifestation.
          </p>
          <button className="bg-purple-500 hover:bg-purple-400 text-white py-2 px-4 rounded-xl">Reserve Your Spot</button>
        </div>
      </main>

      <footer className="mt-12 text-center text-sm text-purple-200">
        <div className="flex justify-center gap-4 mb-2">
          <a href="tel:9362414048" className="flex items-center gap-1"><PhoneCall /> Call</a>
          <a href="mailto:KiffanyLightard0@gmail.com" className="flex items-center gap-1"><Mail /> Email</a>
        </div>
        <p>© {new Date().getFullYear()} Awaken Within. All rights reserved.</p>
      </footer>
    </div>
  );
}
