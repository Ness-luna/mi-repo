pipeline {
  agent any
  stages {
    stage('Clonar codigo') {
      steps {
        git 'https://github.com/Ness-luna/mi-repo.git'
      }
    }
    stage('Compilar') {
      steps{
        sh 'echo "Compilando proyecto"'
      }
  }
    stage('Pruebas'){
      steps{
        sh 'echo "Ejecutando pruebas..."'
      }
    }
  }
}
