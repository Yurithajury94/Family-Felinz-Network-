# Family-Felinz-Network-
Family Felinz Network -The Adult Animated Comedy 

45 minute Runtime 

https://www.imdb.com/title/tt37540233/?ref_=ext_shr

Think Boondocks meets Rick and Morty, with the lyrical fire of Atlanta and the swagger of a midnight cypher. The Family Felinz Network is a bold, irreverent adult animated comedy that dives high-stakes world of hip-hop—through the eyes of two rap superstar brothers yuri tha Jury straight Shooter

English

Director: Yuri tha Jury writer: Terrence Trice Producer: Terrence Trice

Cast: Yuri tha Jury straight Shooter Terrence Trice Thomas Mckenny Actavious Jordan Torre Trice

<!DOCTYPE html><html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Family Felinz Network — Watch Now</title>
  <meta name="description" content="Stream Family Felinz Network and see cast, crew, and ratings pulled from IMDb via the OMDb API." />
  <link rel="preconnect" href="https://cdn.jsdelivr.net" crossorigin>
  <script src="https://cdn.jsdelivr.net/npm/hls.js@1.5.8/dist/hls.min.js" defer></script>
  <script src="https://cdn.tailwindcss.com" defer></script>
  <style>
    body { opacity: 0; transition: opacity .4s ease; }
    body.ready { opacity: 1; }
    .poster-mask { background: linear-gradient(90deg, rgba(0,0,0,0.85) 0%, rgba(0,0,0,0.6) 40%, rgba(0,0,0,0.2) 100%); }
    .backdrop { filter: blur(12px) brightness(.65); transform: scale(1.06); }
  </style>
  <meta property="og:type" content="video.movie" />
  <meta property="og:title" content="Family Felinz Network — Watch Now" />
  <meta property="og:description" content="Adult animated comedy-drama. Stream it here and see details from IMDb." />
  <meta property="og:image" content="/poster.jpg" />
  <meta name="twitter:card" content="summary_large_image" />
  <script id="jsonld" type="application/ld+json">{}</script>
</head>
<body class="bg-zinc-950 text-zinc-100">
  <script>
    window.SITE_CONFIG = {
      imdbId: "tt37540233", // Family Felinz Network IMDb ID
      omdbApiKey: "a3d40a89c9d928c3f8aefb402a60d907",
      streamUrl: null,
      fallbackPoster: "/poster.jpg",
      fallbackBackdrop: "/backdrop.jpg",
      trailerEmbedUrl: "https://www.youtube.com/embed/vGl8yyJuVio",
      ctaUrl: null,
      availability: "Free to watch",
      legalNotice: "IMDb data displayed via OMDb API. This site is not affiliated with IMDb.",
      fullFilmEmbedUrl: "https://www.youtube.com/embed/xJQ1Ky2sVt4"
    };
  </script>
  <header class="sticky top-0 z-40 backdrop-blur bg-black/40 border-b border-white/5">
    <div class="max-w-6xl mx-auto px-4 py-3 flex items-center justify-between">
      <div class="flex items-center gap-3">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" class="w-7 h-7" fill="currentColor"><path d="M3 6.75A2.75 2.75 0 0 1 5.75 4h12.5A2.75 2.75 0 0 1 21 6.75v10.5A2.75 2.75 0 0 1 18.25 20H5.75A2.75 2.75 0 0 1 3 17.25V6.75Zm3.25-.25a.75.75 0 0 0-.75.75v9.5c0 .414.336.75.75.75h11.5a.75.75 0 0 0 .75-.75v-9.5a.75.75 0 0 0-.75-.75H6.25Z"/></svg>
        <span class="font-semibold tracking-tight">Family Felinz Network — Stream</span>
      </div>
      <a id="imdbLink" href="#" target="_blank" rel="noopener" class="text-yellow-400 hover:text-yellow-300 text-sm">View on IMDb</a>
    </div>
  </header>
  <main id="app" class="min-h-screen">
    <section id="hero" class="relative">
      <img id="backdrop" alt="Backdrop" class="absolute inset-0 w-full h-full object-cover backdrop opacity-60" />
      <div class="poster-mask absolute inset-0"></div>
      <div class="relative max-w-6xl mx-auto px-4 py-14 grid lg:grid-cols-[280px_1fr] gap-8 items-start">
        <img id="poster" alt="Poster" class="w-56 h-auto rounded-xl shadow-2xl ring-1 ring-white/10" />
        <div>
          <div class="flex items-center gap-3 mb-3">
            <span id="availability" class="px-2 py-1 rounded bg-emerald-500/20 text-emerald-200 text-xs uppercase tracking-wide"></span>
            <span id="ratingBadge" class="px-2 py-1 rounded bg-white/10 text-white text-xs hidden"></span>
          </div>
          <h1 id="title" class="text-3xl md:text-5xl font-extrabold leading-tight"></h1>
          <p id="meta" class="mt-2 text-zinc-300"></p>
          <p id="plot" class="mt-4 text-zinc-200 max-w-3xl"></p>
          <div class="mt-5 flex flex-wrap gap-3">
            <button id="watchBtn" class="px-5 py-3 rounded-2xl bg-white/95 text-black font-semibold hover:bg-white transition">▶ Watch now</button>
            <a id="ctaBtn" href="#" target="_blank" rel="noopener" class="hidden px-5 py-3 rounded-2xl bg-indigo-500 text-white font-semibold hover:bg-indigo-400">Get access</a>
            <a id="trailerBtn" href="#" target="_blank" rel="noopener" class="px-5 py-3 rounded-2xl bg-white/10 text-white font-semibold hover:bg-white/20">Watch trailer</a>
          </div>
          <div id="ratings" class="mt-6 text-sm text-zinc-300"></div>
        </div>
      </div>
    </section>
  </main>
  <div id="watchModal" class="fixed inset-0 bg-black/80 hidden items-center justify-center p-4 z-50">
    <div class="bg-zinc-900 w-full max-w-5xl rounded-2xl overflow-hidden shadow-2xl ring-1 ring-white/10">
      <div class="flex items-center justify-between px-4 py-3 border-b border-white/10">
        <h3 class="font-semibold">Now Playing — <span id="modalTitle"></span></h3>
        <button id="closeModal" class="text-zinc-300 hover:text-white">✕</button>
      </div>
      <div class="relative bg-black">
        <iframe id="embed" class="w-full aspect-video" allow="autoplay; fullscreen; picture-in-picture"></iframe>
      </div>
      <div class="px-4 py-3 text-xs text-zinc-400 border-t border-white/10">
        <span id="legal"></span>
      </div>
    </div>
  </div>
  <footer class="max-w-6xl mx-auto px-4 py-10 text-xs text-zinc-400">
    <p>© <span id="year"></span> Family Felinz Network. <span id="legalFooter"></span></p>
  </footer>
  <script>
    const $ = id => document.getElementById(id);
    async function fetchOmdb(id, key) {
      const res = await fetch(`https://www.omdbapi.com/?i=${id}&plot=full&r=json&apikey=${key}`);
      const data = await res.json();
      if (data.Response === 'False') throw new Error(data.Error);
      return data;
    }
    function setText(id, text) { const el = $(id); if (el) el.textContent = text || '—'; }
    function show(el, on = true) { el.classList[on ? 'remove' : 'add']('hidden'); }
    async function main() {
      document.body.classList.add('ready');
      const cfg = window.SITE_CONFIG;
      $('imdbLink').href = `https://www.imdb.com/title/${cfg.imdbId}/`;
      setText('availability', cfg.availability);
      $('trailerBtn').href = cfg.trailerEmbedUrl;
      setText('legal', cfg.legalNotice);
      $('legalFooter').textContent = cfg.legalNotice;
      $('year').textContent = new Date().getFullYear();
      try {
        const omdb = await fetchOmdb(cfg.imdbId, cfg.omdbApiKey);
        setText('title', `${omdb.Title} (${omdb.Year})`);
        setText('meta', [omdb.Rated, omdb.Runtime, omdb.Genre].filter(Boolean).join(' • '));
        setText('plot', omdb.Plot);
        setText('ratingBadge', `IMDb ${omdb.imdbRating}/10`);
        $('poster').src = omdb.Poster;
        $('backdrop').src = omdb.Poster;
        $('watchBtn').addEventListener('click', () => {
          $('modalTitle').textContent = omdb.Title;
          $('embed').src = cfg.fullFilmEmbedUrl;
          show($('watchModal'), true);
        });
        $('closeModal').addEventListener('click', () => {
          $('embed').src = '';
          show($('watchModal'), false);
        });
      } catch (e) {
        console.error(e);
        setText('plot', 'Could not load IMDb data.');
      }
    }
    main();
  </script>
</body>
</html>

https://thetvdb.com/movies/family-felinz-network#artwork

https://www.themoviedb.org/movie/1524801-family-felinz-network

Think Boondocks meets Rick and Morty, with the lyrical fire of Atlanta and the swagger of a midnight cypher. The Family Felinz Network is a bold, irreverent adult animated comedy that dives high-stakes world of hip-hop—through the eyes of two rap superstar brothers yuri tha Jury straight Shooter


English

Director: Yuri tha Jury 
writer: Terrence Trice 
Producer: Terrence Trice 

Cast:
Yuri tha Jury 
straight Shooter 
Terrence Trice 
Thomas Mckenny 
Actavious Jordan 
Torre Trice 

https://yurithajury.gumroad.com/l/nzghph

https://patreon.com/FamilyFelinzNetwork?utm_medium=unknown&utm_source=join_link&utm_campaign=creatorshare_creator&utm_content=copyLink

https://filmfreeway.com/projects/3820728

https://en.m.wikipedia.org/wiki/User:Yurithajury94
