github 测试
 
Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}Copy
Step 2. Add the dependency

	dependencies {
	        compile 'com.github.litouche:MyTakePhoto-master:v1'
	}
  
  
To get a Git project into your build:
Maven 
Step 1. Add the JitPack repository to your build file
	<repositories>
		<repository>
		    <id>jitpack.io</id>
		    <url>https://jitpack.io</url>
		</repository>
	</repositories>Copy
Step 2. Add the dependency

	<dependency>
	    <groupId>com.github.litouche</groupId>
	    <artifactId>MyTakePhoto-master</artifactId>
	    <version>v1</version>
	</dependency>

