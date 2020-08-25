node()
{
properties([
  parameters {
        string(name: 'PERSON', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')
    }
   ])
  stage("Stage1")
  {
         steps {
                echo "Hello ${params.PERSON}"
            }
  }
}
