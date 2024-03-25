pipeline {
    agent any
    tools{
        maven 'maven'
    }
    stages {
        stage('validate') {
            steps {
                echo 'validate the structure'
            }
        }
        stage('compile') {
            steps {
                echo 'compile the src'
            }
        }
        stage('test') {
            steps {
                echo 'testing completed'
            }
        }
        stage('package') {
            steps {
                echo 'build success'
            }
        }
    }
}
