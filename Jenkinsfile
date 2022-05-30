pipeline{
    agent any
    tools {
  terraform 'Terraform'
}
    stages{
        stage("git checkout"){
            steps{
                echo ""
            }
        }
          stage("terraforrm initt"){
            steps{
                sh 'terraform init'
            }
        }
    }
}
