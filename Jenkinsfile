pipeline {
    agent any
    stages {
        stage('Jenkins Pipeline Example') {
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
