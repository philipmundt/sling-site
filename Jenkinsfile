pipeline {
    agent {
        label 'ubuntu'
    }

    tools {
        maven 'Maven 3.3.9'
        jdk 'JDK 1.8 (latest)'
    }
    stages {
        stage ('Build') {
            steps {
                sh 'mvn clean package' 
            }
        }
    }
}
