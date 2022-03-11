
pipeline {
    agent any
    stages {
        stage("checkout"){
            steps{
            checkout([$class: 'GitSCM', branches: [[name: 'development']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/Swe20311/dummy1.git']]])
            }
        }
        stage("Test") {
            when {
                branch "develop"
            }
            steps {
                echo "Hello World!"
                sh 'ls -la'
            }
        }
    }
}
