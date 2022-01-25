//START-OF-SCRIPT
node {
    def DOCKER_HOME = tool name: 'docker'
    def REPO_URL = 'https://github.com/akolodkin/weekly-team-report-html.git'
    
    stage('Clone') {        
        git url: REPO_URL, branch: 'develop-team-2'
    }
    stage('Build') {
        docker.withTool('docker') {
            sh "pwd"
            sh "ls -la"
            sh "ls -la ./docker"
        }
    }
}
//END-OF-SCRIPT
