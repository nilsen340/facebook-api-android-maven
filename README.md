The mavenized Facebook Android API
==================================

Current port is based on the v3.0 available at https://developers.facebook.com/android/  

To use it in your Android Maven projects you need to add the following repository and dependency to your project pom.xml.  

The repository :  

    <repositories>  
      ...  
      <repository>  
        <id>The mavenized Facebook Android API</id>  
        <url>http://avianey.github.io/facebook-api-android-maven/</url>  
      </repository>  
    </repositories>

The dependency :  

    <dependencies>
      ...
      <dependency>
        <groupId>com.github.avianey</groupId>
        <artifactId>facebook-android-api</artifactId>
        <version>3.0.1</version>
        <type>apklib</type>
      </dependency>
    </dependencies>

The groupId com.github.avianey was picked to avoid conflicts with other third parties ports published in open repositories.
