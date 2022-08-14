pipeline {
      agent any
  stages{
        stage('Checkout Code') {
            steps {
             checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[credentialsId: 'oktbabs', url: 'https://github.com/oktbabs/TeeCICD.git']]])
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
