pipeline{
    agent any
    stages{
        stage("Git Checkout"){
            steps{
               git credentialsId: 'github', url: 'https://github.com/Saibhuvi/Tempractice'
            }
        }    
        stage("Build"){
            steps{
               echo "Sucessful Build"
            }
        }
    }
}
