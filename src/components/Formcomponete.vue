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
                    <option value="">Selecione o seu pão</option>
                    <option value="Integral">Integral</option>
                    </select>
                </div>
                <div class="input-container">
                    <label for="carne">Escolha a carne do seu Burger:</label>
                    <select id="carne" name="carne" v-model="carne">
                    <option value="">Selecione o tipo de carne</option>
                    <option value="Maminha">Maminha</option>
                    </select>
                </div>
                <div class="input-container">
                    <label for="opcionais">Selecione os opcionais:</label>
                    <div class="checkbox-container">
                        <input type="checkbox" name="opcionais" v-model="opicionais" value="Salame">
                        <span>Salame</span>
                    </div>
                </div>
                <div class="input-container">
                        <input type="submit" name="submit-btn" value="Criar meu Burger">                       
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