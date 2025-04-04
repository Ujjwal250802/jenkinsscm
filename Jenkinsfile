pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
         stage('git clone') {
            steps {
                git branch: 'main', url: 'https://github.com/upessocs/fastapi-dockerize/'
            }
        }
        stage('test clone') {
            steps {
                sh 'ls'
                sh 'pwd'
            }
        }
    }
}
