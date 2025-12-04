pipeline {

    stages{
        stage{
            steps('Build'){
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}
