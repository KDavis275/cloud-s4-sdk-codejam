#!/usr/bin/env groovy 

String pipelineVersion = "google-next"

node {
    deleteDir()
    sh "git clone --depth 1 https://github.com/Lsubatin/cloud-s4-sdk-pipeline.git -b ${pipelineVersion} pipelines"
    load './pipelines/s4sdk-pipeline.groovy'
}
