# docker-webapp
deploy a web application using docker

yum install -y java-1.8.0-amazon-corretto-devel

export JAVA_HOME=/usr/lib/jvm/java-1.8.0-amazon-corretto.x86_64
export PATH=$JAVA_HOME/bin:$PATH

javac -version
mvn -version

mvn clean package
