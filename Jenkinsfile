pipeline {
  agent any
  stages {
    stage('Inicio') {
      steps {
        echo 'Hola desde el stage inicio'
      }
    }
    stage('Test2') {
      agent any
      steps {
        echo 'Hola desde stage 2'
      }
    }
  }
}