@Library ("shared") _
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        
         stage('Github sl') {
            steps {
                echo 'calling sl .....'
                hello()
            }
        }
        
        stage('Call you maybe') {
            steps {
                echo 'Another one'
                koko()
            }
        }
        
    }
}

