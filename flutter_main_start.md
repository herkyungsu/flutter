# main.dart  start

## 기본적인 시작은 아래
~~~dart
void main() => runApp(MyApp());
~~~

```dart
stl(스테이트리스자동완성) => MyApp 스테이트리스를 작성 한다
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
title: Text('AppBar Title),


)
)
}
}
```


