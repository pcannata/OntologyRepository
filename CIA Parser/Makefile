FormatCIAWorldFacts.class: FormatCIAWorldFacts
	javac *java
	jar cmf mainClass FormatCIAWorldFacts.jar *class
	jar tf FormatCIAWorldFacts.jar

FormatCIAWorldFacts: FormatCIAWorldFacts.jj 
	javacc FormatCIAWorldFacts.jj

clean:
	rm *.class *.java

