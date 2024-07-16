pipeline{
    agent any
    stages{
        stage('run script'){
            steps{
                sh 'chmod +x ./deply.sh'
                sh './deploy.sh'
            }
        }
    }
}