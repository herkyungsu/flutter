# main.dart  start


## 기본적인 시작은 아래


~~~dart
void main() => runApp(MyApp());
~~~

```dart
//stl(스테이트리스자동완성) => MyApp 스테이트리스를 작성 한다
class MyApp extends StatelessWidget{
@override
Widget build(BuildContext context){
return MaterialApp(
title: 'Flutter Demo',
home: MyHome();

)
}
}


class MyHome extends statelessWidget{
@override
Widget build(BuildContext context){
return Scaffold(
appBar: AppBar(
title: Text('AppBar Title),  //앱바의 타이틀을 지정 화면상에 표시안됨 앱바의 이름 
backgroundColor: Colors.amber[700],  // 앱바의 배경화면
centerTitle: true,  // 타이틀이 중앙에 위치하는 트루값
elevation: 0.0, // 앱바하단의 높이설정 그림자...
body: Padding(
padding: EdgeInsets.fromLTRB(30.0,40.0,0.0,0.0),
child: Column(
children:[
Text('NAME',
style: TextStyle(
      fontSize: 20.0,
      fontWeight: Bold,
)
)
]
)
)

)
)
}
}
```


