<template>
  <div id="Projects" class="container-fluid">
    <h3 class="text-center">Projetos
      <div>
        <img src="../assets/lie2.png" alt="" width=100>
      </div>
    </h3>
    <div class="row">
  <div class="mb-3 col-lg-4 col-md-4 col-sm-4 col-12" :key="index" v-for="(project,index) in projects">
    <div class="card border-info text-light">
      <div class="card-body  bg-dark">
        <h5 class="card-title">{{project.name}}</h5>
        <p class="card-text text-justify">{{project.desc}}</p>
<!--         <a target="_blank" :href="project.link" class="btn btn-info"><i :class="{'fas fa-external-link-alt': project.button=='Admin Console','fab fa-github':project.button=='Github','fab fa-gitlab':project.button=='Gitlab'}"></i> {{project.button}}</a>
 -->      </div>
    </div>
  </div>
</div>
  </div>
</template>

<script>
export default {
  name : 'Projects',
  data(){
    return{
     
                  
      projects:[{
        name : 'Sistema de Gestão Universitária',
        tehnology : ["HTML","JavaScript","CSS","jQuery","Flask","AWS"],
        desc : "Principal desenvolvedor do projeto. Desenvolvi na Ramossoft",
       
      },
      {
        name : 'Sistema de Gestão de Correspondência',
        tehnology : ["HTML","JavaScript","CSS","jQuery","Flask","AWS"],
        desc : "Desenvolvedor do projeto. Desenvolvi na Ramossoft",
        link : "https://gitlab.com/bhargavkoritala/bookworm.com",
        button : 'Gitlab'
      },
      {
        name : 'Caderneta Electrónica (Gestão Escolar)',
        tehnology : ["Java Socket Programming", "Android Processes and Threads"],
        desc : "Desenvolvedor do projeto. Desenvolvi na Ramossoft",
        link : "https://github.com/bhargavkoritala/Distributed-Systems",
        button : 'Github'
      },
      {
        name : 'Sistema de Gestão de Pedidos de Vendas',
        tehnology : ["VueJS","HTML","JavaScript","CSS","BootStrap"],
        desc : "Desenvolvedor do projeto. Desenvolvi para RZanutto",
        link : "https://github.com/bhargavkoritala/Monster-Attack-Game",
        button : 'Github'
      },
      {
        name : 'Sistema de Gestão de Estagiários',
        tehnology : ["VueJS","HTML","JavaScript","CSS","BootStrap"],
        desc : "Desenvolvedor do projeto. Desenvolvi na Ramossoft",
        link : "https://github.com/bhargavkoritala/SuperQuiz-Game",
        button : 'Github'
      },
     ]
    }
  }
}
</script>

<style scoped>

a:hover{
  color: black;
  background-color: white;
}

</style>

