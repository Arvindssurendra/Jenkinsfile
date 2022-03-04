pipeline { 
  
  stages {
    
    stage ('build') {
      
      steps {
               sh 'sleep 5 ; echo "this is Build stage"'
                
             
      } 
    }
     stage('test') {
                      
      steps {
             sh '''
                    sleep 5
                    echo "this is a test stage"
                     '''
      } 
    }
    
     stage('delpoy') {
      
      steps {
              sh '''
                     sleep 5
                     echo "this is delpoy stage"
                     '''
      } 
    }
     stage('my-stage') {
      
      steps {
              sh '''
                  sleep5
                  echo "this is my-stage"
                  
                  '''
      } 
    }
    
  }

}
  
