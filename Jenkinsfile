pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Hi') {
            steps {
                echo 'Hi how are you!'
            }
        }
        stage ('name') {
            steps {
                echo 'my name is vamc'
            }
        }
         stage ('environment') {
            steps {
                echo env.BUILD_ID
                echo env.JENKINS_HOME
                echo env.JOB_NAME
            }
        }
    }
}

