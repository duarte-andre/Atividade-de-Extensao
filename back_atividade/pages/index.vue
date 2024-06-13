<template>
  <div class="vice">
    <header>
      <div class="interface">
        <div class="logo">
          <a href="#">
            <h1>ADAPTAFITNESS</h1>
            <!-- <img src="images/logo.png" alt="Logo "> -->
          </a>
        </div>
        <nav class="menu-desktop">
          <ul>
            <li><a href="#topo-do-site">Início</a></li>
            <li><a href="#especiliadades">Especialidades</a></li>
            <li><a href="#sobre">Sobre</a></li>
            <li><a href="#portfolio">Projetos</a></li>
          </ul>
        </nav>
        <div class="btn-contato">
          <a href="#">
            <button>Contato</button>
          </a>
        </div>
        <div class="btn-abrir-menu" id="btn-menu">
          <i class="bi bi-list"></i>
        </div>
        <div class="menu-mobile" id="menu-mobile">
          <div class="btn-fechar">
            <i class="bi bi-x-lg"></i>
          </div>
          <nav>
            <ul>
              <li><a href="#topo-do-site">Início</a></li>
              <li><a href="#">Especialidades</a></li>
              <li><a href="#">Sobre</a></li>
              <li><a href="#">Projetos</a></li>
              <li><a href="#">Contato</a></li>
            </ul>
          </nav>
        </div>
        <div class="overlay-menu" id="overlay-menu"></div>
      </div>
    </header>

    <main>
      <section class="topo-do-site" id="topo-do-site">
        <div class="interface">
          <div class="flex">
            <div class="txt-topo-site">
              <h1>TRANSFORMANDO DESAFIOS EM OPORTUNIDADES<span>.</span></h1>
              <p>
                Refletindo sobre a vasta gama de aplicativos de atividade
                física, surge a ponderação sobre quantos são direcionados para
                pessoas com deficiência. Essa indagação foi o ponto de partida
                para um desafio transformado em oportunidade. Embarcamos na
                missão de criar uma solução inovadora, promovendo inclusão e
                acessibilidade por meio de aplicativos dedicados, abrindo portas
                para uma experiência inclusiva para todos.
              </p>

              <div class="btn-contato">
                <a href="#">
                  <button>Entre em contato</button>
                </a>
              </div>
            </div>

            <div class="img-topo-site">
              <img
                src="https://img.freepik.com/fotos-gratis/retrato-de-estudante-sorridente-em-uma-cadeira-de-rodas_23-2148844657.jpg"
                alt=""
              />
            </div>
          </div>
        </div>
      </section>
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
      <section class="especiliadades" id="especiliadades">
        <div class="interface">
          <h2 class="titulo">JÁ CONHECE A <span>CADEFI ?</span></h2>
          <div class="flex">
            <div class="especialidades-box">
              <i class="bi bi-card-text"></i>
              <h3>Sobre a Cadefi</h3>
              <p>
                A CADEFI há 20 anos atua na cidade de Hortolândia oferecendo
                tratamento gratuito para pessoas com deficiência física e
                neurológica.
              </p>
            </div>
            <!--especialidades-box-->

            <div class="especialidades-box">
              <i class="bi bi-arrow-through-heart"></i>
              <h3>Missão</h3>
              <p>
                Garantir direitos, gerar qualidade de vida e reabilitar pessoas
                com deficiência por meio de serviços de saúde, educação e
                inclusão social.
              </p>
            </div>
            <!--especialidades-box-->

          <div class="especialidades-box" onclick="window.open('https://www.google.com.br/maps/place/R.+Romualdo+Ferreira+da+Silva,+220+-+Ch%C3%A1caras+Acarai,+Hortol%C3%A2ndia+-+SP,+13187-003/@-22.8976643,-47.2284291,18.75z/data=!4m6!3m5!1s0x94c8bbc5edd25005:0x5563dfc3b508b472!8m2!3d-22.8975477!4d-47.2281788!16s%2Fg%2F11kn34qv6f?entry=ttu', '_blank');">
              <i class="bi bi-pin-fill"></i>
              <h3>Endereço</h3>
              <p>
                R. Romualdo Ferreira da Silva, n° 220 - 
                Chácaras Acarai Hortolândia - SP, 13187-003
              </p>
            </div>

            <!--especialidades-box-->
          </div>
          <!--flex-->
          <br />
          <br />
          <div class="btn-social">
            <a href="https://www.instagram.com/cendefioficial/"
            target="_blank" ><button><i class="bi bi-instagram"></i></button
            ></a>
            <a href="https://www.youtube.com/@CADEFIHortolandia"
            target="_blank" ><button><i class="bi bi-youtube"></i></button
            ></a>
            <a href="https://www.facebook.com/cadefioficial/"
            target="_blank" ><button><i class="bi bi-facebook"></i></button
            ></a>
          </div>
          <!--btn-social-->
        </div>
        <!--interface-->
      </section>
      <!--especiliadades-->

      <section class="sobre" id="sobre">
        <div class="interface">
          <div class="flex">
            <div class="img-sobre">
              <img id="imagenns"
                src="/equipe.png" alt=""/>
            </div>
            <!--img-sobre-->
            
            
            <div class="txt-sobre ">
                <div>
                  <p>
                        <h2>MUITO PRAZER, <span>SOMOS A ADAPTAFITNESS.</span></h2>
                        Na equipe ADAPITA, estamos comprometidos em apresentar soluções inclusivas e eficazes que promovem a acessibilidade para todos. 
                        Adoramos desafios e vemos cada obstáculo como uma oportunidade de crescimento, 
                        buscando constantemente a excelência para atender às necessidades em constante evolução.
                        <br>
                        <br> 
                        Aqui acreditamos que a diversidade é nossa maior força. 
                        Com uma equipe comprometida e apaixonada, 
                        cada membro se empenha diariamente em aprimorar suas habilidades e conhecimentos. 
                        Estamos determinados a superar todas as barreiras para garantir que nossa tecnologia seja acessível a todos, 
                        independentemente das limitações físicas.
                    </p>
                </div>
                
           
              
              <div class="btn-social eitaa">
                <a href="https://www.instagram.com/adapta_fitness/"
                  ><button><i class="bi bi-instagram"></i></button
                ></a>
                <a href="#"
                  ><button><i class="bi bi-youtube"></i></button
                ></a>
                <a href="#"
                  ><button><i class="bi bi-linkedin"></i></button
                ></a>
              </div>
              <!--btn-social-->
            </div>
            <!--txt-sobre-->
          </div>
          <!--flex-->
        </div>
        <!--interface-->4
        
      </section>
      <!--sobre-->
      <br>
      <br>
      <br>
      <br>
      
        
      <h2 class="titulo">VIDAS QUE FORAM <span>TRANSFORMADAS</span> PELO PROJETO! </h2>
      <section class="portfolio" id="portfolio">
    <div class="menu" ref="menu">
      <div class="menu--wrapper">
        <div
          class="menu--item"
          v-for="(item, index) in portfolioItems"
          :key="index"
          ref="items"
        >
          <figure>
            <img :src="item.imageUrl" alt="" />
          </figure>
        </div>
      </div>
    </div>
  </section>
      <!-- portfolio -->

      <section class="novasection">
    <div class="interface">
        <h2 class="titulo">CONTRIBUIÇÕES
        </h2>
        <div class="flex">
            <div class="especialidades-box" onclick="window.open('https://www.cadefi.com.br/como-doar/', '_blank');">
                <i class="bi bi-heart-fill"></i>
                <h3>COMO AJUDAR?</h3>
                <p>A exemplo de doações.</p>
            </div>
            <div class="especialidades-box" onclick="window.open('https://www.instagram.com/adapta_fitness/', '_blank');">
                <i class="bi bi-person-plus"></i>
                <h3>SIGA A GENTE!</h3>
                <p>Para se manter atualizado.</p>
            </div>
            <div class="especialidades-box">
              <i class="bi bi-arrow-down-square-fill"></i>
                <h3>BAIXE NOSSO APLICATIVO.</h3>
                <p>Clique aqui para ir para a página de referência.</p>
                <!-- Adicione conteúdo aqui -->
            </div>
        </div><!--flex-->
    </div><!--interface-->
</section><!--novasection-->

      <section class="formulario">
        <div class="interface">
          <h2 class="titulo">FALE <span>CONOSCO.</span></h2>

          <form action="">
            <input
              type="text"
              name=""
              id=""
              placeholder="Seu nome completo:"
              required
            />
            <input
              type="text"
              name=""
              id=""
              placeholder="Seu e-mail:"
              required
            />
            <input type="text" name="" id="" placeholder="Seu celular:" />
            <textarea
              name=""
              id=""
              placeholder="Sua mensagem"
              required
            ></textarea>
            <div class="btn-enviar"><input type="submit" value="ENVIAR" /></div>
          </form>
        </div>
        <!--interface-->
      </section>
      <!--formulario-->
    </main>

    <footer>
      <div class="interface">
        <div class="line-footer">
          <div class="flex">
            <!-- <div class="logo-footer">
              <img src="/logo.jpeg" alt="Logotipo adapta" />
            </div> -->
            <!--logo-footer-->
            <div class="btn-social">
              <a href="#"
                ><button><i class="bi bi-instagram"></i></button
              ></a>
              <a href="#"
                ><button><i class="bi bi-youtube"></i></button
              ></a>
              <a href="#"
                ><button><i class="bi bi-linkedin"></i></button
              ></a>
            </div>
            <!--btn-social-->
          </div>
        </div>
        <!--line-footer-->
        <div class="line-footer borda">
          <!-- <p>
            <i class="bi bi-envelope-fill"></i>
            <a href="mailto:contato@andre.com.br">contato@andre.com.br</a>
          </p> -->
        </div>
        <!--line-footer-->
      </div>
      <!--interface-->
    </footer>
  </div>
</template>

<script>
import { gsap } from 'gsap';

export default {
  data() {
    return {
      portfolioItems: [
        { imageUrl: 'https://lh3.googleusercontent.com/p/AF1QipPkKdcQyCmevIXqECB5lrrj_gE4seRxOFzMfwSz=s680-w680-h510' },
        { imageUrl: 'https://lh3.googleusercontent.com/p/AF1QipPJSl5WTT5_79ClQRBOtuBj-HAppQLvF_HzB0Ei=s680-w680-h510' },
        { imageUrl: 'https://lh3.googleusercontent.com/p/AF1QipNTiEBA0u5QYQq21gK82vnYmbXShY3j6SK94QhF=s680-w680-h510' },
        { imageUrl: 'https://lh3.googleusercontent.com/p/AF1QipMc6UHliP6nx-oOvddGxKQI-cnh5Zwzb3TURsI2=s680-w680-h510' },
        { imageUrl: 'https://lh3.googleusercontent.com/p/AF1QipNml2AsYMYDu1JOqp5TQYPi4CSff6I-083JlEbg=s680-w680-h510' },
        { imageUrl: 'https://lh3.googleusercontent.com/p/AF1QipOZyNNOZDP9JWem5-6NNWX8OFrZuxYG1QdusHKP=s680-w680-h510' },
        { imageUrl: 'https://scontent.fcpq4-1.fna.fbcdn.net/v/t39.30808-6/294874170_430024389164424_708676550914121397_n.jpg?_nc_cat=110&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeHwqRhOFw_DWwVOAl5ItFuZyytKBK9gr5jLK0oEr2CvmK_vbyxVcDwB2Mduh79XXi06lLhw9K1GN_LSHMYXaemE&_nc_ohc=kCV-VQYz-PEQ7kNvgFGHubT&_nc_ht=scontent.fcpq4-1.fna&oh=00_AYDAF3uXH3sdcHeTPmytiuy-7a3RIf11tEhyAOwVyKHJsA&oe=667107FD' },
        { imageUrl: 'https://portalhortolandia.com.br/wp-content/uploads/2021/01/CADEFI.jpg' },
      ],
      scrollSpeed: 0,
      oldScrollY: 0,
      scrollY: 0,
      y: 0,
      isDragging: false,
      touchStart: 0,
      touchX: 0,
      menuWidth: 0,
      itemWidth: 0,
      wrapWidth: 0
    };
  },
  mounted() {
    this.$nextTick(() => {
      this.initializeVariables();
      this.addEventListeners();
      this.render();
    });
  },
  methods: {
    initializeVariables() {
      this.$refs.menu.addEventListener('resize', () => {
        this.menuWidth = this.$refs.menu.clientWidth;
        this.itemWidth = this.$refs.items[0].clientWidth;
        this.wrapWidth = this.$refs.items.length * this.itemWidth;
      });
      this.menuWidth = this.$refs.menu.clientWidth;
      this.itemWidth = this.$refs.items[0].clientWidth;
      this.wrapWidth = this.$refs.items.length * this.itemWidth;
    },
    addEventListeners() {
      window.addEventListener('resize', () => {
        this.menuWidth = this.$refs.menu.clientWidth;
        this.itemWidth = this.$refs.items[0].clientWidth;
        this.wrapWidth = this.$refs.items.length * this.itemWidth;
      });

      this.$refs.menu.addEventListener('mousewheel', this.handleMouseWheel);

      this.$refs.menu.addEventListener('touchstart', this.handleTouchStart);
      this.$refs.menu.addEventListener('touchmove', this.handleTouchMove);
      this.$refs.menu.addEventListener('touchend', this.handleTouchEnd);

      this.$refs.menu.addEventListener('mousedown', this.handleTouchStart);
      this.$refs.menu.addEventListener('mousemove', this.handleTouchMove);
      this.$refs.menu.addEventListener('mouseleave', this.handleTouchEnd);
      this.$refs.menu.addEventListener('mouseup', this.handleTouchEnd);

      this.$refs.menu.addEventListener('selectstart', () => { return false });
    },
    handleMouseWheel(e) {
      this.scrollY -= e.deltaY * 0.9;
    },
    handleTouchStart(e) {
      this.touchStart = e.clientX || e.touches[0].clientX;
      this.isDragging = true;
      this.$refs.menu.classList.add('is-dragging');
    },
    handleTouchMove(e) {
      if (!this.isDragging) return;
      this.touchX = e.clientX || e.touches[0].clientX;
      this.scrollY += (this.touchX - this.touchStart) * 2.5;
      this.touchStart = this.touchX;
    },
    handleTouchEnd() {
      this.isDragging = false;
      this.$refs.menu.classList.remove('is-dragging');
    },
    lerp(v0, v1, t) {
      return v0 * (1 - t) + v1 * t;
    },
    dispose(scroll) {
      gsap.set(this.$refs.items, {
        x: (i) => {
          return i * this.itemWidth + scroll;
        },
        modifiers: {
          x: (x, target) => {
            const s = gsap.utils.wrap(-this.itemWidth, this.wrapWidth - this.itemWidth, parseInt(x));
            return `${s}px`;
          }
        }
      });
    },
    render() {
      requestAnimationFrame(this.render);
      this.y = this.lerp(this.y, this.scrollY, .1);
      this.dispose(this.y);

      this.scrollSpeed = this.y - this.oldScrollY;
      this.oldScrollY = this.y;

      gsap.to(this.$refs.items, {
        skewX: -this.scrollSpeed * .2,
        rotate: this.scrollSpeed * .01,
        scale: 1 - Math.min(100, Math.abs(this.scrollSpeed)) * 0.003
      });
    }
  }
};
</script>

<style>
/* ESTILO GERAL */
@import url("https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap");
@import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css");
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Poppins", sans-serif;
}

.vice {
  background-color: black;
}

.interface {
  max-width: 1280px;
  margin: 0 auto;
}

.flex {
  display: flex;
}

.btn-contato button {
  padding: 10px 40px;
  font-size: 18px;
  font-weight: 600;
  background-color: #0eacdb;
  border: 0;
  border-radius: 30px;
  cursor: pointer;
  transition: 0.2s;
}

h2.titulo {
  color: #fff;
  font-size: 38px;
  text-align: center;
}

h2.titulo span {
  color: #0eacdb;
}

button:hover,
form .btn-enviar input:hover {
  box-shadow: 0px 0px 8px #0eacdb;
  transform: scale(1.05);
}

/* ESTILO DO CABEÇALHO */
header {
  padding: 40px 4%;
}

header > .interface {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

header a {
  color: #5c5c5c;
  text-decoration: none;
  display: inline-block;
  transition: 0.2s;
}

header nav.menu-desktop a:hover {
  color: #fff;
  transform: scale(1.05);
}

header nav ul {
  list-style-type: none;
}

header nav.menu-desktop ul li {
  display: inline-block;
  padding: 0 40px;
}

/* ESTILO DO MENU MOBILE */

.btn-abrir-menu {
  display: none;
}

.btn-abrir-menu i {
  color: #0eacdb;
  font-size: 40px;
}

.menu-mobile {
  background-color: #000;
  height: 100vh;
  position: fixed;
  top: 0;
  right: 0;
  z-index: 99999;
  width: 0%;
  overflow: hidden;
  transition: 0.5s;
}

.menu-mobile.abrir-menu {
  width: 70%;
}

.menu-mobile.abrir-menu ~ .overlay-menu {
  display: block;
}

.menu-mobile .btn-fechar {
  padding: 20px 5%;
}

.menu-mobile .btn-fechar i {
  color: #0eacdb;
  font-size: 30px;
}

.menu-mobile nav ul {
  text-align: right;
}

.menu-mobile nav ul li a {
  color: #fff;
  font-size: 20px;
  font-weight: 300;
  padding: 20px 8%;
  display: block;
}

.menu-mobile nav ul li a:hover {
  background-color: #0eacdb;
  color: #000;
}

.overlay-menu {
  background-color: #000000df;
  width: 100%;
  height: 100%;
  position: fixed;
  top: 0;
  left: 0;
  z-index: 88888;
  display: none;
}

/* ESTILO DO TOPO DO SITE */
section.topo-do-site {
  padding: 40px 4%;
  height: 80vh;
}

section.topo-do-site .flex {
  align-items: center;
  justify-content: center;
  gap: 90px;
}

.topo-do-site h1 {
  color: #fff;
  font-size: 42px;
  line-height: 40px;
}

.topo-do-site .txt-topo-site h1 span {
  color: #0eacdb;
}

.topo-do-site .txt-topo-site p {
  color: #fff;
  margin: 40px 0;
}

.topo-do-site .img-topo-site img {
  position: relative;
  animation: flutuar 2s ease-in-out infinite alternate;
}

@keyframes flutuar {
  0% {
    top: 0;
  }

  100% {
    top: 30px;
  }
}

/* ESTILO DAS ESPECIALIDADES */
section.especiliadades {
  padding: 40px 4%;
  /* height: 80vh; */
}

section.especiliadades .flex {
  gap: 60px;
}

.especiliadades .especialidades-box {
  color: #fff;
  padding: 40px;
  border-radius: 20px;
  margin-top: 45px;
  transition: 0.2s;
}

.especiliadades .especialidades-box:hover {
  transform: scale(1.05);
  box-shadow: 0 0 20px #ffffff78;
}

.especiliadades .especialidades-box i {
  font-size: 70px;
  color: #0eacdb;
}

.especiliadades .especialidades-box h3 {
  font-size: 28px;
  margin: 15px 0;
}

/* ESTILO DO SOBRE */
section.sobre {
  padding: 80px 4%;
  height: 65vh;
}

section.sobre .flex {
  align-items: center;
  gap: 60px;
}

.sobre .txt-sobre {
  color: #fff;
  margin-left: 100px;
  display: flex;

}

.sobre .txt-sobre h2 {
  font-size: 40px;
  line-height: 40px;
  margin-bottom: 30px;
}

.sobre .txt-sobre h2 span {
  color: #0eacdb;
  display: block;
}

.sobre .txt-sobre p {
  margin: 20px 0;
  text-align: justify;
}

.btn-social button {
  width: 60px;
  height: 60px;
  border-radius: 50%;
  border: none;
  background-color: #0eacdb;
  font-size: 22px;
  cursor: pointer;
  margin: 0 5px;
  transition: 0.2s;
}

/* ESTILO DO PORTFÓLIO */
.portfolio {
  padding: 100px 8%;
  position: relative;
  overflow-x: hidden;
}

.menu {
  overflow: hidden;
  cursor: grab;
  width: 100%;
  position: relative;
  z-index: 1;
  align-items: center;
  justify-content: center;
  height:70vh;
}

.menu.is-dragging {
  cursor: grabbing;
}

.menu--wrapper {
  counter-reset: count;
  display: flex;
  position: absolute;
  z-index: 1;
  top: 0;
  left: 0;
  transition: transform 0.5s ease;
}

.menu--item {
  counter-increment: count;
  position: absolute;
  z-index: 1;
  top: 0;
  left: 0;
  height: 500px;
  padding: 0 1vw;
  overflow: hidden;
  width: 35vw;
  border-radius: 20px;
  
}

.menu--item figure {
  position: absolute;
  display: block;
  user-select: none;
  -webkit-appearance: none;
  padding: 0;
  border: none;
  outline: none;
  box-shadow: none;
  cursor: pointer;
  width: 100%;
  height: 100%;
  overflow: hidden;
  pointer-events: none;
  transform-origin: center;
  border-radius: 20px;
  object-fit: cover;
}

.menu--item figure img {
  position: absolute;
  z-index: 1;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
  vertical-align: middle;
  transform-origin: center;
}

.menu--item figure:before {
  position: absolute;
  z-index: 2;
  bottom: 1vw;
  left: 1vw;
  display: inline-block;
  content: "0" counter(count);
  color: #ffffff;
  font-size: 3vw;
}

.menu--item:nth-child(n+10):before {
  content: counter(count);
}


section.novasection {
    padding: 80px 4%;
    background-color: #242424;
}

section.novasection .interface {
    max-width: 1280px;
    margin: 0 auto;
}

section.novasection .titulo {
    color: #fff;
    text-align: center;
    margin-bottom: 40px;
}

section.novasection .flex {
    gap: 60px;
}

section.novasection .especialidades-box {
    color: #fff;
    padding: 40px;
    border-radius: 20px;
    margin-top: 45px;
    transition: .2s;
    cursor: pointer;
}

section.novasection .especialidades-box:hover {
    transform: scale(1.05);
    box-shadow: 0 0 20px #ffffff78;
}

section.novasection .especialidades-box i {
    font-size: 70px;
    color: #0eacdb;
}

section.novasection .especialidades-box h3 {
    font-size: 28px;
    margin: 15px 0;
}

/* Estilo do popup */
.popup {
    position: fixed;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    background-color: #fff;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.2);
    z-index: 1000;
}

.popup-overlay {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.5);
    z-index: 999;
    display: none;
}


/* ESTILO DO FORMULÁRIO DE CONTATO */
section.formulario {
  padding: 80px 4%;
}

form {
  max-width: 500px;
  margin: 0 auto;
  display: flex;
  justify-content: center;
  flex-direction: column;
  gap: 10px;
  margin-top: 40px;
}

form input,
form textarea {
  width: 100%;
  background-color: #242424;
  border: 0;
  outline: 0;
  padding: 20px 15px;
  border-radius: 15px;
  color: #fff;
  font-size: 18px;
}

form textarea {
  resize: none;
  max-height: 200px;
}

form .btn-enviar {
  margin-top: 20px;
  text-align: center;
}

form .btn-enviar input {
  width: 120px;
  background-color: #0eacdb;
  color: #000;
  font-weight: 700;
  cursor: pointer;
  transition: 0.2s;
}

/* ESTILO DO RODAPÉ */

footer {
  padding: 40px 4%;
  box-shadow: 0 0 40px 10px #ffffff1d;
}

footer .flex {
  justify-content: space-between;
}

footer .line-footer {
  padding: 20px 0;
}

.borda {
  border-top: 2px solid #0eacdb;
}

footer .line-footer p i {
  color: #0eacdb;
  font-size: 22px;
}

footer .line-footer p a {
  color: #fff;
}

@media screen and (max-width: 1020px) {
  /* CLASSES GERAIS */
  .flex {
    flex-direction: column;
  }

  .topo-do-site .flex {
    flex-direction: column-reverse;
  }

  h2.titulo {
    font-size: 34px;
    line-height: 30px;
  }

  /* CABEÇALHO */
  .menu-desktop,
  .btn-contato {
    display: none;
  }

  /* TOPO DO SITE */

  section.topo-do-site .flex {
    gap: 40px;
  }

  section.topo-do-site {
    padding: 20px 8%;
  }

  .topo-do-site h1 {
    font-size: 30px;
  }

  .topo-do-site .img-topo-site img {
    width: 100%;
  }

  /* ESPECIALIDADES */
  section.especiliadades {
    padding: 40px 8%;
  }

  /* SOBRE */
  section.sobre {
    padding: 80px 8%;
  }

  .sobre .txt-sobre h2 {
    font-size: 34px;
    line-height: 35px;
    text-align: center;
   
  }

  .btn-social {
    text-align: center;
  }

  .img-sobre img {
    width: 100%;
  }

  /* PORTFÓLIO */
  section.portfolio {
    padding: 80px 8%;
  }

  .img-port {
    width: 100%;
    max-width: 360px;
    margin: 0 auto;
  }

  section.portfolio .flex {
    gap: 60px;
  }

  /* RODAPÉ */
  footer .flex {
    flex-direction: column;
    gap: 30px;
  }

  footer .line-footer {
    text-align: center;
  }

}
#imagenns{
  display: flex;
  width: 120%;
  height: auto;
  transition: all .5s ease-in-out;
  border-radius: 20px;
} 

#imagenns:hover{
    transform: scale(1.35);
    border-radius: 0;
}
.eitaa{
    position: relative;
    top:8.25rem;
    left: 3rem;
}
.eitaa a{
    display: flex;
    margin-bottom: 1rem;
}
</style>