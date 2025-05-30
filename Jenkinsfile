eline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'sudo python3 --version'
            }
        }
        stage('Compile') {
                        steps {
                                sh 'sudo python3 web.py'
                        }
                }
                stage('Test') {
                        steps {
                                sh 'sudo python3 test_app.py'
                        }
                }
    }
}
~                                                                                                                                                              
~                                                                                                                                                              
~                                                                                                                                                              
~                                                                                                                                                              
~               
