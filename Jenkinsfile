pipeline {
agent any
stages {
//  stage('scm checkout')             //download the code, scm: source code management
//  {steps {sh 'git clone https://github.com/prakashk0301/maven-project/' } }      //if no branch defined then it will download the code from default branch"master"

stage('scm checkout')
  {steps {'git branch: 'main', url: 'https://github.com/KiranHon/Maven-project' }}
  
}
}
