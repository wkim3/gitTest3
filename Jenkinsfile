<<<<<<< HEAD
    pipeline {
        agent any
        stages {
            stage('Test') {
                steps {
                    echo 'Hello World ...'
                }
            }
        }
    }
=======
pipeline {
    agent any
    stages {
        stage('---clean---') {
            steps {
                sh "mvn clean"
            }
        }
        stage('--test--') {
            steps {
                sh "mvn test"
            }
        }
        stage('--package--') {
            steps {
                sh "mvn package"
            }
        }
    }
}
>>>>>>> bb256f0ca9fbf02a435f16728d2ce340526e9220
