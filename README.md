# Android-Multi-Bluetooth-Library

This library allows you to easily create a socket bluetooth connection for multiple android devices with one server and 7 clients max. This library is compatible with the Android SDK 2.3 to 5.1.

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/svzu2qd_fOo/0.jpg)](http://www.youtube.com/watch?v=svzu2qd_fOo)

For documentation and additional information see [the website][1].

Download
--------
Download __[the latest JAR][2]__  or grab via Maven:
```xml
  <dependencies>
    <dependency>
      <groupId>com.ramimartin.multibluetooth</groupId>
      <artifactId>AndroidMultiBluetoothLibrary</artifactId>
      <version>1.2-SNAPSHOT</version>
    </dependency>
  </dependencies>

  <repositories>
    <repository>
      <id>sfdn-ftp</id>
      <name>Sfdn Ftp</name>
      <url>http://sfdn.com/maven2</url>
    </repository>
  </repositories>
```
or Gradle:
```groovy
repositories {
    maven {
        url "http://sfdn.com/maven2/"
    }
    mavenCentral()
}

dependencies {
    compile 'com.ramimartin.multibluetooth:AndroidMultiBluetoothLibrary:1.2-SNAPSHOT'
}

```
License
-------
    
    /*
    * ----------------------------------------------------------------------------
    * "THE BEER-WARE LICENSE" (Revision 42):
    * Rami Martin wrote this file.  As long as you retain this notice you
    * can do whatever you want with this stuff. If we meet some day, and you think
    * this stuff is worth it, you can buy me a beer in return.   Poul-Henning Kamp
    * ----------------------------------------------------------------------------
    */

[1]: http://arissa34.github.io/Android-Multi-Bluetooth-Library/
[2]: http://93.24.106.19/maven2/com/ramimartin/multibluetooth/AndroidMultiBluetoothLibrary/1.2-SNAPSHOT/AndroidMultiBluetoothLibrary-1.2-20151005.002436-2.jar
