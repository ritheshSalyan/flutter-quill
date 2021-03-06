
<a href="https://bulletjournal.us/home/index.html">
<img src=  
"https://user-images.githubusercontent.com/122956/72955931-ccc07900-3d52-11ea-89b1-d468a6e2aa2b.png"  
 width="150px" height="150px"></a>  
  
# FlutterQuill  
  
Rich text editor and a [Quill] component for [Flutter]. 
  
This library is a WYSIWYG editor built for the modern mobile platform only and web is under development. You can join [Slack Group] for discussion.

https://pub.dev/packages/flutter_quill

This library uses [Quill] as an internal data format.
Use `_controller.document.toDelta()` to extract it or use `_controller.document.toPlainText()` for plain text.

Default branch `master` is on channel `master`. To use channel `stable`, switch to branch `stable`.
Branch `master` on channel `master` supports web. To run the app on web do the following:
1) Change flutter channel to master using `flutter channel master`, followed by `flutter upgrade`.
2) Enable web using `flutter config --enable-web` and restart the IDE.
3) Upon successful execution of step 1 and 2 you should see `Chrome` as one of the devices which you run `flutter devices`.
4) Run the app.

For web development, [ReactQuill] is recommended to use for compatibility.  
  
---  
  
<img width="484" alt="1" src="https://user-images.githubusercontent.com/122956/103142422-9bb19c80-46b7-11eb-83e4-dd0538a9236e.png">  
<img width="484" alt="1" src="https://user-images.githubusercontent.com/122956/103142455-0531ab00-46b8-11eb-89f8-26a77de9227f.png">  
<img width="484" alt="1" src="https://user-images.githubusercontent.com/122956/102963021-f28f5a00-449c-11eb-8f5f-6e9dd60844c4.png">  
<img width="484" alt="1" src="https://user-images.githubusercontent.com/122956/102977404-c9c88e00-44b7-11eb-9423-b68f3b30b0e0.png">  
  
One client and affiliated collaborator of **[FlutterQuill]** is Bullet Journal App: https://bulletjournal.us/home/index.html 
  
[Quill]: https://quilljs.com/docs/formats
[Flutter]: https://github.com/flutter/flutter  
[FlutterQuill]: https://pub.dev/packages/flutter_quill  
[ReactQuill]: https://github.com/zenoamaro/react-quill  
[Slack Group]: https://join.slack.com/t/bulletjournal1024/shared_invite/zt-fys7t9hi-ITVU5PGDen1rNRyCjdcQ2g
