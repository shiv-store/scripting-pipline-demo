pipeline {
    agent any

    stages {
        stage('BUIILD') {
            //git credentialsId: 'anil305rgpv', url: 'https://github.com/shiv-store/docker-jenkins-master-base'
            steps {
                echo 'build is happing'
            }
        }
        stage('sonar scanner') {
            steps {
                echo 'scanning is happing'
            }
        }
        stage('dev deployement') {
            steps {
                echo 'deployment'
            }
        }
    }
}
