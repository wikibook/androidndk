# 「AndroidNDK ネイティブプログラミング」サンプルコード集
[![Gitter](https://badges.gitter.im/Join Chat.svg)](https://gitter.im/wikibook/androidndk?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

ここにあるのは、「AndroidNDKネイティブプログラミング」に掲載されたコード、もしくはその検証用に作成されたコードです。


## 開発環境
Eclipse（Helios）, ADT, CDTを利用しています。

EclipseからNDKのビルドをできるようにしておくと便利です（参考:[EclipseからAndroid NDKのコードをビルドする](http://blog.cnu.jp/2011/07/05/build-ndk-in-eclipse/))

## ファイルについて

章ごとにサンプルコードを掲載しています

### ch02/
- CalcVal/   JavaからCの関数を呼び出す
- CalcVal2/  JavaからCの関数を呼び出す（jniRegisterNativeMethods関数を利用して）
- jniNio/　  Java,C間のjava.nio.Bufferを使った転送例
- jniToast/　CからToastを表示させる
 
### ch03/
- GLNativeActivity　NativeActivity＆OpenGL｜ES1.1でスプライト表示

### ch04/
- CubeDroid/    立方体表示（NatvieActivity、JNIからのOpenGL｜ES1.1呼び出し）  
- cubedroid2/   立方体表示（JNIからのOpenGL|ES2.0呼び出し）  
- NativeBitmap/ NativeBitmap  

### ch06/
- NativeMultiTouch/  JNIによるマルチタッチ取得
- NativeSensor/      JNIによるセンサー取得

### ch07/
- ExportModule/  外部モジュールの設定
- InlineAsm/     インラインアセンブラ使用例

## ライセンスについて

ここに掲載されているコードはすべて、Apache License 2.0とします。

## NOTICE

このコードは、部分的に、Android Open Source Projectのコードを含んでいます。

This product includes software developed as part of
The Android Open Source Project (http://source.android.com).

## 更新履歴

2011/12/19 ch05サンプル削除。コードはNDKのサンプルにあるNativeAudioを参考にしてください
