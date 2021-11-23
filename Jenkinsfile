pipeline {
    agent any
    tools {
        maven 'maven_3_3_9' 
    }
    stages {
        stage('Build') { 
            steps {
                echo 'Hello world!' 
                sh '/opt/maven/apache-maven-3.3.9/bin/mvn -B -DskipTests clean package'
            }
        }
    }
}
