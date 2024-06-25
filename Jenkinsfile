pipeline {
    agent { label 'newagent' }
    stages {
        stage ('Build') {
            steps {
            echo "This is Build"
            }
        }
        stage (' Install Terraform') {
            steps {
                script {
                    sh 'sudo apt-get update && sudo apt-get install -y gnupg software-properties-common'
                }
            }
        }
    }
}