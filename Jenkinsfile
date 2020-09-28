pipeline {
    agent any

    stages {
        stage("Copy all to my dir") {
            steps {
                sh 'mkdir /home/varvara/jentestdir/'
                sh 'cp README.md /home/varvara/jentestdir/'
            }
        }
    }
}
