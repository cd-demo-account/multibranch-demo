#!groovy

stage name: 'Using docker'
docker.image('maven:3.3.3-jdk-8').inside {
  echo "Hello docker"
}

stage name: 'Next stage'
node{
 input 'Ready to go?'
 echo "Ready"
}
