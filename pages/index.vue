<template>
  <div class="flex flex-col items-center justify-center min-h-screen bg-gray-900">


    <div class="w-300 h-300 mb-20 mt-300  text-center w-200 h-124">
      <svg data-v-2a183b29="" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 200 120" class="h-32 w-64mx-auto">
        <circle data-v-2a183b29="" cx="45" cy="35" r="20" fill="#335599"></circle>
        <rect data-v-2a183b29="" x="50" y="5" width="40" height="65" fill="#FFFF00"></rect> <text data-v-2a183b29=""
          x="50" y="35" font-family="Arial" font-size="40" font-weight="bold" fill="#077378">SpecialAI</text>
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
  
  
  
  