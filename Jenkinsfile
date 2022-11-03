pipeline {
    agent {label
    {label'slave-1'
    customWorkspace'/mnt/project/'
    }
    }

    stages {
        stage('Hello') {
            steps {
                sh'yum install httpd -y'
            }
        }
    }
}
