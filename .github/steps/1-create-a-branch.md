## ステップ 1: ブランチを作成する

_「GitHub 入門」へようこそ！ :wave:_

**GitHub とは？**: GitHub は、バージョン管理に _[Git](https://docs.github.com/get-started/quickstart/github-glossary#git)_ を使う共同作業プラットフォームです。GitHub は、[オープンソース](https://docs.github.com/get-started/quickstart/github-glossary#open-source) ソフトウェアを共有したり、コントリビュートしたりする場として広く使われています。

:tv: [動画: GitHub とは？](https://www.youtube.com/watch?v=pBy1zgt0XPc)

**リポジトリとは？**: _[リポジトリ](https://docs.github.com/get-started/quickstart/github-glossary#repository)_ は、ファイルやフォルダーを含むプロジェクトです。リポジトリはファイルやフォルダーのバージョンを追跡します。詳しくは GitHub Docs の「[リポジトリについて](https://docs.github.com/en/repositories/creating-and-managing-repositories/about-repositories)」を参照してください。

**ブランチとは？**: _[ブランチ](https://docs.github.com/en/get-started/quickstart/github-glossary#branch)_ は、リポジトリの並行バージョンです。既定では、リポジトリには `main` という名前のブランチが 1 つあり、これが基準となるブランチです。追加のブランチを作成すると、リポジトリの `main` ブランチをコピーして、メインのプロジェクトに影響を与えずに安全に変更できます。多くの人は、プロジェクトの他の部分に影響を与えずに特定の機能を作業するためにブランチを使います。

ブランチを使うと、自分の作業を `main` ブランチから切り離せます。つまり、あなたがコントリビュートしている間も、全員の作業を安全に保てます。詳しくは「[ブランチについて](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches)」を参照してください。

**プロフィール README とは？**: _[プロフィール README](https://docs.github.com/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme)_ は、GitHub.com のコミュニティに向けて自分の情報を共有できる、GitHub プロフィール上の「自己紹介」セクションのようなものです。GitHub はプロフィール README をプロフィールページの上部に表示します。詳しくは「[プロフィール README の管理](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme)」を参照してください。

![プロフィール README の例を示すスクリーンショット](https://raw.githubusercontent.com/tsato-cnlab/introduction-to-github/main/.github/images/example-profile-readme.png)

### :keyboard: アクティビティ: 最初のブランチ

1. 新しいブラウザータブを開き、作成したばかりのリポジトリ（この演習のコピー）に移動します。このタブで手順を読みながら、2 つ目のタブで作業してください。

2. リポジトリのヘッダーメニューにある **< > Code** タブに移動します。

   ![Code タブを強調表示したスクリーンショット](https://raw.githubusercontent.com/tsato-cnlab/introduction-to-github/main/.github/images/code-tab-highlight.png)

3. **main** ブランチのドロップダウンをクリックします。

   <img width="300" alt="ブランチ選択を強調表示したスクリーンショット" src="https://raw.githubusercontent.com/tsato-cnlab/introduction-to-github/main/.github/images/branch-selection-dropdown.png">

4. **Find or create a branch...** のテキストボックスに `my-first-branch` と入力します。
   
   > **メモ:** 次のステップに進むため、この名前がチェックされます。 :wink:

5. **Create branch: `my-first-branch` from main** というテキストをクリックして、ブランチを作成します。

   <img width="300" alt="ブランチ作成プロンプトを強調表示したスクリーンショット" src="https://raw.githubusercontent.com/tsato-cnlab/introduction-to-github/main/.github/images/create-branch-prompt.png">

   - ブランチは、作成したばかりのブランチに自動で切り替わります。
   - **main** ブランチのドロップダウンメニューには、新しいブランチ名が表示されます。

6. ブランチが GitHub にプッシュされたので、Mona があなたの作業を確認しているはずです。少し待って、コメント欄を見ていてください。進捗情報と次のレッスンが Mona から届きます。

<details>
<summary>うまくいきませんか？</summary><br/>

フィードバックが届かない場合は、次を確認してください。
- ブランチ名が正確に `my-first-branch` になっていることを確認してください。接頭辞や接尾辞は付けないでください。

</details>
