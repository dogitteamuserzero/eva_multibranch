pipeline {
  agent any
  stages {
    stage('Docker Build') {
      steps {
        sh 'docker build -t $BRANCH_NAME .'
      }
    }
  }
}