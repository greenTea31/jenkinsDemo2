pipeline {
    agent {
        label 'demoAgent'
    }
    
    stages {
        stage('Test') {
            steps {
                echo "202206071028"
            }
        }
    }
    
    post {
        always {
            echo 'pipeline is done!!!'
        }
    }
}
