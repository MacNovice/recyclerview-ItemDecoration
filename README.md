# recyclerview-ItemDecoration
首先，发个牢骚，国人的一些习惯啊！！！一篇错误的文章转载无数次，别人一搜，全是一篇，有卵用！！！

这个个人亲自实践出来的，当时心中一万只奔驰而过


使用方法：
recyclerview.addItemDecoration(new RecyclerLineView(this, OrientationHelper.VERTICAL));
recyclerview.addItemDecoration(new RecyclerLineView(this, OrientationHelper.HORIZONTAL));

需要准备：
RecyclerLineView.class   复制到自定义View文件夹
listdivider.xml  复制到res/drawable
在style里面  
    <style name="AppTheme" parent="Theme">
        <!-- Customize your theme here. -->
        <item name="android:listDivider">@drawable/listdivider</item>
    </style>
    
自定义：
   <?xml version="1.0" encoding="utf-8"?>
   <shape xmlns:android="http://schemas.android.com/apk/res/android"
     android:tint="#e0e0e0">
     <solid android:color="#e0e0e0" />
     <size
        android:height="2dp"
        android:width="2dp" />
   </shape>
颜色修改上面的色值
宽度、高度修改height、width

gg
