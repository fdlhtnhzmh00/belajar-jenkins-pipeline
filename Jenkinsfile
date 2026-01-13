pipeline {
    agent {
        node {
            label "linux-agent" 
        }
    }
    stages {
        stage('Build') {
            steps {
                echo "Hello Build 1 by Fadilah Tun Hazimah"
                echo "Hello Build 2 by Fadilah Tun Hazimah"
                echo "Hello Build 3 by Fadilah Tun Hazimah"
            }
        }
        stage('Test') {
            steps {
                echo "Hello Test 1 by Fadilah Tun Hazimah"
                echo "Hello Test 2 by Fadilah Tun Hazimah"
                echo "Hello Test 3 by Fadilah Tun Hazimah"
            }
        }
        stage('Deploy') {
            steps {
                echo "Hello Deploy 1 by Fadilah Tun Hazimah"
                echo "Hello Deploy 2 by Fadilah Tun Hazimah"
                echo "Hello Deploy 3 by Fadilah Tun Hazimah"
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