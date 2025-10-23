pipeline {
  agent any
  stages {
    stage('Clonar codigo') {
      steps {
        git branch: 'main', url: 'https://github.com/Ness-luna/mi-repo.git'
      }
    }
    stage('Compilar') {
      steps{
        sh 'npm install'
      }
  }
    stage('Pruebas'){
      steps{
        sh 'npm test'
      }
    }
  }
}
