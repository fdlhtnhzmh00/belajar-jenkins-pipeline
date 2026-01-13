pipeline {
    agent {
        node {
            label "linux-agent" 
        }
    }
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
    post {
        always {
            echo 'Fadilah: I will always say Hello again!' 
        }
        success {
            echo 'Yay, success!'
        }
        failure {
            echo 'Oh no, failure!'
        }
        cleanup {
            echo 'Don\'t care success or failure, just cleaning up!' 
        }
    }
}