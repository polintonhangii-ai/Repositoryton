<!DOCTYPE html>
<html lang="km" class="h-full bg-slate-950 text-slate-100">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>ក្តារសញ្ញាផ្សាយផ្ទាល់ - Live Signal Board</title>
    
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Google Fonts for Khmer (Kantumruuy Pro) and English (Outfit, Space Grotesk) -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Kantumruuy+Pro:wght@400;500;600;700&family=Outfit:wght@400;600;700;900&family=Space+Grotesk:wght@500;700&display=swap" rel="stylesheet">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['"Kantumruuy Pro"', 'Outfit', 'sans-serif'],
                        mono: ['Space Grotesk', 'monospace']
                    },
                    animation: {
                        'bounce-short': 'bounceShort 0.4s ease-out',
                        'shake': 'shake 0.35s ease-in-out',
                        'zoom-in': 'zoomIn 0.25s ease-out forwards',
                        'pulse-glow': 'pulseGlow 2s infinite'
                    },
                    keyframes: {
                        bounceShort: {
                            '0%, 100%': { transform: 'scale(1)' },
                            '50%': { transform: 'scale(1.15)' }
                        },
                        shake: {
                            '0%, 100%': { transform: 'translateX(0)' },
                            '20%, 60%': { transform: 'translateX(-10px)' },
                            '40%, 80%': { transform: 'translateX(10px)' }
                        },
                        zoomIn: {
                            '0%': { opacity: '0', transform: 'scale(0.88)' },
                            '100%': { opacity: '1', transform: 'scale(1)' }
                        },
                        pulseGlow: {
                            '0%, 100%': { opacity: '0.6' },
                            '50%': { opacity: '1' }
                        }
                    }
                }
            }
        }
    </script>
    <style>
        * {
            -webkit-tap-highlight-color: transparent;
            user-select: none;
        }
        .hide-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .hide-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
        .glass-panel {
            background: rgba(15, 23, 42, 0.85);
            backdrop-filter: blur(16px);
            -webkit-backdrop-filter: blur(16px);
            border: 1px solid rgba(255, 255, 255, 0.08);
        }
    </style>
</head>
<body class="h-full flex flex-col justify-between overflow-x-hidden font-sans select-none antialiased bg-slate-950 text-slate-100 min-h-screen">

    <header class="w-full px-4 py-3 flex flex-wrap items-center justify-between glass-panel sticky top-0 z-20 border-b border-slate-800/80 shadow-lg gap-2">
        <div class="flex items-center gap-3">
            <div class="w-10 h-10 rounded-2xl bg-gradient-to-tr from-blue-600 via-indigo-600 to-rose-500 flex items-center justify-center shadow-md shadow-indigo-500/20">
                <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 002 2h2a2 2 0 002-2z"/>
                </svg>
            </div>
            <div>
                <h1 class="text-base sm:text-lg font-black tracking-wide text-white flex items-center gap-2">
                    <span>ក្តារសញ្ញាផ្សាយផ្ទាល់</span>
                    <span class="text-[10px] uppercase font-mono tracking-wider px-2 py-0.5 rounded-full bg-emerald-950 text-emerald-400 border border-emerald-500/30 flex items-center gap-1">
                        <span class="w-1.5 h-1.5 rounded-full bg-emerald-400 animate-ping"></span> LIVE
                    </span>
                </h1>
                <p class="text-xs text-slate-400 font-medium">ឆ្លើយតបផ្សាយផ្ទាល់ real-time similar to Mentimeter</p>
            </div>
        </div>

        <div class="flex items-center gap-2">
            <!-- Room Code Badge & Share Button -->
            <button onclick="openShareModal()" class="px-3 py-1.5 rounded-xl bg-indigo-950/80 hover:bg-indigo-900/90 text-indigo-300 border border-indigo-500/30 font-mono text-xs font-bold flex items-center gap-1.5 active:scale-95 transition">
                <svg class="w-4 h-4 text-indigo-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8.684 13.342C8.886 12.938 9 12.482 9 12c0-.482-.114-.938-.316-1.342m0 2.684a3 3 0 110-2.684m0 2.684l6.632 3.316m-6.632-6l6.632-3.316m0 0a3 3 0 105.367-2.684 3 3 0 00-5.367 2.684zm0 9.316a3 3 0 105.368 2.684 3 3 0 00-5.368-2.684z"/>
                </svg>
                <span>បន្ទប់: <span id="currentRoomDisplay" class="text-white underline">...</span></span>
            </button>

            <!-- Sound Toggle -->
            <button id="soundToggleBtn" onclick="toggleSound()" class="p-2 rounded-xl bg-slate-800/80 hover:bg-slate-700/80 text-slate-300 border border-slate-700/50 transition active:scale-95" title="បិទ/បើក សំឡេង">
                <svg id="soundOnIcon" class="w-5 h-5 text-emerald-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15.536 8.464a5 5 0 010 7.072m2.828-9.9a9 9 0 010 12.728M5.586 15H4a1 1 0 01-1-1v-4a1 1 0 011-1h1.586l4.707-4.707C10.923 3.663 12 4.109 12 5v14c0 .891-1.077 1.337-1.707.707L5.586 15z"/>
                </svg>
                <svg id="soundOffIcon" class="w-5 h-5 text-slate-600 hidden" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5.586 15H4a1 1 0 01-1-1v-4a1 1 0 011-1h1.586l4.707-4.707C10.923 3.663 12 4.109 12 5v14c0 .891-1.077 1.337-1.707.707L5.586 15z M17 14l2-2m0 0l2-2m-2 2l-2-2m2 2l2 2"/>
                </svg>
            </button>
        </div>
    </header>

    <div class="max-w-xl w-full mx-auto px-4 pt-3 flex justify-center">
        <div class="bg-slate-900/90 p-1 rounded-2xl border border-slate-800 flex w-full max-w-sm shadow-inner">
            <button id="navPresenterTab" onclick="switchViewMode('presenter')" class="flex-1 py-2 px-3 rounded-xl font-bold text-xs flex items-center justify-center gap-2 transition bg-indigo-600 text-white shadow-md">
                <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 002 2h2a2 2 0 002-2z"/>
                </svg>
                <span>ក្តារបង្ហាញ (Board)</span>
            </button>
            <button id="navAudienceTab" onclick="switchViewMode('audience')" class="flex-1 py-2 px-3 rounded-xl font-bold text-xs flex items-center justify-center gap-2 transition text-slate-400 hover:text-white">
                <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 18h.01M8 21h8a2 2 0 002-2V5a2 2 0 00-2-2H8a2 2 0 00-2 2v14a2 2 0 002 2z"/>
                </svg>
                <span>បន្ទះចុចឆ្លើយ (Pad)</span>
            </button>
        </div>
    </div>

    <!-- MAIN VIEW CONTAINER -->
    <main class="flex-1 max-w-xl w-full mx-auto px-4 py-4 flex flex-col justify-center gap-4">

        <!-- VIEW 1: PRESENTER / LIVE BOARD VIEW -->
        <div id="presenterBoardView" class="space-y-4 w-full">

            <!-- Live Summary Card -->
            <div class="glass-panel rounded-3xl p-5 border border-slate-800 shadow-2xl relative overflow-hidden">
                <div class="flex items-center justify-between mb-4">
                    <div class="flex items-center gap-2">
                        <span class="relative flex h-3 w-3">
                          <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-emerald-400 opacity-75"></span>
                          <span class="relative inline-flex rounded-full h-3 w-3 bg-emerald-500"></span>
                        </span>
                        <h2 class="text-sm font-bold tracking-wide text-slate-200 uppercase font-mono">លទ្ធផលផ្សាយផ្ទាល់ (Live Results)</h2>
                    </div>
                    
                    <div class="flex items-center gap-2">
                        <span id="totalRespondersBadge" class="text-xs font-mono font-bold text-indigo-300 bg-indigo-950/80 border border-indigo-700/50 px-3 py-1 rounded-full">
                            អ្នកឆ្លើយសរុប: 0
                        </span>
                        <button onclick="promptResetRoom()" class="p-1.5 rounded-lg bg-slate-800 hover:bg-slate-700 text-rose-400 border border-slate-700 transition" title="លុបលទ្ធផលទាំងអស់">
                            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 4v5h.582m15.356 2A8.001 8.001 0 004.582 9m0 0H9m11 11v-5h-.581m0 0a8.003 8.003 0 01-15.357-2m15.357 2H15"/>
                            </svg>
                        </button>
                    </div>
                </div>

                <!-- Big Visual Mentimeter-Style Live Bars Grid -->
                <div class="grid grid-cols-2 gap-4 my-3">
                    
                    <!-- Option O Live Bar Column -->
                    <div class="bg-gradient-to-b from-blue-950/60 to-slate-900 border border-blue-500/30 rounded-2xl p-4 flex flex-col items-center justify-between min-h-[220px] relative overflow-hidden">
                        <div class="z-10 w-full text-center">
                            <span class="text-xs font-mono font-bold text-blue-300 uppercase block mb-1">ជម្រើស O</span>
                            <span class="text-base font-black text-white block">ត្រឹមត្រូវ / យល់ព្រម</span>
                        </div>

                        <!-- Vertical Bar Animation Container -->
                        <div class="w-full h-32 bg-slate-950/80 rounded-xl relative overflow-hidden flex items-end p-1 border border-blue-900/40 my-2">
                            <div id="barHeightO" class="w-full bg-gradient-to-t from-blue-700 to-blue-400 rounded-lg transition-all duration-500 ease-out flex items-center justify-center font-mono font-extrabold text-white text-sm shadow-lg shadow-blue-500/20" style="height: 0%">
                                <span id="barHeightOText" class="drop-shadow">0%</span>
                            </div>
                        </div>

                        <div class="z-10 flex items-center justify-between w-full pt-1">
                            <span class="text-xs text-blue-300 font-mono">ចំនួន៖</span>
                            <span id="liveCountO" class="text-2xl font-black font-mono text-blue-400">0</span>
                        </div>
                    </div>

                    <!-- Option X Live Bar Column -->
                    <div class="bg-gradient-to-b from-red-950/60 to-slate-900 border border-red-500/30 rounded-2xl p-4 flex flex-col items-center justify-between min-h-[220px] relative overflow-hidden">
                        <div class="z-10 w-full text-center">
                            <span class="text-xs font-mono font-bold text-red-300 uppercase block mb-1">ជម្រើស X</span>
                            <span class="text-base font-black text-white block">មិនត្រឹមត្រូវ / បដិសេធ</span>
                        </div>

                        <!-- Vertical Bar Animation Container -->
                        <div class="w-full h-32 bg-slate-950/80 rounded-xl relative overflow-hidden flex items-end p-1 border border-red-900/40 my-2">
                            <div id="barHeightX" class="w-full bg-gradient-to-t from-red-700 to-rose-400 rounded-lg transition-all duration-500 ease-out flex items-center justify-center font-mono font-extrabold text-white text-sm shadow-lg shadow-rose-500/20" style="height: 0%">
                                <span id="barHeightXText" class="drop-shadow">0%</span>
                            </div>
                        </div>

                        <div class="z-10 flex items-center justify-between w-full pt-1">
                            <span class="text-xs text-red-300 font-mono">ចំនួន៖</span>
                            <span id="liveCountX" class="text-2xl font-black font-mono text-red-400">0</span>
                        </div>
                    </div>

                </div>

                <!-- Combined Horizontal Percentage Distribution -->
                <div class="mt-4">
                    <div class="flex justify-between text-xs font-mono text-slate-400 mb-1.5">
                        <span>សមាមាត្រ O (ត្រឹមត្រូវ) vs X (មិនត្រឹមត្រូវ)</span>
                        <span id="ratioText">0% / 0%</span>
                    </div>
                    <div class="w-full bg-slate-950 rounded-full h-3 overflow-hidden flex border border-slate-800">
                        <div id="ratioBarO" class="bg-blue-500 h-full transition-all duration-500" style="width: 50%"></div>
                        <div id="ratioBarX" class="bg-red-500 h-full transition-all duration-500" style="width: 50%"></div>
                    </div>
                </div>
            </div>

            <!-- Live Incoming Feed Container -->
            <div class="glass-panel rounded-3xl p-4 border border-slate-800">
                <div class="flex items-center justify-between mb-2">
                    <span class="text-xs font-mono font-bold text-slate-300 uppercase flex items-center gap-1.5">
                        <svg class="w-4 h-4 text-indigo-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"/>
                        </svg>
                        កំណត់ត្រាចម្លើយថ្មីៗ (Live Feed)
                    </span>
                    <span class="text-[10px] font-mono text-slate-500">ប្រព័ន្ធ Real-time</span>
                </div>
                <div id="liveFeedList" class="max-h-40 overflow-y-auto hide-scrollbar space-y-1.5 text-xs font-mono">
                    <div class="text-slate-500 italic text-center py-3">រង់ចាំការឆ្លើយតបពីអ្នកចូលរួម...</div>
                </div>
            </div>

            <!-- Join Link Action Card -->
            <div class="glass-panel rounded-2xl p-4 border border-indigo-900/40 bg-indigo-950/20 flex items-center justify-between gap-3">
                <div class="flex items-center gap-3">
                    <div class="w-10 h-10 rounded-xl bg-indigo-600/30 text-indigo-400 flex items-center justify-center border border-indigo-500/30">
                        <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13.828 10.172a4 4 0 00-5.656 0l-4 4a4 4 0 105.656 5.656l1.102-1.101m-.758-4.899a4 4 0 005.656 0l4-4a4 4 0 00-5.656-5.656l-1.1 1.1"/>
                        </svg>
                    </div>
                    <div>
                        <h4 class="text-xs font-bold text-white">អញ្ជើញអ្នកចូលរួមឆ្លើយសំណួរ</h4>
                        <p class="text-[11px] text-slate-400">ចែករំលែកតំណភ្ជាប់ដើម្បីឲ្យអ្នកផ្សេងទៀតបោះឆ្នោត</p>
                    </div>
                </div>
                <button onclick="openShareModal()" class="px-3 py-2 bg-indigo-600 hover:bg-indigo-500 text-white font-bold text-xs rounded-xl transition active:scale-95 flex-shrink-0">
                    ចែករំលែក Link
                </button>
            </div>

        </div>

        <!-- VIEW 2: AUDIENCE / RESPONDER PAD VIEW -->
        <div id="audiencePadView" class="hidden space-y-4 w-full">
            
            <div class="text-center py-1">
                <span class="text-xs font-mono font-semibold text-slate-400 block">ជ្រើសរើសចម្លើយរបស់អ្នក៖</span>
            </div>

            <div class="grid grid-cols-1 gap-4 w-full">
                
                <!-- Option O Big Pad Button -->
                <button id="btnAudienceO" onclick="submitVote('O')" class="group relative w-full h-52 sm:h-60 rounded-3xl bg-gradient-to-br from-blue-600 via-blue-700 to-indigo-950 border-2 border-blue-400/50 p-6 flex flex-col items-center justify-between shadow-2xl shadow-blue-900/50 hover:shadow-blue-500/50 hover:border-blue-300 transition-all duration-200 active:scale-95 overflow-hidden">
                    <div class="absolute -right-10 -bottom-10 w-44 h-44 bg-blue-400/20 rounded-full blur-2xl group-hover:scale-150 transition-transform pointer-events-none"></div>
                    
                    <div class="w-full flex items-center justify-between z-10">
                        <span class="px-2.5 py-1 rounded-full bg-blue-950/80 border border-blue-400/40 text-[11px] font-mono font-bold text-blue-300 uppercase tracking-wider">
                            ជម្រើស O
                        </span>
                        <span class="text-xs font-mono font-bold text-blue-200/80">ចុចដើម្បីបោះឆ្នោត</span>
                    </div>

                    <div class="my-auto relative flex items-center justify-center">
                        <div class="w-20 h-20 sm:w-24 sm:h-24 rounded-full border-[10px] border-white drop-shadow-[0_0_20px_rgba(255,255,255,0.85)] group-hover:scale-110 transition-transform duration-200"></div>
                    </div>

                    <div class="w-full text-center z-10">
                        <span class="block text-2xl font-black text-white drop-shadow-md">
                            ត្រឹមត្រូវ / យល់ព្រម
                        </span>
                    </div>
                </button>

                <!-- Option X Big Pad Button -->
                <button id="btnAudienceX" onclick="submitVote('X')" class="group relative w-full h-52 sm:h-60 rounded-3xl bg-gradient-to-br from-red-600 via-rose-700 to-red-950 border-2 border-red-400/50 p-6 flex flex-col items-center justify-between shadow-2xl shadow-red-950/60 hover:shadow-red-500/50 hover:border-red-300 transition-all duration-200 active:scale-95 overflow-hidden">
                    <div class="absolute -left-10 -bottom-10 w-44 h-44 bg-red-400/20 rounded-full blur-2xl group-hover:scale-150 transition-transform pointer-events-none"></div>
                    
                    <div class="w-full flex items-center justify-between z-10">
                        <span class="px-2.5 py-1 rounded-full bg-red-950/80 border border-red-400/40 text-[11px] font-mono font-bold text-red-300 uppercase tracking-wider">
                            ជម្រើស X
                        </span>
                        <span class="text-xs font-mono font-bold text-red-200/80">ចុចដើម្បីបោះឆ្នោត</span>
                    </div>

                    <div class="my-auto relative flex items-center justify-center">
                        <svg class="w-20 h-20 sm:w-24 sm:h-24 text-white drop-shadow-[0_0_20px_rgba(255,255,255,0.85)] group-hover:scale-110 transition-transform duration-300" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="3.5" d="M6 18L18 6M6 6l12 12"/>
                        </svg>
                    </div>

                    <div class="w-full text-center z-10">
                        <span class="block text-2xl font-black text-white drop-shadow-md">
                            មិនត្រឹមត្រូវ / បដិសេធ
                        </span>
                    </div>
                </button>

            </div>

            <!-- Feedback Badge -->
            <div id="votedFeedbackBadge" class="hidden text-center p-3 rounded-2xl bg-emerald-950/80 border border-emerald-500/40 text-emerald-300 font-bold text-xs animate-zoom-in">
                ✓ បានផ្ញើចម្លើយរបស់អ្នករួចរាល់! លទ្ធផលត្រូវបានធ្វើបច្ចុប្បន្នភាពនៅលើក្តារ។
            </div>

        </div>

    </main>

    <!-- SHARE ROOM / LINK MODAL -->
    <div id="shareModal" class="fixed inset-0 z-50 hidden flex items-center justify-center bg-black/80 backdrop-blur-sm p-4">
        <div class="glass-panel max-w-sm w-full rounded-3xl p-6 border border-slate-700 shadow-2xl animate-zoom-in">
            <div class="flex justify-between items-center mb-4">
                <h3 class="text-base font-bold text-white flex items-center gap-2">
                    <svg class="w-5 h-5 text-indigo-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8.684 13.342C8.886 12.938 9 12.482 9 12c0-.482-.114-.938-.316-1.342m0 2.684a3 3 0 110-2.684m0 2.684l6.632 3.316m-6.632-6l6.632-3.316m0 0a3 3 0 105.367-2.684 3 3 0 00-5.367 2.684zm0 9.316a3 3 0 105.368 2.684 3 3 0 00-5.368-2.684z"/>
                    </svg>
                    ចែករំលែកតំណបោះឆ្នោត
                </h3>
                <button onclick="closeShareModal()" class="text-slate-400 hover:text-white p-1">
                    <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"/>
                    </svg>
                </button>
            </div>
            
            <p class="text-xs text-slate-300 mb-4 leading-relaxed">
                ផ្ញើតំណភ្ជាប់នេះទៅកាន់អ្នកចូលរួមទាំងអស់ ដើម្បីឲ្យពួកគាត់អាចបោះឆ្នោតពីទូរស័ព្ទរបស់ពួកគាត់បាន៖
            </p>

            <div class="mb-4">
                <label class="text-[11px] font-mono text-slate-400 block mb-1">កូដបន្ទប់ (Room Code):</label>
                <div class="flex gap-2">
                    <input id="roomCodeInput" type="text" class="flex-1 bg-slate-900 border border-slate-700 rounded-xl px-3 py-2 text-xs font-mono font-bold text-indigo-300 uppercase focus:outline-none focus:border-indigo-500">
                    <button onclick="changeRoomCode()" class="bg-indigo-600 hover:bg-indigo-500 text-white px-3 py-2 rounded-xl text-xs font-bold transition">
                        ចូលបន្ទប់
                    </button>
                </div>
            </div>

            <div class="mb-5">
                <label class="text-[11px] font-mono text-slate-400 block mb-1">Link សម្រាប់ចែករំលែក:</label>
                <div class="p-2.5 rounded-xl bg-slate-900 border border-slate-800 font-mono text-[11px] text-slate-300 break-all" id="shareUrlDisplay">
                    ...
                </div>
            </div>

            <button id="copyBtn" onclick="copyShareLink()" class="w-full bg-emerald-600 hover:bg-emerald-500 text-white font-bold py-2.5 rounded-xl transition text-xs flex items-center justify-center gap-2">
                <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 5H6a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2v-1M8 5a2 2 0 002 2h2a2 2 0 002-2M8 5a2 2 0 012-2h2a2 2 0 012 2m0 0h2a2 2 0 012 2v3m2 4H10m0 0l3-3m-3 3l3 3"/>
                </svg>
                <span id="copyBtnText">ចម្លង Link</span>
            </button>
        </div>
    </div>

    <!-- RESET CONFIRMATION MODAL -->
    <div id="resetModal" class="fixed inset-0 z-50 hidden flex items-center justify-center bg-black/80 backdrop-blur-sm p-4">
        <div class="glass-panel max-w-xs w-full rounded-3xl p-5 border border-slate-700 shadow-2xl text-center animate-zoom-in">
            <div class="w-12 h-12 rounded-2xl bg-rose-500/20 text-rose-400 flex items-center justify-center mx-auto mb-3 border border-rose-500/30">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 9v2m0 4h.01m-6.938 4h13.856c1.54 0 2.502-1.667 1.732-3L13.732 4c-.77-1.333-2.694-1.333-3.464 0L3.34 16c-.77 1.333.192 3 1.732 3z"/>
                </svg>
            </div>
            <h3 class="text-sm font-bold text-white mb-1">កំណត់បន្ទប់នេះឡើងវិញ?</h3>
            <p class="text-xs text-slate-300 mb-4 leading-relaxed">ការធ្វើបែបនេះនឹងលុបលទ្ធផល និងចំនួនអ្នកឆ្លើយទាំងអស់ក្នុងបន្ទប់នេះមក ០ វិញ។</p>
            <div class="flex gap-2">
                <button onclick="closeResetModal()" class="flex-1 bg-slate-800 hover:bg-slate-700 text-slate-300 font-semibold py-2 rounded-xl text-xs">បោះបង់</button>
                <button onclick="confirmResetRoom()" class="flex-1 bg-rose-600 hover:bg-rose-500 text-white font-bold py-2 rounded-xl text-xs">លុបទាំងអស់</button>
            </div>
        </div>
    </div>

    <!-- FULL OVERLAY SIGNAL FEEDBACK -->
    <div id="fullOverlay" class="fixed inset-0 z-50 hidden flex-col items-center justify-center transition-opacity duration-200 cursor-pointer select-none" onclick="dismissOverlay()">
        <div id="overlayBg" class="absolute inset-0 transition-colors duration-300"></div>
        <div class="relative z-10 flex flex-col items-center text-center p-6 max-w-lg w-full animate-zoom-in">
            <div id="overlaySymbol" class="mb-5 flex items-center justify-center"></div>
            <h2 id="overlayTitle" class="text-4xl sm:text-5xl font-black uppercase text-white drop-shadow-md mb-2"></h2>
            <p id="overlaySubtitle" class="text-base sm:text-xl font-bold text-white/90 font-mono drop-shadow"></p>
            <div class="mt-8 px-5 py-2.5 rounded-full bg-black/40 backdrop-blur-md border border-white/25 text-white text-xs font-medium flex items-center gap-2 animate-bounce">
                <span>ចុចត្រង់ណាក៏បានដើម្បីបិទ</span>
            </div>
        </div>
    </div>

    <script type="module">
        import { initializeApp } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-app.js";
        import { getAuth, signInAnonymously, signInWithCustomToken } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-auth.js";
        import { getFirestore, doc, onSnapshot, setDoc, updateDoc, arrayUnion } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-firestore.js";

        const appId = typeof __app_id !== 'undefined' ? __app_id : 'signal-board-app';
        const firebaseConfig = typeof __firebase_config !== 'undefined' 
            ? JSON.parse(__firebase_config) 
            : { apiKey: "demo", authDomain: "demo.firebaseapp.com", projectId: "demo" };

        const app = initializeApp(firebaseConfig);
        const auth = getAuth(app);
        const db = getFirestore(app);

        let currentRoomId = getRoomIdFromURL();
        let currentUserId = null;
        let isMuted = false;
        let audioCtx = null;
        let roomUnsubscribe = null;

        async function initApp() {
            try {
                if (typeof __initial_auth_token !== 'undefined' && __initial_auth_token) {
                    await signInWithCustomToken(auth, __initial_auth_token);
                } else {
                    await signInAnonymously(auth);
                }
                currentUserId = auth.currentUser?.uid || ('user_' + Math.random().toString(36).substring(2, 9));
            } catch (err) {
                console.warn('Auth fallback:', err);
                currentUserId = 'user_' + Math.random().toString(36).substring(2, 9);
            }

            document.getElementById('currentRoomDisplay').innerText = currentRoomId;
            document.getElementById('roomCodeInput').value = currentRoomId;
            updateShareUrlDisplay();

            // Listen to current room
            subscribeToRoom(currentRoomId);
        }

        function getRoomIdFromURL() {
            const urlParams = new URLSearchParams(window.location.search);
            const roomParam = urlParams.get('room');
            if (roomParam && roomParam.trim() !== '') {
                return roomParam.trim().toUpperCase();
            }
            return 'MAIN';
        }

        function subscribeToRoom(roomId) {
            if (roomUnsubscribe) roomUnsubscribe();

            // Strict Path: /artifacts/{appId}/public/data/rooms/{roomId}
            const roomDocRef = doc(db, 'artifacts', appId, 'public', 'data', 'rooms', roomId);

            roomUnsubscribe = onSnapshot(roomDocRef, (snapshot) => {
                if (snapshot.exists()) {
                    const data = snapshot.data();
                    renderRoomData(data);
                } else {
                    // Initialize empty room
                    setDoc(roomDocRef, {
                        countO: 0,
                        countX: 0,
                        history: [],
                        updatedAt: Date.now()
                    }, { merge: true });
                }
            }, (error) => {
                console.error("Firestore room sync error:", error);
            });
        }

        function renderRoomData(data) {
            const countO = data.countO || 0;
            const countX = data.countX || 0;
            const total = countO + countX;

            document.getElementById('liveCountO').innerText = countO;
            document.getElementById('liveCountX').innerText = countX;
            document.getElementById('totalRespondersBadge').innerText = `អ្នកឆ្លើយសរុប: ${total}`;

            const percentO = total > 0 ? Math.round((countO / total) * 100) : 0;
            const percentX = total > 0 ? (100 - percentO) : 0;

            // Height Bars
            document.getElementById('barHeightO').style.height = `${percentO}%`;
            document.getElementById('barHeightX').style.height = `${percentX}%`;
            document.getElementById('barHeightOText').innerText = `${percentO}%`;
            document.getElementById('barHeightXText').innerText = `${percentX}%`;

            // Ratio horizontal bar
            document.getElementById('ratioBarO').style.width = `${total > 0 ? percentO : 50}%`;
            document.getElementById('ratioBarX').style.width = `${total > 0 ? percentX : 50}%`;
            document.getElementById('ratioText').innerText = `${percentO}% / ${percentX}%`;

            // Render Feed Log
            const historyList = data.history || [];
            const feedContainer = document.getElementById('liveFeedList');
            if (historyList.length === 0) {
                feedContainer.innerHTML = `<div class="text-slate-500 italic text-center py-3">រង់ចាំការឆ្លើយតបពីអ្នកចូលរួម...</div>`;
            } else {
                feedContainer.innerHTML = historyList.slice(0, 20).map(item => `
                    <div class="flex items-center justify-between py-1.5 px-3 rounded-xl ${item.choice === 'O' ? 'bg-blue-950/40 text-blue-300 border border-blue-900/40' : 'bg-red-950/40 text-red-300 border border-red-900/40'}">
                        <span class="font-bold flex items-center gap-1.5">
                            ${item.choice === 'O' ? '🔵 សញ្ញា O (ត្រឹមត្រូវ/យល់ព្រម)' : '❌ សញ្ញា X (មិនត្រឹមត្រូវ/បដិសេធ)'}
                        </span>
                        <span class="text-[10px] text-slate-400 font-mono">${item.time || ''}</span>
                    </div>
                `).join('');
            }
        }

        window.submitVote = async function(choice) {
            initAudioContext();
            playChime(choice);
            showOverlay(choice);

            const badge = document.getElementById('votedFeedbackBadge');
            badge.classList.remove('hidden');
            setTimeout(() => badge.classList.add('hidden'), 4000);

            const roomDocRef = doc(db, 'artifacts', appId, 'public', 'data', 'rooms', currentRoomId);
            const timeStr = new Date().toLocaleTimeString([], { hour: '2-digit', minute: '2-digit', second: '2-digit' });

            try {
                await updateDoc(roomDocRef, {
                    [choice === 'O' ? 'countO' : 'countX']: (choice === 'O' ? (parseInt(document.getElementById('liveCountO').innerText) || 0) + 1 : (parseInt(document.getElementById('liveCountX').innerText) || 0) + 1),
                    history: arrayUnion({
                        choice: choice,
                        userId: currentUserId,
                        time: timeStr
                    }),
                    updatedAt: Date.now()
                });
            } catch (err) {
                // If doc does not exist yet
                setDoc(roomDocRef, {
                    countO: choice === 'O' ? 1 : 0,
                    countX: choice === 'X' ? 1 : 0,
                    history: [{ choice, userId: currentUserId, time: timeStr }],
                    updatedAt: Date.now()
                }, { merge: true });
            }
        };

        window.confirmResetRoom = async function() {
            const roomDocRef = doc(db, 'artifacts', appId, 'public', 'data', 'rooms', currentRoomId);
            await setDoc(roomDocRef, {
                countO: 0,
                countX: 0,
                history: [],
                updatedAt: Date.now()
            });
            closeResetModal();
        };

        window.changeRoomCode = function() {
            const newCode = document.getElementById('roomCodeInput').value.trim().toUpperCase();
            if (newCode && newCode !== currentRoomId) {
                currentRoomId = newCode;
                document.getElementById('currentRoomDisplay').innerText = currentRoomId;
                updateShareUrlDisplay();
                
                // Update URL parameter without reload
                const newUrl = window.location.protocol + "//" + window.location.host + window.location.pathname + '?room=' + currentRoomId;
                window.history.pushState({path: newUrl}, '', newUrl);

                subscribeToRoom(currentRoomId);
                closeShareModal();
            }
        };

        function updateShareUrlDisplay() {
            const url = window.location.protocol + "//" + window.location.host + window.location.pathname + '?room=' + currentRoomId;
            document.getElementById('shareUrlDisplay').innerText = url;
        }

        // Global UI helper functions
        window.switchViewMode = function(mode) {
            const presTab = document.getElementById('navPresenterTab');
            const audTab = document.getElementById('navAudienceTab');
            const presView = document.getElementById('presenterBoardView');
            const audView = document.getElementById('audiencePadView');

            if (mode === 'presenter') {
                presTab.className = "flex-1 py-2 px-3 rounded-xl font-bold text-xs flex items-center justify-center gap-2 transition bg-indigo-600 text-white shadow-md";
                audTab.className = "flex-1 py-2 px-3 rounded-xl font-bold text-xs flex items-center justify-center gap-2 transition text-slate-400 hover:text-white";
                presView.classList.remove('hidden');
                audView.classList.add('hidden');
            } else {
                audTab.className = "flex-1 py-2 px-3 rounded-xl font-bold text-xs flex items-center justify-center gap-2 transition bg-indigo-600 text-white shadow-md";
                presTab.className = "flex-1 py-2 px-3 rounded-xl font-bold text-xs flex items-center justify-center gap-2 transition text-slate-400 hover:text-white";
                audView.classList.remove('hidden');
                presView.classList.add('hidden');
            }
        };

        window.openShareModal = function() {
            updateShareUrlDisplay();
            document.getElementById('shareModal').classList.remove('hidden');
        };

        window.closeShareModal = function() {
            document.getElementById('shareModal').classList.add('hidden');
        };

        window.copyShareLink = function() {
            const textToCopy = document.getElementById('shareUrlDisplay').innerText;
            const input = document.createElement("textarea");
            input.value = textToCopy;
            document.body.appendChild(input);
            input.select();
            document.execCommand('copy');
            document.body.removeChild(input);

            const btnText = document.getElementById('copyBtnText');
            btnText.innerText = "✓ បានចម្លងរួចរាល់!";
            setTimeout(() => { btnText.innerText = "ចម្លង Link"; }, 2000);
        };

        window.promptResetRoom = function() {
            document.getElementById('resetModal').classList.remove('hidden');
        };

        window.closeResetModal = function() {
            document.getElementById('resetModal').classList.add('hidden');
        };

        window.toggleSound = function() {
            isMuted = !isMuted;
            document.getElementById('soundOnIcon').classList.toggle('hidden', isMuted);
            document.getElementById('soundOffIcon').classList.toggle('hidden', !isMuted);
        };

        function initAudioContext() {
            if (!audioCtx) {
                const AudioCtxClass = window.AudioContext || window.webkitAudioContext;
                if (AudioCtxClass) audioCtx = new AudioCtxClass();
            }
            if (audioCtx && audioCtx.state === 'suspended') {
                audioCtx.resume();
            }
        }

        function playChime(type) {
            if (isMuted) return;
            try {
                if (!audioCtx) return;
                const osc = audioCtx.createOscillator();
                const gain = audioCtx.createGain();
                osc.connect(gain);
                gain.connect(audioCtx.destination);
                const now = audioCtx.currentTime;

                if (type === 'O') {
                    osc.type = 'sine';
                    osc.frequency.setValueAtTime(523.25, now);
                    osc.frequency.exponentialRampToValueAtTime(880, now + 0.2);
                    gain.gain.setValueAtTime(0.35, now);
                    gain.gain.exponentialRampToValueAtTime(0.001, now + 0.4);
                    osc.start(now);
                    osc.stop(now + 0.4);
                } else {
                    osc.type = 'sawtooth';
                    osc.frequency.setValueAtTime(260, now);
                    osc.frequency.setValueAtTime(160, now + 0.12);
                    gain.gain.setValueAtTime(0.3, now);
                    gain.gain.exponentialRampToValueAtTime(0.001, now + 0.35);
                    osc.start(now);
                    osc.stop(now + 0.35);
                }
            } catch (e) {}
        }

        function showOverlay(type) {
            const overlay = document.getElementById('fullOverlay');
            const bg = document.getElementById('overlayBg');
            const symbol = document.getElementById('overlaySymbol');
            const title = document.getElementById('overlayTitle');
            const subtitle = document.getElementById('overlaySubtitle');

            if (type === 'O') {
                bg.className = 'absolute inset-0 bg-blue-600 transition-colors duration-200';
                title.innerText = "ត្រឹមត្រូវ / យល់ព្រម";
                subtitle.innerText = "OPTION O - APPROVED";
                symbol.innerHTML = `<div class="w-36 h-36 sm:w-48 sm:h-48 rounded-full border-[16px] sm:border-[20px] border-white drop-shadow-[0_0_35px_rgba(255,255,255,0.9)] animate-bounce-short"></div>`;
            } else {
                bg.className = 'absolute inset-0 bg-red-600 transition-colors duration-200';
                title.innerText = "មិនត្រឹមត្រូវ / បដិសេធ";
                subtitle.innerText = "OPTION X - DENIED";
                symbol.innerHTML = `<svg class="w-36 h-36 sm:w-48 sm:h-48 text-white drop-shadow-[0_0_35px_rgba(255,255,255,0.9)] animate-shake" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="3" d="M6 18L18 6M6 6l12 12"/></svg>`;
            }

            overlay.classList.remove('hidden');
            overlay.classList.add('flex');
            setTimeout(dismissOverlay, 1800);
        }

        window.dismissOverlay = function() {
            const overlay = document.getElementById('fullOverlay');
            overlay.classList.add('hidden');
            overlay.classList.remove('flex');
        };

        // Start initialization
        window.addEventListener('DOMContentLoaded', initApp);
    </script>
</body>
</html>
