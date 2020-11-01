pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build is completed'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deployment completed'
        git(url: 'https://github.com/Balajiiguru/Jenkins.git', branch: 'master')
      }
    }

    stage('Test') {
      steps {
        echo 'Run test'
        git(url: 'https://github.com/Balajiiguru/Python.git', branch: 'master')
      }
    }

  }
}