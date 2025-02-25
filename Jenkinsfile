pipeline
{
  agent any
  stages
  {
    stage('clone')
    {
      steps{
        git 'https://github.com/Snehithavadla/repo1.git'
      }
    }
    stage('build')
    {
      steps{
        sh 'javac hello.java'
      }
    }
    stage('run')
    {
      steps{
        sh 'java hello'
      }
    }
  }
}
