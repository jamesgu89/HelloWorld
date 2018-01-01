pipeline {
  agent {
    docker {
      image 'maven:3.3.9-jdk-8'
    }
    
  }
  stages {
    stage('Initialize') {
      steps {
        echo 'This is a minimal pipeline.'
        sh '''echo PATH = ${path}
echo M2_HOME = ${RZ_HOME}'''
      }
    }
  }
}