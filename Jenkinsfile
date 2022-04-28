pipeline {
  agent any 
  stages {
    stage('sample1') {
        steps {
          echo 'summition'
        }
    }
    stage ('sample2') {
     steps{
        echo 'addition'
        sh 'python3 app.py'
      }
    }
  }
}
