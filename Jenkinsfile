pipeline{
    agents none
    tools{nodejs "nodejs"}
    stages{
        stage('develop'){
            checkout scm
            echo "In dev stage"
            sh 'node -v'
            sh 'npm install'
        }
        stage('stage'){
            checkout scm
            echo "In dev stage"
            sh 'node -v'
            sh 'npm install'
        }
        stage('prod'){
            checkout scm
            echo "In dev stage"
            sh 'node -v'
            sh 'npm install'
        }

    }

}
