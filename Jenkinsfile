pipeline {
  agent any 
  stages {
    stage('Build') {
      steps {
        sh 'echo "Hello World The Michaels"'
        sh '''
                  echo "Multiline shell steps works too"
                  ls -lah
               '''
      }
    }
  }
}