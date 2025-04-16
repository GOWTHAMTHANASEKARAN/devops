pipeline{
    agent {
        label 'java_slave_node'
    }
    tools
    {
        maven 'maven'
    }
    stages{
        stage('clean'){
            steps{
                sh 'mvn clean package'
            }
        }
    }
}
