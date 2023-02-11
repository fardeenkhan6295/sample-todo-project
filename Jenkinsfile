pipeline {
    agent any
    environment{
        staging_server="172.17.173.65" 
    }
    stages{
        stage('deploy to remote'){
            steps{
                sh 'scp -r ${WORKSPACE}/* root@${staging_server}:/var/www/html/fardeen/'
            }
        }
    }
}
