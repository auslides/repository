Configuring your pom.xml as the following to use this repository:
````
   <repositories>
      <repository>
        <id>mvn-repo</id>
        <name>mvn-repo repository</name>
        <url>https://github.com/auslides/repository/raw/master/maven/releases</url>
      </repository>
   </repositories>
   <pluginRepositories>
      <pluginRepository>
        <id>mvn-repo</id>
        <name>mvn-repo plugin repository</name>
        <url>https://github.com/auslides/repository/raw/master/maven/releases</url>
      </pluginRepository>
   </pluginRepositories>
````