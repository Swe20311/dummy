
pipeline {
    agent any
    stages {
        stage("Test") {
            when {
                branch "develop"
            }
            steps {
                echo "Hello World!"
            }
        }
    }
}
