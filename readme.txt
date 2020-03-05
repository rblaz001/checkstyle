Commands:

	Install Checkstyle:
	[mvn install]

	Compile Checkstyle:
	[mvn compile]

	Jaccoco Code Coverage Report:
	[mvn test jacoco:restore-instrumented-classes jacoco:report@default-report​ ]

	PITEST Mutation Coverage Report:
	[mvn -e -Ppitest-imports test org.pitest:pitest-maven:mutationCoverage]

	Checkstyle AST GUI:
	[java -cp ../checkstyle-8.30-all.jar com.puppycrawl.tools.checkstyle.gui.Main]
	
	note: I struggled getting this to work and the above command is likely only to work on my 	system. Downloaded jar referenced above and used relative path while inside of class folder.