pipeline{

agent any
  
  tools{
maven 'maven3.8.6'

}
  
  stages{

  stage('CheckOutCode'){
    steps{
      git branch: 'main', url: 'https://github.com/saikumar21698/Webapplication.git'
    }
  }
  
    stage('Build'){
    steps{
      sh 'mvn clean package'
    }
  }
  }
} 
  
    
