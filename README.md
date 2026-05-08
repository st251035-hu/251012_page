<!DOCTYPE html>
<html lang="ja" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>アニメ「七つの大罪」非公式解説サイト</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Serif+JP:wght@400;700;900&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        serif: ['"Noto Serif JP"', 'serif'],
                    },
                    colors: {
                        'sin-red': '#B91C1C',
                        'sin-gold': '#D97706',
                        'sin-dark': '#111827',
                    }
                }
            }
        }
    </script>
    <style>
        /* カスタムスクロールバー */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #111827;
        }
        ::-webkit-scrollbar-thumb {
            background: #B91C1C;
            border-radius: 4px;
        }
        .hero-bg {
            background: radial-gradient(circle at center, #374151 0%, #111827 100%);
            position: relative;
        }
        .hero-bg::before {
            content: '';
            position: absolute;
            top: 0; left: 0; right: 0; bottom: 0;
            background-image: url('data:image/svg+xml,%3Csvg width="60" height="60" viewBox="0 0 60 60" xmlns="http://www.w3.org/2000/svg"%3E%3Cg fill="none" fill-rule="evenodd"%3E%3Cg fill="%23b91c1c" fill-opacity="0.05"%3E%3Cpath d="M36 34v-4h-2v4h-4v2h4v4h2v-4h4v-2h-4zm0-30V0h-2v4h-4v2h4v4h2V6h4V4h-4zM6 34v-4H4v4H0v2h4v4h2v-4h4v-2H6zM6 4V0H4v4H0v2h4v4h2V6h4V4H6z"/%3E%3C/g%3E%3C/g%3E%3C/svg%3E');
            opacity: 0.5;
            z-index: 0;
        }
    </style>
</head>
<body class="font-serif bg-sin-dark text-gray-200 antialiased selection:bg-sin-red selection:text-white">

    <!-- ナビゲーション -->
    <nav class="fixed w-full z-50 bg-sin-dark/90 backdrop-blur-sm border-b border-sin-red/30">
        <div class="max-w-6xl mx-auto px-4">
            <div class="flex justify-between items-center h-16">
                <a href="#" class="text-2xl font-black text-white tracking-widest drop-shadow-md">
                    <span class="text-sin-red">七</span>つの大罪<span class="text-sm font-normal ml-2 text-gray-400">解説録</span>
                </a>
                <div class="hidden md:flex space-x-8">
                    <a href="#synopsis" class="hover:text-sin-red transition-colors duration-300">あらすじ</a>
                    <a href="#characters" class="hover:text-sin-red transition-colors duration-300">キャラクター</a>
                    <a href="#world" class="hover:text-sin-red transition-colors duration-300">世界観・用語</a>
                </div>
            </div>
        </div>
    </nav>

    <!-- ヒーローセクション -->
    <header class="hero-bg min-h-[70vh] flex items-center justify-center pt-16 relative overflow-hidden">
        <div class="absolute inset-0 bg-black/40 z-0"></div>
        <div class="relative z-10 text-center px-4 max-w-4xl mx-auto">
            <p class="text-sin-gold tracking-[0.2em] mb-4 text-sm md:text-base font-bold">
                人と、人ならざるものの世界が、分かたれてはいなかった古の物語。
            </p>
            <h1 class="text-5xl md:text-7xl font-black text-white mb-6 tracking-widest drop-shadow-2xl">
                <span class="text-sin-red">七</span>つの大罪
            </h1>
            <p class="text-lg md:text-xl text-gray-300 leading-relaxed max-w-2xl mx-auto mb-8">
                伝説の逆賊〈七つの大罪〉。彼らは本当に国を裏切った悪党なのか？<br>
                王女エリザベスと、少年メリオダスの出会いが、世界を変える旅の始まりとなる。
            </p>
            <a href="#synopsis" class="inline-block bg-sin-red hover:bg-red-700 text-white font-bold py-3 px-8 rounded-full transition-all duration-300 transform hover:scale-105 shadow-lg shadow-red-900/50">
                物語の扉を開く
            </a>
        </div>
    </header>

    <!-- あらすじ -->
    <section id="synopsis" class="py-20 px-4">
        <div class="max-w-4xl mx-auto">
            <div class="flex items-center justify-center mb-12">
                <div class="h-[1px] w-16 bg-sin-red"></div>
                <h2 class="text-3xl font-bold mx-6 tracking-widest text-white">あらすじ</h2>
                <div class="h-[1px] w-16 bg-sin-red"></div>
            </div>
            
            <div class="bg-gray-800/50 p-8 md:p-12 rounded-2xl border border-gray-700 shadow-2xl relative">
                <div class="absolute top-0 left-1/2 -translate-x-1/2 -translate-y-1/2 text-sin-red text-6xl opacity-20">"</div>
                <p class="text-lg leading-loose text-gray-300 mb-6">
                    いまだ人と、ひとならざるものの世界が、分かたれてはいなかった古の物語。<br>
                    絶大なる魔力を有し、人々から敬われ、時に恐れられる存在<strong>〈聖騎士〉</strong>に守られた「リオネス王国」。
                </p>
                <p class="text-lg leading-loose text-gray-300">
                    王国の王女エリザベスは、たった一人国を離れ、ある者たちを探す旅に出ていた。<br>
                    それは最強最悪の騎士団として恐れられ、国を裏切り全聖騎士を敵に回した罪人たち——<strong>〈七つの大罪〉</strong>。<br>
                    辿り着いた一軒の酒場で、エリザベスは店主を名乗る少年・メリオダスに出会う。それは、彼女と〈七つの大罪〉たち、そして世界の命運を一変させる驚天動地の冒険の始まりだった！
                </p>
            </div>
        </div>
    </section>

    <!-- キャラクター -->
    <section id="characters" class="py-20 bg-gray-900 px-4">
        <div class="max-w-6xl mx-auto">
            <div class="flex items-center justify-center mb-16">
                <div class="h-[1px] w-16 bg-sin-gold"></div>
                <h2 class="text-3xl font-bold mx-6 tracking-widest text-white">登場人物</h2>
                <div class="h-[1px] w-16 bg-sin-gold"></div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                
                <!-- メリオダス -->
                <div class="group bg-gray-800 border border-gray-700 rounded-xl overflow-hidden hover:border-sin-red transition-all duration-300 shadow-lg hover:shadow-sin-red/20 hover:-translate-y-1">
                    <div class="h-32 bg-gradient-to-br from-red-900 to-gray-900 flex items-center justify-center relative">
                        <span class="text-6xl text-white/10 font-black absolute">WRATH</span>
                        <h3 class="text-2xl font-bold text-white z-10">メリオダス</h3>
                    </div>
                    <div class="p-6">
                        <div class="text-sin-red text-sm font-bold mb-2">憤怒の罪（ドラゴン・シン）</div>
                        <p class="text-gray-400 text-sm leading-relaxed">
                            本作の主人公。移動酒場「豚の帽子」亭の店長にして、〈七つの大罪〉の団長。見た目は少年だが、底知れぬ力と過去を秘めている。セクハラが玉に瑕。
                        </p>
                    </div>
                </div>

                <!-- エリザベス -->
                <div class="group bg-gray-800 border border-gray-700 rounded-xl overflow-hidden hover:border-blue-500 transition-all duration-300 shadow-lg hover:shadow-blue-500/20 hover:-translate-y-1">
                    <div class="h-32 bg-gradient-to-br from-blue-900 to-gray-900 flex items-center justify-center relative">
                        <span class="text-6xl text-white/10 font-black absolute">PRINCESS</span>
                        <h3 class="text-2xl font-bold text-white z-10">エリザベス</h3>
                    </div>
                    <div class="p-6">
                        <div class="text-blue-400 text-sm font-bold mb-2">リオネス王国第3王女</div>
                        <p class="text-gray-400 text-sm leading-relaxed">
                            本作のヒロイン。聖騎士によるクーデターから王国を救うため、〈七つの大罪〉を探す旅に出た。泣き虫だが強い信念と優しさを持つ。
                        </p>
                    </div>
                </div>

                <!-- ホーク -->
                <div class="group bg-gray-800 border border-gray-700 rounded-xl overflow-hidden hover:border-pink-500 transition-all duration-300 shadow-lg hover:shadow-pink-500/20 hover:-translate-y-1">
                    <div class="h-32 bg-gradient-to-br from-pink-900 to-gray-900 flex items-center justify-center relative">
                        <span class="text-6xl text-white/10 font-black absolute">PIG</span>
                        <h3 class="text-2xl font-bold text-white z-10">ホーク</h3>
                    </div>
                    <div class="p-6">
                        <div class="text-pink-400 text-sm font-bold mb-2">残飯処理騎士団団長</div>
                        <p class="text-gray-400 text-sm leading-relaxed">
                            メリオダスの相棒で、人語を話す豚。「豚の帽子」亭の看板豚であり、客の残飯を処理するのが仕事。自称「最強の戦士」。
                        </p>
                    </div>
                </div>

                <!-- ディアンヌ -->
                <div class="group bg-gray-800 border border-gray-700 rounded-xl overflow-hidden hover:border-orange-500 transition-all duration-300 shadow-lg hover:shadow-orange-500/20 hover:-translate-y-1">
                    <div class="p-6 h-full flex flex-col justify-between">
                        <div>
                            <h3 class="text-xl font-bold text-white mb-1">ディアンヌ</h3>
                            <div class="text-orange-500 text-sm font-bold mb-4">嫉妬の罪（サーペント・シン）</div>
                            <p class="text-gray-400 text-sm leading-relaxed">巨人族の少女。メリオダスのことが大好きで、彼に近づく女性には嫉妬心を燃やす。巨大な体と大地を操る魔力を持つ。</p>
                        </div>
                    </div>
                </div>

                <!-- バン -->
                <div class="group bg-gray-800 border border-gray-700 rounded-xl overflow-hidden hover:border-purple-500 transition-all duration-300 shadow-lg hover:shadow-purple-500/20 hover:-translate-y-1">
                    <div class="p-6 h-full flex flex-col justify-between">
                        <div>
                            <h3 class="text-xl font-bold text-white mb-1">バン</h3>
                            <div class="text-purple-500 text-sm font-bold mb-4">強欲の罪（フォックス・シン）</div>
                            <p class="text-gray-400 text-sm leading-relaxed">「不死身のバン」の異名を持つ。どんな傷も瞬時に回復する不老不死の肉体を持つ。メリオダスとは親友であり喧嘩仲間。</p>
                        </div>
                    </div>
                </div>

                <!-- キング -->
                <div class="group bg-gray-800 border border-gray-700 rounded-xl overflow-hidden hover:border-green-500 transition-all duration-300 shadow-lg hover:shadow-green-500/20 hover:-translate-y-1">
                    <div class="p-6 h-full flex flex-col justify-between">
                        <div>
                            <h3 class="text-xl font-bold text-white mb-1">キング</h3>
                            <div class="text-green-500 text-sm font-bold mb-4">怠惰の罪（グリズリー・シン）</div>
                            <p class="text-gray-400 text-sm leading-relaxed">本名は妖精王ハーレクイン。普段は空中に浮遊するクッションを抱えた少年の姿をしているが、緊張するとふくよかなおっさんの姿になる。</p>
                        </div>
                    </div>
                </div>

                <!-- ゴウセル -->
                <div class="group bg-gray-800 border border-gray-700 rounded-xl overflow-hidden hover:border-pink-300 transition-all duration-300 shadow-lg hover:shadow-pink-300/20 hover:-translate-y-1">
                    <div class="p-6 h-full flex flex-col justify-between">
                        <div>
                            <h3 class="text-xl font-bold text-white mb-1">ゴウセル</h3>
                            <div class="text-pink-300 text-sm font-bold mb-4">色欲の罪（ゴート・シン）</div>
                            <p class="text-gray-400 text-sm leading-relaxed">中性的な容姿で、常に無表情かつ抑揚のない話し方をする。人の心や記憶を読み取ったり、操作したりする魔力を持つ。</p>
                        </div>
                    </div>
                </div>

                <!-- マーリン -->
                <div class="group bg-gray-800 border border-gray-700 rounded-xl overflow-hidden hover:border-indigo-500 transition-all duration-300 shadow-lg hover:shadow-indigo-500/20 hover:-translate-y-1">
                    <div class="p-6 h-full flex flex-col justify-between">
                        <div>
                            <h3 class="text-xl font-bold text-white mb-1">マーリン</h3>
                            <div class="text-indigo-500 text-sm font-bold mb-4">暴食の罪（ボア・シン）</div>
                            <p class="text-gray-400 text-sm leading-relaxed">ブリタニア一の魔術士と称される妖艶な美女。常に不敵な笑みを浮かべ、様々な魔法具（マジックアイテム）を開発している。</p>
                        </div>
                    </div>
                </div>

                <!-- エスカノール -->
                <div class="group bg-gray-800 border border-gray-700 rounded-xl overflow-hidden hover:border-yellow-500 transition-all duration-300 shadow-lg hover:shadow-yellow-500/20 hover:-translate-y-1">
                    <div class="p-6 h-full flex flex-col justify-between">
                        <div>
                            <h3 class="text-xl font-bold text-white mb-1">エスカノール</h3>
                            <div class="text-yellow-500 text-sm font-bold mb-4">傲慢の罪（ライオン・シン）</div>
                            <p class="text-gray-400 text-sm leading-relaxed">夜は気弱で痩せ細った老人だが、日の出と共に体が巨大化し、性格も「傲慢」に変化する。正午には無敵の強さを誇る。</p>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- 世界観・用語 -->
    <section id="world" class="py-20 bg-gray-800 px-4 border-t border-gray-700">
        <div class="max-w-4xl mx-auto">
            <div class="flex items-center justify-center mb-12">
                <div class="h-[1px] w-16 bg-gray-500"></div>
                <h2 class="text-3xl font-bold mx-6 tracking-widest text-white">世界観・用語</h2>
                <div class="h-[1px] w-16 bg-gray-500"></div>
            </div>

            <div class="space-y-6">
                <!-- 用語1 -->
                <div class="bg-gray-900 p-6 rounded-lg border-l-4 border-sin-red shadow-md">
                    <h3 class="text-xl font-bold text-white mb-2">ブリタニア</h3>
                    <p class="text-gray-400 leading-relaxed">
                        物語の舞台となる大陸。人間族、巨人族、妖精族、魔神族、女神族など、多様な種族が存在する（または過去に存在していた）地。
                    </p>
                </div>
                <!-- 用語2 -->
                <div class="bg-gray-900 p-6 rounded-lg border-l-4 border-blue-500 shadow-md">
                    <h3 class="text-xl font-bold text-white mb-2">聖騎士（せいきし）</h3>
                    <p class="text-gray-400 leading-relaxed">
                        一騎当千の力を誇る、王国を守護する騎士たち。魔力を操り、強大な戦闘力を持つため、一般の兵士や民衆からは畏怖の対象となっている。
                    </p>
                </div>
                <!-- 用語3 -->
                <div class="bg-gray-900 p-6 rounded-lg border-l-4 border-purple-600 shadow-md">
                    <h3 class="text-xl font-bold text-white mb-2">聖戦（せいせん）</h3>
                    <p class="text-gray-400 leading-relaxed">
                        三千年前、魔神族と、人間・女神・妖精・巨人の四種族連合との間で起こった大規模な戦争。この戦いにより魔神族は封印されたと伝えられている。
                    </p>
                </div>
                <!-- 用語4 -->
                <div class="bg-gray-900 p-6 rounded-lg border-l-4 border-sin-gold shadow-md">
                    <h3 class="text-xl font-bold text-white mb-2">神器（じんぎ）</h3>
                    <p class="text-gray-400 leading-relaxed">
                        リオネス国王から〈七つの大罪〉のメンバーそれぞれに下賜された特別な武器。持ち主の魔力を最大限に引き出すことができる。
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- フッター -->
    <footer class="bg-sin-dark py-8 border-t border-gray-800 text-center">
        <div class="max-w-6xl mx-auto px-4">
            <p class="text-gray-500 text-sm mb-4">
                ※当サイトはアニメ「七つの大罪」の非公式ファンサイト（解説用サンプル）です。<br>
                公式の制作会社、出版社等とは一切関係ありません。
            </p>
            <p class="text-gray-600 font-bold tracking-widest text-lg">
                <span class="text-sin-red">THE SEVEN DEADLY SINS</span>
            </p>
        </div>
    </footer>

</body>
</html>
