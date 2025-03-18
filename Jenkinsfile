pipeline {
    agent any
      tools{
        maven "Maven_3_9_5"
    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
