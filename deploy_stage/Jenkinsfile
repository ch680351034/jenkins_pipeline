pipeline {
    agent any
    environment {
        RELEASE='20.04'
    }
    stages {
        stage('Build') {
            agent any
            environment {
                LOG_LEVEL='INFO'
            }
            steps {
                echo "Hello World!!! This is the ${RELEASE} and its log level is ${LOG_LEVEL}"
            }
        }
            
            stage('Test'){
                steps {
                    echo "yes!! can see ${RELEASE} but cant access log_level param"
                }
            
            
    }
}
}
