pipeline {
  agent any
  
  stages {
    stage('Build') {
      steps {
        echo 'Pull changes'
        git 'https://github.com/fibaihaqi/cicd.git'
        sh './mvnw clean compile'
      }
    }
  }
}
