pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
                script {
                     sh """echo 'Hello > result'""";
                     def output = readFile('result').trim()
                     echo "output=$output;
                }
            }
        }
    }
}