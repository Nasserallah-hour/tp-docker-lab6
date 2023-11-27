pipeline {
    agent any
tools{ jdk 'JDK17' }
environment {

JAVA_HOME = '/opt/java/openjdk/bin/java'
DOCKER_TAG = getVersion()

}
    stages{
    stage ('Clone Stage') {
steps {
git 'https://github.com/Nasserallah-hour/tp-docker-lab6.git'
}
}
}
}