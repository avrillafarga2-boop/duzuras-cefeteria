
<!DOCTYPE html>
<html lang="es" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dulcuras Pastelería | Repostería Fina & Tortas Personalizadas</title>
    
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,600;0,700;1,400&family=Plus+Jakarta+Sans:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        vanilla: '#FFF9F2',
                        vanilladark: '#F8EFE4',
                        rosepastel: {
                            50: '#FFF5F4',
                            100: '#FCE8E6',
                            200: '#F7D0CC',
                            300: '#F4C2C2',
                            400: '#E89E9E',
                            500: '#D97777',
                            600: '#B85454'
                        },
                        chocolate: {
                            light: '#5A3830',
                            DEFAULT: '#3D231D',
                            dark: '#251410'
                        },
                        caramel: {
                            light: '#E5BD78',
                            DEFAULT: '#D4A359',
                            dark: '#C58B3A'
                        }
                    },
                    fontFamily: {
                        serif: ['Cormorant Garamond', 'Georgia', 'serif'],
                        sans: ['Plus Jakarta Sans', 'sans-serif']
                    },
                    boxShadow: {
                        'glow': '0 0 25px -5px rgba(212, 163, 89, 0.3)',
                        'soft': '0 10px 30px -5px rgba(61, 35, 29, 0.06)',
                        'floating': '0 20px 40px -15px rgba(217, 119, 119, 0.25)'
                    }
                }
            }
        }
    </script>
    
    <style>
        body { background-color: #FFF9F2; color: #3D231D; font-family: 'Plus Jakarta Sans', sans-serif; }
        .glass-card { background: rgba(255, 255, 255, 0.82); backdrop-filter: blur(12px); -webkit-backdrop-filter: blur(12px); border: 1px solid rgba(255, 255, 255, 0.9); }
        .glass-nav { background: rgba(255, 249, 242, 0.9); backdrop-filter: blur(16px); -webkit-backdrop-filter: blur(16px); border-bottom: 1px solid rgba(212, 163, 89, 0.15); }
        .gold-gradient-text { background: linear-gradient(135deg, #C58B3A 0%, #D4A359 50%, #E5BD78 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
        .gold-gradient-bg { background: linear-gradient(135deg, #C58B3A 0%, #D4A359 50%, #E5BD78 100%); }
        @keyframes pulse-glow { 0% { box-shadow: 0 0 0 0 rgba(34, 197, 94, 0.6); } 70% { box-shadow: 0 0 0 18px rgba(34, 197, 94, 0); } 100% { box-shadow: 0 0 0 0 rgba(34, 197, 94, 0); } }
        .whatsapp-pulse { animation: pulse-glow 2s infinite; }
    </style>
</head>
<body class="antialiased selection:bg-rosepastel-200 selection:text-chocolate">

    <!-- BARRA DE NAVEGACIÓN -->
    <header class="sticky top-0 z-50 glass-nav transition-all duration-300">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-20">
                <a href="#hero" class="flex items-center gap-3 group">
                    <div class="w-12 h-12 rounded-full gold-gradient-bg flex items-center justify-center text-white shadow-glow group-hover:scale-105 transition-transform duration-300">
                        <i class="fa-solid fa-cake-candles text-xl"></i>
                    </div>
                    <div class="flex flex-col">
                        <span class="font-serif text-2xl sm:text-3xl font-bold text-chocolate tracking-tight group-hover:text-rosepastel-600 transition-colors">
                            Dulcuras Pastelería
                        </span>
                        <span class="text-[10px] uppercase tracking-[0.25em] text-caramel font-semibold -mt-1">
                            Artesanal & Gourmet
                        </span>
                    </div>
                </a>

                <nav class="hidden lg:flex items-center space-x-8 text-sm font-medium text-chocolate/80">
                    <a href="#hero" class="hover:text-rosepastel-600 transition-colors">Inicio</a>
                    <a href="#catalogo" class="hover:text-rosepastel-600 transition-colors">Catálogo</a>
                    <a href="#cotizador" class="hover:text-rosepastel-600 transition-colors">Cotizador</a>
                    <a href="#contacto" class="hover:text-rosepastel-600 transition-colors">Contacto</a>
                </nav>

                <div class="hidden sm:flex items-center space-x-4">
                    <a href="https://instagram.com/dulcuraspasteleria_" target="_blank" class="w-10 h-10 rounded-full border border-caramel/30 flex items-center justify-center text-chocolate hover:bg-rosepastel-100 transition-colors">
                        <i class="fa-brands fa-instagram text-lg"></i>
                    </a>
                    <a href="https://wa.me/5491131416486?text=%C2%A1Hola%20Dulcuras%20Pasteler%C3%ADa!" target="_blank" class="bg-rosepastel-500 hover:bg-rosepastel-600 text-white font-semibold px-5 py-2.5 rounded-full shadow-floating flex items-center gap-2 text-sm transition-all hover:scale-105">
                        <i class="fa-brands fa-whatsapp text-lg"></i>
                        <span>WhatsApp</span>
                    </a>
                </div>
            </div>
        </div>
    </header>

    <!-- INICIO / HERO -->
    <section id="hero" class="relative pt-12 pb-20 md:py-28 overflow-hidden">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
                <div class="lg:col-span-7 text-center lg:text-left space-y-8">
                    <span class="inline-flex items-center gap-2 px-4 py-1.5 rounded-full bg-rosepastel-100 border border-rosepastel-300 text-chocolate text-xs font-semibold">
                        <i class="fa-solid fa-crown text-caramel"></i> Repostería de Alta Calidad
                    </span>
                    <h1 class="font-serif text-4xl sm:text-6xl font-bold text-chocolate leading-tight">
                        El toque dulce <br>
                        <span class="italic font-normal gold-gradient-text">para tus momentos</span> más especiales.
                    </h1>
                    <p class="text-base sm:text-lg text-chocolate/80 max-w-2xl font-light">
                        Tortas artesanales, budines y delicias hechas a pedido con los mejores ingredientes. Diseños únicos creados con amor y dedicación.
                    </p>
                    <div class="flex flex-col sm:flex-row items-center gap-4 justify-center lg:justify-start">
                        <a href="https://wa.me/5491131416486?text=%C2%A1Hola!%20Quiero%20consultar%20por%20sus%20tortas." target="_blank" class="w-full sm:w-auto bg-rosepastel-500 hover:bg-rosepastel-600 text-white font-semibold px-8 py-4 rounded-full shadow-floating flex items-center justify-center gap-3 transition-all">
                            <i class="fa-brands fa-whatsapp text-2xl"></i>
                            <span>Pedir por WhatsApp</span>
                        </a>
                        <a href="#cotizador" class="w-full sm:w-auto bg-white text-chocolate border border-caramel/40 font-semibold px-7 py-4 rounded-full flex items-center justify-center gap-2 shadow-soft hover:bg-vanilladark transition-colors">
                            <i class="fa-solid fa-calculator text-caramel"></i>
                            <span>Cotizar mi Torta</span>
                        </a>
                    </div>
                </div>
                <div class="lg:col-span-5 relative">
                    <div class="rounded-[2.5rem] overflow-hidden p-3 glass-card shadow-2xl">
                        <img src="https://images.unsplash.com/photo-1535141192574-5d4897c13136?auto=format&fit=crop&w=1000&q=80" alt="Torta Dulcuras" class="w-full h-[400px] object-cover rounded-[2rem]">
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- CATÁLOGO DE PRODUCTOS -->
    <section id="catalogo" class="py-16">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-2xl mx-auto mb-12">
                <span class="text-xs uppercase font-bold text-caramel tracking-widest">Favoritos de la casa</span>
                <h2 class="font-serif text-4xl font-bold text-chocolate mt-1">Nuestro Catálogo</h2>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- Producto 1 -->
                <div class="glass-card rounded-3xl p-5 flex flex-col justify-between hover:-translate-y-2 transition-transform duration-300 shadow-soft">
                    <div>
                        <img src="https://images.unsplash.com/photo-1578985545062-69928b1d9587?auto=format&fit=crop&w=500&q=80" class="w-full h-48 object-cover rounded-2xl mb-4" alt="Chocotorta">
                        <h3 class="font-serif text-xl font-bold text-chocolate">Chocotorta Deluxe</h3>
                        <p class="text-xs text-chocolate/70 mt-2">Capas húmedas de chocolinas, dulce de leche repostero y queso crema suave.</p>
                    </div>
                    <div class="mt-6 pt-4 border-t border-caramel/20 flex items-center justify-between">
                        <span class="font-bold text-lg text-caramel-dark">$18.500</span>
                        <a href="https://wa.me/5491131416486?text=%C2%A1Hola!%20Quiero%20encargar%20una%20Chocotorta%20Deluxe" target="_blank" class="bg-rosepastel-500 hover:bg-rosepastel-600 text-white p-2.5 rounded-full">
                            <i class="fa-brands fa-whatsapp text-lg"></i>
                        </a>
                    </div>
                </div>

                <!-- Producto 2 -->
                <div class="glass-card rounded-3xl p-5 flex flex-col justify-between hover:-translate-y-2 transition-transform duration-300 shadow-soft">
                    <div>
                        <img src="https://images.unsplash.com/photo-1519869325930-281384150729?auto=format&fit=crop&w=500&q=80" class="w-full h-48 object-cover rounded-2xl mb-4" alt="Key Lime Pie">
                        <h3 class="font-serif text-xl font-bold text-chocolate">Key Lime Pie</h3>
                        <p class="text-xs text-chocolate/70 mt-2">Base crujiente, crema suave de lima natural y suave merengue italiano.</p>
                    </div>
                    <div class="mt-6 pt-4 border-t border-caramel/20 flex items-center justify-between">
                        <span class="font-bold text-lg text-caramel-dark">$16.000</span>
                        <a href="https://wa.me/5491131416486?text=%C2%A1Hola!%20Quiero%20encargar%20un%20Key%20Lime%20Pie" target="_blank" class="bg-rosepastel-500 hover:bg-rosepastel-600 text-white p-2.5 rounded-full">
                            <i class="fa-brands fa-whatsapp text-lg"></i>
                        </a>
                    </div>
                </div>

                <!-- Producto 3 -->
                <div class="glass-card rounded-3xl p-5 flex flex-col justify-between hover:-translate-y-2 transition-transform duration-300 shadow-soft">
                    <div>
                        <img src="https://images.unsplash.com/photo-1586985289688-ca3cf47d3e6e?auto=format&fit=crop&w=500&q=80" class="w-full h-48 object-cover rounded-2xl mb-4" alt="Red Velvet">
                        <h3 class="font-serif text-xl font-bold text-chocolate">Red Velvet Cake</h3>
                        <p class="text-xs text-chocolate/70 mt-2">Bizcochuelo rojo aterciopelado con relleno y cobertura de cream cheese.</p>
                    </div>
                    <div class="mt-6 pt-4 border-t border-caramel/20 flex items-center justify-between">
                        <span class="font-bold text-lg text-caramel-dark">$22.000</span>
                        <a href="https://wa.me/5491131416486?text=%C2%A1Hola!%20Quiero%20encargar%20una%20Red%20Velvet" target="_blank" class="bg-rosepastel-500 hover:bg-rosepastel-600 text-white p-2.5 rounded-full">
                            <i class="fa-brands fa-whatsapp text-lg"></i>
                        </a>
                    </div>
                </div>

                <!-- Producto 4 -->
                <div class="glass-card rounded-3xl p-5 flex flex-col justify-between hover:-translate-y-2 transition-transform duration-300 shadow-soft">
                    <div>
                        <img src="https://images.unsplash.com/photo-1558961363-fa8fdf82db35?auto=format&fit=crop&w=500&q=80" class="w-full h-48 object-cover rounded-2xl mb-4" alt="Cookies NY">
                        <h3 class="font-serif text-xl font-bold text-chocolate">Cookies NY Style</h3>
                        <p class="text-xs text-chocolate/70 mt-2">Galletas súper húmedas rellenas de Nutella o Dulce de Leche.</p>
                    </div>
                    <div class="mt-6 pt-4 border-t border-caramel/20 flex items-center justify-between">
                        <span class="font-bold text-lg text-caramel-dark">$3.500 c/u</span>
                        <a href="https://wa.me/5491131416486?text=%C2%A1Hola!%20Quiero%20encargar%20Cookies%20NY" target="_blank" class="bg-rosepastel-500 hover:bg-rosepastel-600 text-white p-2.5 rounded-full">
                            <i class="fa-brands fa-whatsapp text-lg"></i>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- COTIZADOR INTERACTIVO DE TORTAS -->
    <section id="cotizador" class="py-16">
        <div class="max-w-3xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="glass-card rounded-[2.5rem] p-8 sm:p-12 border border-white shadow-2xl">
                <div class="text-center space-y-2 mb-8">
                    <span class="text-xs uppercase font-bold text-caramel tracking-widest">Personalizá a tu gusto</span>
                    <h2 class="font-serif text-3xl sm:text-4xl font-bold text-chocolate">Cotizá tu Torta en Vivo</h2>
                </div>

                <div class="space-y-6">
                    <div>
                        <label class="text-sm font-bold text-chocolate flex justify-between mb-2">
                            <span>¿Para cuántas personas?</span>
                            <span id="guests-val" class="text-rosepastel-600 font-bold">12 invitados</span>
                        </label>
                        <input type="range" id="guests-slider" min="8" max="50" step="2" value="12" oninput="updatePrice()" class="w-full accent-rosepastel-500 cursor-pointer">
                    </div>

                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                        <div>
                            <label class="text-sm font-bold text-chocolate block mb-2">Bizcochuelo:</label>
                            <select id="sponge-select" onchange="updatePrice()" class="w-full bg-white border border-caramel/30 rounded-xl p-3 text-sm focus:outline-none focus:border-rosepastel-500">
                                <option value="1.0">Vainilla Madagascan</option>
                                <option value="1.0">Chocolate Belga</option>
                                <option value="1.1">Red Velvet (+10%)</option>
                            </select>
                        </div>

                        <div>
                            <label class="text-sm font-bold text-chocolate block mb-2">Relleno Principal:</label>
                            <select id="filling-select" onchange="updatePrice()" class="w-full bg-white border border-caramel/30 rounded-xl p-3 text-sm focus:outline-none focus:border-rosepastel-500">
                                <option value="0">Dulce de Leche Tradicional</option>
                                <option value="1500">Ganache de Chocolate (+ $1.500)</option>
                                <option value="2000">Crema Bariloche con Frutos Rojos (+ $2.000)</option>
                            </select>
                        </div>
                    </div>

                    <div class="p-6 bg-white/90 rounded-2xl border border-caramel/20 text-center space-y-4">
                        <span class="text-xs text-chocolate/60 font-semibold uppercase tracking-wider">Estimación aproximada:</span>
                        <div id="price-display" class="font-serif text-4xl sm:text-5xl font-bold gold-gradient-text">$24.000</div>
                        <button onclick="sendWhatsAppOrder()" class="w-full bg-rosepastel-500 hover:bg-rosepastel-600 text-white font-semibold py-4 rounded-xl shadow-floating flex items-center justify-center gap-3 text-base transition-transform active:scale-95">
                            <i class="fa-brands fa-whatsapp text-2xl"></i>
                            <span>Pedir esta Cotización por WhatsApp</span>
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- FOOTER / CONTACTO -->
    <footer id="contacto" class="bg-chocolate text-vanilla pt-12 pb-8 mt-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center space-y-6">
            <h3 class="font-serif text-3xl font-bold gold-gradient-text">Dulcuras Pastelería</h3>
            <p class="text-xs text-vanilla/70 max-w-md mx-auto">Pedidos con anticipación. Realizamos envíos y retiros acordados previamente.</p>
            <div class="flex justify-center space-x-6 text-xl">
                <a href="https://instagram.com/dulcuraspasteleria_" target="_blank" class="hover:text-caramel transition-colors"><i class="fa-brands fa-instagram"></i></a>
                <a href="https://wa.me/5491131416486" target="_blank" class="hover:text-caramel transition-colors"><i class="fa-brands fa-whatsapp"></i></a>
            </div>
            <div class="text-[11px] text-vanilla/40 border-t border-white/10 pt-6">
                &copy; 2026 Dulcuras Pastelería. Todos los derechos reservados.
            </div>
        </div>
    </footer>

    <!-- BOTÓN FLOTANTE DE WHATSAPP -->
    <a href="https://wa.me/5491131416486?text=%C2%A1Hola%20Dulcuras%20Pasteler%C3%ADa!" target="_blank" class="fixed bottom-6 right-6 z-50 bg-emerald-500 text-white w-14 h-14 rounded-full flex items-center justify-center text-3xl shadow-2xl whatsapp-pulse border-2 border-white hover:scale-110 transition-transform">
        <i class="fa-brands fa-whatsapp"></i>
    </a>

    <!-- LÓGICA JAVASCRIPT DE CÁLCULO -->
    <script>
        function updatePrice() {
            const guests = parseInt(document.getElementById('guests-slider').value);
            const spongeFactor = parseFloat(document.getElementById('sponge-select').value);
            const fillingExtra = parseInt(document.getElementById('filling-select').value);

            document.getElementById('guests-val').innerText = `${guests} invitados`;

            const basePerGuest = 1600;
            const total = Math.round((guests * basePerGuest * spongeFactor) + fillingExtra);
            
            const formatted = new Intl.NumberFormat('es-AR', { style: 'currency', currency: 'ARS', maximumFractionDigits: 0 }).format(total);
            document.getElementById('price-display').innerText = formatted;
        }

        function sendWhatsAppOrder() {
            const guests = document.getElementById('guests-slider').value;
            const sponge = document.getElementById('sponge-select').options[document.getElementById('sponge-select').selectedIndex].text;
            const price = document.getElementById('price-display').innerText;

            const text = `¡Hola Dulcuras Pastelería! Estuve cotizando en su página web:\n\n- Cantidad de invitados: ${guests}\n- Bizcochuelo: ${sponge}\n- Estimado: ${price}\n\n¿Tienen disponibilidad para coordinar?`;
            
            window.open(`https://wa.me/5491131416486?text=${encodeURIComponent(text)}`, '_blank');
        }

        window.onload = updatePrice;
    </script>
</body>
</html>