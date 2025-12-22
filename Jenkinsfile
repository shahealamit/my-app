pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                echo 'Code already checked out by Jenkins'
            }
        }

        stage('Build with Maven') {
            steps {
                bat '''
                set JAVA_HOME=C:\\Users\\Lenovo\\AppData\\Local\\Programs\\Eclipse Adoptium\\jdk-17.0.17.10-hotspot
                set PATH=%JAVA_HOME%\\bin;%PATH%
                mvn clean package
                '''
            }
        }
    }
}
