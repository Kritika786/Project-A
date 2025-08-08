@Library('jenkins-shared-library') _

pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                build('Project-A-Compile')
            }
        }
        stage('Deploy') {
            steps {
                deploy()
            }
        }
    }
}
