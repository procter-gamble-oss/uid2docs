---
title: UID2 GMA Plugin for Android
description: Android アプリの広告リクエストに GMA を使用するパブリッシャーのためのガイド。
hide_table_of_contents: false
sidebar_position: 12
---
# UID2 GMA Plugin for Android Integration Guide

UID2 Google Mobile Ads (GMA) Plugin for Android は、[Google Mobile Ads (GMA) SDK](https://developers.google.com/ad-manager/mobile-ads-sdk) を使用するパブリッシャーが、Android アプリからの広告リクエストで [UID2 Token](../ref-info/glossary-uid.md#gl-uid2-token) を送信できるようにします。これは自動的に行われ、アプリ開発者が直接コーディングする必要はありません。

## Functionality

このプラグインは、Android 端末で動作するアプリで UID2 をサポートしたいパブリッシャー向けに、Google Mobile Ads（GMA）とのインテグレーションを簡素化します。

## Version

<!-- As of 2023-07-15 -->

このドキュメントは、UID2 GMA Plugin for Android バージョン 0.4.0 用です。

## GitHub Repository

このプラグインは以下のオープンソースの GitHub リポジトリにあります:

- [https://github.com/IABTechLab/uid2-android-sdk/tree/main/securesignals-gma](https://github.com/IABTechLab/uid2-android-sdk/tree/main/securesignals-gma)

## Requirements 

このプラグインを実行するには、以下をインストールします:

- [Google Mobile Ads SDK v22.0.0+](https://developers.google.com/admob/android/sdk)
- [UID2 SDK for Android v0.4.0](https://central.sonatype.com/artifact/com.uid2/uid2-android-sdk) (ドキュメントについては、[UID2 SDK for Android Reference Guide](../sdks/uid2-sdk-ref-android.md) を参照してください。)
- [UID2 Android GMA Plugin v0.4.0](https://central.sonatype.com/artifact/com.uid2/uid2-android-sdk-gma)

## Installation

前提条件: Google Mobile Ads SDK と UID2 Android SDK をインストールしてください。

UID2 Android SDK と Google IMA SDK がインストールされている既存のアプリに、UID2 Android GMA Plugin v0.4.0 をインストールします。インストール方法は 2 つあります:

- [Gradle](#gradle)
- [Maven](#maven)

### Gradle 

Gradle でインストールするには、`build.gradle` ファイルに依存関係として SDK を追加します:

```
implementation 'com.uid2:uid2-android-sdk-gma:0.4.0'
```

### Maven 

Maven でインストールするには、`pom.xml` ファイルに依存関係として SDK を追加します:

```
<dependency>
  <groupId>com.uid2</groupId>
  <artifactId>uid2-android-sdk-gma</artifactId>
  <version>0.4.0</version>
</dependency>
```

<!-- eng_jp -->