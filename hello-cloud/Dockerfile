FROM java
ADD ./target/hello-cloud-0.1.0.jar /hello-cloud-0.1.0.jar
ADD ./hadoop-mapreduce-examples-2.6.0.jar /hadoop-mapreduce-examples-2.6.0.jar
ADD ./run.sh /run.sh
RUN chmod a+x /run.sh
CMD /run.sh