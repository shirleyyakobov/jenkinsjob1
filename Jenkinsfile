pipeline{
    agent any
    stages{
        stage("fetching"){
            steps{
              echo "fetching"
            }
        }

        stage("building"){
            steps{
              echo "building"
            }
        }

        stage("testing"){
            steps{
              echo "testing"
            }
        }

        stage("deploying"){
            steps{
              echo "deploying"
            }
        }
    }

    post{
        always{
            echo "====++++always++++===="
        }
        success{
            echo "====++++only when successful++++===="
        }
        failure{
            echo "====++++only when failed++++===="
        }
    }
}