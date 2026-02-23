# BashirAliGsm
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BashirAliGsm | عالم التكنولوجيا</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Changa:wght@300;400;700&display=swap');
        
        body {
            font-family: 'Changa', sans-serif;
            background-color: #0a0a0a;
            color: #e0e0e0;
        }

        .neon-border-green {
            box-shadow: 0 0 10px #22c55e, inset 0 0 5px #22c55e;
        }

        .neon-text-red {
            text-shadow: 0 0 10px #ef4444;
        }

        .card-hover:hover {
            transform: translateY(-5px);
            transition: all 0.3s ease;
            box-shadow: 0 0 20px rgba(34, 197, 94, 0.3);
        }

        .matrix-bg {
            background: linear-gradient(180deg, rgba(0,0,0,0.9) 0%, rgba(10,10,10,1) 100%);
        }

        .nav-link:hover {
            color: #22c55e;
            text-shadow: 0 0 8px #22c55e;
        }
    </style>
</head>
<body class="matrix-bg">

    <!-- Header / Navigation -->
    <nav class="sticky top-0 z-50 bg-black/80 backdrop-blur-md border-b border-green-500/30 p-4">
        <div class="container mx-auto flex justify-between items-center">
            <h1 class="text-2xl font-bold text-green-500 tracking-tighter">
                BASHIR<span class="text-red-500 italic">ALI</span><span class="text-white">GSM</span>
            </h1>
            <div class="hidden md:flex space-x-reverse space-x-6 text-sm font-medium">
                <a href="#home" class="nav-link">الرئيسية</a>
                <a href="#apps" class="nav-link">تطبيقات</a>
                <a href="#software" class="nav-link">Software</a>
                <a href="#forum" class="nav-link">المنتدى</a>
                <a href="#gallery" class="nav-link">صور</a>
            </div>
            <div class="md:hidden">
                <i class="fas fa-bars text-green-500 text-xl"></i>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header id="home" class="py-20 text-center relative overflow-hidden">
        <div class="container mx-auto px-4">
            <h2 class="text-5xl md:text-7xl font-bold mb-6 neon-text-red">Hacker X Portal</h2>
            <p class="text-xl text-green-400 mb-8 max-w-2xl mx-auto">
                منصة BashirAliGsm الرسمية لكل ما يتعلق بصيانة المحمول، السوفتوير، وأحدث أخبار التكنولوجيا.
            </p>
            <div class="flex justify-center gap-4">
                <button class="bg-green-600 hover:bg-green-700 text-white px-8 py-3 rounded-full font-bold transition">استكشف التطبيقات</button>
                <button class="border border-red-500 text-red-500 hover:bg-red-500 hover:text-white px-8 py-3 rounded-full font-bold transition">آخر الأخبار</button>
            </div>
        </div>
    </header>

    <!-- Content Sections -->
    <main class="container mx-auto px-4 py-12">
        
        <!-- Software News -->
        <section id="software" class="mb-20">
            <div class="flex items-center mb-10">
                <div class="h-1 w-10 bg-red-500 ml-4"></div>
                <h3 class="text-3xl font-bold">أخبار الـ Software اليوم</h3>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-zinc-900 p-6 rounded-xl border border-zinc-800 card-hover">
                    <img src="https://images.unsplash.com/photo-1550751827-4bd374c3f58b?auto=format&fit=crop&q=80&w=400" alt="Software Security" class="rounded-lg mb-4 w-full h-40 object-cover">
                    <span class="text-red-500 text-xs font-bold uppercase">تحديثات الأمان</span>
                    <h4 class="text-xl font-bold mt-2 mb-3">ثغرة جديدة في معالجات الأجهزة الذكية</h4>
                    <p class="text-gray-400 text-sm">تفاصيل الثغرة التقنية وكيفية حماية أجهزتك من الاختراق البرمجي...</p>
                    <a href="#" class="inline-block mt-4 text-green-500 font-bold">اقرأ المزيد ←</a>
                </div>
                <div class="bg-zinc-900 p-6 rounded-xl border border-zinc-800 card-hover">
                    <img src="https://images.unsplash.com/photo-1633356122544-f134324a6cee?auto=format&fit=crop&q=80&w=400" alt="Android Development" class="rounded-lg mb-4 w-full h-40 object-cover">
                    <span class="text-green-500 text-xs font-bold uppercase">أنظمة التشغيل</span>
                    <h4 class="text-xl font-bold mt-2 mb-3">إطلاق النسخة التجريبية من نظام Android 15</h4>
                    <p class="text-gray-400 text-sm">أهم المميزات الجديدة في النظام وكيفية تثبيته على أجهزة Google Pixel...</p>
                    <a href="#" class="inline-block mt-4 text-green-500 font-bold">اقرأ المزيد ←</a>
                </div>
                <div class="bg-zinc-900 p-6 rounded-xl border border-zinc-800 card-hover">
                    <img src="https://images.unsplash.com/photo-1605379399642-870262d3d051?auto=format&fit=crop&q=80&w=400" alt="Coding" class="rounded-lg mb-4 w-full h-40 object-cover">
                    <span class="text-blue-500 text-xs font-bold uppercase">برمجة</span>
                    <h4 class="text-xl font-bold mt-2 mb-3">أفضل أدوات الـ GSM لعام 2026</h4>
                    <p class="text-gray-400 text-sm">مراجعة شاملة لأدوات تخطي الحسابات وفك الشفرات لهذا الموسم...</p>
                    <a href="#" class="inline-block mt-4 text-green-500 font-bold">اقرأ المزيد ←</a>
                </div>
            </div>
        </section>

        <!-- Apps Section -->
        <section id="apps" class="mb-20 bg-green-500/5 p-8 rounded-3xl border border-green-500/20">
            <h3 class="text-3xl font-bold mb-10 text-center">أحدث التطبيقات المعدلة</h3>
            <div class="grid grid-cols-2 md:grid-cols-4 gap-6">
                <div class="text-center group">
                    <div class="w-20 h-20 bg-zinc-800 rounded-2xl mx-auto mb-4 flex items-center justify-center group-hover:bg-green-600 transition">
                        <i class="fab fa-whatsapp text-3xl"></i>
                    </div>
                    <p class="font-bold">WhatsApp Plus</p>
                    <span class="text-xs text-gray-500 italic">v12.0 (MOD)</span>
                </div>
                <div class="text-center group">
                    <div class="w-20 h-20 bg-zinc-800 rounded-2xl mx-auto mb-4 flex items-center justify-center group-hover:bg-green-600 transition">
                        <i class="fas fa-shield-halved text-3xl"></i>
                    </div>
                    <p class="font-bold">ZVPN Pro</p>
                    <span class="text-xs text-gray-500 italic">v5.4 (VIP)</span>
                </div>
                <div class="text-center group">
                    <div class="w-20 h-20 bg-zinc-800 rounded-2xl mx-auto mb-4 flex items-center justify-center group-hover:bg-green-600 transition">
                        <i class="fas fa-terminal text-3xl"></i>
                    </div>
                    <p class="font-bold">Termux Tools</p>
                    <span class="text-xs text-gray-500 italic">Script Pack</span>
                </div>
                <div class="text-center group">
                    <div class="w-20 h-20 bg-zinc-800 rounded-2xl mx-auto mb-4 flex items-center justify-center group-hover:bg-green-600 transition">
                        <i class="fas fa-tools text-3xl"></i>
                    </div>
                    <p class="font-bold">GSM Flash Tool</p>
                    <span class="text-xs text-gray-500 italic">PC Version</span>
                </div>
            </div>
        </section>

        <!-- Gallery -->
        <section id="gallery" class="mb-20">
            <h3 class="text-3xl font-bold mb-8">معرض الصور التقنية</h3>
            <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
                <div class="h-48 bg-zinc-800 rounded-lg overflow-hidden border border-zinc-700">
                    <img src="https://images.unsplash.com/photo-1542831371-29b0f74f9713?auto=format&fit=crop&q=80&w=300" class="w-full h-full object-cover opacity-70 hover:opacity-100 transition" alt="Code">
                </div>
                <div class="h-48 bg-zinc-800 rounded-lg overflow-hidden border border-zinc-700">
                    <img src="https://images.unsplash.com/photo-1597733336794-12d05021d510?auto=format&fit=crop&q=80&w=300" class="w-full h-full object-cover opacity-70 hover:opacity-100 transition" alt="Server">
                </div>
                <div class="h-48 bg-zinc-800 rounded-lg overflow-hidden border border-zinc-700">
                    <img src="https://images.unsplash.com/photo-1588508065123-287b28e013da?auto=format&fit=crop&q=80&w=300" class="w-full h-full object-cover opacity-70 hover:opacity-100 transition" alt="Circuits">
                </div>
                <div class="h-48 bg-zinc-800 rounded-lg overflow-hidden border border-zinc-700">
                    <img src="https://images.unsplash.com/photo-1531297484001-80022131f5a1?auto=format&fit=crop&q=80&w=300" class="w-full h-full object-cover opacity-70 hover:opacity-100 transition" alt="Tech Device">
                </div>
            </div>
        </section>

        <!-- Forum Section -->
        <section id="forum" class="mb-20">
            <div class="bg-zinc-900 border border-red-500/20 rounded-2xl p-8">
                <h3 class="text-2xl font-bold mb-6 text-red-500"><i class="fas fa-comments ml-3"></i>منتدى BashirAliGsm للنقاش</h3>
                <div class="space-y-4">
                    <div class="flex items-center justify-between p-4 bg-black/40 rounded-lg border-r-4 border-green-500">
                        <div>
                            <p class="font-bold">كيفية تخطي حساب جوجل لجهاز Samsung S24 Ultra؟</p>
                            <span class="text-xs text-gray-500">بواسطة: Tech_King | منذ ساعتين</span>
                        </div>
                        <span class="bg-zinc-800 px-3 py-1 rounded-full text-xs">24 رد</span>
                    </div>
                    <div class="flex items-center justify-between p-4 bg-black/40 rounded-lg border-r-4 border-red-500">
                        <div>
                            <p class="font-bold">مشكلة في أداة Chimera بعد التحديث الأخير</p>
                            <span class="text-xs text-gray-500">بواسطة: Bashir_Ali | منذ 5 ساعات</span>
                        </div>
                        <span class="bg-zinc-800 px-3 py-1 rounded-full text-xs">12 رد</span>
                    </div>
                </div>
                <button class="w-full mt-6 py-3 border-2 border-dashed border-zinc-700 text-zinc-500 rounded-lg hover:border-green-500 hover:text-green-500 transition">
                    + ابدأ موضوعاً جديداً في المنتدى
                </button>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-black py-12 border-t border-zinc-800">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-xl font-bold mb-4 text-green-500">BashirAliGsm</h2>
            <div class="flex justify-center space-x-reverse space-x-6 mb-8 text-2xl">
                <a href="#" class="text-gray-500 hover:text-blue-500"><i class="fab fa-facebook"></i></a>
                <a href="#" class="text-gray-500 hover:text-blue-400"><i class="fab fa-twitter"></i></a>
                <a href="#" class="text-gray-500 hover:text-red-500"><i class="fab fa-youtube"></i></a>
                <a href="#" class="text-gray-500 hover:text-green-500"><i class="fab fa-telegram"></i></a>
            </div>
            <p class="text-gray-600 text-sm">© 2026 BashirAliGsm. جميع الحقوق محفوظة لـ Hacker X.</p>
        </div>
    </footer>

    <script>
        // تأثير بسيط للتمرير السلس
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>

