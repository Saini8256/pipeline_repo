pipeline {
    agent Slave_1
    stages {
        stage('STAGE1'){
            steps{
                    sh 'sleep 10'
                    echo "This is the first stage step"
            }
        }
        stage('STAGE2'){
            steps{
                    sh 'sleep 15'
                    echo "This is the second stage step"
            }
        }
        stage('STAGE3'){ 
            steps{
                    sh 'sleep 20'
                    echo "This is the third stage step"
            }
        }
    }

}