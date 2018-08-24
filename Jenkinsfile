pipeline {
    agent any
    parameters {
       string (name: 'PERSON', defaultvalue: 'rchittala', description: 'User creation')
    }
    stages {
      stage('Useracreate') {
          steps {
           useradd $(params.PERSON)
           }
      }
    } 
}
