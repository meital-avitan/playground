pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
                script {
                     def ret =  sh (
                         script: """echo 'Hello'""",
                         returnStdout: true)
                     println ret
                }
            }
        }
    }
}