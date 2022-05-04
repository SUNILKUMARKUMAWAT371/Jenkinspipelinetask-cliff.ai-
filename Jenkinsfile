pipeline {
  agent any
  
  stages{

    stage('docker build') {
      steps {
        sh 'sudo docker build . -t newimage3'
        echo 'your build is success this time'
      }
    }
    
     stage('docker run ') {
      steps {
        sh 'sudo docker run --name mynewos1  newimage3'
        echo 'your build is success this time'
      }
    }
   
  }
}
