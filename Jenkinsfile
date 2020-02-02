node {
  stage('stage1') {
    echo 'Hello World'
  }
  stage('checkout') {
    checkout scm
  }
  stage('build') {
    bat label: 'Compile & Assemble', script: 'mvn clean package'
  }
}
