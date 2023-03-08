pipeline {
	agent {
		label {
			label "built-in"
			customWorkspace "/mnt/data"
}
}

stages {

	stage ("create-file-1") {
	
	steps {
		sh "touch file 1"
}
}

	stage ("create-file-2") {
	
	steps {
		dir ("/mnt/wsp") {

		sh "touch file 2"
}
}
}
}
}
