pipeline {
    agent any

    stages {
        stage("Copy all to my dir") {
            steps {
                sh 'rm -r /var/jenkins_home/jentestdir/*'
                sh 'cp ./* /var/jenkins_home/jentestdir/'
            }
        }
    }
}
