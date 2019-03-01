pipeline{
    agent any
    tools{nodejs "nodejs"}
    stages{
        stage('develop'){
        	steps{
       			checkout scm
            	echo "In dev stage"
            	sh 'node -v'
            	sh 'npm install'     
        	}

       }
        stage('stage'){
            steps{
       			checkout scm
            	echo "In dev stage"
            	sh 'node -v'
            	sh 'npm install'     
        	}
        }
        stage('prod'){
           steps{
       			checkout scm
            	echo "In dev stage"
            	sh 'node -v'
            	sh 'npm install'     
        	}
        }
    }
}
