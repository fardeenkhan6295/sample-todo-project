pipeline {
    agent any
    stages{
        stage('deploy to remote'){
            steps{
                sh 'cp -r ${WORKSPACE}/* /var/www/html/fardeen/'
            }
        }
    }
}
