pipeline {
    agent any

    stages {
        stage("Copy all to my dir") {
            steps {
                sh 'mkdir /var/jenkins_home/jentestdir/'
                sh 'cp README.md /var/jenkins_home/jentestdir/'
            }
        }
    }
}
