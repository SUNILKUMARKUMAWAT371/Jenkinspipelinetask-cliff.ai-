pipeline {
  agent any
  
  stages{

    stage('build stage') {
      steps {
        sh 'sudo docker build . -t newimage7'
        echo 'your build stage success !'
      }
    }
    
     stage('run stage ') {
      steps {
        sh 'sudo docker run --name mynewos2  newimage7'
        echo 'your build stage success !'
      }
    }
   
  }
}
