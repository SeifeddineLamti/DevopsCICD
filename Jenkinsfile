pipeline {
    agent rayene
    tools {
        maven 'M2_HOME'
    }
    stages {
        stage('Maven') {
            steps {
                sh "mvn -version"
            }
        }
    }
}