pipeline {
  agent any
  stages {
    
    stage('Git-Checkout') {
      steps {
        git(url: 'https://github.com/skakella/ansible-repo.git', branch: 'main')
      }
    }
    
    stage('test')
      {
         steps
        {
        echo 'Testing is done'
        }
      }
    
    stage('deploy'){
        steps{
        echo 'Deploy build'
      }
      }
      
    

  }
 
}
