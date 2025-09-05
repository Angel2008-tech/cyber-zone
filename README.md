<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cuscatrips - Viajes en El Salvador</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="font-sans bg-gray-50 text-gray-800">

  <!-- Header -->
  <header class="bg-green-600 text-white shadow-md">
    <div class="container mx-auto flex justify-between items-center p-4">
      <h1 class="text-2xl font-bold">Cuscatrips</h1>
      <nav>
        <ul class="flex space-x-6">
          <li><a href="#inicio" class="hover:text-yellow-300">Inicio</a></li>
          <li><a href="#tours" class="hover:text-yellow-300">Tours</a></li>
          <li><a href="#nosotros" class="hover:text-yellow-300">Nosotros</a></li>
          <li><a href="#contacto" class="hover:text-yellow-300">Contacto</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <section id="inicio" class="bg-cover bg-center h-[70vh] flex items-center justify-center text-center" style="background-image: url('https://images.unsplash.com/photo-1526772662000-3f88f10405ff?auto=format&fit=crop&w=1400&q=80');">
    <div class="bg-black bg-opacity-50 p-6 rounded-xl">
      <h2 class="text-4xl md:text-6xl font-bold text-white mb-4">Descubre El Salvador</h2>
      <p class="text-lg text-gray-200 mb-6">Playas, montañas y cultura con Cuscatrips</p>
      <a href="#tours" class="bg-yellow-400 text-black px-6 py-3 rounded-full font-semibold hover:bg-yellow-300 transition">Explorar Tours</a>
    </div>
  </section>

  <!-- Tours -->
  <section id="tours" class="py-16 container mx-auto">
    <h3 class="text-3xl font-bold text-center mb-10">Nuestros Tours</h3>
    <div class="grid md:grid-cols-3 gap-8">
      <div class="bg-white rounded-2xl shadow-lg overflow-hidden">
        <img src="https://images.unsplash.com/photo-1617196034915-6e8f08f66f0a?auto=format&fit=crop&w=800&q=80" alt="Playa El Tunco" class="h-48 w-full object-cover">
        <div class="p-5">
          <h4 class="text-xl font-semibold mb-2">Playa El Tunco</h4>
          <p class="text-gray-600">Disfruta del surf, atardeceres mágicos y ambiente relajado.</p>
        </div>
      </div>
      <div class="bg-white rounded-2xl shadow-lg overflow-hidden">
        <img src="https://images.unsplash.com/photo-1600100727946-3c4b8f4c5e1b?auto=format&fit=crop&w=800&q=80" alt="Ruta de las Flores" class="h-48 w-full object-cover">
        <div class="p-5">
          <h4 class="text-xl font-semibold mb-2">Ruta de las Flores</h4>
          <p class="text-gray-600">Un recorrido por pueblos coloniales, café y artesanías.</p>
        </div>
      </div>
      <div class="bg-white rounded-2xl shadow-lg overflow-hidden">
        <img src="https://images.unsplash.com/photo-1584147741050-9c66216a8c1e?auto=format&fit=crop&w=800&q=80" alt="Volcán de Izalco" class="h-48 w-full object-cover">
        <div class="p-5">
          <h4 class="text-xl font-semibold mb-2">Volcán de Izalco</h4>
          <p class="text-gray-600">Aventura y senderismo en uno de los volcanes más icónicos.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Nosotros -->
  <section id="nosotros" class="bg-green-100 py-16">
    <div class="container mx-auto text-center">
      <h3 class="text-3xl font-bold mb-6">Sobre Nosotros</h3>
      <p class="max-w-2xl mx-auto text-lg text-gray-700">
        En <span class="font-semibold">Cuscatrips</span> creemos que viajar es más que moverse de un lugar a otro: es conectar con la cultura, la naturaleza y la historia de El Salvador. Nuestro equipo te guiará para que vivas experiencias auténticas, seguras y memorables.
      </p>
    </div>
  </section>

  <!-- Contacto -->
  <section id="contacto" class="py-16 container mx-auto">
    <h3 class="text-3xl font-bold text-center mb-10">Contáctanos</h3>
    <form class="max-w-xl mx-auto bg-white p-8 rounded-2xl shadow-lg">
      <div class="mb-4">
        <label class="block text-left font-semibold">Nombre</label>
        <input type="text" class="w-full border rounded-lg px-3 py-2 mt-2" placeholder="Tu nombre">
      </div>
      <div class="mb-4">
        <label class="block text-left font-semibold">Correo</label>
        <input type="email" class="w-full border rounded-lg px-3 py-2 mt-2" placeholder="tu@correo.com">
      </div>
      <div class="mb-4">
        <label class="block text-left font-semibold">Mensaje</label>
        <textarea class="w-full border rounded-lg px-3 py-2 mt-2" rows="4" placeholder="Escribe tu mensaje..."></textarea>
      </div>
      <button type="submit" class="bg-green-600 text-white px-6 py-3 rounded-full font-semibold hover:bg-green-500 transition">Enviar</button>
    </form>
  </section>

  <!-- Footer -->
  <footer class="bg-green-700 text-white text-center py-6">
    <p>&copy; 2025 Cuscatrips. Todos los derechos reservados.</p>
  </footer>

</body>
</html>
