pipeline {
  agent any
  stages {
    stage('Init') {
      agent any
      steps {
        dir(path: './')
        echo 'Hello Step 1'
      }
    }

    stage('DoSome') {
      steps {
        sh '''pwd
ls -al'''
      }
    }

  }
}