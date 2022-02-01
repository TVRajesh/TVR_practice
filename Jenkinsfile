pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh 'echo "firstpipeline via blueocean"'
      }
    }

    stage('stage2') {
      steps {
        sh 'echo "hello pipeline"'
      }
    }

    stage('Deploy') {
      steps {
        sh 'docker infor| grep -i version'
      }
    }

  }
}