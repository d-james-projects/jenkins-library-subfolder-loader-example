@Library('local-shared-library') _
loadLocalLibrary scm, "library"

pipeline {
	agent any
	stages {
		stage("Test") {
			steps {
				localTest()
			}
		}

		stage("Test 2") {
			steps {
				myNewFunc("hello my world!")
			}
		}
	}
}
