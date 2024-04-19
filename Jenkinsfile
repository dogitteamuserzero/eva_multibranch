pipeline {
  agent any
  stages {
    stage('Docker Build') {
      steps {
        sh 'docker build -t ${REPO}/$BRANCH_NAME .'
      }
    }
  }
}