pipeline{
    agent any
    stages{
        stage('checkout the repo'){
            steps{
                git 'https://github.com/FaizanUlHaq262/jenkins-test-repo.git'
            }
        }

        stage('print statement'){
            steps{
                sh echo "Working till here boss hahaha...."
            }
        }
    }
}