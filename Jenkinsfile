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
}
