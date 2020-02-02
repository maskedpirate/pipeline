node {
  stage('stage1') {
    echo 'Hello World'
  }
  stage('build') {
    sh label: 'Compile & Assemble', script: 'mvn clean package'
  }
}
