# Hello!!
personal project

Hi!Nice to meet you!

I like JAVA and ANDROID(that's what I'm made of!).

Just do it!

# How to
To get a Git project into your build:

# Step 1
Add the JitPack repository to your build file

gradle
maven
sbt
leiningen
Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
# Step 2
Add the dependency

	dependencies {
	        implementation 'com.github.BingaChen:feng_lib:V1.0'
	}
