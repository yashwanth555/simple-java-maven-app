pipeline {
agent any
    stages{
        stage('build'){
            steps{
                sh 'mvn -B -DskipTests clean package'
            }
        }
        stage('Test'){
            steps{
                sh 'mvn test'
            }
        }
        stage('Deploy'){
            steps{
                sh 'java -jar target/my-app-1.0-SNAPSHOT.jar'
            }
        }
    }
}
