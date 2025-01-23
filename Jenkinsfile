node {
   
   	stage 'Stage 1'
   		echo 'Hello there, shell scripts'
   	stage 'Checkout'
   		git url: 'https://github.com/gopih2022/ffptest.git'
   	stage 'Build'
   		sh './myBuild.sh'
   	stage 'Deploy'
   		sh './myDeployment.sh'
  
}
