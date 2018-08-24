pipeline {
    agent any
    parameters {
       string (name: 'PERSON', defaultValue: 'rchittala', description: 'User creation')
    }
    stages {
      stage('Useracreate') {
          steps {
           useradd $PERSON
           }
      }
    } 
}
