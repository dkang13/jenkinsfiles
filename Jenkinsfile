pipeline {
    agent any 
    stages {
        stage('curl call') {
            steps {
                curlOutput = sh returnStdout: true, script: "curl -X GET -u dalkang:Kan78735TX http://qef-linux1.deloitte.com:8085/job/NMSLO_run/"
                echo curlOutput
            }
        }
    }
}