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
	}
}
