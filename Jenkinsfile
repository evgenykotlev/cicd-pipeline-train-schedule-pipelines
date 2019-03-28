pipeline {
agent any
stages {
stage ('Build'){
steps {
  echo 'test is ok'
  sh './ gradllew build --nodahs-deamon'
        archiveartifacts artifacts: 'dist/trainShedule.zip'
      }
    }
  }
}
