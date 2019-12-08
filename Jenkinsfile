pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
                def ret =  sh("""echo 'Hello' > test_file""", returnStdout: true)
                println ret
            }
        }
    }
}