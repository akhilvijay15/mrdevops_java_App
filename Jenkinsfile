pipleline{

        agent any

        stages{
         
        stage('Git Checkout'){
                    when { expression {  params.action == 'create' } }
            steps{
            gitCheckout(

                git branch: 'main', url: 'https://github.com/akhilvijay15/mrdevops_java_App.git')
             }

            }
        }
    }


}