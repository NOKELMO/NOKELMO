<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>NOKELMO - Beatmaker Officiel</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <meta name="description" content="NOKELMO - Beatmaker congolais. Écoutez et achetez des beats Trap, Afro, Drill, Rap.">
</head>
<body class="bg-black text-white font-sans">

  <!-- HEADER -->
  <header class="bg-gradient-to-r from-green-600 to-blue-600 p-6 shadow-lg">
    <div class="max-w-7xl mx-auto flex justify-between items-center">
      <h1 class="text-3xl font-bold">NOKELMO</h1>
      <nav class="space-x-6 text-lg">
        <a href="#beats" class="hover:underline">Beats</a>
        <a href="#bio" class="hover:underline">À propos</a>
        <a href="#contact" class="hover:underline">Contact</a>
      </nav>
    </div>
  </header>

  <!-- HERO SECTION -->
  <section class="h-screen bg-cover bg-center flex items-center justify-center text-center" style="background-image: url('https://images.unsplash.com/photo-1504384308090-c894fdcc538d');">
    <div class="bg-black bg-opacity-70 p-10 rounded-xl">
      <h2 class="text-5xl font-bold mb-4">BEATS PAR NOKELMO</h2>
      <p class="text-xl mb-6">Trap | Afro | Drill | Rap</p>
      <a href="#beats" class="bg-green-500 text-black px-6 py-3 rounded-full font-semibold hover:bg-green-400 transition">Écouter mes Beats</a>
    </div>
  </section>

  <!-- BEATS SECTION -->
  <section id="beats" class="py-16 px-6 bg-gray-900">
    <div class="max-w-6xl mx-auto text-center">
      <h3 class="text-4xl font-bold mb-10">🎧 Mes Beats</h3>
      <div class="grid md:grid-cols-3 gap-8">
        <!-- Beat 1 -->
        <div class="bg-gray-800 p-4 rounded-lg shadow-md">
          <h4 class="text-xl font-bold mb-2">Trap Vibe</h4>
          <audio controls class="w-full">
            <source src="ton_beat1.mp3" type="audio/mpeg">
            Ton navigateur ne supporte pas l'audio.
          </audio>
        </div>
        <!-- Beat 2 -->
        <div class="bg-gray-800 p-4 rounded-lg shadow-md">
          <h4 class="text-xl font-bold mb-2">Afro Banger</h4>
          <audio controls class="w-full">
            <source src="ton_beat2.mp3" type="audio/mpeg">
            Ton navigateur ne supporte pas l'audio.
          </audio>
        </div>
        <!-- Beat 3 -->
        <div class="bg-gray-800 p-4 rounded-lg shadow-md">
          <h4 class="text-xl font-bold mb-2">Chill Drill</h4>
          <audio controls class="w-full">
            <source src="ton_beat3.mp3" type="audio/mpeg">
            Ton navigateur ne supporte pas l'audio.
          </audio>
        </div>
      </div>
    </div>
  </section>

  <!-- BIO SECTION -->
  <section id="bio" class="py-16 px-6 bg-black">
    <div class="max-w-4xl mx-auto text-center">
      <h3 class="text-4xl font-bold mb-6">🧠 À propos</h3>
      <p class="text-lg leading-relaxed">
        NOKELMO est un beatmaker du Congo passionné par la musique urbaine. Il mélange les sonorités africaines avec la Trap, la Drill et le Rap moderne pour créer des beats puissants, émotionnels et uniques. Disponible pour collaborations, commandes personnalisées ou achats exclusifs.
      </p>
    </div>
  </section>

  <!-- CONTACT SECTION -->
  <section id="contact" class="py-16 px-6 bg-gray-900">
    <div class="max-w-4xl mx-auto text-center">
      <h3 class="text-4xl font-bold mb-6">📩 Contact</h3>
      <p class="mb-4 text-lg">Intéressé par une collaboration ou un beat ? Contacte-moi :</p>
      <p>Email : <a href="mailto:nokelmo.beats@gmail.com" class="text-green-400 underline">nokelmo.beats@gmail.com</a></p>
      <p>Instagram : <a href="https://instagram.com/nokelmo" class="text-green-400 underline">@nokelmo</a></p>
      <p>YouTube : <a href="https://youtube.com/@nokelmo" class="text-green-400 underline">@nokelmo</a></p>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="bg-black text-center py-6 border-t border-gray-700">
    <p class="text-sm text-gray-400">&copy; 2025 NOKELMO - Tous droits réservés.</p>
  </footer>

</body>
</html>
