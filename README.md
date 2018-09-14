# Version
[![](https://jitpack.io/v/Mouse0w0/Version.svg)](https://jitpack.io/#Mouse0w0/Version)

## How to use it

### Maven
Step 1. Add the JitPack repository to your build file

```xml
	<repositories>
		<repository>
		    <id>jitpack.io</id>
		    <url>https://jitpack.io</url>
		</repository>
	</repositories>
```
Step 2. Add the dependency
```xml
	<dependency>
	    <groupId>com.github.Mouse0w0</groupId>
	    <artifactId>Version</artifactId>
	    <version>1.0.0</version>
	</dependency>
```
### Gradle
Step 1. Add the JitPack repository to your build file

Add it in your root build.gradle at the end of repositories:
```gradle
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```
Step 2. Add the dependency
```gradle
	dependencies {
	        implementation 'com.github.Mouse0w0:Version:1.0.0'
	}
```
