pipeline {
    agent any
    tools {
        maven 'maven_3_5_4' 
        jdk 'JAVA_jdk1.7.0_55'
    }
    stages {
        stage('Build') { 
            steps {
                echo 'Hello world Pedrooooo!' 
                sh 'ls -l'
                sh 'mvn compile'
            }
        }
    }
}
