node('slave-1') {
    stage('continuous download_dev')
     {
   git 'https://github.com/sunildevops77/maven.git'
	}
stage('continuous build_dev')
     {
   sh 'mvn package'
	}

}

