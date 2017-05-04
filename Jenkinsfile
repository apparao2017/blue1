pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        parallel(
          "step11": {
            echo 'Stage1-step1'
            
          },
          "step12": {
            echo 'Step2'
            
          }
        )
      }
    }
    stage('Stage2') {
      steps {
        parallel(
          "Stage2": {
            echo 'step1-stage2'
            
          },
          "step2": {
            echo 'step22'
            
          }
        )
      }
    }
    stage('Stage3') {
      steps {
        echo 'step31'
      }
    }
  }
}