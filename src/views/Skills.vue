<template>
  <div id="Skills" class="container-fluid">
    <h3 class="text-center">Habilidades
      <div>
        <img src="../assets/lie2.png" alt="" width=100>
      </div></h3>
    
    <div>
        <h4 class="font-weight-bold">Linguagens de Programação</h4>
    </div>
    <div class="row">
      <div :key="key" v-for="(value,key) in programmingSkills" class="mb-3 col-lg-4 col-md-4 col-sm-4 col-6">
        <div class="bg-dark rounded p-3">
        <p>
          <i :class="value.icon"></i>
          {{key}}
        </p>
      <!-- <div class="icon">
          <div class="progress border border-secondary">
            <div class="progress-bar bg-info" role="progressbar" aria-valuenow="value" aria-valuemin="0" aria-valuemax="100" :style="{width: value.skillValue+'%'}"></div>
          </div>
      </div> -->
      </div>
      </div>
      
    </div>
    <div>
        <h4 class="font-weight-bold">Web UI</h4>
      </div>

        <div class="row">
      <div :key="key" v-for="(value,key) in webSkills" class="mb-3 col-lg-4 col-md-4 col-sm-4 col-6">
        <div class="bg-dark rounded p-3">
        <p>
          <i :class="value.icon"></i>
          <img v-if="key=='jQuery'" src="../assets/jquery.png" alt="" width=15 height=15>
          {{key}}
        </p>
    <!--   <div class="icon">
          <div class="progress border border-secondary">
            <div class="progress-bar bg-info" role="progressbar" aria-valuenow="value" aria-valuemin="0" aria-valuemax="100" :style="{width: value.skillValue+'%'}"></div>
          </div>
      </div> -->
        </div>
      </div>
    </div>

    
    <div>
        <h4 class="font-weight-bold">Frameworks</h4>
      </div>
    <div class="row">
      <div :key="key" v-for="(value,key) in frameworks" class="mb-3 col-lg-4 col-md-4 col-sm-4 col-6">
        <div class="bg-dark rounded p-3">
        <p>
          <i :class="value.icon"></i>
          {{key}}
        </p>
     <!--  <div class="icon">
          <div class="progress border border-secondary">
            <div class="progress-bar bg-info" role="progressbar" aria-valuenow="value" aria-valuemin="0" aria-valuemax="100" :style="{width: value.skillValue+'%'}"></div>
          </div>
      </div> -->
      <!-- <div class="icon">
          <div class="progress border border-secondary">
            <div class="progress-bar bg-info" role="progressbar" aria-valuenow="value" aria-valuemin="0" aria-valuemax="100" :style="{width: value.skillValue+'%'}"></div>
          </div>
      </div> -->
        </div>
      </div>
      
    </div>
    <div>
      <h4 class="font-weight-bold">Banco de Dados</h4>
    </div>
    <div class="row">
      <div :key="key" v-for="(value,key) in databases" class="mb-3 col-lg-4 col-md-4 col-sm-4 col-6">
          <div class="bg-dark rounded p-3">
          <p>
            <img v-if="key=='MySQL'" style="filter: gray;-webkit-filter: grayscale(1);filter: grayscale(1);" src="../assets/mysql.svg" alt="" width=15 height=15>
            <img v-if="key=='mongoDB'" style="filter: gray;-webkit-filter: grayscale(1);filter: grayscale(1);" src="../assets/mongo.svg" alt="" width=15 height=15>
            <i :class="value.icon"></i>
            {{key}}
          </p>
    <!--   <div class="icon">
          <div class="progress border border-secondary">
            <div class="progress-bar bg-info" role="progressbar" aria-valuenow="value" aria-valuemin="0" aria-valuemax="100" :style="{width: value.skillValue+'%'}"></div>
          </div>
      </div> -->
          </div>
      </div>
      
    </div>
    <div>
        <h4 class="font-weight-bold">Versionamento de código</h4>
      </div>
    <div class="row">
      <div :key="key" v-for="(value,key) in Tools" class="col-lg-4 col-md-4 col-sm-4 col-6">
          <div class="bg-dark p-3 rounded">
            <p>
              <img v-if="key=='Grafana'" style="filter: gray;-webkit-filter: grayscale(1);filter: grayscale(1);" src="../assets/grafana.svg" alt="" width=15 height=15>
              <i :class="value.icon"></i>
              {{key}}
            </p>
         <!--    <div class="icon">
              <div class="progress border border-secondary">
                <div class="progress-bar bg-info" role="progressbar" aria-valuenow="value" aria-valuemin="0" aria-valuemax="100" :style="{width: value.skillValue+'%'}"></div>
              </div>
            </div> -->
          </div>
      </div>
      
    </div>
    <br>
    <div>
        <h4 class="font-weight-bold">Hospedagem / Deploy</h4>
      </div>
    <div class="row">
      <div :key="key" v-for="(value,key) in HostingAndDeploy" class="col-lg-4 col-md-4 col-sm-4 col-6">
          <div class="bg-dark p-3 rounded">
            <p>
              <img v-if="key=='Grafana'" style="filter: gray;-webkit-filter: grayscale(1);filter: grayscale(1);" src="../assets/grafana.svg" alt="" width=15 height=15>
              <i :class="value.icon"></i>
              {{key}}
            </p>
           <!--  <div class="icon">
              <div class="progress border border-secondary">
                <div class="progress-bar bg-info" role="progressbar" aria-valuenow="value" aria-valuemin="0" aria-valuemax="100" :style="{width: value.skillValue+'%'}"></div>
              </div>
            </div> -->
          </div>
      </div>
      
    </div>
  </div>
</template>

<script>
export default {
  name : 'Skills',
  computed:{
    programmingSkills(){
      return {
        "Java" : {
          skillValue : 50,
          icon : "fab fa-java",
          type : "Programming"
        },
        "PHP" : {
          skillValue : 90,
          icon : "fab fa-php",
          type : "Programming"
        },
         "TypeScript" : {
            skillValue : 50,
            icon : "fab fa-ts-square",
            type : "Web"
          },
         "JavaScript" : {
            skillValue : 90,
            icon : "fab fa-js-square",
            type : "Web"
          },
        "C#" : {
          skillValue : 30,
          icon : "fab fa-Csharp",
          type : "Programming"
        },
      }
    },
    webSkills(){
        return{
          "Vuetify" : {
            skillValue : 80,
            icon : "fab fa-vuetify",
            type : "Web"
          },
          "HTML" : {
            skillValue : 90,
            icon : "fab fa-html5",
            type : "Web"
          },
          "jQuery" : {
            skillValue : 50,
            icon : "jquery"
          },
          "CSS" : {
            skillValue : 70,
            icon : "fab fa-css3-alt"
          },
          "BootStrap" : {
            skillValue : 90,
            icon : "fab fa-bootstrap"
          }
        }
    },
    frameworks(){
      return{
        "VueJS" : {
          skillValue : 80,
          icon : "fab fa-vuejs"
        },
        "Laravel" : {
          skillValue : 80,
          icon : "fab fa-laravel"
        },
        "SpringBoot" : {
          skillValue : 50,
          icon : "fab fa-springboot"
        },
        "Aspnet" : {
          skillValue : 30,
          icon : "fab fa-aspnet"
        },
        "Angular" : {
          skillValue : 30,
          icon : "fab fa-aspnet"
        },
      }
    },
    databases(){
      return{
        "MySQL" : {
          skillValue : 80,
          icon : "mysql"
        },
        "SQL Server" : {
          skillValue : 70,
          icon : "sqlserver"
        },
        "PostgreSql" : {
          skillValue : 50,
          icon : "sqlserver"
        },
        "FireBird" : {
          skillValue : 40,
          icon : "sqlserver"
        },
       
      }
    },
    Tools(){
      return{
        "Git" : {
          skillValue : 75,
          icon : "fab fa-git-alt"
        },
        
      }
    },
    HostingAndDeploy(){
      return{
        "CPanel" : {
          skillValue:75 ,
          icon : "fab fa-cpanel-alt"
        },
        "CyberPanel" : {
          skillValue : 75,
          icon : "fab fa-cyberpanel-alt"
        },
        "Servidores Linux e Windows" : {
          skillValue : 90,
          icon : "fab fa-linux-alt"
        },
       
        
      }
    }
  }
}
</script>

<style scoped>

p,i{
  color:white;
}

.progress .progress-bar {
  transition: unset;
}

.jquery{
 background-image: url('../../src/assets/jquery.png');
}
</style>
