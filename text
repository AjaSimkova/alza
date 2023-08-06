const toReveal = document.querySelectorAll(".reveal");
console.log();

function Myscroll() {
  for (let i of toReveal) {
    let windowHeight = window.innerHeight;
    let elementPosition = i.getBoundingClientRect().top;

    if (elementPosition < windowHeight * 0.6) {
      i.classList.add("active");
    }
  }
}

window.addEventListener("scroll", Myscroll);
