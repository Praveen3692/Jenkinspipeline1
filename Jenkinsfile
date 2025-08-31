pipeline {
    agent any

    stages {
        stage("Pull Code") {
            steps {
                echo "Pulling code from GitHub..."
            }
        }

        stage("Build") {
            steps {
                echo "Building packages from code..."
            }
        }

        stage("Test") {
            steps {
                echo "Testing package..."
            }
        }

        stage("Deploy") {
            steps {
                echo "Deploying application..."
            }
        }
    }
}
