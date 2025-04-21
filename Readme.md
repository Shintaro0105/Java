# Java Dev Container Environment (Java 21 + Gradle)

このリポジトリは、Visual Studio Code の Dev Containers 機能を用いて Java 開発環境を Docker コンテナ内に構築するテンプレートです。Java 21 および Gradle を使用した開発に最適化されています。

## 🐳 利用技術

- Java 21 (OpenJDK)
- Gradle（Mavenは未インストール）
- Debian Bullseye ベースのDockerイメージ
- VS Code Dev Containers 拡張

## Java コードのコンパイルと実行手順

1. ターミナルを開く
VS Code で `Ctrl + `` で開くか、メニューから開きます。

2. Java ファイルをコンパイル
```sh
javac src/main/HelloWorld.java
```
成功すると src/main/HelloWorld.class が生成されます。

3. Java クラスを実行
```sh
cd src/main
java HelloWorld
```
出力例：
```sh
Hello, World!!
```