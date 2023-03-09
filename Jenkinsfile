pipeline {
    agent any
    stages {
        stage('Run Tests') {
            parallel {
                stage('Test On Windows') {
                    steps {
                        echo "welcome to tests"
                    }
                }
                stage('Test On Linux') {
                    steps {
                        echo "welcome to linux"
                    }
                }
            }
        }
    }
}
