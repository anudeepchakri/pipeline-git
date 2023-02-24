pipeline {
  agent any
  stages {
    stage('Deploy-Dev') {
      steps {
        echo 'hello'
      }
    }
    stage('deploy-QA') {
          steps{
            echo 'QA'
            input"does the string environment look ok ?"
          }
          }
          stage('deploy-production') {
            steps{
              echo'production'
            }
          }
        }
      }
          
         
