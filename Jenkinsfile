pipeline {
    agent any
    stages {
        stage('input1') {
            steps {
                sh("./ip_print testing/input1.json")
            }
        }
        stage('input2') {
            steps {
                sh("./ip_print input1.json")
            }
        }
    }
}
