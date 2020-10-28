node()
{
  properties([
    parameters([
      string(name: 'UNSTABLE', defaultValue: 'SUCCESS')
    ])
   ])
  stage("Stage1")
  {
      // something went wrong, but it isn't catastrophic...
	  currentBuild.result = "${UNSTABLE}"
  }
  stage("PBA"){
       cloudBeesFlowRunPipeline addParam: '{"pipeline":{"pipelineName":"qe pipeline name","parameters":[]}}', configuration: 'flow-server', pipelineName: 'qe pipeline name', projectName: 'qe proj'
  }
}
