document.addEventListener('DOMContentLoaded', function () {
  const projets = document.querySelectorAll('.projet-card');

  // Affichage des projets avec animation
  setTimeout(() => {
    projets.forEach((projet, index) => {
      setTimeout(() => {
        projet.classList.add('fade-in');
      }, 300 * index);
    });
  }, 1000);
});
