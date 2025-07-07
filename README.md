<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>NOKELMO - Beatmaker Portfolio</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-black text-white font-sans">

  <!-- HEADER AVEC LOGO PERSO -->
  <header class="bg-gradient-to-r from-green-700 to-blue-700 p-4 shadow-xl">
    <div class="max-w-7xl mx-auto flex justify-between items-center">
      <div class="flex items-center gap-4">
        <img src="/mnt/data/ChatGPT Image 6 juil. 2025, 18_38_23.png" alt="Logo Nokelmo" class="w-14 h-14 rounded-full">
        <h1 class="text-3xl font-bold">NOKELMO</h1>
      </div>
      <nav class="space-x-6 text-lg">
        <a href="#beats" class="hover:underline">Beats</a>
        <a href="#bio" class="hover:underline">Bio</a>
        <a href="#contact" class="hover:underline">Contact</a>
      </nav>
    </div>
  </header>

  <!-- SECTION HERO -->
  <section class="relative h-[80vh] bg-cover bg-center flex items-center justify-center text-center" style="background-image: url('https://images.unsplash.com/photo-1585386959984-a4155222f270');">
    <div class="bg-black bg-opacity-70 p-10 rounded-xl">
      <h2 class="text-5xl font-bold mb-4">🎼 NOKELMO - Beatmaker Congolais</h2>
      <p class="text-xl mb-6">Trap | Afro | Drill | Rap</p>
      <a href="#beats" class="bg-green-500 text-black px-6 py-3 rounded-full font-semibold hover:bg-green-400 transition">Écouter & Télécharger</a>
    </div>
  </section>

  <!-- SECTION BEATS AVEC TÉLÉCHARGEMENT -->
  <section id="beats" class="py-16 px-6 bg-gray-900">
    <div class="max-w-6xl mx-auto text-center">
      <h3 class="text-4xl font-bold mb-10">🎧 Beats à vendre</h3>
      <div class="grid md:grid-cols-3 gap-8">
        <div class="bg-gray-800 p-4 rounded-lg shadow-lg">
          <h4 class="text-xl font-bold mb-2">Trap Vibe</h4>
          <audio controls class="w-full mb-2">
            <source src="beats/trap-vibe.mp3" type="audio/mpeg">
          </audio>
          <a href="beats/trap-vibe.mp3" download class="bg-green-500 text-black px-4 py-2 rounded-full font-semibold hover:bg-green-400 transition">Télécharger - $20</a>
        </div>
        <div class="bg-gray-800 p-4 rounded-lg shadow-lg">
          <h4 class="text-xl font-bold mb-2">Afro Banger</h4>
          <audio controls class="w-full mb-2">
            <source src="beats/afro-banger.mp3" type="audio/mpeg">
          </audio>
          <a href="beats/afro-banger.mp3" download class="bg-green-500 text-black px-4 py-2 rounded-full font-semibold hover:bg-green-400 transition">Télécharger - $35</a>
        </div>
        <div class="bg-gray-800 p-4 rounded-lg shadow-lg">
          <h4 class="text-xl font-bold mb-2">Drill Power</h4>
          <audio controls class="w-full mb-2">
            <source src="beats/drill-power.mp3" type="audio/mpeg">
          </audio>
          <a href="beats/drill-power.mp3" download class="bg-green-500 text-black px-4 py-2 rounded-full font-semibold hover:bg-green-400 transition">Télécharger - $50</a>
        </div>
      </div>
    </div>
  </section>

  <!-- BIOGRAPHIE -->
  <section id="bio" class="py-16 px-6 bg-black">
    <div class="max-w-4xl mx-auto text-center">
      <h3 class="text-4xl font-bold mb-6">🧠 À propos de NOKELMO</h3>
      <p class="text-lg leading-relaxed">
        Beatmaker congolais passionné, NOKELMO mélange des sonorités modernes avec les racines africaines pour produire des beats puissants et originaux. Que ce soit pour des projets Trap, Afrobeat, Drill ou Rap, ses productions font vibrer la scène urbaine.
      </p>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact" class="py-16 px-6 bg-gray-900">
    <div class="max-w-4xl mx-auto text-center">
      <h3 class="text-4xl font-bold mb-6">📩 Contact</h3>
      <p class="mb-4 text-lg">Tu veux collaborer ou commander un beat sur mesure ?</p>
      <p>Email : <a href="mailto:beatznokelmo@gmail.com" class="text-green-400 underline">nokelmo.beats@gmail.com</a></p>
      <p>Instagram : <a href="https://instagram.com/nokelmo.officiel" class="text-green-400 underline">@nokelmo</a></p>
      <p>YouTube : <a href="https://youtube.com/@nokelmo" class="text-green-400 underline">@nokelmo</a></p>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="bg-black text-center py-6 border-t border-gray-700">
    <p class="text-sm text-gray-400">&copy; 2025 NOKELMO - Tous droits réservés.</p>
  </footer>

</body>
</html>
