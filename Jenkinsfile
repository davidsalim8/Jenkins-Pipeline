pipeline{
    agent any
    stages{
        stage("Build"){
            steps{
                echo "Building..."
            }
            post{
                success{
                    mail to: "david.salim88888@gmail.com",
                    subject: "Build Status Email",
                    body: "Build was successfu;"
                }
            }
        }
    }
}