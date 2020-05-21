pipeline{
    agent any
    stages{
        stage("Git Checkout"){
            steps{
               git credentialsId: 'github', url: 'https://github.com/Saibhuvi/Tempractice'
            }
        }    
        stage("Build"){
           input {
                message "Can we Proceed?"
                ok "Yes"
                }
            steps{
               echo "Sucessful Build"
            }
        }
    }
}
