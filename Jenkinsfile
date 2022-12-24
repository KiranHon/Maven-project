pipeline {
agent any
stages {
//  stage('scm checkout')             //download the code, scm: source code management
//  {steps {sh 'git clone https://github.com/prakashk0301/maven-project/' } }      //if no branch defined then it will download the code from default branch"master"

stage('scm checkout')
  {steps {sh 'git branch: 'main', url: 'https://github.com/KiranHon/Maven-project' } }
 stage('build job')
  {steps{sh 'echo package is building'}}
 stage('artifact generated')
   {steps {sh 'echo artifact stored in repo'}}
  
}
}
