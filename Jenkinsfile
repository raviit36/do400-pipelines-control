pipeline { 
    agent  {
	node {
		label 'nodejs'	
	} 
     }
   stages {
   stage('Backend Tests'){
	steps{
	 echo 'backend'
	sh 'node ./backend/test.js'	
	}
    }	
   stage('Frontend Tests') {
	steps{
	 sh 'node ./frontend/test.js'	
	}
    }
 }
}
