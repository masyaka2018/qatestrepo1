node()
{
properties([
   parameters([
    string(name: 'SUCCESS', defaultValue: 'SUCCESS')
    ])
   ])
  stage("Stage1")
  {
      // something went wrong, but it isn't catastrophic...
	  currentBuild.result = '${SUCCESS}'
  }
}
