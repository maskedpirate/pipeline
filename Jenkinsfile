node {
  stage('stage1') {
    echo 'Hello World'
  }
  stage('build') {
    bat label: 'Compile & Assemble', script: 'mvn clean package'
  }
}
