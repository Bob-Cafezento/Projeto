<script setup>
</script>

<template>
  <header>
    <a href="Principal.html" id="header">
      <img src="@/assets/imagens/logo-branca.png" title="Logo" width="100%" />
    </a>
    <div class="header-item">
      <a id="cabecalho" href="login.html">Login</a>
    </div>
    <div class="header-item">
      <a id="cabecalho" href="Conta.html">Conta</a>
    </div>
    <div class="header-item">
      <a id="cabecalho" href="Ajuda.html">Ajuda</a>
    </div>
    <div class="progress">Progresso</div>
  </header>

  <RouterView />
</template>

