pipeline {
  agent any

  stages
  {
    stage{'checkout'}
    {
      steps { git branch: 'main', url: ""
    }
    stage('build'){
      steps { echo "building...."}
    }
    stage('test'){
      steps
      { 
        echo "testing "
      }
    }
  }  
}
