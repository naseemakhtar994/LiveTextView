# LiveTextView# LiveTextView
Android Library to display text while it is being spoken

[ ![Download](https://api.bintray.com/packages/jeffg05/Text-To-Speech-File/Live-Text-View/images/download.svg) ](https://bintray.com/jeffg05/Text-To-Speech-File/Live-Text-View/_latestVersion) [![API](https://img.shields.io/badge/API-21%2B-brightgreen.svg?style=flat)](https://android-arsenal.com/api?level=21)

## Getting Started

Follow one of these steps to import Live-Text-View into your project:

### Gradle

```
compile 'com.jeffg.live_text_view:live_text_view:1.0.0'
```

### Maven

```
<dependency>
  <groupId>com.jeffg.live_text_view</groupId>
  <artifactId>live_text_view</artifactId>
  <version>1.0.0</version>
  <type>pom</type>
</dependency>
```

### Ivy

```
<dependency org='com.jeffg.live_text_view' name='live_text_view' rev='1.0.0'>
  <artifact name='live_text_view' ext='pom' ></artifact>
</dependency>
```

## Implementing into your project

### Add XML
```
<com.jeffg.live_text_view.LiveTextView
      android:id="@+id/liveTextView"
      android:layout_width="0dp"
      android:layout_height="0dp"/>
```

### Initialise LiveTextView
```
LiveTextView liveTextView = (LiveTextView) findViewById(R.id.liveTextView);
liveTextView.setText(Text);
liveTextView.start();
```

## License

```
Copyright 2018 Jeff Gugelmann

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