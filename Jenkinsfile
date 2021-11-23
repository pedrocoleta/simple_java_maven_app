pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                echo 'Hello world!' 
                sh '/opt/maven/apache-maven-3.3.9/bin/mvn -B -DskipTests clean package'
            }
        }
    }
}
