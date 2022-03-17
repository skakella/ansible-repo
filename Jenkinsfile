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
        echo 'Let us test multibranch pipeline with a web hook'
        
        }
      }
    
    stage('deploy'){
        steps{
        echo 'Deploy build'
      }
      }
      
    

  }
 
}
