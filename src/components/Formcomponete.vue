<template>
    <div>
        <p>Componente de mensagem</p>
        <div>
            <form id="burger-form">
                <div class="input-container">
                    <label for="nome">Nome do cliente:</label>
                    <input type="text" id="nome" name="nome" v-model="nome" placeholder="Digite o seu nome">
                </div>
                <div class="input-container">
                    <label for="pao">Escolha o pão:</label>
                    <select id="pao" name="pao" v-model="pao">
                    
                    </select>
                </div>
            </form>
        </div>
    </div>
  </template>
  
  <script>
  
  
  
  export default {
    name: 'FormComponente',
    components: {
      
  }
  }
  </script>

  <style scoped>
  
  </style>