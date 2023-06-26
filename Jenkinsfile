@Library('my-shared-library') _    // this is how to import library located in Jenkins 

pipeline{

    agent any

    stages{

        stage('Git Checkout'){
            
            steps{
            gitCheckout(
                branch: "main",
                url: "https://github.com/rhn424/project1.git"
            )
            }
        }
    } 
}