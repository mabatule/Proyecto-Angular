pipeline{
    agent any
    tools{
        nodejs "NodeJSMabatule"
    }
    parameters{
        string (name:'container_name', defaultValue:'Pagina web', description:'Nombre del contenedor')
        string (name:'image_name', defaultValue:'Pagina img', description:'Nombre de la image contenedor')
        string (name:'container_port', defaultValue: '80', description:'Puerto que usa')
    }
    stages{
        stage('install')
        {
          steps
          {
              git 'https://github.com/Training-Nice/Proyecto-Angular.git'
              //sh 'npm install'
              dir('/src')
              {

              // some block
              }
          }
        }
    }
}
