<!DOCTYPE html>
<html lang="es" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Producto Exclusive — Landing Page</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts: Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Inter', sans-serif; }
        .glass-panel {
            background: rgba(255, 255, 255, 0.03);
            backdrop-filter: blur(16px);
            border: 1px solid rgba(255, 255, 255, 0.08);
        }
        .glow-effect {
            box-shadow: 0 0 50px -10px rgba(99, 102, 241, 0.3);
        }
    </style>
</head>
<body class="bg-slate-950 text-slate-100 antialiased overflow-x-hidden">

    <!-- Ambient Gradient Background -->
    <div class="fixed top-0 left-1/2 -translate-x-1/2 w-[800px] h-[400px] bg-gradient-to-tr from-indigo-600/20 to-purple-600/20 blur-[140px] pointer-events-none -z-10 rounded-full"></div>

    <!-- Header / Navbar -->
    <header class="fixed top-0 left-0 right-0 z-50 glass-panel border-b border-slate-800/50">
        <div class="max-w-7xl mx-auto px-6 h-20 flex items-center justify-between">
            <a href="#" class="text-2xl font-extrabold tracking-wider bg-gradient-to-r from-white via-slate-200 to-indigo-400 bg-clip-text text-transparent">
                KREA<span class="text-indigo-500">.</span>
            </a>
            <nav class="hidden md:flex items-center space-x-8 text-sm font-medium text-slate-300">
                <a href="#inicio" class="hover:text-white transition-colors">Inicio</a>
                <a href="#caracteristicas" class="hover:text-white transition-colors">Características</a>
                <a href="#beneficios" class="hover:text-white transition-colors">Beneficios</a>
                <a href="#contacto" class="hover:text-white transition-colors">Contacto</a>
            </nav>
            <a href="#comprar" class="px-5 py-2.5 rounded-full text-sm font-semibold bg-indigo-600 hover:bg-indigo-500 text-white shadow-lg shadow-indigo-600/30 transition-all hover:scale-[1.02]">
                Obtener Ahora
            </a>
        </div>
    </header>

    <!-- Hero Section (Usando 1000303267.jpg) -->
    <section id="inicio" class="pt-32 pb-20 md:pt-44 md:pb-32 max-w-7xl mx-auto px-6 grid md:grid-cols-2 gap-12 items-center">
        <div class="space-y-6">
            <div class="inline-flex items-center gap-2 px-3 py-1.5 rounded-full glass-panel text-xs font-medium text-indigo-300">
                <span class="w-2 h-2 rounded-full bg-indigo-400 animate-pulse"></span>
                Nuevo Lanzamiento Exclusivo
            </div>
            <h1 class="text-4xl sm:text-6xl font-extrabold tracking-tight text-white leading-[1.1]">
                Redefiniendo la <span class="bg-gradient-to-r from-indigo-400 via-purple-300 to-pink-400 bg-clip-text text-transparent">excelencia</span> y el diseño.
            </h1>
            <p class="text-slate-400 text-lg leading-relaxed font-normal">
                Descubre una experiencia sin precedentes donde la innovación tecnológica y la estética minimalista se unen para ofrecer resultados extraordinarios.
            </p>
            <div class="pt-4 flex flex-col sm:flex-row gap-4">
                <a href="#comprar" class="px-8 py-4 rounded-xl font-semibold bg-white text-slate-950 hover:bg-slate-200 transition-all text-center shadow-xl hover:shadow-2xl">
                    Comprar Producto
                </a>
                <a href="#caracteristicas" class="px-8 py-4 rounded-xl font-semibold glass-panel text-white hover:bg-white/10 transition-all text-center">
                    Explorar Más
                </a>
            </div>
            <!-- Social Proof -->
            <div class="pt-6 flex items-center gap-6 text-slate-400 text-sm">
                <div class="flex -space-x-2">
                    <div class="w-8 h-8 rounded-full bg-slate-700 border-2 border-slate-950 flex items-center justify-center text-xs font-bold text-white">4.9★</div>
                </div>
                <span>Más de <strong>10,000+</strong> clientes satisfechos</span>
            </div>
        </div>
        
        <!-- Hero Image Frame -->
        <div class="relative group">
            <div class="absolute -inset-1 bg-gradient-to-r from-indigo-500 to-purple-600 rounded-3xl blur-2xl opacity-25 group-hover:opacity-40 transition duration-1000"></div>
            <div class="relative rounded-2xl overflow-hidden glass-panel p-3 border border-slate-800">
                <img src="1000303267.jpg" alt="Producto Principal" class="w-full h-auto object-cover rounded-xl shadow-2xl transition-transform duration-700 group-hover:scale-[1.02]">
            </div>
        </div>
    </section>

    <!-- Stat Counter -->
    <section class="border-y border-slate-800/80 bg-slate-900/30 backdrop-blur-md">
        <div class="max-w-7xl mx-auto px-6 py-12 grid grid-cols-2 md:grid-cols-4 gap-8 text-center">
            <div>
                <p class="text-3xl font-bold text-white">99.8%</p>
                <p class="text-slate-400 text-sm mt-1">Precisión y Calidad</p>
            </div>
            <div>
                <p class="text-3xl font-bold text-white">24/7</p>
                <p class="text-slate-400 text-sm mt-1">Soporte Premium</p>
            </div>
            <div>
                <p class="text-3xl font-bold text-white">+50k</p>
                <p class="text-slate-400 text-sm mt-1">Unidades Vendidas</p>
            </div>
            <div>
                <p class="text-3xl font-bold text-white">100%</p>
                <p class="text-slate-400 text-sm mt-1">Garantía de Satisfacción</p>
            </div>
        </div>
    </section>

    <!-- Features Section (Usando 1000303268.png) -->
    <section id="caracteristicas" class="py-24 max-w-7xl mx-auto px-6">
        <div class="text-center max-w-3xl mx-auto mb-16 space-y-4">
            <h2 class="text-xs font-bold tracking-widest text-indigo-400 uppercase">Detalles Excepcionales</h2>
            <p class="text-3xl sm:text-5xl font-extrabold text-white">Diseñado con precisión en cada ángulo.</p>
        </div>

        <div class="grid md:grid-cols-2 gap-12 items-center">
            <!-- Image Showcase 2 -->
            <div class="relative order-2 md:order-1">
                <div class="absolute -inset-1 bg-gradient-to-r from-purple-600 to-indigo-500 rounded-3xl blur-xl opacity-20"></div>
                <div class="relative rounded-2xl overflow-hidden glass-panel p-3 border border-slate-800">
                    <img src="1000303268.png" alt="Detalle de Producto" class="w-full h-auto object-cover rounded-xl shadow-xl">
                </div>
            </div>

            <!-- Feature List -->
            <div class="space-y-8 order-1 md:order-2">
                <div class="flex gap-4 items-start">
                    <div class="w-12 h-12 rounded-xl bg-indigo-600/20 border border-indigo-500/30 flex items-center justify-center text-indigo-400 shrink-0 font-bold">
                        01
                    </div>
                    <div>
                        <h3 class="text-xl font-bold text-white">Materiales de Alta Gama</h3>
                        <p class="text-slate-400 mt-2 leading-relaxed">Fabricado meticulosamente utilizando los estándares más exigentes de durabilidad y elegancia táctil.</p>
                    </div>
                </div>

                <div class="flex gap-4 items-start">
                    <div class="w-12 h-12 rounded-xl bg-purple-600/20 border border-purple-500/30 flex items-center justify-center text-purple-400 shrink-0 font-bold">
                        02
                    </div>
                    <div>
                        <h3 class="text-xl font-bold text-white">Ergonomía & Estética</h3>
                        <p class="text-slate-400 mt-2 leading-relaxed">Pensado para integrarse perfectamente en tu estilo de vida diario con una presencia sofisticada.</p>
                    </div>
                </div>

                <div class="flex gap-4 items-start">
                    <div class="w-12 h-12 rounded-xl bg-pink-600/20 border border-pink-500/30 flex items-center justify-center text-pink-400 shrink-0 font-bold">
                        03
                    </div>
                    <div>
                        <h3 class="text-xl font-bold text-white">Rendimiento Incomparable</h3>
                        <p class="text-slate-400 mt-2 leading-relaxed">Optimizado para ofrecer la máxima eficiencia sin comprometer el estilo ni la funcionalidad.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Call to Action Banner -->
    <section id="comprar" class="py-20 max-w-7xl mx-auto px-6">
        <div class="relative rounded-3xl glass-panel p-10 md:p-16 text-center border border-slate-800 overflow-hidden glow-effect">
            <div class="absolute inset-0 bg-gradient-to-r from-indigo-900/30 via-slate-900/50 to-purple-900/30 -z-10"></div>
            <h2 class="text-3xl sm:text-5xl font-extrabold text-white mb-6">¿Listo para elevar tu experiencia?</h2>
            <p class="text-slate-300 max-w-2xl mx-auto text-lg mb-8">Consigue la edición limitada hoy mismo con envío gratuito a todo el mundo y garantía extendida.</p>
            <a href="#" class="inline-block px-10 py-4 rounded-xl font-bold bg-indigo-600 hover:bg-indigo-500 text-white shadow-xl shadow-indigo-600/40 transition-all hover:scale-105">
                Realizar Pedido Ahora
            </a>
        </div>
    </section>

    <!-- Footer -->
    <footer class="border-t border-slate-800/80 py-12 text-center text-slate-500 text-sm">
        <div class="max-w-7xl mx-auto px-6 flex flex-col md:flex-row items-center justify-between gap-4">
            <p>© 2026 KREA. Todos los derechos reservados.</p>
            <div class="flex space-x-6">
                <a href="#" class="hover:text-slate-300">Privacidad</a>
                <a href="#" class="hover:text-slate-300">Términos</a>
                <a href="#" class="hover:text-slate-300">Soporte</a>
            </div>
        </div>
    </footer>

</body>
</html>
