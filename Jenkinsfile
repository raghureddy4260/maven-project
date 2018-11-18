pipeline {
    agent any
    stages {
        stage('Pipeline Example') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
