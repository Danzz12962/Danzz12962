`SEPERTI YANG DI JANJI KAN BASE HTML MURLOG`

*SUMBER UTAMA*
https://whatsapp.com/channel/0029Vb6FBcTJENxysa3Aj637


<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MURLOG SHARE BY BLACK HUNTER</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700;900&display=swap');
        
        .app-container {
            font-family: 'Orbitron', monospace;
            background: linear-gradient(135deg, #000000 0%, #1a0000 50%, #330000 100%);
            min-height: 100vh;
        }
        
        .glow-effect {
            box-shadow: 0 0 20px rgba(255, 0, 0, 0.3);
            transition: all 0.3s ease;
        }
        
        .glow-effect:hover {
            box-shadow: 0 0 30px rgba(255, 0, 0, 0.6);
            transform: translateY(-2px);
        }
        
        .cyber-border {
            border: 2px solid #ff0000;
            position: relative;
        }
        
        .cyber-border::before {
            content: '';
            position: absolute;
            top: -2px;
            left: -2px;
            right: -2px;
            bottom: -2px;
            background: linear-gradient(45deg, #ff0000, #ffffff, #000000, #ff0000);
            z-index: -1;
            border-radius: inherit;
            opacity: 0;
            transition: opacity 0.3s ease;
        }
        
        .cyber-border:hover::before {
            opacity: 0.7;
        }
    </style>
</head>
<body class="app-container">
    <div class="container mx-auto px-3 py-6 pt-16">
        <!-- Header -->
        <div class="text-center mb-8">
            <h1 class="text-2xl md:text-6xl font-black text-transparent bg-clip-text bg-gradient-to-r from-red-500 via-white to-red-600 mb-3">
                MURLOG SHARE
            </h1>
            <p class="text-lg md:text-2xl text-white font-bold tracking-wider">
                BY BLACK HUNTER
            </p>
            <div class="w-24 h-1 bg-gradient-to-r from-red-500 to-white mx-auto mt-3 rounded-full"></div>
        </div>

        <!-- Main Menu -->
        <div id="mainMenu" class="max-w-sm mx-auto space-y-4">
            <button onclick="openGroup()" class="w-full py-3 px-4 bg-gradient-to-r from-red-600 to-black text-white font-bold text-base rounded-lg cyber-border glow-effect hover:from-red-700 hover:to-gray-900 transition-all duration-300">
                GROUP MURLOG
            </button>
            
            <button onclick="openChannel()" class="w-full py-3 px-4 bg-gradient-to-r from-black to-red-600 text-white font-bold text-base rounded-lg cyber-border glow-effect hover:from-gray-900 hover:to-red-700 transition-all duration-300">
                SALURAN BLACK HUNTER
            </button>
            
            <button onclick="showCreateMenu()" class="w-full py-3 px-4 bg-gradient-to-r from-red-500 to-red-800 text-white font-bold text-base rounded-lg cyber-border glow-effect hover:from-red-600 hover:to-red-900 transition-all duration-300">
                BAHAN CREATE LOGO
            </button>
            
            <!-- Thank You Banner in Main Menu -->
            <div class="bg-gradient-to-r from-black via-red-900 to-black py-3 px-4 border-2 border-red-500 rounded-lg mt-4">
                <div class="text-center text-white">
                    <p class="text-xs md:text-base font-bold mb-2 leading-relaxed">
                        "I AM BLACK HUNTER AS THE DEVELOPER OF THE APK MURLOG SHARE BY BLACK HUNTER, I WANT TO SAY THANK YOU TO THE LOGO CREATOR, THAT IS ZANSXD"
                    </p>
                    <div class="mt-2">
                        <p class="text-red-400 font-bold text-xs mb-1">SUPPORT US</p>
                        <p class="text-white text-xs">• YOUTUBE: ZAN'S XD</p>
                    </div>
                </div>
            </div>
        </div>

        <!-- Create Logo Menu -->
        <div id="createMenu" class="max-w-sm mx-auto space-y-3 hidden">
            <div class="text-center mb-4">
                <h2 class="text-xl font-bold text-white mb-2">BAHAN CREATE LOGO</h2>
                <div class="w-20 h-1 bg-gradient-to-r from-red-500 to-white mx-auto rounded-full"></div>
            </div>
            
            <button onclick="openCategory('arts')" class="w-full py-2.5 px-4 bg-gradient-to-r from-red-600 to-black text-white font-bold text-sm rounded-lg cyber-border glow-effect hover:from-red-700 hover:to-gray-900 transition-all duration-300">
                ART'S
            </button>
            
            <button onclick="openCategory('background')" class="w-full py-2.5 px-4 bg-gradient-to-r from-black to-red-600 text-white font-bold text-sm rounded-lg cyber-border glow-effect hover:from-gray-900 hover:to-red-700 transition-all duration-300">
                BACKGROUND
            </button>
            
            <button onclick="openCategory('effect')" class="w-full py-2.5 px-4 bg-gradient-to-r from-red-500 to-red-800 text-white font-bold text-sm rounded-lg cyber-border glow-effect hover:from-red-600 hover:to-red-900 transition-all duration-300">
                EFFECT
            </button>
            
            <button onclick="openCategory('icon')" class="w-full py-2.5 px-4 bg-gradient-to-r from-red-700 to-black text-white font-bold text-sm rounded-lg cyber-border glow-effect hover:from-red-800 hover:to-gray-900 transition-all duration-300">
                ICON
            </button>
            
            <button onclick="openCategory('stickers')" class="w-full py-2.5 px-4 bg-gradient-to-r from-black to-red-500 text-white font-bold text-sm rounded-lg cyber-border glow-effect hover:from-gray-900 hover:to-red-600 transition-all duration-300">
                STICKERS
            </button>
            
            <button onclick="backToMain()" class="w-full py-2.5 px-4 bg-gradient-to-r from-gray-800 to-red-600 text-white font-bold text-sm rounded-lg cyber-border glow-effect hover:from-gray-900 hover:to-red-700 transition-all duration-300">
                KEMBALI
            </button>
            
            <!-- Thank You Banner -->
            <div class="bg-gradient-to-r from-black via-red-900 to-black py-3 px-4 border-2 border-red-500 rounded-lg mt-4">
                <div class="text-center text-white">
                    <p class="text-xs md:text-base font-bold mb-2 leading-relaxed">
                        "I AM BLACK HUNTER AS THE DEVELOPER OF THE APK MURLOG SHARE BY BLACK HUNTER, I WANT TO SAY THANK YOU TO THE LOGO CREATOR, THAT IS ZANSXD"
                    </p>
                    <div class="mt-2">
                        <p class="text-red-400 font-bold text-xs mb-1">SUPPORT US</p>
                        <p class="text-white text-xs">• YOUTUBE: ZAN'S XD</p>
                    </div>
                </div>
            </div>
        </div>



        <!-- Category Modal -->
        <div id="categoryModal" class="fixed inset-0 bg-black bg-opacity-75 flex items-center justify-center p-4 hidden z-50">
            <div class="bg-gradient-to-br from-black to-red-900 p-6 rounded-lg max-w-md w-full cyber-border">
                <h3 id="categoryTitle" class="text-xl font-bold text-white mb-4"></h3>
                <div class="text-gray-300 mb-6">
                    <p>Kategori ini berisi berbagai bahan untuk membuat logo yang menakjubkan!</p>
                    <p class="mt-2 text-sm text-red-400">Fitur dalam pengembangan...</p>
                </div>
                <button onclick="closeCategory()" class="w-full py-2 px-4 bg-gradient-to-r from-red-600 to-black text-white font-bold rounded-lg hover:from-red-700 hover:to-gray-900 transition-all duration-300">
                    TUTUP
                </button>
            </div>
        </div>
    </div>

    <!-- Moving Banner -->
    <div class="fixed top-0 left-0 right-0 bg-gradient-to-r from-red-600 via-black to-red-800 py-2 overflow-hidden z-40">
        <div class="moving-text whitespace-nowrap text-white font-bold text-sm md:text-lg">
            JOIN SALURAN RESMI BLACK HUNTER OFFICIAL DI BAWAH , UNTUK INFO APK² SERU LAIN NYA DI MASA AKAN DATANG
        </div>
    </div>

    <style>
        .moving-text {
            animation: moveLeft 20s linear infinite;
            display: inline-block;
        }
        
        @keyframes moveLeft {
            0% {
                transform: translateX(100vw);
            }
            100% {
                transform: translateX(-100%);
            }
        }
    </style>



    <script>


        function openGroup() {
            window.open('https://chat.whatsapp.com/FX45F8eh0h5B7htYDeCZtk?mode=ac_t', '_blank');
        }

        function openChannel() {
            window.open('https://whatsapp.com/channel/0029Vb6FBcTJENxysa3Aj637', '_blank');
        }

        function showCreateMenu() {
            document.getElementById('mainMenu').classList.add('hidden');
            document.getElementById('createMenu').classList.remove('hidden');
        }

        function backToMain() {
            document.getElementById('createMenu').classList.add('hidden');
            document.getElementById('mainMenu').classList.remove('hidden');
        }

        function openCategory(category) {
            if (category === 'arts') {
                window.open('https://drive.google.com/drive/folders/1GfyRhVFR_005WyxiPOsZoi-zi936K4w5', '_blank');
                return;
            }
            
            if (category === 'background') {
                window.open('https://drive.google.com/drive/folders/1dwjGF8mW1QYi4X5mKfMu-2tFKhgHOCtr', '_blank');
                return;
            }
            
            if (category === 'effect') {
                window.open('https://drive.google.com/drive/folders/1yhRR7W2uaXBfhkMs0UtbQmXBH0-p3JGD', '_blank');
                return;
            }
            
            if (category === 'icon') {
                window.open('https://drive.google.com/drive/folders/1IHvWUxIbpdui-ko6jNYe_6nLqqwq6n0M', '_blank');
                return;
            }
            
            if (category === 'stickers') {
                window.open('https://drive.google.com/drive/folders/1YN14qu0pzZqRITnZpEt1x70IvN6-vOOG', '_blank');
                return;
            }
        }

        function closeCategory() {
            document.getElementById('categoryModal').classList.add('hidden');
        }

        // Add some interactive effects
        document.addEventListener('DOMContentLoaded', function() {
            // Add click sound effect simulation
            const buttons = document.querySelectorAll('button');
            buttons.forEach(button => {
                button.addEventListener('click', function() {
                    this.style.transform = 'scale(0.95)';
                    setTimeout(() => {
                        this.style.transform = '';
                    }, 100);
                });
            });
        });
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9742c65dc6563c57',t:'MTc1NjAzNzcyNC4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
