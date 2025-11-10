pipeline {
  agent any

  stages
  {
    stage('checkout')
    {
      steps { git branch: 'main', url: "https://github.com/Rjiv07/jenkins-file.git"}
    }
    stage('build'){
      steps { echo "building...."}
    }
    stage('test'){
      steps
      {
        sh "python3 Exam.py"
        sh "java -jar A.java"
      }
    }
  }  
}
