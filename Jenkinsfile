pipeline {
    agent any
    tools {
        maven 'maven_3_3_9' 
    }
    stages {
        stage('Build') { 
            steps {
                echo 'Hello world!' 
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}
