node (){
  echo 'Starting run'

  def workSpaceHome = pwd()
  env.CHECKOUT_WORKSPACE = pwd()

  stage 'Running docker build'

  echo 'End run'
}

/*
node (){
  echo 'Starting run'
  stage 'Change directory to code root'
  dir("/code_root"){
    stage 'SCM Checkout'
    checkout scm
  }
  echo 'End run'
}
*/
