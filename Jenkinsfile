@Library('piper-lib-os') _
node() {
    stage('prepare') {
        checkout scm
        setupCommonPipelineEnvironment script:this
    }
}
node() {
    stage('build') {
    mtaBuild script: this
    }
}
    
