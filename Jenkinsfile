pipeline {
    agent any
    stages {
        stage('input1') {
            steps {
                export PATH=$PATH:$(pwd)
                sh("chmod +x ip_print")
                sh("ip_print input1.json")
            }
        }
        stage('input2') {
            steps {
                sh("./ip_print input2.json")
            }
        }
    }
}
