@Library('jenkins-shared-library') _

pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                build('Project-A')
            }
        }
        stage('Deploy') {
            steps {
                deploy('dev')
            }
        }
    }
}
