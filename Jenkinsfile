pipeline
{
 agent any
 stages
 {
  stage('get git stage')
  { steps { git branch: 'main', url: 'https://github.com/ravirajole/Devops_jenkins.git' } }
  stage('print welcome stage')
  { steps { sh 'echo Hello'}  }
 }
}
