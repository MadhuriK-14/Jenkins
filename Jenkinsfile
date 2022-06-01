pipeline {

agent any

stages {

stage('Build') {

steps {

 //sh 'javac Helloworld.java'
 git url : 'https://github.com/MadhuriK-14/Jenkins.git' , branch : 'main'

}

}

stage('Run') {

steps {
 javac Helloworld.java
 java Helloworld
}
}
}
}
