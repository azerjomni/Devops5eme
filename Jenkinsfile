pipeline {
<<<<<<< HEAD
    agent any

    stages {
       stage ('GIT') {
	
=======

    agent any


    stages {
        stage ('GIT') {
            steps {
               echo "Getting Project from Git"; 
                git branch: "main", 
                    url: "https://github.com/......";
            }
        }
       
        stage("Build") {
            steps {
                sh "mvn -version"
                bat "mvn clean package -DskipTests"
            }
        }

        stage("Sonar") {
            steps {
                bat "mvn sonar:sonar"
            }
        }
        
        stage("SRC Analysis Testing") {
            steps {
                bat "mvn sonar:sonar"
            }
        }
        
        stage("Build Docker image") {
            steps {
                sh "..............."
            }
        }

        stage("Deploy Artifact to private registry") {
            steps {
                sh "..............."
            }
        }

        stage("Deploy Dokcer Image to private registry") {
            steps {
                sh "..............."
            }
        }
    }
   
    post {
        always {
            cleanWs()
        }
    }
    
}
>>>>>>> 95124c2544224b45db886f55a17f4d5ca23a8646
