
document.addEventListener("DOMContentLoaded", () => {
  const header = document.querySelector("header");
  header.style.opacity = 0;
  header.style.transform = "translateY(-20px)";
  setTimeout(() => {
    header.style.transition = "opacity 1s ease, transform 1s ease";
    header.style.opacity = 1;
    header.style.transform = "translateY(0)";
  }, 100);

  const form = document.querySelector("form");
  if (form) {
    form.addEventListener("submit", (e) => {
      e.preventDefault();
      alert("Message sent! (This is a demo.)");
      form.reset();
    });
  }
});
