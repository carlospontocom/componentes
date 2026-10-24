<script setup></script>

<template>
  <div class="info">
    <div class="info-content">
      <h3 class="title">Precisa de ajuda?</h3>
      <p>Entre em contato conosco para tirar dúvidas e saber mais
        sobre nossas funcionalidades.</p>
      <button class="btn-info">
        <img width="48" height="48" src="https://img.icons8.com/emoji/48/e-mail.png" alt="e-mail"/>
        <p>Clique aqui enviar e-mail</p>
      </button>
    </div>
  </div>
</template>


<style scoped>
.info {
  padding: 5rem 2rem;
  background-color: orange;
}

.info-content{
  border-radius: 5rem;
  box-shadow: 0 3px 5px #00000050;
  background-color: #f2f2f2;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  padding: 3rem 1rem;
  gap: 15px;
  max-width: 768px;
  margin: 0 auto;
}

.btn-info{
  border: 0;
  cursor: pointer;
  display: flex;
  align-items: center;
  gap: 10px;
  border: 2px solid blueviolet;
  background-color: #fff;
  color: blueviolet;
  font-size: 1.3rem;
  padding: 4px 2rem;
  border-radius: 2rem;
}
</style>
