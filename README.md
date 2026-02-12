<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Documentación - Sorpresa Romántica</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Comfortaa:wght@300;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Comfortaa', cursive;
            background-color: #0f172a;
            color: #f0faff;
        }
        .glass {
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        code {
            background: rgba(0, 0, 0, 0.3);
            padding: 0.2rem 0.4rem;
            border-radius: 4px;
            font-family: monospace;
            color: #60efff;
        }
        pre {
            background: #000;
            padding: 1.5rem;
            border-radius: 8px;
            overflow-x: auto;
            border: 1px solid #1e293b;
        }
    </style>
</head>
<body class="p-6 md:p-12">
    <div class="max-w-4xl mx-auto glass p-8 md:p-12 rounded-3xl shadow-2xl">
        
        <header class="text-center mb-12">
            <h1 class="text-4xl md:text-6xl font-bold mb-4 bg-clip-text text-transparent bg-gradient-to-r from-aurora-green to-aurora-purple">
                ❄️ Sorpresa Romántica: Akureyri Edition
            </h1>
            <p class="text-lg text-slate-300 leading-relaxed italic">
                Una experiencia web inmersiva de <strong>Storytelling Digital</strong> diseñada para narrar una historia personal y realizar una propuesta interactiva.
            </p>
        </header>

        <section class="mb-12">
            <h2 class="text-2xl font-bold text-aurora-purple mb-6 border-b border-white/10 pb-2">📸 Experiencia de Usuario (UX)</h2>
            <div class="grid md:grid-cols-3 gap-6">
                <div class="bg-white/5 p-6 rounded-2xl">
                    <h3 class="font-bold text-white mb-2">1. El Álbum</h3>
                    <p class="text-sm text-slate-400">Sistema de diapositivas estilo Polaroid con tipografías manuscritas y emojis dinámicos.</p>
                </div>
                <div class="bg-white/5 p-6 rounded-2xl">
                    <h3 class="font-bold text-white mb-2">2. El Clímax</h3>
                    <p class="text-sm text-slate-400">Transición dramática a noche ártica con lógica de evasión en el botón "No".</p>
                </div>
                <div class="bg-white/5 p-6 rounded-2xl">
                    <h3 class="font-bold text-white mb-2">3. La Celebración</h3>
                    <p class="text-sm text-slate-400">Motor de confeti temático y mensaje final tras la confirmación exitosa.</p>
                </div>
            </div>
        </section>

        <section class="mb-12">
            <h2 class="text-2xl font-bold text-aurora-purple mb-6 border-b border-white/10 pb-2">✨ Características Técnicas</h2>
            <ul class="space-y-4">
                <li><strong class="text-aurora-green">Snow Engine (Canvas API):</strong> Sistema de partículas de alto rendimiento para una nevada constante.</li>
                <li><strong class="text-aurora-green">Aurora Borealis Effect:</strong> Fondo animado mediante gradientes lineares y filtros <code>backdrop-filter</code>.</li>
                <li><strong class="text-aurora-green">Lógica de Evasión Inteligente:</strong> Reposicionamiento dinámico mediante <code>getBoundingClientRect()</code>.</li>
                <li><strong class="text-aurora-green">Responsive & Touch Ready:</strong> Optimizado para visualización y gestos en iOS y Android.</li>
            </ul>
        </section>

        <section class="mb-12">
            <h2 class="text-2xl font-bold text-aurora-purple mb-6 border-b border-white/10 pb-2">🏗️ Stack Tecnológico</h2>
            <div class="flex flex-wrap gap-4">
                <span class="px-4 py-2 bg-slate-800 rounded-full text-sm">HTML5 / CSS3</span>
                <span class="px-4 py-2 bg-slate-800 rounded-full text-sm">Tailwind CSS 3.0</span>
                <span class="px-4 py-2 bg-slate-800 rounded-full text-sm">Vanilla JS (ES6+)</span>
                <span class="px-4 py-2 bg-slate-800 rounded-full text-sm">Google Fonts</span>
            </div>
        </section>

        <section class="mb-12">
            <h2 class="text-2xl font-bold text-aurora-purple mb-6 border-b border-white/10 pb-2">🚀 Despliegue Rápido</h2>
            <ol class="list-decimal list-inside space-y-3 text-slate-300">
                <li>Sube el archivo <code>index.html</code> a un nuevo repositorio en GitHub.</li>
                <li>En <code>Settings > Pages</code>, activa la rama <strong>main</strong>.</li>
                <li>Accede a la URL generada por GitHub Pages.</li>
            </ol>
        </section>

        <section class="mb-12">
            <h2 class="text-2xl font-bold text-aurora-purple mb-6 border-b border-white/10 pb-2">⚙️ Personalización</h2>
            <p class="mb-4">Edita el array <code>storyPages</code> en el bloque de JavaScript del index:</p>
            <pre><code class="text-sm text-aurora-green">
const storyPages = [
    { text: "Tu mensaje personalizado", emoji: "❤️" },
    // Añade o quita páginas según necesites
];
            </code></pre>
        </section>

        <footer class="text-center pt-8 border-t border-white/10">
            <p class="text-slate-500 text-sm italic">
                Desarrollado con ❤️ para transformar código en recuerdos.
            </p>
            <p class="mt-2 text-xs opacity-50 text-white">Licencia MIT</p>
        </footer>

    </div>
</body>
</html>
