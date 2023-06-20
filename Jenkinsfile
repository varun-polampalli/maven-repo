pipeline {
agent any
tools {
maven 'maven'
}

stages {

stage ('compilation process') {
steps {
sh "mvn comiple"
}
}

stage ('Testing') {
steps {
sh "mvn test"
}
}

stage ('packaging') {
steps {
sh "mvn package"
}
}

}
}
