<template>
  <div class="about">
    <h1>À propos de moi</h1>

    <p>
      Étudiant en informatique, passionné par le développement web
      et les technologies full stack.
    </p>

    <a
      href="/CV_AKT_STAGE.pdf"
      target="_blank"
      rel="noopener"
      class="cv-btn"
    >
      📄 Consulter mon CV
    </a>
  </div>
</template>

<style scoped>
.about {
  max-width: 800px;
  margin: 40px auto;
  padding: 20px;
}

.cv-btn {
  display: inline-block;
  margin-top: 20px;
  padding: 12px 18px;
  background-color: #2c3e50;
  color: white;
  text-decoration: none;
  border-radius: 6px;
  font-weight: 600;
}

.cv-btn:hover {
  background-color: #1a252f;
}
</style>
