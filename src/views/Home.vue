<template>
  <div id="home" class="container-fluid">
    <div class="row justify-content-center">
      <div class="container justify-content-center col-lg-6 col-md-6 col-sm-6">
        <img
          class="me img-fluid img-responsive rounded mx-auto d-block"
          src="../assets/perfil.jpg"
          alt=""
        />
        <div class="justify-content-center text-center">
          <!--   <a @mouseover="isHovering=!isHovering" @mouseleave="isHovering=!isHovering" :href="`${pathforPublic}Sri_Sai_Bhargav_Koritala_Resume.pdf`" download="SriSaiBhargav_Resume.pdf">
                   <br>
                    <button class="btn btn-sm btn-outline-dark" :class="{hovering:isHovering}">
                      <i class="fas fa-file-pdf"></i> Currículo
                    </button>
                  </a> -->
        </div>
      </div>
      <div class="align-self-center typewriter col-lg-6 col-md-6 col-sm-6">
        <h3 class="text-center">
          <div class="d-flex justify-content-center">
            <strong class="text-info">Alfredo António Cambundo</strong>
          </div>
        </h3>
        <p>
          Sou um <b>Desenvolvedor de Software Fullstack</b> dedicado e apaixonado, com sólida
          experiência no desenvolvimento de aplicações.
        </p>
        <p>
          Minha abordagem é caracterizada por fortes capacidades analíticas e
          habilidades avançadas de resolução de problemas.
        </p>
        <div class="d-flex justify-content-around">
          <ul>
            <li>
              <a
                target="_blank"
                href="http://linkedin.com/in/alfredo-cambundo-181b82150"
              >
                <i class="fab fa-linkedin-in"></i>
              </a>
            </li>
            <li>
              <a target="_blank" href="https://github.com/FredoAntonio">
                <i class="fab fa-github"></i>
              </a>
            </li>
            <!-- <li>
                        <a target="_blank" href="https://facebook.com/bhargav.kss"><i class="fab fa-facebook-f"></i></a>
                    </li> -->
            <li>
              <a target="_blank" href="mailto:acfred@outlook.com"
                ><i class="far fa-envelope"></i
              ></a>
            </li>
          
          
            <li style="margin-top:10px!important">
              <a
                target="_blank"
                href="https://wa.me/+244998816626"
                ><i class="fab fa-whatsapp" style="font-size: 26px; color: green;"></i
              ></a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
  data() {
    return {
      pathforPublic: process.env.BASE_URL,
      isHovering: false,
    };
  },
};
</script>

<style scoped>
.hovering {
  color: white;
  background-image: black;
}

.me {
  max-width: 100%;
  max-height: 75vh;
}

ul {
  position: relative;
  margin: 0;
  padding: 0;
  display: flex;
}

ul li {
  list-style: none;
}

ul li a {
  position: relative;
  width: 60px;
  height: 60px;
  display: block;
  text-align: center;
  margin: 0 10px;
  border-radius: 50%;
  padding: 6px;
  box-sizing: border-box;
  text-decoration: none;
  box-shadow: 0 0px 0px rgba(0, 0, 0, 1);
  transition: 0.5s;
}

ul li a:hover {
  box-shadow: 0 0px 0px rgba(0, 0, 0, 0.7);
}

ul li a .fa-linkedin-in {
  width: 100%;
  height: 100%;
  display: block;
  background: linear-gradient(0deg, #ffffff, #ffffff);
  border-radius: 50%;
  line-height: calc(60px - 12px);
  font-size: 24px;
  color: #0e76a8;
  transition: 0.5s;
}

ul li a .fa-github {
  width: 100%;
  height: 100%;
  display: block;
  background: linear-gradient(0deg, white, white);
  border-radius: 50%;
  line-height: calc(60px - 12px);
  font-size: 24px;
  color: black;
  transition: 0.5s;
}

ul li a .fa-facebook-f {
  width: 100%;
  height: 100%;
  display: block;
  background: linear-gradient(0deg, #ffffff, #ffffff);
  border-radius: 50%;
  line-height: calc(60px - 12px);
  font-size: 24px;
  color: #3b5998;
  transition: 0.5s;
}

ul li a .fa-envelope {
  width: 100%;
  height: 100%;
  display: block;
  background: linear-gradient(0deg, #ffffff, #ffffff);
  border-radius: 50%;
  line-height: calc(60px - 12px);
  font-size: 24px;
  color: #d44638;
  transition: 0.5s;
}

ul li:nth-child(1) a:hover .fab {
  color: white;
  background: #0e76a8;
}

ul li:nth-child(2) a:hover .fab {
  color: white;
  background: black;
}

ul li:nth-child(3) a:hover .fab {
  color: white;
  background: #3b5998;
}

ul li:nth-child(4) a:hover .far {
  color: white;
  background: #d44638;
}

.typewriter h3 strong {
  color: 2c3e50;
  text-align: center;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  overflow: hidden; /* Ensures the content is not revealed until the animation */
  border-right: 0.15em solid blue; /* The typwriter cursor */
  white-space: nowrap; /* Keeps the content on a single line */
  margin: 0 auto; /* Gives that scrolling effect as the typing happens */
  letter-spacing: 0.15em; /* Adjust as needed */
  animation: typing 3.5s steps(30, end), blink-caret 0.5s step-end infinite;
}

/* The typing effect */
@keyframes typing {
  from {
    width: 0;
  }
  to {
    width: 100%;
  }
}

/* The typewriter cursor effect */
@keyframes blink-caret {
  from,
  to {
    border-color: transparent;
  }
  50% {
    border-color: transparent;
  }
}

h3,
h6 {
  font-style: italic;
}

div p {
  text-align: justify;
}
</style>