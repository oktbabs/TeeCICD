pipeline {
      agent any
  stages{
        stage('Checkout Code') {
            steps {
              withCredentials([gitUsernamePassword(credentialsId: '73b3562f-8684-4049-a7c1-ff8983c89640', gitToolName: 'git')]) {
               sh 'git clone https://github.com/oktbabs/mycicdpipeline.git'
              }
            }
        }
     stage("Build"){
      steps{
        echo "I am checking out"
            }
           } 
       stage("Unit Tests"){
      steps{
        echo "I am checking out"
            }
           }
        stage("Quality Scan"){
      steps{
        echo "I am checking out"
            }
           }
        
       stage("Security scan"){
      steps{
        echo "I am checking out"
            }
           }  
       stage("Foss Scan"){
      steps{
        echo "I am checking out"
            }
           }
          stage("Packing"){
      steps{
        echo "I am checking out"
            }
           }
        
        stage("Publish"){
      steps{
        echo "I am checking out"
            }
           }
  }
  }
