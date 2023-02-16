pipeline {
    agent any
    stages{
        stage('deploy to remote'){
            steps{
                sh 'scp -r ${WORKSPACE}/* root@172.31.132.192:/var/www/html/fardeen/'
            }
        }
    }
}
