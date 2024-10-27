pipeline {
  agent any
  stages {
    stage('Build')
    {
      steps { 
        sh 'echo "Building the application"'
      }
    }
    stage('Test') {
      parallel {
      stage ("sleep1") {
        steps {
          sleep 10
          sh "ls -l"
        }
      }
      stage ("sleep2") {
        steps {
          sleep 10
          sh "ls -l"
        }
      }
      stage ("sleep3") {
        steps {
          sleep 10
          sh "ls -l"
        }
      }
    }
  }
}
             
