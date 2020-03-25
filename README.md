# QuizActiivty

A simple demo in which method:
1. item.setOnClickListener(new View.OnClickListener())
2. Toast.makeText
3. tools和tools:text属性的命名空间很特别，可以覆盖某个组件的任何属性，而在运行的时候tools:text又不会显现出来
4. 一个activity启动另一个activity最简单的方式是startActivity方法，调用请求发送给操作系统的ActivityManager。AcitivtyManager负责创建Activity实例并调用其onCreate方法。
``` sss
Intent intent = new Intent(context,class);
startActivity(intent)
```
5. intent.putExtra(key,value)方法，用于在activity之间传递信息
6. Activity.getIntent()方法获取了startActivity（Intent）方法转发的Intent对象
7. 需要从子activity获取返回信息时，调用startActivityForResult（Intent intent,int requestCode）
8. 实现子activity发送信息给父Activity，使用setResult（int resultCode,Intent data）。
9. 最后onActivityResult(int,int,Intent)方法来处理返回结果
10. 添加了一个动画效果，但是原理尚未学习。

were used.
