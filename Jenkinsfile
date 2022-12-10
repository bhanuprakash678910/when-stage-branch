pipeline {
    agent any
    stages {
        stage("Building Main") {
            when {
                branch 'main'
            }
            steps {
                echo "Building Main"
            }
        }
      stage("Building Dev") {
            when {
                branch 'dev'
            }
            steps {
                echo "Building Dev"
            }
        }
    }
}
