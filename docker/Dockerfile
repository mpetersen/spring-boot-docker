FROM anapsix/alpine-java

RUN curl -o mvn.tar.gz http://apache.openmirror.de/maven/maven-3/3.3.3/binaries/apache-maven-3.3.3-bin.tar.gz &&\
	tar xzvf mvn.tar.gz &&\
	mv apache-maven-3.3.3 mvn &&\
	rm mvn.tar.gz &&\
	mkdir /app
	
CMD cd /app && /mvn/bin/mvn spring-boot:run