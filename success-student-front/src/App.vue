<script setup>
</script>

<template>
  <header>
      <RouterLink to="/" id="header">
        <img src="@/assets/imagens/logo-branca.png" title="Logo" width="100" />
      </RouterLink>
    <div class="header-item">
      <RouterLink id="cabecalho" to="/login">Login</RouterLink>
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

