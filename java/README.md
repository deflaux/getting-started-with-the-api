# Getting started in java

1. If you have not already done so, follow the Google Genomics [sign up instructions](https://cloud.google.com/genomics/install-genomics-tools#authenticate) to generate and download a valid ``client_secrets.json`` file.  
2. Copy the client_secrets.json file into this directory.
3. [Install maven](http://maven.apache.org/download.cgi)
4. Build and run the code:

```
mvn assembly:assembly
java -jar target/getting-started-java-v1-jar-with-dependencies.jar
```
