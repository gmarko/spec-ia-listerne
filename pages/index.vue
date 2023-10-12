<template>
  <div class="flex flex-col items-center justify-center min-h-screen bg-gray-900">


    <div class="mt-8 text-center">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 200 150" class="h-32 w-32 mx-auto">
        <!-- Círculo rojo -->
        <circle cx="50" cy="50" r="40" fill="#FF0000" />

        <circle cx="150" cy="50" r="30" fill="#FF00FF" />
        <rect x="80" y="10" width="40" height="80" fill="#FFFF00" />


        <!-- Rectángulo verde -->
        <rect x="110" y="30" width="60" height="40" fill="#00FF00" />

        <!-- Triángulo azul -->
        <polygon points="80,130 120,130 100,170" fill="#0000FF" />

        <!-- Línea negra -->
        <line x1="20" y1="180" x2="180" y2="20" stroke="#000000" stroke-width="5" />

        <text x="60" y="35" font-family="Arial" font-size="22" font-weight="bold" fill="#FFFFFF">Special AI</text>
      </svg>
    </div>

    <div class="chat-container bg-gray-700 p-4 rounded-lg fixed bottom-0 left-0 right-0 mb-4">

      <div class="chat-messages">
        <!-- Mensajes del chat -->
        <!-- Ejemplo: <div class="message">Mensaje del chat</div> -->
      </div>

      <div class="flex items-center space-x-2 mt-4">
        <input type="text" class="bg-white rounded-l px-4 py-2 w-full">
        <button @click="enviarMensaje" class="bg-green-500 hover:bg-green-600 text-white font-bold py-2 px-4 rounded-r">
          Enviar
        </button>
        <label class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded cursor-pointer">
          <input type="file" class="hidden" @change="adjuntarArchivo">
          Adjuntar archivos
        </label>
      </div>

    </div>

  </div>
</template>
  
<script>
export default {
  methods: {
    enviarMensaje() {
      // Lógica para enviar mensajes
    },
    adjuntarArchivo(event) {
      // Lógica para manejar archivos adjuntos
    }
  }
}
</script>
  
<style scoped>
/* Estilos específicos para este componente */
</style>
  
  
  
  