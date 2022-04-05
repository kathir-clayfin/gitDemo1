pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        bat 'echo hi'
        retry(count: 4)
      }
    }

  }
}