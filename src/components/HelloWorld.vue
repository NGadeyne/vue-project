<template>
  <div class="greetings">
    <h1 class="green">Nicolas Gadeyne</h1>
    <h3>
      Product Manager Freelance, <br>
      <a href="https://scrum.org/" target="_blank" rel="noopener">SCRUM</a> +
      <a href="https://scaledagileframework.com/" target="_blank" rel="noopener">SAFe</a> + 
      <a href="https://fr.wikipedia.org/wiki/Lean_Six_Sigma" target="_blank" rel="noopener">Lean Six Sigma</a>.
    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
