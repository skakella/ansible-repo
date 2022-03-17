pipeline {
  agent any
  stages {
    
    stage('Git-Checkout') {
      steps {
        git(url: 'https://github.com/skakella/ansible-repo.git', branch: 'dev')
      }
    }
    
    stage('test')
      {
         steps
        {
        echo 'I am from Dev branch'
        
        }
      }
    
    stage('deploy'){
        steps{
        echo 'Deploy build'
      }
      }
      
    

  }
 
}
