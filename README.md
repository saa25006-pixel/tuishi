<!DOCTYPE html>
<html lang="ja" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>西条市 三大特産品「推し」紹介サイト</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Lucide Icons (for beautiful iconography) -->
    <script src="https://unpkg.com/lucide@latest"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        saijo: {
                            blue: '#0077c2',
                            lightBlue: '#e3f2fd',
                            persimmon: '#e05a2b',
                            eggplant: '#4a154b',
                            tea: '#556b2f',
                        }
                    },
                    fontFamily: {
                        sans: ['Helvetica Neue', 'Arial', 'Hiragino Kaku Gothic ProN', 'Hiragino Sans', 'Meiryo', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        .diagonal-bg {
            clip-path: polygon(0 0, 100% 0, 100% 95%, 0 100%);
        }
    </style>
</head>
<body class="bg-stone-50 text-slate-800 font-sans leading-relaxed">

    <!-- Header / Navigation -->
    <header class="fixed top-0 left-0 w-full bg-white/95 backdrop-blur-md border-b border-slate-100 z-50 shadow-sm">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-16 flex items-center justify-between">
            <div class="flex items-center space-x-2">
                <i data-lucide="droplet" class="text-saijo-blue w-6 h-6 animate-pulse"></i>
                <span class="font-bold text-lg tracking-wider text-slate-900">西条の恵み「推し」ナビ</span>
            </div>
            <nav class="hidden md:flex space-x-8 text-sm font-medium">
                <a href="#about" class="text-slate-600 hover:text-saijo-blue transition-colors">西条と水</a>
                <a href="#persimmon" class="text-slate-600 hover:text-saijo-persimmon transition-colors">愛宕柿</a>
                <a href="#eggplant" class="text-slate-600 hover:text-saijo-eggplant transition-colors">絹皮なす</a>
                <a href="#tea" class="text-slate-600 hover:text-saijo-tea transition-colors">石鎚黒茶</a>
                <a href="#diagnostic" class="bg-saijo-blue text-white px-4 py-2 rounded-full hover:bg-sky-700 transition-all shadow-sm">おすすめ診断</a>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="relative pt-32 pb-20 md:pt-40 md:pb-32 bg-gradient-to-b from-sky-50 to-stone-50 overflow-hidden">
        <div class="absolute inset-0 opacity-10">
            <svg class="w-full h-full" xmlns="http://www.w3.org/2000/svg">
                <defs>
                    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
                        <path d="M 40 0 L 0 0 0 40" fill="none" stroke="currentColor" stroke-width="1"/>
                    </pattern>
                </defs>
                <rect width="100%" height="100%" fill="url(#grid)" />
            </svg>
        </div>
        <div class="max-w-5xl mx-auto px-4 text-center relative z-10">
            <span class="inline-block bg-saijo-blue/10 text-saijo-blue px-4 py-1.5 rounded-full text-xs font-semibold tracking-wider uppercase mb-6">愛媛県西条市ブランド</span>
            <h1 class="text-4xl md:text-6xl font-extrabold text-slate-950 tracking-tight leading-tight mb-6">
                名水の都が育んだ、<br><span class="text-transparent bg-clip-text bg-gradient-to-r from-saijo-blue to-teal-600">3つの奇跡の「推し」</span>
            </h1>
            <p class="text-lg md:text-xl text-slate-600 max-w-2xl mx-auto mb-10 leading-relaxed">
                西日本最高峰「石鎚山」から湧き出る名水「うちぬき」。豊かな自然と受け継がれる伝統、整理、そして<br class="hidden md:inline">
                <a href="https://ehm-saijo-ah.esnet.ed.jp/" target="_blank" rel="noopener noreferrer" class="font-bold text-saijo-blue border-b-2 border-saijo-blue hover:text-sky-700 hover:border-sky-700 transition-colors">愛媛県立西条農業高等学校</a>の情熱が生み出した極上の品々をあなたに。
            </p>
            <div class="flex flex-wrap justify-center gap-4">
                <a href="#diagnostic" class="px-8 py-4 bg-saijo-blue hover:bg-sky-700 text-white font-medium rounded-full shadow-lg hover:shadow-xl transition-all flex items-center space-x-2">
                    <span>あなたに合う「推し」を診断する</span>
                    <i data-lucide="sparkles" class="w-5 h-5"></i>
                </a>
                <a href="#about" class="px-8 py-4 bg-white border border-slate-300 hover:border-slate-400 text-slate-700 font-medium rounded-full transition-all">
                    ストーリーを見る
                </a>
            </div>
        </div>
    </section>

    <!-- Intro Section: Saijo & Water -->
    <section id="about" class="py-16 md:py-24 bg-white border-y border-slate-100">
        <div class="max-w-6xl mx-auto px-4 text-center">
            <div class="flex justify-center mb-4">
                <div class="p-3 bg-sky-50 rounded-full text-saijo-blue">
                    <i data-lucide="droplet" class="w-8 h-8"></i>
                </div>
            </div>
            <h2 class="text-2xl md:text-3xl font-bold text-slate-900 mb-6">名水「うちぬき」が創る美味しさ</h2>
            <p class="text-slate-600 leading-relaxed max-w-3xl mx-auto mb-12">
                西条市は、街のあちこちから清らかな地下水が自噴する「名水の都」です。石鎚山系に降り注いだ雨や雪が、何十年もの歳月をかけて自然にろ過され、ミネラルをバランスよく含んだ美味しい水へと生まれ変わります。この最高品質の水こそが、西条市が誇る豊かな農作物や特産品の味わいの源泉となっています。
            </p>
            
            <!-- Water Showcase Image -->
            <div class="relative rounded-3xl overflow-hidden shadow-xl max-w-4xl mx-auto h-64 md:h-96 group">
                <img src="https://images.unsplash.com/photo-1470071459604-3b5ec3a7fe05?auto=format&fit=crop&w=1600&q=80" 
                     alt="うちぬきの清流イメージ" 
                     class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105">
                <div class="absolute inset-0 bg-gradient-to-t from-slate-950/70 via-slate-950/20 to-transparent flex flex-col justify-end p-6 md:p-10 text-left">
                    <span class="text-sky-300 text-xs md:text-sm font-bold tracking-widest uppercase mb-1">Saijo Pure Water</span>
                    <h3 class="text-white text-xl md:text-2xl font-bold">名水百選に選ばれる自噴水「うちぬき」</h3>
                    <p class="text-slate-200 text-xs md:text-sm mt-2 max-w-2xl">
                        市内約3,000箇所から今も湧き出し続ける清らかな地下水。この水が、抜群の瑞々しさを持つ作物たちの命の源です。
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Specialties Presentation -->
    <section class="py-16 md:py-24 space-y-24 md:space-y-36">

        <!-- Specialty 1: Atago Persimmon -->
        <div id="persimmon" class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="lg:grid lg:grid-cols-12 lg:gap-12 items-center">
                <div class="lg:col-span-5 mb-8 lg:mb-0">
                    <span class="text-sm font-semibold tracking-wider uppercase text-saijo-persimmon mb-2 block">特産品 01</span>
                    <h3 class="text-3xl md:text-4xl font-extrabold text-slate-900 mb-6">
                        愛宕柿 <span class="text-saijo-persimmon">（あたごがき）</span>
                    </h3>
                    <p class="text-slate-600 mb-6 leading-relaxed">
                        愛宕柿は、釣鐘のような美しい形をした西条を代表する大ぶりの渋柿です。そのままでは非常に渋いですが、炭酸ガス等を用いて丁寧に「脱渋（だつじゅう）」を行うことで、驚くほど上品で濃厚な甘みへと生まれ変わります。軒先に吊るされた温もりある光景は、西条の美しい冬の風物詩です。
                    </p>
                    <div class="space-y-4">
                        <div class="flex items-start">
                            <span class="flex-shrink-0 p-1 bg-orange-100 text-saijo-persimmon rounded-lg mr-3">
                                <i data-lucide="check" class="w-5 h-5"></i>
                            </span>
                            <div>
                                <h4 class="font-bold text-slate-900">サクサクから、とろける完熟まで</h4>
                                <p class="text-slate-500 text-sm">最初は程よく締まったサクサク食感、日が経つにつれてスプーンですくえるほどジューシーでとろとろのゼリー状になります。</p>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <span class="flex-shrink-0 p-1 bg-orange-100 text-saijo-persimmon rounded-lg mr-3">
                                <i data-lucide="check" class="w-5 h-5"></i>
                            </span>
                            <div>
                                <h4 class="font-bold text-slate-900">冬を彩る上品な贈り物</h4>
                                <p class="text-slate-500 text-sm">贈答品としても名高く、冬の味覚として全国のファンに愛され続けています。</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="lg:col-span-7 space-y-6">
                    <!-- Image Card using image_f0d2f3.jpg -->
                    <div class="relative rounded-3xl overflow-hidden shadow-2xl aspect-[16/10] group border-4 border-white bg-white">
                        <img src="image_f0d2f3.jpg" 
                             alt="愛宕柿" 
                             class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105">
                        <div class="absolute inset-0 bg-gradient-to-t from-slate-950/50 via-transparent to-transparent flex items-end p-6">
                            <div>
                                <span class="bg-saijo-persimmon text-white text-xs font-bold px-3 py-1 rounded-full shadow">西条の冬を彩る美しい愛宕柿</span>
                            </div>
                        </div>
                    </div>
                    <!-- Dynamic Visual Layout -->
                    <div class="bg-gradient-to-tr from-amber-500 to-orange-600 rounded-3xl p-8 text-white shadow-xl relative overflow-hidden">
                        <div class="absolute right-0 bottom-0 opacity-10">
                            <i data-lucide="sun" class="w-48 h-48"></i>
                        </div>
                        <h4 class="text-xl font-bold mb-4 flex items-center">
                            <i data-lucide="sparkles" class="mr-2"></i> 愛宕柿の「推し」ポイント
                        </h4>
                        <div class="grid md:grid-cols-2 gap-6 relative z-10">
                            <div class="bg-white/10 backdrop-blur-sm rounded-xl p-5 border border-white/20">
                                <h5 class="font-bold text-lg mb-2">熟練の脱渋技術</h5>
                                <p class="text-white/80 text-sm">渋みの元であるタンニンを完全に閉じ込め、本来の圧倒的な糖度（20度近くに達することも）を引き出します。</p>
                            </div>
                            <div class="bg-white/10 backdrop-blur-sm rounded-xl p-5 border border-white/20">
                                <h5 class="font-bold text-lg mb-2">おすすめの食べ方</h5>
                                <p class="text-white/80 text-sm">冷やしてそのままはもちろん、完熟した果肉を凍らせて贅沢な「天然シャーベット」にするのも絶品です！</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Specialty 2: Kinukawa Eggplant -->
        <div id="eggplant" class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="lg:grid lg:grid-cols-12 lg:gap-12 items-center">
                <div class="lg:col-span-7 order-last lg:order-first space-y-6">
                    <!-- Image Card using image_f0d337.jpg -->
                    <div class="relative rounded-3xl overflow-hidden shadow-2xl aspect-[16/10] group border-4 border-white bg-white">
                        <img src="image_f0d337.jpg" 
                             alt="絹皮なす" 
                             class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105">
                        <div class="absolute inset-0 bg-gradient-to-t from-slate-950/50 via-transparent to-transparent flex items-end p-6">
                            <div>
                                <span class="bg-saijo-eggplant text-white text-xs font-bold px-3 py-1 rounded-full shadow">愛媛県西条市産 特産絹皮なす</span>
                            </div>
                        </div>
                    </div>
                    <!-- Dynamic Visual Layout + High School Collaboration (with Official Link) -->
                    <div class="bg-gradient-to-tr from-fuchsia-950 to-purple-800 rounded-3xl p-8 text-white shadow-xl relative overflow-hidden">
                        <div class="absolute left-0 bottom-0 opacity-10">
                            <i data-lucide="graduation-cap" class="w-48 h-48"></i>
                        </div>
                        <h4 class="text-xl font-bold mb-4 flex items-center text-amber-300">
                            <i data-lucide="graduation-cap" class="mr-2"></i> 
                            <a href="https://ehm-saijo-ah.esnet.ed.jp/" target="_blank" rel="noopener noreferrer" class="hover:underline flex items-center space-x-1 decoration-amber-300">
                                <span>西条農業高校</span>
                                <i data-lucide="external-link" class="w-4 h-4 inline-block"></i>
                            </a>
                            <span class="ml-2 font-normal text-sm text-white/90">との共同研究・栽培技術</span>
                        </h4>
                        <p class="text-white/90 text-sm mb-6 leading-relaxed">
                            地元の「<a href="https://ehm-saijo-ah.esnet.ed.jp/" target="_blank" rel="noopener noreferrer" class="font-semibold underline hover:text-amber-200">愛媛県立西条農業高等学校</a>」の生徒たちは、この極上の食感を持つ『絹皮なす』の栽培研究を日々行っています。傷つきやすく安定生産が難しいこのナスを、最新の環境制御技術などを使いながら守り育て、品質の向上や普及PR活動に全力を注ぎました。高校生の情熱が、この伝統野菜の未来を力強く支えています。
                        </p>
                        <div class="grid md:grid-cols-2 gap-6 relative z-10">
                            <div class="bg-white/10 backdrop-blur-sm rounded-xl p-5 border border-white/20">
                                <h5 class="font-bold text-lg mb-2 text-amber-200">「生」でも抜群のジューシーさ</h5>
                                <p class="text-white/80 text-sm">アクが非常に少なく、スライスするとまるでリンゴのように爽やかでほんのり甘い香りが広がります。</p>
                            </div>
                            <div class="bg-white/10 backdrop-blur-sm rounded-xl p-5 border border-white/20">
                                <h5 class="font-bold text-lg mb-2 text-amber-200">おすすめの料理</h5>
                                <p class="text-white/80 text-sm">まずは薄切りを浅漬けにして。または、厚切りを焼きナスにして、口の中でジュワッととろける食感をご堪能ください。</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="lg:col-span-5">
                    <span class="text-sm font-semibold tracking-wider uppercase text-saijo-eggplant mb-2 block">特産品 02</span>
                    <h3 class="text-3xl md:text-4xl font-extrabold text-slate-900 mb-6">
                        絹皮なす <span class="text-saijo-eggplant">（きぬかわなす）</span>
                    </h3>
                    <p class="text-slate-600 mb-6 leading-relaxed">
                        西条市だけで古くから栽培されてきた特別な伝統野菜。写真の通り、張りがありツヤツヤと輝くそのボディ。その名の通り「絹のように極めて薄く柔らかい皮」と、果肉に含まれる圧倒的な水分量が特徴です。大変デリケートで傷つきやすく、市場にあまり出回らない「幻のナス」です。
                    </p>
                    <div class="space-y-4">
                        <div class="flex items-start">
                            <span class="flex-shrink-0 p-1 bg-purple-100 text-saijo-eggplant rounded-lg mr-3">
                                <i data-lucide="check" class="w-5 h-5"></i>
                            </span>
                            <div>
                                <h4 class="font-bold text-slate-900">極薄の皮、口に残らない滑らかさ</h4>
                                <p class="text-slate-500 text-sm">通常のナスの皮のような硬さはなく、皮ごとそのまま柔らかく噛みしめることができます。</p>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <span class="flex-shrink-0 p-1 bg-purple-100 text-saijo-eggplant rounded-lg mr-3">
                                <i data-lucide="check" class="w-5 h-5"></i>
                            </span>
                            <div>
                                <h4 class="font-bold text-slate-900">水を絞るだけで極上の味わい</h4>
                                <p class="text-slate-500 text-sm">名水「うちぬき」をたっぷり吸い込んだ実は、軽く塩もみするだけでまるでフルーツのようなご馳走に早変わりします。</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Specialty 3: Ishizuchi Kurocha -->
        <div id="tea" class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="lg:grid lg:grid-cols-12 lg:gap-12 items-center">
                <div class="lg:col-span-5 mb-8 lg:mb-0">
                    <span class="text-sm font-semibold tracking-wider uppercase text-saijo-tea mb-2 block">特産品 03</span>
                    <h3 class="text-3xl md:text-4xl font-extrabold text-slate-900 mb-6">
                        石鎚黒茶 <span class="text-saijo-tea">（いしづちくろちゃ）</span>
                    </h3>
                    <p class="text-slate-600 mb-6 leading-relaxed">
                        愛媛県西条市小松地域にのみ伝承されてきた、極めてユニークな独自の伝統技法で作られる希少な「二段発酵茶」です。日本にわずか4つしか存在しない大変珍しい「後発酵茶」で、国の無形民俗文化財にも指定されています。手仕事で丹念に仕上げられ、澄んだ黄金色に輝きます。
                    </p>
                    <div class="space-y-4">
                        <div class="flex items-start">
                            <span class="flex-shrink-0 p-1 bg-emerald-100 text-saijo-tea rounded-lg mr-3">
                                <i data-lucide="check" class="w-5 h-5"></i>
                            </span>
                            <div>
                                <h4 class="font-bold text-slate-900">「カビ」と「乳酸菌」の二段階発酵</h4>
                                <p class="text-slate-500 text-sm">まず糸状菌（こうじ菌）で発酵させ、さらに乳酸菌で二度目の発酵を行う、世界的にも極めて珍しい製法を今も守っています。</p>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <span class="flex-shrink-0 p-1 bg-emerald-100 text-saijo-tea rounded-lg mr-3">
                                <i data-lucide="check" class="w-5 h-5"></i>
                            </span>
                            <div>
                                <h4 class="font-bold text-slate-900">すっきり美味しく、体に嬉しい健康茶</h4>
                                <p class="text-slate-500 text-sm">乳酸発酵によるさわやかでフルーティーな酸味は、食事の脂っこさを洗い流し、温活や腸活にも役立つと注目を集めています。</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="lg:col-span-7 space-y-6">
                    <!-- Image Card using image_f0d317.jpg -->
                    <div class="relative rounded-3xl overflow-hidden shadow-2xl aspect-[16/10] group border-4 border-white bg-white">
                        <img src="image_f0d317.jpg" 
                             alt="石鎚黒茶" 
                             class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105">
                        <div class="absolute inset-0 bg-gradient-to-t from-slate-950/50 via-transparent to-transparent flex items-end p-6">
                            <div>
                                <span class="bg-saijo-tea text-white text-xs font-bold px-3 py-1 rounded-full shadow">幻の二段発酵茶「石鎚黒茶」</span>
                            </div>
                        </div>
                    </div>
                    <!-- Dynamic Visual Layout + High School Collaboration (with Official Link) -->
                    <div class="bg-gradient-to-tr from-stone-800 to-emerald-900 rounded-3xl p-8 text-white shadow-xl relative overflow-hidden">
                        <div class="absolute right-0 bottom-0 opacity-10">
                            <i data-lucide="heart" class="w-48 h-48"></i>
                        </div>
                        <h4 class="text-xl font-bold mb-4 flex items-center text-amber-200">
                            <i data-lucide="heart" class="mr-2"></i> 
                            <a href="https://ehm-saijo-ah.esnet.ed.jp/" target="_blank" rel="noopener noreferrer" class="hover:underline flex items-center space-x-1 decoration-amber-300">
                                <span>西条農業高校</span>
                                <i data-lucide="external-link" class="w-4 h-4 inline-block"></i>
                            </a>
                            <span class="ml-2 font-normal text-sm text-white/90">が紡ぐ伝統「石鎚黒茶」の未来</span>
                        </h4>
                        <p class="text-white/90 text-sm mb-6 leading-relaxed">
                            一度は後継者不足により存続の危機に直面した「石鎚黒茶」。その危機を救うため、<a href="https://ehm-saijo-ah.esnet.ed.jp/" target="_blank" rel="noopener noreferrer" class="font-semibold underline hover:text-amber-200">愛媛県立西条農業高等学校</a>の生徒たちが立ち上がりました。伝統の製法（糸状菌発酵＆乳酸発酵）を保存会の方々から学び、学校で独自の製造と研究を行っています。さらに新商品の開発や若い世代への積極的な普及など、素晴らしい伝統の灯火を守り続けています。
                        </p>
                        <div class="grid md:grid-cols-2 gap-6 relative z-10">
                            <div class="bg-white/10 backdrop-blur-sm rounded-xl p-5 border border-white/20">
                                <h5 class="font-bold text-lg mb-2 text-amber-100">黄金に輝く上品な液体</h5>
                                <p class="text-white/80 text-sm">丁寧に淹れると、えも言われぬ美しい黄金〜琥珀色。独特のほのかな酸味と甘みがお茶の概念を優しく広げてくれます。</p>
                            </div>
                            <div class="bg-white/10 backdrop-blur-sm rounded-xl p-5 border border-white/20">
                                <h5 class="font-bold text-lg mb-2 text-amber-100">おすすめの飲み方</h5>
                                <p class="text-white/80 text-sm">温かくして豊かな香りを味わうのはもちろん、冷たく冷やした冷茶は夏の渇きを潤すのに抜群の美味しさです。</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

    </section>

    <!-- Interactive Section: Diagnostic Tool -->
    <section id="diagnostic" class="py-16 md:py-24 bg-gradient-to-b from-stone-50 to-sky-50 border-t border-slate-200">
        <div class="max-w-3xl mx-auto px-4">
            <div class="text-center mb-12">
                <span class="text-sm font-semibold tracking-wider text-saijo-blue uppercase mb-2 block">診断ゲーム</span>
                <h2 class="text-3xl font-bold text-slate-900">今のあなたにぴったりな「西条の恵み」は？</h2>
                <p class="text-slate-600 mt-2">簡単な3つの質問に答えて、今日のあなたに一番おすすめの特産品を診断しましょう！</p>
            </div>

            <!-- Quiz Container -->
            <div id="quiz-box" class="bg-white rounded-3xl p-8 md:p-12 shadow-xl border border-slate-100 transition-all">
                
                <!-- Welcome Screen -->
                <div id="q-intro" class="text-center py-6">
                    <p class="text-lg text-slate-700 mb-8">お腹のすき具合や気分に合わせて、最適な「推し特産品」を選び出します。</p>
                    <button onclick="startQuiz()" class="px-8 py-4 bg-saijo-blue hover:bg-sky-700 text-white font-medium rounded-full shadow-md transition-all">
                        診断をスタートする
                    </button>
                </div>

                <!-- Questions (Hidden initially) -->
                <div id="q-container" class="hidden">
                    <div class="mb-4 flex justify-between items-center text-xs font-semibold text-slate-400">
                        <span id="question-number">質問 1 / 3</span>
                        <div class="w-32 bg-slate-100 h-2 rounded-full overflow-hidden">
                            <div id="progress-bar" class="bg-saijo-blue h-full w-1/3 transition-all duration-300"></div>
                        </div>
                    </div>
                    <h3 id="question-text" class="text-xl font-bold text-slate-800 mb-8">ここに質問テキストが入ります</h3>
                    <div id="answers-container" class="space-y-4">
                        <!-- Buttons will be dynamically inserted here -->
                    </div>
                </div>

                <!-- Result Screen (Hidden initially) -->
                <div id="q-result" class="hidden text-center py-4">
                    <div class="inline-block p-4 bg-slate-100 rounded-full text-slate-700 mb-4" id="result-icon-container">
                        <!-- Icon dynamically generated -->
                    </div>
                    <span class="text-sm font-bold text-slate-400 block mb-1">あなたにおすすめなのは...</span>
                    <h3 id="result-title" class="text-3xl font-extrabold mb-4">結果タイトル</h3>
                    <p id="result-description" class="text-slate-600 mb-8 max-w-lg mx-auto">結果の説明が入ります。</p>
                    <div class="flex justify-center space-x-4">
                        <button onclick="restartQuiz()" class="px-6 py-3 bg-slate-100 hover:bg-slate-200 text-slate-700 font-medium rounded-full transition-all text-sm">
                            もう一度診断する
                        </button>
                        <a id="result-link" href="#" class="px-6 py-3 bg-saijo-blue text-white font-medium rounded-full transition-all text-sm hover:shadow-md">
                            詳しく見る
                        </a>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-slate-900 text-white py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row justify-between items-center">
                <div class="flex items-center space-x-2 mb-6 md:mb-0">
                    <i data-lucide="droplet" class="text-sky-400 w-6 h-6"></i>
                    <span class="font-bold text-lg tracking-wider">西条の恵み「推し」ナビ</span>
                </div>
                <div class="text-sm text-slate-400 text-center md:text-right">
                    <p class="mb-2">このサイトは愛媛県西条市の魅力的な特産品を紹介するプロトタイプです。</p>
                    <p>&copy; 2026 Saijo City Bounty Showcase. Created by Lyra.</p>
                </div>
            </div>
        </div>
    </footer>

    <script>
        // Initialize Lucide Icons
        lucide.createIcons();

        // Quiz State & Data
        const questions = [
            {
                text: "今のあなたのお腹や喉のコンディションは？",
                answers: [
                    { text: "なんだか少し喉が渇いている、または一息つきたい", points: { tea: 3, persimmon: 1, eggplant: 0 } },
                    { text: "小腹が空いていて、甘いものが食べたい気分！", points: { persimmon: 3, tea: 1, eggplant: 0 } },
                    { text: "ヘルシーに、みずみずしくて美味しいお野菜・おかずが食べたい", points: { eggplant: 3, persimmon: 0, tea: 0 } }
                ]
            },
            {
                text: "誰と一緒に楽しみたいですか？",
                answers: [
                    { text: "一人でゆっくり、贅沢で静かなリラックスタイムに", points: { tea: 3, persimmon: 1, eggplant: 1 } },
                    { text: "大切な家族や友人へのお土産・ギフト、食卓のおかずに", points: { persimmon: 2, eggplant: 3, tea: 1 } },
                    { text: "スイーツ代わりに、贅沢な果実味をデザートとして", points: { persimmon: 3, eggplant: 0, tea: 1 } }
                ]
            },
            {
                text: "一番求める「味わい」の要素はどれ？",
                answers: [
                    { text: "驚くほどジューシーで、優しくフルーティーな甘さ", points: { persimmon: 3, eggplant: 2, tea: 0 } },
                    { text: "すっきり爽やかで、ほんのりとした奥深い酸味", points: { tea: 3, eggplant: 1, persimmon: 0 } },
                    { text: "とにかくみずみずしく、素材本来の圧倒的な新鮮さ", points: { eggplant: 3, tea: 0, persimmon: 1 } }
                ]
            }
        ];

        const results = {
            persimmon: {
                title: "甘みあふれる「愛宕柿（あたごがき）」",
                description: "極限まで引き出された甘さとコク、大ぶりの柿が今のあなたにぴったり！とろけるような完熟状態や、冷やしてスプーンですくって食べる贅沢な風合いを楽しんでみてください。",
                colorClass: "text-saijo-persimmon",
                bgClass: "bg-orange-50",
                icon: "sun",
                link: "#persimmon"
            },
            eggplant: {
                title: "みずみずしさ抜群の「絹皮なす」",
                description: "口に含んだ瞬間にジュワッと水分があふれ出る、超ジューシーな「絹皮なす」が最適です。薄くスライスしてお醤油を数滴、またはじっくり焼いた、とろとろの焼きナスが一番のオススメです！",
                colorClass: "text-saijo-eggplant",
                bgClass: "bg-purple-50",
                icon: "leaf",
                link: "#eggplant"
            },
            tea: {
                title: "幻の二段発酵「石鎚黒茶（いしづちくろちゃ）」",
                description: "独自の製法による芳醇な香りと、さわやかな微酸味が癖になる「石鎚黒茶」がおすすめです。疲れた心と体を内側から優しく温め、クリアに整えてくれる至極の1杯をご堪能ください。",
                colorClass: "text-saijo-tea",
                bgClass: "bg-emerald-50",
                icon: "soup",
                link: "#tea"
            }
        };

        let currentQuestionIndex = 0;
        let score = { persimmon: 0, eggplant: 0, tea: 0 };

        function startQuiz() {
            document.getElementById('q-intro').classList.add('hidden');
            document.getElementById('q-container').classList.remove('hidden');
            currentQuestionIndex = 0;
            score = { persimmon: 0, eggplant: 0, tea: 0 };
            showQuestion();
        }

        function showQuestion() {
            const q = questions[currentQuestionIndex];
            document.getElementById('question-number').innerText = `質問 ${currentQuestionIndex + 1} / ${questions.length}`;
            document.getElementById('progress-bar').style.width = `${((currentQuestionIndex + 1) / questions.length) * 100}%`;
            document.getElementById('question-text').innerText = q.text;

            const answersDiv = document.getElementById('answers-container');
            answersDiv.innerHTML = '';

            q.answers.forEach((ans, idx) => {
                const btn = document.createElement('button');
                btn.className = "w-full text-left p-4 rounded-xl border border-slate-200 hover:border-saijo-blue hover:bg-slate-50 transition-all duration-200 focus:outline-none focus:ring-2 focus:ring-saijo-blue/50 text-slate-700 font-medium";
                btn.innerText = ans.text;
                btn.onclick = () => selectAnswer(ans.points);
                answersDiv.appendChild(btn);
            });
        }

        function selectAnswer(points) {
            for (let key in points) {
                score[key] += points[key];
            }

            currentQuestionIndex++;
            if (currentQuestionIndex < questions.length) {
                showQuestion();
            } else {
                showResult();
            }
        }

        function showResult() {
            document.getElementById('q-container').classList.add('hidden');
            const resultDiv = document.getElementById('q-result');
            resultDiv.classList.remove('hidden');

            // Find key with max score
            let maxKey = 'persimmon';
            let maxScore = -1;
            for (let key in score) {
                if (score[key] > maxScore) {
                    maxScore = score[key];
                    maxKey = key;
                }
            }

            const r = results[maxKey];
            document.getElementById('result-title').innerText = r.title;
            document.getElementById('result-title').className = `text-3xl font-extrabold mb-4 ${r.colorClass}`;
            document.getElementById('result-description').innerText = r.description;
            
            // Icon handling
            const iconContainer = document.getElementById('result-icon-container');
            iconContainer.className = `inline-block p-4 rounded-full ${r.colorClass} ${r.bgClass} mb-4`;
            iconContainer.innerHTML = `<i data-lucide="${r.icon}" class="w-10 h-10"></i>`;
            
            // Set link
            const linkBtn = document.getElementById('result-link');
            linkBtn.href = r.link;
            linkBtn.className = `px-6 py-3 text-white font-medium rounded-full transition-all text-sm hover:shadow-md ${maxKey === 'persimmon' ? 'bg-saijo-persimmon hover:bg-orange-600' : maxKey === 'eggplant' ? 'bg-saijo-eggplant hover:bg-fuchsia-950' : 'bg-saijo-tea hover:bg-emerald-900'}`;

            lucide.createIcons();
        }

        function restartQuiz() {
            document.getElementById('q-result').classList.add('hidden');
            startQuiz();
        }
    </script>
</body>
</html>
    
