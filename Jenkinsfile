pipeline{
    agent any
    tools {
  terraform 'Terraform'
}
    stages{
        stage("git checkout"){
            steps{
               git credentialsId: 'a5b7fc7e-a13b-4785-a6b3-4feb7ee336d8', url: 'https://github.com/Divyabd/terraform-jenkins.git'
            }
        }
          stage("terraforrm initt"){
            steps{
                sh 'terraform init'
            }
        }
    }
}
