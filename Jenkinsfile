pipeline{
agent any
tools{
maven 'maven'
}
stages{
stage('checkout'){
steps{
git 'https://github.com/bharah08/maven-web-application.git'

}

}
stage('build package'){
steps{
sh 'mvn clean install -Dskiptests=true'

}

}
}

}
