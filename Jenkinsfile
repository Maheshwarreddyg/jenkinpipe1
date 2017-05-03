pipeline {
  agent any
  stages {
    stage('STAGE') {
      steps {
        parallel(
          "STAGE": {
            echo 'HELLOW STAGE1'
            
          },
          "STEP1": {
            echo 'STEP1'
            
          }
        )
      }
    }
    stage('STAGE2') {
      steps {
        parallel(
          "STAGE2": {
            echo 'HELLOW STAGE2'
            
          },
          "STEP1STAGE2": {
            echo 'HELLOW STEP1'
            
          },
          "STEP2": {
            echo 'HELLOW STEP2'
            
          }
        )
      }
    }
    stage('STAGE3') {
      steps {
        parallel(
          "STAGE3": {
            echo 'STAGE3 HELLOW'
            
          },
          "STEP1": {
            echo 'HELLOW STEP1'
            
          }
        )
      }
    }
  }
}