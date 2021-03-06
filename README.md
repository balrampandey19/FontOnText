# Font-on-Text
[![](https://jitpack.io/v/balrampandey19/FontOnText.svg)](https://jitpack.io/#balrampandey19/FontOnText)
[![License](http://img.shields.io/:license-apache-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)


## Set custom fonts in android easily. 



<img align="center" src='https://raw.githubusercontent.com/balrampandey19/FontOnText/master/Screen/img.jpeg' width='250' height='400'/>

FontOnText is a library to add custom fonts in android easily. by using this library you can easily set custom font on Textview, Button, EditText and other android views.

# Usage
```
Add your custom fonts to assets/.
```

#### Add custom font on TextView.
```
   <com.balram.library.FotTextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:gravity="center"
        android:text="@string/message"
        android:textSize="20dp"
        app:font="FONT_NAME"/>
        
```

#### Add custom font on Buuton

```
  <com.balram.library.FotRadioButton
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:textSize="20dp"
        android:layout_marginTop="8dp"
        android:gravity="center"
        android:hint="@string/message"
        app:font="FONT_NAME"/>
```
#### Proguard

```
 -dontwarn com.balram.library.**
```


# Download

#### Add it to your build.gradle with:
```gradle
allprojects {
    repositories {
        maven { url "https://jitpack.io" }
    }
}
```
and:

```gradle
dependencies {
    compile 'com.github.balrampandey19:FontOnText:0.0.1'
}
```

# License

```
      Copyright 2017 Balram Pandey

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.

```




