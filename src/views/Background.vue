<template>
  <div id="Background" class="container-fluid">
    <div class="row">
      <div class="col-lg-12">
        <h3 class="text-center">
         Experiência & Educação 
          <div>
            <img src="../assets/lie2.png" alt="" width="100" />
          </div>
        </h3>
        <ul class="timeline">
          <!-- Item 1 -->
             <li>
            <div class="comego direction-l">
              <div class="flag-wrapper">
                <span class="hexa"></span>
                <span class="flag text-info">Freelancer</span>
                <span class="time-wrapper"
                  ><span class="time bg-info"></span></span
                >
              </div>
              <div class="desc text-center font-italic">
                Desenvolvedor Web Fullstack
              </div>
              <div class="desc text-justify font-italic">
                <p>Faço desenvolvimento web com as várias tecnologias listadas nas minhas habilidades</p>
               
              </div>
            </div>
          </li>
          <li>
            <div class="comego direction-l">
              <div class="flag-wrapper">
                <span class="hexa"></span>
                <span class="flag text-info">Movicel Telecomunicações</span>
                <span class="time-wrapper"
                  ><span class="time bg-info">Junho 2022 - presente</span></span
                >
              </div>
              <div class="desc text-center font-italic">
                Desenvolvedor Web Fullstack
              </div>
              <div class="desc text-justify font-italic">
                <p>
                  Desenvolvimento fullstack de aplicações web com SpringBoot e
                  Laravel. Desenvolvo e consumo API´s para integração com outras
                  aplicações como CRM e Middleware. Utilizo os bancos de dados
                  SQLServer e Mysql.
                </p>
                <p>
                  Para o front end e UI trabalho com Vuejs, Vuetify,
                  Materializecss e Bootstrap respectivamente. Faço manutenção e
                  forneço suporte das aplicações desenvolvidas.
                </p>
                <p>
                  Tambem realizo actividades de gerenciamento de base de dados
                  Mysql e SqlServer. Versionamento de projectos utilizando o Git
                  e GitHub. Hospedagem e deploy de aplicações web em ambiente
                  Linux e Windows. Faço frequentemente deploy de aplicações para
                  o linux.
                </p>
              </div>
            </div>
          </li>
          <li>
            <div class="comego direction-l">
              <div class="flag-wrapper">
                <span class="hexa"></span>
                <span class="flag text-info">Ramossoft Tecnologias</span>
                <span class="time-wrapper"
                  ><span class="time bg-info"
                    >Março 2019 - Junho 2022</span
                  ></span
                >
              </div>
              <div class="desc text-center font-italic">
                Desenvolvedor Web Fullstack
              </div>
              <div class="desc text-justify font-italic">
                <p>
                  Desenvolvimento fullstack de aplicações web com PHP,
                  Javascript e Mysql utilizando Laravel, Vuejs, Vuetify,
                  Materializecss e Bootstrap. Administração e manutenção das
                  aplicações desenvolvidas.
                </p>
                <p>
                  Realização de actividades de gerenciamento de base de dados
                  Mysql. Versionamento de projectos utilizando o Git e GitHub.
                  Hospedagem de aplicações web em ambiente Linux e Windows.
                </p>
                <p>
                  Desenvolvimento e consumo de API's em integração com outras
                  aplicações web. Orientação e suporte a equipe
                </p>
                <p>
                  Projectos: Sistema de Gestão Universitária. Sistema de Gestão
                  de Correspondência. Caderneta Electrónica (Gestão Escolar).
                  Sistema de Gestão de Estagiários.
                </p>
              </div>
            </div>
          </li>
          <li>
            <div class="comego direction-l">
              <div class="flag-wrapper">
                <span class="hexa"></span>
                <span class="flag text-info">Sincron Lda</span>
                <span class="time-wrapper"
                  ><span class="time bg-info"
                    >Janeiro 2015 - Dezembro 2017</span
                  ></span
                >
              </div>
              <div class="desc text-center font-italic">
                Desenvolvedor de Software
              </div>
              <div class="desc text-justify font-italic">
                <p>
                  Desenvolvimento, aplicação e manutenção de Softwares de Gestão
                  Aduaneira
                </p>
              </div>
            </div>
          </li>
          <!-- Item 1 -->
          <li>
            <div class="comego direction-r">
              <div class="flag-wrapper">
                <span class="hexa"></span>
                <span class="flag text-info"
                  >Instituo Superior Politécnico Metropolitano de Angola -
                  IMETRO</span
                >
                <span class="time-wrapper"
                  ><span class="time bg-info">2014 - 2018</span></span
                >
              </div>
              <div class="desc text-center font-italic">
                Ciências da Computação
              </div>
              <div class="desc text-justify font-italic">
                <strong>Descrição: </strong>
                <p>
                  Sou um profissional de Ciência da Computação com uma sólida
                  formação acadêmica e experiência prática em desenvolvimento de
                  software e soluções tecnológicas. Meus estudos em Ciência da
                  Computação me proporcionaram uma base sólida em princípios de
                  programação, algoritmos, estruturas de dados e teoria da
                  computação. Além disso, adquiri habilidades em diversas áreas,
                  como desenvolvimento web, aprendizado de máquina,
                  cibersegurança e análise de dados.
                </p>
              </div>
            </div>
          </li>

          <!-- Item 2 -->
     
          <!-- Item3 -->
       
        </ul>
      </div>
    </div>
  </div>
</template>

<style scoped>
header h1 {
  text-align: center;
  font-weight: bold;
  margin-top: 0;
}

header p {
  text-align: center;
  margin-bottom: 0;
}

.mytext {
  text-align: justify !important;
}

.hexa {
  border: 0px;
  float: left;
  text-align: center;
  height: 35px;
  width: 60px;
  font-size: 22px;
  background: #17a2b8;
  color: #17a2b8;
  position: relative;
  margin-top: 15px;
}

.hexa:before {
  content: "";
  position: absolute;
  left: 0;
  width: 0;
  height: 0;
  border-bottom: 15px solid #17a2b8;
  border-left: 30px solid transparent;
  border-right: 30px solid transparent;
  top: -15px;
}

.hexa:after {
  content: "";
  position: absolute;
  left: 0;
  width: 0;
  height: 0;
  border-left: 30px solid transparent;
  border-right: 30px solid transparent;
  border-top: 15px solid #17a2b8;
  bottom: -15px;
}

.timeline {
  position: relative;
  padding: 0;
  width: 100%;
  margin-top: 20px;
  list-style-type: none;
}

.timeline:before {
  position: absolute;
  left: 50%;
  top: 0;
  content: " ";
  display: block;
  width: 2px;
  height: 100%;
  margin-left: -1px;
  background: rgb(213, 213, 213);
  background: -moz-linear-gradient(
    top,
    rgba(213, 213, 213, 0) 0%,
    rgb(213, 213, 213) 8%,
    rgb(213, 213, 213) 92%,
    rgba(213, 213, 213, 0) 100%
  );
  background: -webkit-gradient(
    linear,
    left top,
    left bottom,
    color-stop(0%, rgba(30, 87, 153, 1)),
    color-stop(100%, rgba(125, 185, 232, 1))
  );
  background: -webkit-linear-gradient(
    top,
    rgba(213, 213, 213, 0) 0%,
    rgb(213, 213, 213) 8%,
    rgb(213, 213, 213) 92%,
    rgba(213, 213, 213, 0) 100%
  );
  background: -o-linear-gradient(
    top,
    rgba(213, 213, 213, 0) 0%,
    rgb(213, 213, 213) 8%,
    rgb(213, 213, 213) 92%,
    rgba(213, 213, 213, 0) 100%
  );
  background: -ms-linear-gradient(
    top,
    rgba(213, 213, 213, 0) 0%,
    rgb(213, 213, 213) 8%,
    rgb(213, 213, 213) 92%,
    rgba(213, 213, 213, 0) 100%
  );
  background: linear-gradient(
    to bottom,
    rgba(213, 213, 213, 0) 0%,
    rgb(213, 213, 213) 8%,
    rgb(213, 213, 213) 92%,
    rgba(213, 213, 213, 0) 100%
  );
  z-index: 5;
}

.timeline li {
  padding: 2em 0;
}

.timeline .hexa {
  width: 16px;
  height: 10px;
  position: absolute;
  background: #17a2b8;
  z-index: 5;
  left: 0;
  right: 0;
  margin-left: auto;
  margin-right: auto;
  top: -30px;
  margin-top: 0;
}

.timeline .hexa:before {
  border-bottom: 4px solid #17a2b8;
  border-left-width: 8px;
  border-right-width: 8px;
  top: -4px;
}

.timeline .hexa:after {
  border-left-width: 8px;
  border-right-width: 8px;
  border-top: 4px solid #17a2b8;
  bottom: -4px;
}

.direction-l,
.direction-r {
  float: none;
  width: 100%;
  text-align: center;
}

.flag-wrapper {
  text-align: center;
  position: relative;
}

.flag {
  position: relative;
  display: block;
  background: rgb(255, 255, 255);
  font-weight: 600;
  z-index: 15;
  padding: 6px 10px;
  text-align: center;
  border-radius: 5px;
}

.direction-l .flag:after,
.direction-r .flag:after {
  content: "";
  position: absolute;
  left: 50%;
  top: -15px;
  height: 0;
  width: 0;
  margin-left: -8px;
  border: solid transparent;
  border-bottom-color: rgb(255, 255, 255);
  border-width: 8px;
  pointer-events: none;
}

.direction-l .flag {
  -webkit-box-shadow: -1px 1px 1px rgba(0, 0, 0, 0.15),
    0 0 1px rgba(0, 0, 0, 0.15);
  -moz-box-shadow: -1px 1px 1px rgba(0, 0, 0, 0.15), 0 0 1px rgba(0, 0, 0, 0.15);
  box-shadow: -1px 1px 1px rgba(0, 0, 0, 0.15), 0 0 1px rgba(0, 0, 0, 0.15);
}

.direction-r .flag {
  -webkit-box-shadow: 1px 1px 1px rgba(0, 0, 0, 0.15),
    0 0 1px rgba(0, 0, 0, 0.15);
  -moz-box-shadow: 1px 1px 1px rgba(0, 0, 0, 0.15), 0 0 1px rgba(0, 0, 0, 0.15);
  box-shadow: 1px 1px 1px rgba(0, 0, 0, 0.15), 0 0 1px rgba(0, 0, 0, 0.15);
}

.time-wrapper {
  display: block;
  position: relative;
  margin: 4px 0 0 0;
  z-index: 14;
  line-height: 1em;
  color: #fff;
}

.direction-l .time-wrapper {
  float: none;
}

.direction-r .time-wrapper {
  float: none;
}

.time {
  background: #333;
  display: inline-block;
  padding: 8px;
}

.desc {
  position: relative;
  margin: 1em 0 0 0;
  padding: 1em;
  background: rgb(254, 254, 254);
  -webkit-box-shadow: 0 0 1px rgba(0, 0, 0, 0.2);
  -moz-box-shadow: 0 0 1px rgba(0, 0, 0, 0.2);
  box-shadow: 0 0 1px rgba(0, 0, 0, 0.2);
  z-index: 15;
}

.direction-l .desc,
.direction-r .desc {
  position: relative;
  margin: 1em 1em 0 1em;
  padding: 1em;
  z-index: 15;
}

.comego {
  -webkit-animation: fadein 1s; /* Safari, Chrome and Opera > 12.1 */
  -moz-animation: fadein 1s; /* Firefox < 16 */
  -ms-animation: fadein 1s; /* Internet Explorer */
  -o-animation: fadein 1s; /* Opera < 12.1 */
  animation: fadein 1s;
}

@keyframes fadein {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}

/* Firefox < 16 */
@-moz-keyframes fadein {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}

/* Safari, Chrome and Opera > 12.1 */
@-webkit-keyframes fadein {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}

/* Internet Explorer */
@-ms-keyframes fadein {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}

@media (min-width: 768px) {
  .timeline {
    width: 660px;
    margin: 0 auto;
    margin-top: 20px;
  }

  .timeline li:after {
    content: "";
    display: block;
    height: 0;
    clear: both;
    visibility: hidden;
  }

  .timeline .hexa {
    left: -28px;
    right: auto;
    top: 8px;
  }

  .timeline .direction-l .hexa {
    left: auto;
    right: -28px;
  }

  .direction-l {
    position: relative;
    width: 310px;
    float: left;
    text-align: right;
  }

  .direction-r {
    position: relative;
    width: 310px;
    float: right;
    text-align: left;
  }

  .flag-wrapper {
    display: inline-block;
  }

  .flag {
    font-size: 18px;
  }

  .direction-l .flag:after {
    left: auto;
    right: -16px;
    top: 50%;
    margin-top: -8px;
    border: solid transparent;
    border-left-color: rgb(254, 254, 254);
    border-width: 8px;
  }

  .direction-r .flag:after {
    top: 50%;
    margin-top: -8px;
    border: solid transparent;
    border-right-color: rgb(254, 254, 254);
    border-width: 8px;
    left: -8px;
  }

  .time-wrapper {
    display: inline;
    vertical-align: middle;
    margin: 0;
  }

  .direction-l .time-wrapper {
    float: left;
  }

  .direction-r .time-wrapper {
    float: right;
  }

  .time {
    padding: 5px 10px;
  }

  .direction-r .desc {
    margin: 1em 0 0 0.75em;
  }
}

@media (min-width: 992px) {
  .timeline {
    width: 800px;
    margin: 0 auto;
    margin-top: 20px;
  }

  .direction-l {
    position: relative;
    width: 380px;
    float: left;
    text-align: right;
  }

  .direction-r {
    position: relative;
    width: 380px;
    float: right;
    text-align: left;
  }
}
</style>

