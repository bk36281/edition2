<template>
  <section class="about">
    <h1>À propos de l'éditeur</h1>

    <p>
      Éditeur indépendant, passionné par la littérature et les projets
      numériques. Retrouvez mon parcours et mes compétences dans mon CV.
    </p>

    <div class="cv">
      <a
        href="/CV_AKT_STAGE.pdf"
        target="_blank"
        rel="noopener"
        class="cv-btn"
      >
        📄 Consulter mon CV
      </a>
    </div>
  </section>
</template>

<style scoped>
.about {
  max-width: 800px;
  margin: 40px auto;
  padding: 20px;
}

.cv {
  margin-top: 20px;
}

.cv-btn {
  padding: 12px 18px;
  background-color: #2c3e50;
  color: white;
  text-decoration: none;
  border-radius: 6px;
  font-weight: bold;
}

.cv-btn:hover {
  background-color: #1a252f;
}
</style>
