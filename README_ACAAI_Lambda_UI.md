# ACAΛI – Lambda UI

Dit is de officiële gebruikersinterface voor het ACAΛI systeem – een AI-gedreven comfort- en energieplatform voor gebouwen. Deze interface vormt het menselijk gezicht van het ecosysteem, met een focus op eenvoud, ritme en real-time feedback.

## 🌍 Doel
Een intuïtieve, frictieloze interface die gebruikers toelaat:
- De comfortslider aan te passen (warm/koud/meer licht)
- Voorinstellingen (presets) te kiezen: focus, ontspanning, default
- Inzicht te krijgen in de huidige status van de ruimte
- Later: automatische aanpassingen op basis van AI-inzichten (Pulse)

## ⚙️ Stack
- React + Vite (snelle dev)
- Tailwind CSS (stijl)
- Firebase (later voor realtime data)
- Optioneel: Netlify/Vercel voor deploy

## 🧱 Structuur
```bash
📁 acaai-lambda-ui
├── README.md               # Projectuitleg, setup en visie
├── /public                 # Statics zoals icoontjes, logo, fonts
├── /src
│   ├── /components         # UI elementen (Slider, Knoppen)
│   ├── /pages              # Home, Dashboard, Settings
│   ├── /styles             # Tailwind config of extra CSS
│   ├── /logic              # Comfortregels, simulatie-logica
│   ├── /data               # Dummy JSON-data voor MVP
│   └── /lib                # Helper-functies, presets
├── tailwind.config.js     # Stylingconfig
├── package.json           # Dependencies & projectmetadata
└── .gitignore             # Node_modules, build etc
```

## 🚀 Installatie
```bash
git clone https://github.com/acaaidev/acaai-lambda-ui.git
cd acaai-lambda-ui
npm install
npm run dev
```

## 🧠 Volgende stappen
- Slider-component bouwen + logica koppelen aan presets
- Dummydata simuleren in `/data`
- Regelgebaseerde logica in `/logic`
- Eerste connectie met Firebase of andere databron

## 📌 Licentie
Private (ACAΛI dev team) – niet openbaar te gebruiken zonder toestemming.

---

Meer info of toegang? Contacteer arnaud@acaaigroup.com
