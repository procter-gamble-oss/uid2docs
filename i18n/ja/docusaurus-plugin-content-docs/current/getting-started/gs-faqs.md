---
title: Frequently Asked Questions
description: UID2 の実装に関するよくある質問。
hide_table_of_contents: false
sidebar_position: 20
---

# Frequently Asked Questions

UID2 に関するよくある質問は、以下のカテゴリーに分かれています:

UID2に関するよくある質問は、対象者別に一般的なカテゴリーに分類されています。

このページには、以下のものがあります：

- [FAQs -- General](#faqs----general)
- [FAQs for Publishers Using an SDK](#faqs-for-publishers-using-an-sdk)
- [FAQs for Publishers Not Using an SDK](#faqs-for-publishers-not-using-an-sdk)
- [FAQs for Advertisers and Data Providers](#faqs-for-advertisers-and-data-providers)
- [FAQs for Demand-Side Platforms (DSPs)](#faqs-for-demand-side-platforms-dsps)

## FAQs -- General

UID2 フレームワークに関するよくある質問を紹介します。

- [EUID インフラストラクチャのすべてのインテグレーションパートナー（SSP、第三者データプロバイダー、測定プロバイダー）は、自動的に UID2 にインテグレーションされるのでしょうか？](#euid-%E3%82%A4%E3%83%B3%E3%83%95%E3%83%A9%E3%82%B9%E3%83%88%E3%83%A9%E3%82%AF%E3%83%81%E3%83%A3%E3%81%AE%E3%81%99%E3%81%B9%E3%81%A6%E3%81%AE%E3%82%A4%E3%83%B3%E3%83%86%E3%82%B0%E3%83%AC%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3%E3%83%91%E3%83%BC%E3%83%88%E3%83%8A%E3%83%BCssp%E7%AC%AC%E4%B8%89%E8%80%85%E3%83%87%E3%83%BC%E3%82%BF%E3%83%97%E3%83%AD%E3%83%90%E3%82%A4%E3%83%80%E3%83%BC%E6%B8%AC%E5%AE%9A%E3%83%97%E3%83%AD%E3%83%90%E3%82%A4%E3%83%80%E3%83%BC%E3%81%AF%E8%87%AA%E5%8B%95%E7%9A%84%E3%81%AB-uid2-%E3%81%AB%E3%82%A4%E3%83%B3%E3%83%86%E3%82%B0%E3%83%AC%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3%E3%81%95%E3%82%8C%E3%82%8B%E3%81%AE%E3%81%A7%E3%81%97%E3%82%87%E3%81%86%E3%81%8B)
- [ユーザーは、UID2 ID に関連するターゲティング広告の配信を拒否できますか？](#%E3%83%A6%E3%83%BC%E3%82%B6%E3%83%BC%E3%81%AFuid2-id-%E3%81%AB%E9%96%A2%E9%80%A3%E3%81%99%E3%82%8B%E3%82%BF%E3%83%BC%E3%82%B2%E3%83%86%E3%82%A3%E3%83%B3%E3%82%B0%E5%BA%83%E5%91%8A%E3%81%AE%E9%85%8D%E4%BF%A1%E3%82%92%E6%8B%92%E5%90%A6%E3%81%99%E3%82%8B%E3%81%93%E3%81%A8%E3%81%8C%E3%81%A7%E3%81%8D%E3%81%BE%E3%81%99%E3%81%8B)
- [オプトアウトポータルにアクセスする場所をユーザーが知るにはどうすればよいですか？](#%E3%82%AA%E3%83%97%E3%83%88%E3%82%A2%E3%82%A6%E3%83%88%E3%83%9D%E3%83%BC%E3%82%BF%E3%83%AB%E3%81%AB%E3%82%A2%E3%82%AF%E3%82%BB%E3%82%B9%E3%81%99%E3%82%8B%E5%A0%B4%E6%89%80%E3%82%92%E3%83%A6%E3%83%BC%E3%82%B6%E3%83%BC%E3%81%8C%E7%9F%A5%E3%82%8B%E3%81%AB%E3%81%AF%E3%81%A9%E3%81%86%E3%81%99%E3%82%8C%E3%81%B0%E3%82%88%E3%81%84%E3%81%A7%E3%81%99%E3%81%8B)

<!-- (gwh note: section is taken from original readme) -->

#### EUID インフラストラクチャのすべてのインテグレーションパートナー（SSP、第三者データプロバイダー、測定プロバイダー）は、自動的に UID2 にインテグレーションされるのでしょうか？

<!-- FAQ_01 -->

いいえ。UID2 は EUID とは別の独自のフレームワークとして機能します。そのため、EUID フレームワークへのアクセスや使用に関する事務手続きは、UID2 フレームワークへの使用やアクセスを自動的に許可するものではありません。新規契約を UID2 用に締結する必要があります。

#### ユーザーは、UID2 ID に関連するターゲティング広告の配信を拒否できますか？

<!-- FAQ_02 -->

はい。[Transparency and Control Portal](https://transparentadvertising.org)を通して、ユーザーは自分の UID2 ID に関連するターゲティング広告の配信をオプトアウトできます。各リクエストは、UID2 Opt-Opt Service と UID2 Operator を通じて、関連するすべての参加者に配信されます。

#### オプトアウトポータルにアクセスする場所をユーザーが知るにはどうすればよいですか？

<!-- FAQ_03 -->

パブリッシャー、SSO プロバイダー、または同意管理プラットフォームは、ログインフロー、同意フロー、プライバシーポリシー、およびその他の手段で、[Transparency and Control Portal](https://transparentadvertising.org)へのリンクを開示します。

## FAQs for Publishers Using an SDK

UID2 フレームワークを使用するパブリッシャーが、クライアントサイド SDK を使用する際に、よくある質問を紹介します。

- [ユーザーオプトアウトの通知はどのように行われますか？](#%E3%83%A6%E3%83%BC%E3%82%B6%E3%83%BC%E3%82%AA%E3%83%97%E3%83%88%E3%82%A2%E3%82%A6%E3%83%88%E3%81%AE%E9%80%9A%E7%9F%A5%E3%81%AF%E3%81%A9%E3%81%AE%E3%82%88%E3%81%86%E3%81%AB%E8%A1%8C%E3%82%8F%E3%82%8C%E3%81%BE%E3%81%99%E3%81%8B-sdk-%E4%BD%BF%E7%94%A8%E6%99%82)
- [トークン生成の呼び出しは、サーバー側とクライアント側のどちらで行うべきですか？](#%E3%83%88%E3%83%BC%E3%82%AF%E3%83%B3%E7%94%9F%E6%88%90%E3%81%AE%E5%91%BC%E3%81%B3%E5%87%BA%E3%81%97%E3%81%AF%E3%82%B5%E3%83%BC%E3%83%90%E3%83%BC%E5%81%B4%E3%81%A8%E3%82%AF%E3%83%A9%E3%82%A4%E3%82%A2%E3%83%B3%E3%83%88%E5%81%B4%E3%81%AE%E3%81%A9%E3%81%A1%E3%82%89%E3%81%A7%E8%A1%8C%E3%81%86%E3%81%B9%E3%81%8D%E3%81%A7%E3%81%99%E3%81%8B-sdk-%E4%BD%BF%E7%94%A8%E6%99%82)
- [クライアントサイドから Token Refresh を呼び出すことはできますか？](#%E3%82%AF%E3%83%A9%E3%82%A4%E3%82%A2%E3%83%B3%E3%83%88%E3%82%B5%E3%82%A4%E3%83%89%E3%81%8B%E3%82%89-token-refresh-%E3%82%92%E5%91%BC%E3%81%B3%E5%87%BA%E3%81%99%E3%81%93%E3%81%A8%E3%81%AF%E3%81%A7%E3%81%8D%E3%81%BE%E3%81%99%E3%81%8B-sdk-%E4%BD%BF%E7%94%A8%E6%99%82)
- [送信された DII と返されたトークンが一致することをテストするにはどうすればよいですか？](#%E9%80%81%E4%BF%A1%E3%81%95%E3%82%8C%E3%81%9F-dii-%E3%81%A8%E8%BF%94%E3%81%95%E3%82%8C%E3%81%9F%E3%83%88%E3%83%BC%E3%82%AF%E3%83%B3%E3%81%8C%E4%B8%80%E8%87%B4%E3%81%99%E3%82%8B%E3%81%93%E3%81%A8%E3%82%92%E3%83%86%E3%82%B9%E3%83%88%E3%81%99%E3%82%8B%E3%81%AB%E3%81%AF%E3%81%A9%E3%81%86%E3%81%99%E3%82%8C%E3%81%B0%E3%82%88%E3%81%84%E3%81%A7%E3%81%99%E3%81%8B-sdk-%E4%BD%BF%E7%94%A8%E6%99%82)
- [Refresh Token のワークフローをテストするにはどうすればよいですか？](#refresh-token-%E3%81%AE%E3%83%AF%E3%83%BC%E3%82%AF%E3%83%95%E3%83%AD%E3%83%BC%E3%82%92%E3%83%86%E3%82%B9%E3%83%88%E3%81%99%E3%82%8B%E3%81%AB%E3%81%AF%E3%81%A9%E3%81%86%E3%81%99%E3%82%8C%E3%81%B0%E3%82%88%E3%81%84%E3%81%A7%E3%81%99%E3%81%8B-sdk-%E4%BD%BF%E7%94%A8%E6%99%82)

#### ユーザーオプトアウトの通知はどのように行われますか？ （SDK 使用時）

<!-- FAQ_05 -->

[Client-Side JavaScript SDK](../sdks/client-side-identity.md) のバックグラウンドトークン自動更新処理では、ユーザーのオプトアウトを処理します。ユーザーがオプトアウトした場合、SDK がトークンのリフレッシュを試みる際に、オプトアウトを知り、セッション（クッキーを含む）をクリアし、`OPTOUT`ステータスを持つコールバックを呼び出します。トークン生成プロセスでも、ユーザーのオプトアウトステータスをチェックします。

#### トークン生成の呼び出しは、サーバー側とクライアント側のどちらで行うべきですか？ （SDK 使用時）

<!-- FAQ_06 -->

UID2 Token は、認証後にサーバー側で生成する必要があります。つまり、サービスにアクセスするための API キーが秘密になるように、[POST /token/generate](../endpoints/post-token-generate.md) エンドポイントは、サーバー側からのみ呼び出される必要があります。

#### クライアントサイドから Token Refresh を呼び出すことはできますか？ （SDK 使用時）

<!-- FAQ_07 -->

はい。[POST /token/refresh](../endpoints/post-token-refresh.md) は、API キーを使用する必要がないため、クライアント側（ブラウザやモバイルアプリなど）から呼び出すことが可能です。

#### 送信された DII と返されたトークンが一致することをテストするにはどうすればよいですか？ （SDK 使用時）

<!-- FAQ_08 -->

[POST /token/validate](../endpoints/post-token-validate.md) エンドポイントを使用して、[POST /token/generate](../endpoints/post-token-generate.md) を通じて送信する個人に関するデータが有効かどうかをチェックできます。

1. 個人に関するデータがメールアドレスか電話番号かによって、次のいずれかの値を使用して[POST /token/generate](../endpoints/post-token-generate.md) リクエストを送信します：
   - `email`の値として`validate@email.com`を指定します。
   - `validate@email.com`のハッシュを `email_hash` 値として指定します。
   - `phone`の値として `+12345678901` を指定します。
   - `phone_hash`値として`+12345678901`のハッシュを指定します。
2. 次のステップで使用するために、返された `advertising_token` を保存します。
3. ステップ 1 で送信した `email`、`email_hash`、`phone`、`phone_hash` のいずれかの値と、`token` プロパティ値として `advertising_token` （ステップ 2 で保存）を使用して [POST /token/validate](../endpoints/post-token-validate.md) リクエストを送信します。
   - レスポンスが `true` の場合、ステップ 1 でリクエストとして送信した個人に関するデータが、ステップ 1 のレスポンスで受け取ったトークンと一致することを示します。
   - false` の場合は、メールアドレス、電話番号、またはそれぞれのハッシュを送信する方法に問題がある可能性があることを示しています。

#### Refresh Token のワークフローをテストするにはどうすればよいですか？ （SDK 使用時）

<!-- FAQ_09 -->

メールアドレス`optout@email.com`または電話番号`+000000000`を使用して、Refresh Token ワークフローをテストできます。リクエストでいずれかのパラメータ値を使用すると、常に`refresh_token`を含む ID レスポンスが生成され、ログアウト レスポンスが返されます。

1. 個人に関するデータがメールアドレスか電話番号かに応じて、次のいずれかの値を使用して [POST /token/generate](../endpoints/post-token-generate.md) 要求を送信します：
   - `email`の値として`optout@email.com`を指定します。
   - `optout@email.com`のハッシュを `email_hash` 値として指定します。
   - `phone`の値として `+00000000000` を指定する。
   - `phone_hash`値として`+000000000`のハッシュを指定します。
2. SDK の [background auto-refresh](../sdks/client-side-identity.md#background-token-auto-refresh) が Advertising Token のリフレッシュを試みるまで待ちます（これは数時間かかることがあります）、リフレッシュ試みが`OPTOUT`ステータスで失敗するのを観察します。この時点で SDK はファーストパーティのクッキーもクリアします。

## FAQs for Publishers Not Using an SDK

パブリッシャーがクライアントサイド SDK を使用していない場合、UID2 フレームワークを使用する際によくある質問を紹介します。

- [トークンの復号化は必要ですか？](#%E3%83%88%E3%83%BC%E3%82%AF%E3%83%B3%E3%81%AE%E5%BE%A9%E5%8F%B7%E5%8C%96%E3%81%AF%E5%BF%85%E8%A6%81%E3%81%A7%E3%81%99%E3%81%8B)
- [ユーザーのオプトアウトはどのように通知されるのですか？](#%E3%83%A6%E3%83%BC%E3%82%B6%E3%83%BC%E3%81%AE%E3%82%AA%E3%83%97%E3%83%88%E3%82%A2%E3%82%A6%E3%83%88%E3%81%AF%E3%81%A9%E3%81%AE%E3%82%88%E3%81%86%E3%81%AB%E9%80%9A%E7%9F%A5%E3%81%95%E3%82%8C%E3%82%8B%E3%81%AE%E3%81%A7%E3%81%99%E3%81%8B-sdk-%E3%81%AA%E3%81%97)
- [トークン生成の呼び出しは、サーバー側とクライアント側のどちらから行うべきでしょうか？](#%E3%83%88%E3%83%BC%E3%82%AF%E3%83%B3%E7%94%9F%E6%88%90%E3%81%AE%E5%91%BC%E3%81%B3%E5%87%BA%E3%81%97%E3%81%AF%E3%82%B5%E3%83%BC%E3%83%90%E3%83%BC%E5%81%B4%E3%81%A8%E3%82%AF%E3%83%A9%E3%82%A4%E3%82%A2%E3%83%B3%E3%83%88%E5%81%B4%E3%81%AE%E3%81%A9%E3%81%A1%E3%82%89%E3%81%8B%E3%82%89%E8%A1%8C%E3%81%86%E3%81%B9%E3%81%8D%E3%81%A7%E3%81%97%E3%82%87%E3%81%86%E3%81%8B-sdk-%E3%81%AA%E3%81%97)
- [クライアントサイドからトークンリフレッシュの呼び出しを行うことは可能ですか？](#%E3%82%AF%E3%83%A9%E3%82%A4%E3%82%A2%E3%83%B3%E3%83%88%E3%82%B5%E3%82%A4%E3%83%89%E3%81%8B%E3%82%89%E3%83%88%E3%83%BC%E3%82%AF%E3%83%B3%E3%83%AA%E3%83%95%E3%83%AC%E3%83%83%E3%82%B7%E3%83%A5%E3%81%AE%E5%91%BC%E3%81%B3%E5%87%BA%E3%81%97%E3%82%92%E8%A1%8C%E3%81%86%E3%81%93%E3%81%A8%E3%81%AF%E5%8F%AF%E8%83%BD%E3%81%A7%E3%81%99%E3%81%8B-sdk-%E3%81%AA%E3%81%97)
- [UID2 Token の一意性とローテーションのポリシーは何ですか？](#uid2-token-%E3%81%AE%E4%B8%80%E6%84%8F%E6%80%A7%E3%81%A8%E3%83%AD%E3%83%BC%E3%83%86%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3%E3%81%AE%E3%83%9D%E3%83%AA%E3%82%B7%E3%83%BC%E3%81%AF%E4%BD%95%E3%81%A7%E3%81%99%E3%81%8B)
- [送信された DII と返されたトークンが一致することをテストするにはどうすればよいですか？](#%E9%80%81%E4%BF%A1%E3%81%95%E3%82%8C%E3%81%9F-dii-%E3%81%A8%E8%BF%94%E3%81%95%E3%82%8C%E3%81%9F%E3%83%88%E3%83%BC%E3%82%AF%E3%83%B3%E3%81%8C%E4%B8%80%E8%87%B4%E3%81%99%E3%82%8B%E3%81%93%E3%81%A8%E3%82%92%E3%83%86%E3%82%B9%E3%83%88%E3%81%99%E3%82%8B%E3%81%AB%E3%81%AF%E3%81%A9%E3%81%86%E3%81%99%E3%82%8C%E3%81%B0%E3%82%88%E3%81%84%E3%81%A7%E3%81%99%E3%81%8B-sdk-%E3%81%AA%E3%81%97)
- [Refresh Token のワークフローをテストするにはどうすればよいですか？](#refresh-token-%E3%81%AE%E3%83%AF%E3%83%BC%E3%82%AF%E3%83%95%E3%83%AD%E3%83%BC%E3%82%92%E3%83%86%E3%82%B9%E3%83%88%E3%81%99%E3%82%8B%E3%81%AB%E3%81%AF%E3%81%A9%E3%81%86%E3%81%99%E3%82%8C%E3%81%B0%E3%82%88%E3%81%84%E3%81%A7%E3%81%99%E3%81%8B-sdk-%E3%81%AA%E3%81%97)

#### トークンの復号化は必要ですか？

<!-- FAQ_11 -->

いいえ、パブリッシャーがトークンを復号化する必要はありません。

#### ユーザーのオプトアウトはどのように通知されるのですか？ (SDK なし)

<!-- FAQ_12 -->

トークンのリフレッシュプロセスは、ユーザーのオプトアウトを処理する。[POST /token/refresh](../endpoints/post-token-refresh.md) は、空の ID とユーザーのオプトアウトステータスを返します。

#### トークン生成の呼び出しは、サーバー側とクライアント側のどちらから行うべきでしょうか？ (SDK なし)

<!-- FAQ_13 -->

UID2 Token は、認証後にサーバー側でのみ生成する必要があります。つまり、サービスへのアクセスに使用される API キーが秘密であることを保証するために、[POST /token/generate](../endpoints/post-token-generate.md) エンドポイントは、サーバーサイドからのみ呼び出す必要があります。

#### クライアントサイドからトークンリフレッシュの呼び出しを行うことは可能ですか？ (SDK なし)

<!-- FAQ_14 -->

[POST /token/refresh](../endpoints/post-token-refresh.md) は、API キーを使用する必要がないため、クライアント側（たとえば、ブラウザやモバイルアプリ）から呼び出すことが可能です。

#### UID2 Token の一意性とローテーションのポリシーは何ですか？

<!-- FAQ_15 -->

UID2 Service は、ランダムな初期化ベクトルを使用してトークンを暗号化します。暗号化された UID2 は、インターネットを閲覧している特定のユーザーにとって一意です。更新のたびに、トークンは再暗号化されます。この仕組みにより、信頼できない第三者がユーザーの身元を追跡できないようにします。

#### 送信された DII と返されたトークンが一致することをテストするにはどうすればよいですか？ (SDK なし)

<!-- FAQ_16 -->

[POST /token/validate](../endpoints/post-token-validate.md) エンドポイントを使用して、[POST /token/generate](../endpoints/post-token-generate.md) を通じて送信する DII が有効かどうかをチェックできます。

1. DII がメールアドレスか電話番号かによって、次のいずれかの値を使用して [POST /token/generate](../endpoints/post-token-generate.md) リクエストを送信してください：
   - `email`の値として`validate@email.com`を指定します。
   - `validate@email.com`のハッシュを `email_hash` 値として指定します。
   - `phone`の値として `+12345678901` を指定します。
   - `phone_hash`値として`+12345678901`のハッシュを指定します。
2. 次のステップで使用するために、返された `advertising_token` を保存します。
3. ステップ 1 で送信した `email`、`email_hash`、`phone`、`phone_hash` のいずれかの値と、`token` プロパティ値として `advertising_token` （ステップ 2 で保存）を使用して [POST /token/validate](../endpoints/post-token-validate.md) 要求を送信します。
   - レスポンスが `true` の場合、ステップ 1 でリクエストとして送信した DII は、ステップ 1 のレスポンスで受け取ったトークンと一致します。
   - false` の場合は、メールアドレス、電話番号、またはそれぞれのハッシュを送信する方法に問題がある可能性があります。

#### Refresh Token のワークフローをテストするにはどうすればよいですか？ (SDK なし)

<!-- FAQ_17 -->

`optout@email.com` のメールアドレスまたは `+00000000000` の電話番号を使用して、Refresh Token ワークフローをテストできます。メールアドレスまたは電話番号をリクエストに使用すると、常に `refresh_token` を含む ID レスポンスが生成され、ログアウトのレスポンスになります。

1. DII がメールアドレスか電話番号かに応じて、次のいずれかの値を使用して [POST /token/generate](../endpoints/post-token-generate.md) 要求を送信します：
   - `email`の値として`optout@email.com`を指定します。
   - `optout@email.com`のハッシュを `email_hash` 値として指定します。
   - `phone`の値として `+00000000000` を指定する。
   - `phone_hash`値として`+000000000`のハッシュを指定します。
2. 次のステップで使用するために、返された `refresh_token` を保存する。
3. 3.ステップ 2 で保存した `refresh_token` を `token` 値として [POST /token/refresh](../endpoints/post-token-refresh.md) リクエストを送信します。<br/>ボディレスポンスは空で、`status` 値は `optout` に設定してください。これは `optout@email.com` メールと `+00000000` という電話番号によって常にログアウトしたユーザーと見なされることになります。

## FAQs for Advertisers and Data Providers

UID2 フレームワークを使用する広告主やデータプロバイダーによくある質問を紹介します。

- [ソルトバケットのローテーションにより、UID2 を更新するタイミングを知るにはどうすればよいですか？](#%E3%82%BD%E3%83%AB%E3%83%88%E3%83%90%E3%82%B1%E3%83%83%E3%83%88%E3%81%AE%E3%83%AD%E3%83%BC%E3%83%86%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3%E3%81%AB%E3%82%88%E3%82%8Auid2-%E3%82%92%E6%9B%B4%E6%96%B0%E3%81%99%E3%82%8B%E3%82%BF%E3%82%A4%E3%83%9F%E3%83%B3%E3%82%B0%E3%82%92%E7%9F%A5%E3%82%8B%E3%81%AB%E3%81%AF%E3%81%A9%E3%81%86%E3%81%99%E3%82%8C%E3%81%B0%E3%82%88%E3%81%84%E3%81%A7%E3%81%99%E3%81%8B)
- [リフレッシュされたメールアドレスは、以前関連付けられていたバケットと同じバケットに割り当てられるのでしょうか？](#%E3%83%AA%E3%83%95%E3%83%AC%E3%83%83%E3%82%B7%E3%83%A5%E3%81%95%E3%82%8C%E3%81%9F%E3%83%A1%E3%83%BC%E3%83%AB%E3%82%A2%E3%83%89%E3%83%AC%E3%82%B9%E3%81%AF%E4%BB%A5%E5%89%8D%E9%96%A2%E9%80%A3%E4%BB%98%E3%81%91%E3%82%89%E3%82%8C%E3%81%A6%E3%81%84%E3%81%9F%E3%83%90%E3%82%B1%E3%83%83%E3%83%88%E3%81%A8%E5%90%8C%E3%81%98%E3%83%90%E3%82%B1%E3%83%83%E3%83%88%E3%81%AB%E5%89%B2%E3%82%8A%E5%BD%93%E3%81%A6%E3%82%89%E3%82%8C%E3%82%8B%E3%81%AE%E3%81%A7%E3%81%97%E3%82%87%E3%81%86%E3%81%8B)
- [インクリメンタルアップデートの場合、UID はどれくらいの頻度で更新されるべきですか？](#%E3%82%A4%E3%83%B3%E3%82%AF%E3%83%AA%E3%83%A1%E3%83%B3%E3%82%BF%E3%83%AB%E3%82%A2%E3%83%83%E3%83%97%E3%83%87%E3%83%BC%E3%83%88%E3%81%AE%E5%A0%B4%E5%90%88uid-%E3%81%AF%E3%81%A9%E3%82%8C%E3%81%8F%E3%82%89%E3%81%84%E3%81%AE%E9%A0%BB%E5%BA%A6%E3%81%A7%E6%9B%B4%E6%96%B0%E3%81%95%E3%82%8C%E3%82%8B%E3%81%B9%E3%81%8D%E3%81%A7%E3%81%99%E3%81%8B)
- [マッピング用の DII の SHA-256 はどのように生成すればよいですか？](#%E3%83%9E%E3%83%83%E3%83%94%E3%83%B3%E3%82%B0%E7%94%A8%E3%81%AE-dii-%E3%81%AE-sha-256-%E3%81%AF%E3%81%A9%E3%81%AE%E3%82%88%E3%81%86%E3%81%AB%E7%94%9F%E6%88%90%E3%81%99%E3%82%8C%E3%81%B0%E3%82%88%E3%81%84%E3%81%A7%E3%81%99%E3%81%8B)

- [大量のメールアドレスや電話番号、またはそれらのハッシュマッピングを保存する必要がありますか？](#%E5%A4%A7%E9%87%8F%E3%81%AE%E3%83%A1%E3%83%BC%E3%83%AB%E3%82%A2%E3%83%89%E3%83%AC%E3%82%B9%E3%82%84%E9%9B%BB%E8%A9%B1%E7%95%AA%E5%8F%B7%E3%81%BE%E3%81%9F%E3%81%AF%E3%81%9D%E3%82%8C%E3%82%89%E3%81%AE%E3%83%8F%E3%83%83%E3%82%B7%E3%83%A5%E3%83%9E%E3%83%83%E3%83%94%E3%83%B3%E3%82%B0%E3%82%92%E4%BF%9D%E5%AD%98%E3%81%99%E3%82%8B%E5%BF%85%E8%A6%81%E3%81%8C%E3%81%82%E3%82%8A%E3%81%BE%E3%81%99%E3%81%8B)
- [ユーザーのオプトアウトはどのように処理すればよいですか？](#%E3%83%A6%E3%83%BC%E3%82%B6%E3%83%BC%E3%81%AE%E3%82%AA%E3%83%97%E3%83%88%E3%82%A2%E3%82%A6%E3%83%88%E3%81%AF%E3%81%A9%E3%81%AE%E3%82%88%E3%81%86%E3%81%AB%E5%87%A6%E7%90%86%E3%81%99%E3%82%8C%E3%81%B0%E3%82%88%E3%81%84%E3%81%A7%E3%81%99%E3%81%8B)

#### ソルトバケットのローテーションにより、UID2 を更新するタイミングを知るにはどうすればよいですか？

<!-- FAQ_19 ADP -->

UID2 生成リクエストで提供されるメタデータには、UID2 の生成に使用されるソルトバケットが含まれます。ソルトバケットは持続し、UID2 の生成に使用された基礎的な DII に対応します。指定されたタイムスタンプ以降にローテーションしたソルトバケットを得るには、[POST /identity/buckets](../endpoints/post-identity-buckets.md) エンドポイントを使用します。返されたローテーションしたソルトバケットは、どの UID2 をリフレッシュすべきかを教えてくれます。

#### リフレッシュされたメールアドレスは、以前関連付けられていたバケットと同じバケットに割り当てられるのでしょうか？

<!-- FAQ_20 ADP -->

必ずしもそうとは限りません。特定のバケット ID に関連付けられたメールアドレスを再マッピングした後、そのメールが異なるバケット ID に割り当てられる可能性があります。バケット ID を確認するには、[マッピング関数を呼び出す](../guides/advertiser-dataprovider-guide.md#retrieve-a-raw-uid2-for-dii-using-the-identity-map-endpoints) そして返された UID2 とバケット ID を再び保存してください。

IMPORTANT: メールアドレスのマッピングや再マッピングを行う際には、バケット番号やローテーションした日、どのバケットにメールアドレスが割り当てられるかなどを想定しないように注意してください。

#### インクリメンタルアップデートの場合、UID はどれくらいの頻度で更新されるべきですか？

<!-- FAQ_21 ADP -->

オーディエンスの更新は、毎日行うことが推奨されています。

ソルトバケットは 1 年に 1 回程度更新されますが、個々のバケットの更新は 1 年に分散して行われます。これは、全バケットの約 1/365 が毎日ローテーションされることを意味します。もし忠実さが重要であれば、[POST /identity/buckets](../endpoints/post-identity-buckets.md) エンドポイントをもっと頻繁に、たとえば 1 時間ごとに呼び出すことを検討してください。

#### マッピング用の DII の SHA-256 はどのように生成すればよいですか？

<!-- FAQ_22 ADP -->

システムは[メールアドレス正規化ルール](../getting-started/gs-normalization-encoding#email-address-normalization)にしたがって、salt せずにハッシュ化する必要があります。

#### 大量のメールアドレスや電話番号、またはそれらのハッシュマッピングを保存する必要がありますか？

<!-- FAQ_23 ADP -->

はい。何百万ものメールアドレスや電話番号をマッピングする必要がある場合、マッピングを保存しないことで処理時間が大幅に増加する可能性があります。しかし、実際に更新が必要なマッピングだけを再計算すると、毎日更新する必要があるのは UID2 の約 365 分の 1 なので、総処理時間が短縮されます。

> IMPORTANT: プライベートオペレーターを使用していない限り、1 つの HTTP 接続を使用して、一度に 5,000 通のバッチで、メールアドレス、電話番号、またはハッシュを連続的にマッピングする必要があります。言い換えれば、複数の並列接続を作成することなく、マッピングを行うことです。

#### ユーザーのオプトアウトはどのように処理すればよいですか？

<!-- FAQ_24 ADP -->

ユーザーが[Transparency and Control Portal](https://www.transparentadvertising.org/)を通じて UID2 ベースのターゲティング広告をオプトアウトすると、オプトアウト信号が DSP とパブリッシャーに送信され、入札時にオプトアウトが処理されます。広告主やデータプロバイダーとして、このシナリオで UID2 オプトアウトを確認する必要はありません。

たとえば、そのユーザーに対して UID2 を生成しないことを選択することもできます。

## FAQs for Demand-Side Platforms (DSPs)

ここでは、DSP によくある質問を紹介します。

- [UID2 に適用する復号鍵はどのように決定すればよいですか？](#uid2-%E3%81%AB%E9%81%A9%E7%94%A8%E3%81%99%E3%82%8B%E5%BE%A9%E5%8F%B7%E5%8C%96%E9%8D%B5%E3%81%AF%E3%81%A9%E3%81%AE%E3%82%88%E3%81%86%E3%81%AB%E6%B1%BA%E5%AE%9A%E3%81%99%E3%82%8C%E3%81%B0%E3%82%88%E3%81%84%E3%81%A7%E3%81%99%E3%81%8B)
- [復号鍵はどこで手に入りますか？](#%E5%BE%A9%E5%8F%B7%E3%82%AD%E3%83%BC%E3%81%AF%E3%81%A9%E3%81%93%E3%81%A7%E6%89%8B%E3%81%AB%E5%85%A5%E3%82%8A%E3%81%BE%E3%81%99%E3%81%8B)
- [ソルトバケットがローテーションしたかどうかを知るにはどうしたらよいですか？](#%E3%82%BD%E3%83%AB%E3%83%88%E3%83%90%E3%82%B1%E3%83%83%E3%83%88%E3%81%8C%E3%83%AD%E3%83%BC%E3%83%86%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3%E3%81%97%E3%81%9F%E3%81%8B%E3%81%A9%E3%81%86%E3%81%8B%E3%82%92%E7%9F%A5%E3%82%8B%E3%81%AB%E3%81%AF%E3%81%A9%E3%81%86%E3%81%97%E3%81%9F%E3%82%89%E3%82%88%E3%81%84%E3%81%A7%E3%81%99%E3%81%8B)
- [DSP はレイテンシーを気にする必要があるのでしょうか？](#dsp-%E3%81%AF%E3%83%AC%E3%82%A4%E3%83%86%E3%83%B3%E3%82%B7%E3%83%BC%E3%82%92%E6%B0%97%E3%81%AB%E3%81%99%E3%82%8B%E5%BF%85%E8%A6%81%E3%81%8C%E3%81%82%E3%82%8B%E3%81%AE%E3%81%A7%E3%81%97%E3%82%87%E3%81%86%E3%81%8B)
- [UID2 で DSP がフリークエンシーキャッピングを行には、どのようにすればよいですか？](#uid2-%E3%81%A7-dsp-%E3%81%8C%E3%83%95%E3%83%AA%E3%83%BC%E3%82%AF%E3%82%A8%E3%83%B3%E3%82%B7%E3%83%BC%E3%82%AD%E3%83%A3%E3%83%83%E3%83%94%E3%83%B3%E3%82%B0%E3%82%92%E8%A1%8C%E3%81%86%E3%81%AB%E3%81%AF%E3%81%A9%E3%81%AE%E3%82%88%E3%81%86%E3%81%AB%E3%81%99%E3%82%8C%E3%81%B0%E3%82%88%E3%81%84%E3%81%A7%E3%81%99%E3%81%8B)
- [ユーザーのオプトアウトのトラフィックはすべて DSP に送信されるのでしょうか？](#%E3%83%A6%E3%83%BC%E3%82%B6%E3%83%BC%E3%81%AE%E3%82%AA%E3%83%97%E3%83%88%E3%82%A2%E3%82%A6%E3%83%88%E3%81%AE%E3%83%88%E3%83%A9%E3%83%95%E3%82%A3%E3%83%83%E3%82%AF%E3%81%AF%E3%81%99%E3%81%B9%E3%81%A6-dsp-%E3%81%AB%E9%80%81%E4%BF%A1%E3%81%95%E3%82%8C%E3%82%8B%E3%81%AE%E3%81%A7%E3%81%97%E3%82%87%E3%81%86%E3%81%8B)
- [DSP は、既に記憶している UID2 に対してのみオプトアウト信号を処理することを想定しているのでしょうか？](#dsp-%E3%81%AF%E6%97%A2%E3%81%AB%E8%A8%98%E6%86%B6%E3%81%97%E3%81%A6%E3%81%84%E3%82%8B-uid2-%E3%81%AB%E5%AF%BE%E3%81%97%E3%81%A6%E3%81%AE%E3%81%BF%E3%82%AA%E3%83%97%E3%83%88%E3%82%A2%E3%82%A6%E3%83%88%E4%BF%A1%E5%8F%B7%E3%82%92%E5%87%A6%E7%90%86%E3%81%99%E3%82%8B%E3%81%93%E3%81%A8%E3%82%92%E6%83%B3%E5%AE%9A%E3%81%97%E3%81%A6%E3%81%84%E3%82%8B%E3%81%AE%E3%81%A7%E3%81%97%E3%82%87%E3%81%86%E3%81%8B)
- [オプトアウトリストはいつまで保存しておくべきですか？](#%E3%82%AA%E3%83%97%E3%83%88%E3%82%A2%E3%82%A6%E3%83%88%E3%83%AA%E3%82%B9%E3%83%88%E3%81%AF%E3%81%84%E3%81%A4%E3%81%BE%E3%81%A7%E4%BF%9D%E5%AD%98%E3%81%97%E3%81%A6%E3%81%8A%E3%81%8F%E3%81%B9%E3%81%8D%E3%81%A7%E3%81%99%E3%81%8B)
- [オプトアウトしたユーザーの UID は、暗号化された形でオプトアウトエンドポイントに送信されますか？](#%E3%82%AA%E3%83%97%E3%83%88%E3%82%A2%E3%82%A6%E3%83%88%E3%81%97%E3%81%9F%E3%83%A6%E3%83%BC%E3%82%B6%E3%83%BC%E3%81%AE-uid-%E3%81%AF%E6%9A%97%E5%8F%B7%E5%8C%96%E3%81%95%E3%82%8C%E3%81%9F%E5%BD%A2%E3%81%A7%E3%82%AA%E3%83%97%E3%83%88%E3%82%A2%E3%82%A6%E3%83%88%E3%82%A8%E3%83%B3%E3%83%89%E3%83%9D%E3%82%A4%E3%83%B3%E3%83%88%E3%81%AB%E9%80%81%E4%BF%A1%E3%81%95%E3%82%8C%E3%81%BE%E3%81%99%E3%81%8B)
- [オプトアウトはどのようなリクエストタイプを使用するのですか？](#%E3%82%AA%E3%83%97%E3%83%88%E3%82%A2%E3%82%A6%E3%83%88%E3%81%AF%E3%81%A9%E3%81%AE%E3%82%88%E3%81%86%E3%81%AA%E3%83%AA%E3%82%AF%E3%82%A8%E3%82%B9%E3%83%88%E3%82%BF%E3%82%A4%E3%83%97%E3%82%92%E4%BD%BF%E7%94%A8%E3%81%99%E3%82%8B%E3%81%AE%E3%81%A7%E3%81%99%E3%81%8B)
- [オプトアウトに対応するための要件はどの程度厳しいのでしょうか？](#%E3%82%AA%E3%83%97%E3%83%88%E3%82%A2%E3%82%A6%E3%83%88%E3%81%AB%E5%AF%BE%E5%BF%9C%E3%81%99%E3%82%8B%E3%81%9F%E3%82%81%E3%81%AE%E8%A6%81%E4%BB%B6%E3%81%AF%E3%81%A9%E3%81%AE%E7%A8%8B%E5%BA%A6%E5%8E%B3%E3%81%97%E3%81%84%E3%81%AE%E3%81%A7%E3%81%97%E3%82%87%E3%81%86%E3%81%8B)
- [メモリーに存在する復号鍵は何個までですか？](#%E3%83%A1%E3%83%A2%E3%83%AA%E3%83%BC%E3%81%AB%E5%AD%98%E5%9C%A8%E3%81%99%E3%82%8B%E5%BE%A9%E5%8F%B7%E9%8D%B5%E3%81%AF%E4%BD%95%E5%80%8B%E3%81%BE%E3%81%A7%E3%81%A7%E3%81%99%E3%81%8B)
- [SDK のエラーは、DSP の入札対応にどのような影響を与えるのでしょうか？](#sdk-%E3%81%AE%E3%82%A8%E3%83%A9%E3%83%BC%E3%81%AFdsp-%E3%81%AE%E5%85%A5%E6%9C%AD%E5%AF%BE%E5%BF%9C%E3%81%AB%E3%81%A9%E3%81%AE%E3%82%88%E3%81%86%E3%81%AA%E5%BD%B1%E9%9F%BF%E3%82%92%E4%B8%8E%E3%81%88%E3%82%8B%E3%81%AE%E3%81%A7%E3%81%97%E3%82%87%E3%81%86%E3%81%8B)

#### UID2 に適用する復号鍵はどのように決定すればよいですか？

<!-- FAQ_25 DSP -->

各 Server-Side SDK（[SDKs](../sdks/summary-sdks.md)を参照）は、復号鍵を自動的に更新します。UID2 Token と共に提供されるメタデータは、使用する復号鍵の ID を示します。

#### 復号鍵はどこで手に入りますか？

<!-- FAQ_26 DSP -->

Server-Side  SDK のいずれか（[SDKs](../sdks/summary-sdks.md)を参照）を使用して UID2 Service と通信し、最新の鍵を取得することができます。鍵を確実に最新に保つため、例えば1時間に1回など、定期的に鍵を取得することを推奨します。

#### ソルトバケットがローテーションしたかどうかを知るにはどうしたらよいですか？

<!-- FAQ_27 DSP -->

DSP は、UID2 ソルトバケットがいつローテーションしたかを知ることができません。これは、ユーザーが Cookie をクリアしても DSP が気づかないのと同じです。ソルトバケットのローテーションは、DSP に大きな影響を与えません。

#### DSP はレイテンシーを気にする必要があるのでしょうか？

<!-- FAQ_28 DSP -->

UID2 Service は、入札プロセスに遅延を生じさせることはありません。発生した遅延は、UID2 Service ではなく、ネットワークに起因すると考えられます

#### UID2 で DSP がフリークエンシーキャッピングを行うには、どのようにすればよいですか？

<!-- FAQ_29 DSP -->

UID2 は、クッキーと同じように古くなる可能性があります。したがって、DSP は、クッキーまたは Device ID ベースのフリークエンシーキャッピングに現在使用されているものと同じインフラを UID2 に適応させることができます。詳細は、[ソルトバケットのローテーションにより、UID2 を更新するタイミングを知るにはどうすればよいですか？](#%E3%82%BD%E3%83%AB%E3%83%88%E3%83%90%E3%82%B1%E3%83%83%E3%83%88%E3%81%AE%E3%83%AD%E3%83%BC%E3%83%86%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3%E3%81%AB%E3%82%88%E3%82%8Auid2-%E3%82%92%E6%9B%B4%E6%96%B0%E3%81%99%E3%82%8B%E3%82%BF%E3%82%A4%E3%83%9F%E3%83%B3%E3%82%B0%E3%82%92%E7%9F%A5%E3%82%8B%E3%81%AB%E3%81%AF%E3%81%A9%E3%81%86%E3%81%99%E3%82%8C%E3%81%B0%E3%82%88%E3%81%84%E3%81%A7%E3%81%99%E3%81%8B)を参照してください。

#### ユーザーのオプトアウトのトラフィックはすべて DSP に送信されるのでしょうか？

<!-- FAQ_30 DSP -->

はい、UID2 [Transparency and Control Portal](https://transparentadvertising.org/)からのすべてのオプトアウトは、オプトアウト エンドポイントに到達します。DSP は、ユーザーの[オプトアウトを受け入れる](../guides/dsp-guide.md#honor-user-opt-outs)ように構成する必要があります。

#### DSP は、既に記憶している UID2 に対してのみオプトアウト信号を処理することを想定しているのでしょうか？

<!-- FAQ_31 DSP -->

場合によっては、DSP は、オプトアウト・タイムスタンプ以前に生成された、新たに保管された UID2 に対する UID2 Token を受け取ることがあります。DSP はこのようなトークンに入札することはできません。したがって、対応する UID2 が現在 DSP によって保存されているかどうかにかかわらず、すべてのオプトアウト信号を保存することが推奨されます。詳細は、[Bidding Opt-Out Logic](../guides/dsp-guide.md#bidding-opt-out-logic)の図を参照してください。

#### オプトアウトリストはいつまで保存しておくべきですか？

<!-- FAQ_32 DSP -->

少なくとも 30 日間です。

#### オプトアウトしたユーザーの UID は、暗号化された形でオプトアウトエンドポイントに送信されますか？

<!-- FAQ_33 DSP -->

暗号化されていない（raw）UID2 として送信されます。

#### オプトアウトはどのようなリクエストタイプを使用するのですか？

<!-- FAQ_34 DSP -->

一般的には GET リクエストですが、DSP によって異なるタイプを使用することがあります。

#### オプトアウトに対応するための要件はどの程度厳しいのでしょうか？

<!-- FAQ_35 DSP -->

オプトアウトは常に受け入れなければなりません。オプトアウトのリクエストがシステムに伝わるまでに時間がかかることがありますが、その間に一部の入札がオプトアウトを受け入れないことが予想されます。

#### メモリーに存在する復号鍵は何個までですか？

<!-- FAQ_36 DSP -->

ある時点で数千の復号鍵が存在する可能性があります。

#### SDK のエラーは、DSP の入札対応にどのような影響を与えるのでしょうか？

<!-- FAQ_37 DSP-client-v1 -->

エラーが発生した場合、SDK は UID2 Token を UID2 に復号化しません。