pipeline{
    agent any
    stages{
        stage('Compile'){
            steps{
                echo "Building the project"
                sh 'mvn compile'
            }
        }

        stage('Test'){
            steps{
                echo "Tesing of the project"
                sh 'mvn test'
            }
        }

        stage('Package'){
            steps{
                echo "Packaging the project"
                sh 'mvn package'
            }
        }
    }
}