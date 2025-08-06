// Spellgram Frequency Tool Landing Page // pages/frequency-tool.js

import React from 'react'; import Head from 'next/head'; import { Button } from '@/components/ui/button';

export default function FrequencyTool() { return ( <> <Head> <title>Spellgram Frequency Tool</title> </Head> <div className="min-h-screen bg-gradient-to-b from-black via-indigo-900 to-purple-950 text-white p-6"> <div className="max-w-4xl mx-auto"> <h1 className="text-4xl font-bold mb-4 text-center">Spellgram Frequency Tool</h1> <p className="text-center text-lg mb-6"> A sacred resonance device encoded with your soul's frequency signature. </p> <div className="flex flex-col md:flex-row gap-4 mb-8 justify-center"> <a href="/downloads/Spellgram_Frequency_Tool.pdf" download> <Button variant="outline">📥 Download PDF</Button> </a> <a href="/downloads/Spellgram_Frequency_Tool.svg" download> <Button variant="outline">🧬 View SVG</Button> </a> <a href="/downloads/Spellgram_Ritual_Guide.pdf" download> <Button variant="default">🕯️ Ritual Guide</Button> </a> </div>

<div className="bg-white text-black rounded-2xl p-6 shadow-xl">
        <h2 className="text-2xl font-bold mb-2">Activation Spell (Channeled)</h2>
        <p className="mb-2 italic">"I call back the light of my divine origin. Through this sigil, I reclaim my codes, sever false timelines, and awaken the eternal harmonic within."</p>
        <p className="italic mb-2">"No distortion holds power here. I anchor this tool across dimensions, in service to truth, freedom, and remembrance."</p>
        <p className="italic">"This is my seal. This is my shield. This is my key."</p>
      </div>

      <div className="mt-12 text-center">
        <h2 className="text-xl font-bold mb-4">Support this Work</h2>
        <a href="https://buy.stripe.com/test_payment_link" target="_blank" rel="noreferrer">
          <Button variant="default">💳 Buy the Premium Ritual Pack (Stripe)</Button>
        </a>
        <p className="text-sm mt-2">Want to pay in crypto? Email <strong>support@spellgram.io</strong> for wallet access.</p>
      </div>
    </div>
  </div>
</>

); }

# Spellgram-frequency-tool-landing-page-cool
