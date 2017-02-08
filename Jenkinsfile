node {
    stage('Build') {
        git branch: 'feature-orchestrator-integration', changelog: false, credentialsId: '37456615-87c7-424b-9473-0b117d0fab19', poll: false, url: 'https://github.com/shinesolutions/aem-aws-stack-builder.git'
        make create-set-aem stack_prefix=$STACK_PREFIX

    }

}
