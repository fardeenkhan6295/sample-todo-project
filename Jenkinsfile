pipeline {
    agent any
    environment{
        staging_server="172.17.163.253" 
    }
    stages{
        stage('deploy to remote'){
            steps{
                sh 'sh scp -r ${WORKSPACE}/* root@${staging_server}:/var/www/html/fardeen/'
            }
        }
    }
}
