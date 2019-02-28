node{
    stages{
        stage('develop'){
        	checkout scm
            echo "In develop stage"
            sh 'node -v'
            sh 'npm install'
        }
        stage('stage'){
          	checkout scm
          	sh 'node -v'
            sh 'npm install'
        }
        stage('prod'){
            checkout scm
            sh 'node -v'
            sh 'npm install'
        }

    }

}
