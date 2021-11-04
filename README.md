# my_lib_toast

> step : 1 #Add it in your root build.gradle at the end of repositories:


allprojects {
		repositories {
			maven { url 'https://jitpack.io' }
		}
	}
  
  > step : 2 #Add the dependency
  	dependencies {
	        implementation 'com.github.bijoycse:my_lib_toast:1.0.0'
	}
