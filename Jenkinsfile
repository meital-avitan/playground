pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
                script {
                     def ret = sh(returnStdout: true, script: "echo 'Hello' > result.txt")
                     println ret
                }
            }
        }
    }
}