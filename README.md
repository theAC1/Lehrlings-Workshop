<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>README - Das 3. Standbein (R. Brunner AG)</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&family=Oswald:wght@500;700&display=swap');
        
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f9fafb;
            color: #1f2937;
        }
        h1, h2, h3, .brand-font {
            font-family: 'Oswald', sans-serif;
        }
    </style>
</head>
<body class="p-8 md:p-12 max-w-4xl mx-auto">

    <!-- Header -->
    <header class="mb-12 border-b-4 border-orange-600 pb-6">
        <h1 class="text-4xl md:text-5xl font-bold text-gray-900 mb-2">Pitch-Deck: Das 3. Standbein</h1>
        <p class="text-xl text-gray-500">R. Brunner AG - Ausbildungskonzept</p>
    </header>

    <!-- Intro -->
    <section class="mb-12">
        <p class="text-lg leading-relaxed text-gray-700">
            Dieses Repository enthält die interaktive Präsentations-Website ("Pitch-Deck") für das neue Ausbildungskonzept der Lehrlings-Workshops.
            Die Website wurde entwickelt, um der Geschäftsleitung in einer 20-30 minütigen Sitzung die Idee, den Nutzen und die Umsetzung des "3. Standbeins" (Betriebsspezifische Workshops) visuell ansprechend vorzustellen.
        </p>
    </section>

    <!-- Goal -->
    <section class="mb-12 bg-white p-8 rounded-xl shadow-sm border border-gray-200">
        <h2 class="text-2xl font-bold mb-4 flex items-center text-orange-700">
            <i class="fas fa-bullseye mr-3"></i> Ziel des Projekts
        </h2>
        <p class="mb-4">Einführung monatlicher Workshops (Theorie & Praxis) für alle Lernenden (Schreiner & Zeichner), um:</p>
        <ul class="list-disc pl-6 space-y-2 text-gray-700">
            <li>Schulwissen mit betriebsspezifischen Prozessen zu verknüpfen.</li>
            <li>Einen homogenen Wissensstand im Team zu sichern.</li>
            <li>Die Identifikation mit dem Betrieb zu stärken.</li>
        </ul>
    </section>

    <!-- Tech Stack -->
    <section class="mb-12">
        <h2 class="text-2xl font-bold mb-4 flex items-center text-gray-800">
            <i class="fas fa-tools mr-3"></i> Technologien
        </h2>
        <div class="grid md:grid-cols-2 gap-4">
            <div class="bg-gray-100 p-4 rounded-lg">
                <span class="font-bold block">HTML5</span>
                <span class="text-sm text-gray-600">Single Page Application Struktur</span>
            </div>
            <div class="bg-gray-100 p-4 rounded-lg">
                <span class="font-bold block">Tailwind CSS</span>
                <span class="text-sm text-gray-600">Styling via CDN für schnelles Prototyping</span>
            </div>
            <div class="bg-gray-100 p-4 rounded-lg">
                <span class="font-bold block">FontAwesome</span>
                <span class="text-sm text-gray-600">Icons für visuelle Unterstützung</span>
            </div>
            <div class="bg-gray-100 p-4 rounded-lg">
                <span class="font-bold block">Google Fonts</span>
                <span class="text-sm text-gray-600">Oswald & Inter für Typografie</span>
            </div>
        </div>
    </section>

    <!-- Usage -->
    <section class="mb-12 bg-gray-900 text-white p-8 rounded-xl shadow-lg">
        <h2 class="text-2xl font-bold mb-6 flex items-center text-orange-400">
            <i class="fas fa-rocket mr-3"></i> Nutzung
        </h2>
        <ol class="space-y-4 list-decimal pl-6">
            <li class="pl-2">Lade die Datei <code class="bg-gray-800 px-2 py-1 rounded text-orange-200">Pitch_Lehrlingsworkshops.html</code> herunter.</li>
            <li class="pl-2">Lege dein Firmenlogo unter dem Namen <code class="bg-gray-800 px-2 py-1 rounded text-orange-200">logo.png</code> im selben Ordner ab (optional).</li>
            <li class="pl-2">Öffne die HTML-Datei in einem beliebigen modernen Browser (Chrome, Edge, Firefox).</li>
            <li class="pl-2">Nutze die Navigation oder scrolle durch die Sektionen, um durch den Pitch zu führen.</li>
        </ol>
        
        <div class="mt-8 pt-6 border-t border-gray-700">
            <a href="Pitch_Lehrlingsworkshops.html" class="inline-flex items-center bg-orange-600 hover:bg-orange-700 text-white font-bold py-2 px-6 rounded transition">
                <i class="fas fa-play mr-2"></i> Pitch jetzt öffnen
            </a>
        </div>
    </section>

    <!-- Structure -->
    <section class="mb-12">
        <h2 class="text-2xl font-bold mb-4 flex items-center text-gray-800">
            <i class="fas fa-folder-open mr-3"></i> Struktur des Pitchs
        </h2>
        <ul class="space-y-3">
            <li class="flex items-start">
                <span class="font-bold text-gray-900 min-w-[150px]">1. Ausgangslage:</span>
                <span class="text-gray-600">Das "fehlende Glied" zwischen Schule und Alltag.</span>
            </li>
            <li class="flex items-start">
                <span class="font-bold text-gray-900 min-w-[150px]">2. Konzept:</span>
                <span class="text-gray-600">Ablauf eines Abends (Theorie, Test, Praxis).</span>
            </li>
            <li class="flex items-start">
                <span class="font-bold text-gray-900 min-w-[150px]">3. Themen:</span>
                <span class="text-gray-600">Interaktive Kacheln zu den Modulen (Massivholz, Hi-Macs, etc.).</span>
            </li>
            <li class="flex items-start">
                <span class="font-bold text-gray-900 min-w-[150px]">4. Mehrwert:</span>
                <span class="text-gray-600">Vorteile für Betrieb und Unternehmenskultur.</span>
            </li>
            <li class="flex items-start">
                <span class="font-bold text-gray-900 min-w-[150px]">5. Umsetzung:</span>
                <span class="text-gray-600">Fakten zu Zeitaufwand, Kosten und rechtlichen Schritten.</span>
            </li>
        </ul>
    </section>

    <!-- Footer / Authors -->
    <footer class="mt-20 pt-10 border-t border-gray-300 text-center md:text-left flex flex-col md:flex-row justify-between items-center text-sm text-gray-500">
        <div class="mb-4 md:mb-0">
            <p class="font-bold text-gray-900 mb-1">Verantwortliche</p>
            <p>Juan Hausherr (Projektleiter Innovation)</p>
            <p>Julian Mosimann (Produktionsleiter Stv.)</p>
        </div>
        <div class="text-right">
            <p class="mb-1">Internes Dokument</p>
            <p class="font-bold">Stand Januar 2026</p>
        </div>
    </footer>

</body>
</html>
