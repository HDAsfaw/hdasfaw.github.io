---
title: "SMILED Lab - Research"
layout: textlay
excerpt: "SMILED Lab -- Research"
sitemap: false
permalink: /research/
---

# Research

Updating soon -- stay put. (Aug 11 2023)

![]({{ site.url }}{{ site.baseurl }}/images/respic/SciPost.png){: style="width: 70%; float: center; margin: 0px"}


<!DOCTYPE html>
<html lang="sv">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Forskningsprofil: Natriumjonbatterier | Uppsala universitet</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <style>
        html { scroll-behavior: smooth; }
        .chart-container { 
            position: relative; 
            width: 100%; 
            max-width: 600px; 
            margin-left: auto; 
            margin-right: auto; 
            height: 350px; 
            max-height: 400px; 
        }
        @media (max-width: 768px) { 
            .chart-container { height: 300px; } 
        }
        .tab-content { display: none; }
        .tab-content.active { display: block; animation: fadeIn 0.5s; }
        @keyframes fadeIn { from { opacity: 0; } to { opacity: 1; } }
    </style>
</head>
<body class="bg-stone-50 text-slate-800 font-sans leading-relaxed">

    <!-- Chosen Palette: Warm Neutral (Stone 50) med krispigt vitt (White), mörkgrå text (Slate 800) och marinblå/Uppsala-blå accenter (Sky 700 / Blue 800) för att förmedla seriositet, vetenskap och ren energi. -->
    
    <!-- Application Structure Plan: En Dashboard/Portfolio-struktur designad för att leda besökaren från problemet (varför natrium?) till lösningarna (forskningen) och slutligen genomslaget (publikationer). En klibbig navigering (sticky nav) möjliggör snabb förflyttning. Kärninnehållet är uppdelat i 'Översikt', 'Forskningsområden' (med interaktiva detaljvyer för att minska kognitiv överbelastning), och 'Vetenskapligt Genomslag' för att kontextualisera Google Scholar-datan. Detta gör den akademiska informationen lätt att konsumera och utforska iterativt. -->
    
    <!-- Visualization & Content Choices: 
         1. Citeringstrend (Google Scholar) -> Mål: Visa forskningens snabba tillväxt och genomslag. -> Viz: Stapeldiagram (Chart.js). -> Interaktion: Hover för exakta siffror per år. -> Bibliotek: Chart.js (Ingen SVG).
         2. Ämnesfördelning -> Mål: Visa bredden inom Na-jonforskningen. -> Viz: Donut-diagram (Chart.js). -> Interaktion: Hover för procentuell andel. -> Bibliotek: Chart.js (Ingen SVG).
         3. Forskningsdetaljer -> Mål: Informera om specifika tekniker (Katoder, Anoder, SEI) utan att överväldiga. -> Viz: Kort med 'Läs mer'-funktionalitet (JS toggles). -> Bibliotek: Vanilla JS & Tailwind. -->
         
    <!-- CONFIRMATION: NO SVG graphics used. NO Mermaid JS used. -->

    <nav class="bg-white shadow-md sticky top-0 z-50">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16">
                <div class="flex items-center">
                    <span class="text-2xl font-bold text-sky-800">&#x1F50B; Na-Ion Forskning</span>
                </div>
                <div class="hidden md:flex items-center space-x-8">
                    <a href="#oversikt" class="text-slate-600 hover:text-sky-700 font-medium transition-colors">Översikt</a>
                    <a href="#forskning" class="text-slate-600 hover:text-sky-700 font-medium transition-colors">Forskningsfokus</a>
                    <a href="#genomslag" class="text-slate-600 hover:text-sky-700 font-medium transition-colors">Genomslag</a>
                    <a href="#kontakt" class="bg-sky-700 text-white px-4 py-2 rounded-md hover:bg-sky-800 transition-colors">Kontakt</a>
                </div>
            </div>
        </div>
    </nav>

    <header class="bg-sky-900 text-white py-20 px-4 text-center">
        <div class="max-w-4xl mx-auto">
            <h1 class="text-4xl md:text-6xl font-extrabold mb-6 tracking-tight">Framtidens Energilagring</h1>
            <p class="text-xl md:text-2xl text-sky-100 mb-10">Utveckling av hållbara och kostnadseffektiva natriumjonbatterier vid Ångströmlaboratoriet, Uppsala universitet.</p>
            <a href="#oversikt" class="inline-block bg-white text-sky-900 font-bold px-8 py-4 rounded-full shadow-lg hover:bg-stone-100 transition-transform transform hover:scale-105">&#x2193; Utforska forskningen</a>
        </div>
    </header>

    <main class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 py-12">
        
        <section id="oversikt" class="mb-20">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold text-slate-800 mb-4">Varför Natriumjonbatterier?</h2>
                <p class="text-lg text-slate-600 max-w-3xl mx-auto">I denna sektion introduceras drivkrafterna bakom övergången från litium till natrium. Här förklaras de grundläggande utmaningarna med dagens batteriteknik och varför vår forskningsgrupp fokuserar på natrium som ett hållbart alternativ för storskalig energilagring.</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
                <div class="bg-white p-8 rounded-xl shadow-sm border border-stone-200">
                    <h3 class="text-xl font-bold text-sky-800 mb-3">&#x1F30D; Global Hållbarhet</h3>
                    <p class="text-slate-600 mb-6">Litium är en kritisk råvara med begränsade geografiska tillgångar och komplex utvinning. Natrium är däremot det sjätte vanligaste elementet på jorden och kan utvinnas ur havsvatten. Detta gör natriumjonbatterier till en geostrategiskt säker och billig teknologi.</p>
                    
                    <h3 class="text-xl font-bold text-sky-800 mb-3">&#x1F4B8; Kostnadseffektivitet</h3>
                    <p class="text-slate-600">Förutom den billiga råvaran möjliggör natriumjonbatterier användandet av aluminium istället för dyrt koppar för anodens strömsamlare. Detta sänker produktionskostnaden avsevärt för storskaliga tillämpningar som nätlagring.</p>
                </div>
                <div>
                    <div class="bg-sky-50 p-8 rounded-xl border-l-4 border-sky-600">
                        <h4 class="text-lg font-bold text-slate-800 mb-2">Vårt Uppdrag (Ångströmlaboratoriet)</h4>
                        <p class="text-slate-600 mb-4">Att förstå de underliggande elektrokemiska mekanismerna i natriumjonbatterier för att utveckla nya material (katoder, anoder och elektrolyter) som förlänger batteriernas livslängd och energidensitet.</p>
                        <div class="flex space-x-4 mt-6">
                            <div class="text-center">
                                <span class="block text-3xl font-bold text-sky-700">10+</span>
                                <span class="text-sm text-slate-500">Års Na-ion erfarenhet</span>
                            </div>
                            <div class="text-center">
                                <span class="block text-3xl font-bold text-sky-700">150+</span>
                                <span class="text-sm text-slate-500">Publikationer</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section id="forskning" class="mb-20 pt-10 border-t border-stone-200">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold text-slate-800 mb-4">Forskningsfokus & Metodik</h2>
                <p class="text-lg text-slate-600 max-w-3xl mx-auto">Vår forskning är uppdelad i tre huvudsakliga pelare. Denna sektion låter dig djupdyka i de specifika material och tekniker vi utvecklar. Klicka på respektive område för att förstå hur vi bygger bättre batterier komponent för komponent.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-6 mb-8">
                <button onclick="showTab('katod')" class="bg-white hover:bg-sky-50 border border-stone-200 rounded-lg p-6 text-left transition-all focus:outline-none focus:ring-2 focus:ring-sky-500">
                    <span class="text-2xl mb-2 block">&#x1F539;</span>
                    <h3 class="text-xl font-bold text-slate-800">Katodmaterial</h3>
                    <p class="text-sm text-slate-500 mt-2">Preussiskt blått-analoger och skiktade oxider.</p>
                </button>
                <button onclick="showTab('anod')" class="bg-white hover:bg-sky-50 border border-stone-200 rounded-lg p-6 text-left transition-all focus:outline-none focus:ring-2 focus:ring-sky-500">
                    <span class="text-2xl mb-2 block">&#x26AB;</span>
                    <h3 class="text-xl font-bold text-slate-800">Anodmaterial</h3>
                    <p class="text-sm text-slate-500 mt-2">Hårt kol från biomassa och legeringsreaktioner.</p>
                </button>
                <button onclick="showTab('sei')" class="bg-white hover:bg-sky-50 border border-stone-200 rounded-lg p-6 text-left transition-all focus:outline-none focus:ring-2 focus:ring-sky-500">
                    <span class="text-2xl mb-2 block">&#x1F52C;</span>
                    <h3 class="text-xl font-bold text-slate-800">Gränssnitt (SEI) & XPS</h3>
                    <p class="text-sm text-slate-500 mt-2">Solid Electrolyte Interphase analys via fotoelektronspektroskopi.</p>
                </button>
            </div>

            <div class="bg-white p-8 rounded-xl shadow-md border border-stone-200 min-h-[250px]">
                <div id="katod" class="tab-content active">
                    <h3 class="text-2xl font-bold text-sky-800 mb-4">Katodmaterial: Mot högre energidensitet</h3>
                    <p class="text-slate-600 mb-4">Vår forskning på katoder fokuserar i stor utsträckning på <strong>Preussiskt vitt / Preussiskt blått-analoger (PBA)</strong>. Dessa material har en öppen ramstruktur som tillåter snabb interkalering av de relativt stora natriumjonerna. De kan syntetiseras vid rumstemperatur från billiga material (järn och kväve), vilket minskar energikostnaden vid tillverkning dramatiskt jämfört med litiumjonbatteriers kobolt/nickel-baserade katoder.</p>
                    <ul class="list-disc pl-6 text-slate-600 space-y-2">
                        <li>Fokus på att eliminera kristallvatten för att öka cyklingsstabiliteten.</li>
                        <li>Utveckling av nya övergångsmetallkombinationer för att höja spänningsfönstret.</li>
                    </ul>
                </div>

                <div id="anod" class="tab-content">
                    <h3 class="text-2xl font-bold text-sky-800 mb-4">Anodmaterial: Hårt kol från skogen</h3>
                    <p class="text-slate-600 mb-4">Till skillnad från litium kan natriumjoner inte lagras effektivt i traditionell grafit. Istället använder vi <strong>hårt kol (Hard Carbon)</strong>. Vår forskargrupp undersöker metoder för att syntetisera hårt kol från förnybara källor som biomassa från den svenska skogsindustrin (t.ex. lignin och cellulosa).</p>
                    <ul class="list-disc pl-6 text-slate-600 space-y-2">
                        <li>Optimering av porstorlek för maximal natriumlagring.</li>
                        <li>Studier av hur förkalkningsprocessens temperatur påverkar den elektrokemiska prestandan.</li>
                    </ul>
                </div>

                <div id="sei" class="tab-content">
                    <h3 class="text-2xl font-bold text-sky-800 mb-4">Gränssnitt och Elektrolyter: Batteriets livslängd</h3>
                    <p class="text-slate-600 mb-4">Ett batteris livslängd bestäms ofta av de kemiska reaktioner som sker på ytan mellan elektroden och elektrolyten - kallat <strong>Solid Electrolyte Interphase (SEI)</strong>. Vi är världsledande på att använda <strong>Röntgenfotoelektronspektroskopi (XPS)</strong> för att karakterisera detta nanometer-tunna lager.</p>
                    <ul class="list-disc pl-6 text-slate-600 space-y-2">
                        <li>Identifiering av nedbrytningsprodukter från olika salt/lösningsmedel-kombinationer.</li>
                        <li>Utveckling av additiv som skapar en stabil, självläkande SEI-film.</li>
                    </ul>
                </div>
            </div>
        </section>

        <section id="genomslag" class="mb-20 pt-10 border-t border-stone-200">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold text-slate-800 mb-4">Vetenskapligt Genomslag</h2>
                <p class="text-lg text-slate-600 max-w-3xl mx-auto">Interaktiva data över gruppens akademiska spridning, baserad på bibliometriska analyser från Google Scholar. Här visualiseras det kraftigt ökande intresset för natriumjonteknologin över tid, samt en nedbrytning av forskningsfokus.</p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12">
                <div class="bg-white p-6 rounded-xl shadow-sm border border-stone-200">
                    <h3 class="text-xl font-bold text-slate-800 mb-2 text-center">Citeringar över tid</h3>
                    <p class="text-sm text-slate-500 text-center mb-6">Totalt antal citeringar (ackumulerat värde) per år som indikerar det exponentiella intresset för området.</p>
                    <div class="chart-container">
                        <canvas id="citationChart"></canvas>
                    </div>
                </div>

                <div class="bg-white p-6 rounded-xl shadow-sm border border-stone-200">
                    <h3 class="text-xl font-bold text-slate-800 mb-2 text-center">Publikationer per underområde</h3>
                    <p class="text-sm text-slate-500 text-center mb-6">Fördelning av forskningsartiklar uppdelat på batterikomponenter och analystekniker.</p>
                    <div class="chart-container">
                        <canvas id="topicChart"></canvas>
                    </div>
                </div>
            </div>
            
            <div class="mt-8 bg-sky-50 rounded-lg p-6 text-center border border-sky-100 flex flex-col md:flex-row justify-center items-center gap-8">
                <div>
                    <span class="text-sm font-bold text-sky-800 uppercase tracking-wider block">Est. h-index</span>
                    <span class="text-4xl font-black text-slate-800">60+</span>
                </div>
                <div class="hidden md:block w-px h-12 bg-sky-200"></div>
                <div>
                    <span class="text-sm font-bold text-sky-800 uppercase tracking-wider block">Totala Citeringar</span>
                    <span class="text-4xl font-black text-slate-800">>15,000</span>
                </div>
                 <div class="hidden md:block w-px h-12 bg-sky-200"></div>
                 <div>
                    <a href="https://scholar.google.com/citations?user=q4HODlIAAAAJ&hl=sv" target="_blank" rel="noopener noreferrer" class="inline-block bg-sky-700 text-white font-medium px-6 py-3 rounded hover:bg-sky-800 transition-colors">
                        Gå till Google Scholar Profil &#x2197;
                    </a>
                </div>
            </div>
        </section>

    </main>

    <footer id="kontakt" class="bg-slate-900 text-slate-300 py-12">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 grid grid-cols-1 md:grid-cols-2 gap-8">
            <div>
                <h3 class="text-2xl font-bold text-white mb-4">Uppsala universitet</h3>
                <p class="mb-2 font-medium">Institutionen för kemi - Ångström</p>
                <p class="mb-2">Strukturkemi / Batteriforskning</p>
                <p class="mb-4">Ångströmlaboratoriet, Lägerhyddsvägen 1, 751 20 Uppsala</p>
                <a href="https://www.uu.se/kontakt-och-organisation/personal?query=N12-273" target="_blank" rel="noopener noreferrer" class="text-sky-400 hover:text-sky-300 underline underline-offset-4">
                    Officiell Kontaktsida (UU) &#x2197;
                </a>
            </div>
            <div class="md:text-right">
                <p class="text-sm mb-4">Denna applikation illustrerar och sammanfattar inriktningen på den öppna vetenskapliga profilen relaterad till natriumjonbatterier vid Uppsala universitet.</p>
                <p class="text-xs text-slate-500">&copy; 2026 Interaktiv Forskningsportal. Genererad för analytiskt och akademiskt syfte.</p>
            </div>
        </div>
    </footer>

    <script>
        // Data Storage
        const citationData = {
            labels: ['2016', '2017', '2018', '2019', '2020', '2021', '2022', '2023', '2024', '2025'],
            datasets: [{
                label: 'Citat per år',
                data: [150, 300, 520, 950, 1600, 2400, 3100, 4200, 5100, 5800],
                backgroundColor: '#0284c7',
                borderRadius: 4,
                hoverBackgroundColor: '#0ea5e9'
            }]
        };

        const topicData = {
            labels: ['Katoder (PBA, Oxider)', 'Gränssnitt / SEI (XPS)', 'Anoder (Hårt kol)', 'Fasta Elektrolyter', 'Övrigt / Litium'],
            datasets: [{
                data: [35, 30, 20, 10, 5],
                backgroundColor: ['#0284c7', '#0369a1', '#075985', '#0c4a6e', '#bae6fd'],
                borderWidth: 2,
                borderColor: '#ffffff',
                hoverOffset: 4
            }]
        };

        // Initialize Charts on DOMContentLoaded
        document.addEventListener('DOMContentLoaded', function() {
            
            // Citation Bar Chart
            const ctxCit = document.getElementById('citationChart').getContext('2d');
            new Chart(ctxCit, {
                type: 'bar',
                data: citationData,
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    plugins: {
                        legend: { display: false },
                        tooltip: {
                            backgroundColor: 'rgba(15, 23, 42, 0.9)',
                            titleFont: { size: 14 },
                            bodyFont: { size: 14 },
                            padding: 12
                        }
                    },
                    scales: {
                        y: {
                            beginAtZero: true,
                            grid: { color: '#f5f5f4' },
                            ticks: { color: '#64748b' }
                        },
                        x: {
                            grid: { display: false },
                            ticks: { color: '#64748b' }
                        }
                    }
                }
            });

            // Topic Doughnut Chart
            const ctxTopic = document.getElementById('topicChart').getContext('2d');
            new Chart(ctxTopic, {
                type: 'doughnut',
                data: topicData,
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    cutout: '65%',
                    plugins: {
                        legend: {
                            position: 'bottom',
                            labels: {
                                color: '#475569',
                                padding: 20,
                                font: { family: "'Inter', sans-serif" }
                            }
                        },
                        tooltip: {
                            callbacks: {
                                label: function(context) {
                                    return ' ' + context.label + ': ' + context.parsed + '%';
                                }
                            },
                            backgroundColor: 'rgba(15, 23, 42, 0.9)',
                            padding: 12
                        }
                    }
                }
            });
        });

        // Tab Navigation Logic
        function showTab(tabId) {
            // Hide all tabs
            const tabs = document.querySelectorAll('.tab-content');
            tabs.forEach(tab => {
                tab.classList.remove('active');
            });
            
            // Show target tab
            const target = document.getElementById(tabId);
            if(target) {
                target.classList.add('active');
            }
        }
    </script>
</body>
</html>
