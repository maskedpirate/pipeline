node {
  stage('stage1') {
    echo 'Hello World'
  }
  stage('checkout') {
    checkout scm
  }
  /*
  stage('project-jenkinsfile') {
    load 'Jenkinsfile'
  }
  */
  stage('config') {
    def pipelineConfig = readJSON file: '.pipeline'
    echo "Pipeline Type: [${pipelineConfig.type}]"
  }
}
