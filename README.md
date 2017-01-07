# Font-on-Text

####Set custom font in android easily. 

<img align="center" src='https://raw.githubusercontent.com/balrampandey19/FontOnText/master/Screen/img.jpeg' width='250' height='400'/>

FontOnText is a libiray to add custom font in andorid easily. by using this libray you can set custom font on Textview, Button, EditText and others android views.

# Usage


#### Initilize app loger in App Application class.
```
 AppLocker.getInstance().enableAppLock(this);
```

#### Extend LockActivity in all app activity as base activity.

```
 public class MainActivity extends LockActivity {
 
  @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        }
 
 }
```
#### Proguard

```
 -dontwarn com.balram.locker.**
```


# Download

#### The Gradle dependency is available via jCenter. jCenter is the default Maven repository used by Android Studio.


```
dependencies {

compile 'com.balrampandey.locker:1.0.0'

}

```

# License

```
      Copyright 2016 Balram Pandey

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




