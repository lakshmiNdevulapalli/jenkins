node{
        stage('develop'){
            checkout scm
            echo "In develop stage"
            def nodejs = tool 'Nodejs'
            sh 'node -v'
            sh 'npm install'
        }
        stage('stage'){
          	checkout scm
                echo "In Stage stage"
                def nodejs = tool 'Nodejs'
          	sh 'node -v'
            sh 'npm install'
        }
        stage('prod'){
            checkout scm
                echo "In Prod stage"
                def nodejs = tool 'Nodejs'
            sh 'node -v'
            sh 'npm install'
        }
}

