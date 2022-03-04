pipeline {
            agent any {
			           stages {
					   stage ('build')
					   {
					   steps{
					   sh 'sleep 5;echo "this is build stage"'
					   }
					   }
					   stage ('test')
					   {
					   steps {
					   sh '''
					   sleep 5
					   echo "this is Test stage"
					   }
					   
					   }
					   stage ('deploy')
					   
					      {
						  steps {
						  sh '''
						         sleep 5
								 echo " this is deploy stage"
						 }
					   
					   }
					   stage('My-stage')
					   {
					   steps {
					          sh '''
							  sleep 5
								 echo " this is deploy stage"
					     }
	}		 

}
