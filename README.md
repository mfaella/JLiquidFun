This project provides ready-to-use Java bindings for LiquidFun, including the pre-compiled library for Android architectures.

Instructions to use this project in your Android Studio project:

Copy the content of "java" into your folder <project root>/app/src/main/java
Copy the content of "libs" into your folder <project root>/app/src/main/jniLibs

In your onCreate method, load the library:

System.loadLibrary(“liquidfun”);
System.loadLibrary(“liquidfun_jni”);

Then, you can create a World, add Body objects to it, etc.
