pipeline{

    agent any

    stages{

        stage('Git Checkout'){
            
            steps{

                script{
                    git branch: 'main', url: 'https://github.com/rhn424/project1.git'
                }
            }
        }
    } 

}