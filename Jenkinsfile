pipeline {
    agent any
    tools {
        maven 'maven_3_3_9' 
        jdk 'JAVA_jdk1.7.0_55'
    }
    stages {
        stage('Build') { 
            steps {
                echo 'Hello world!' 
                sh 'mvn clean package'
                //sh 'mvn -B -DskipTests clean package'
                //sh 'ls -l'
                //sh 'mvn compile'
            }
        }
    }
}
