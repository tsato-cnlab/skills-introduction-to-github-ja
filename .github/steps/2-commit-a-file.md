## ステップ 2: ファイルをコミットする

_ブランチを作成できました！ :tada:_

ブランチを作成すると、`main` ブランチを変更せずにプロジェクトを編集できます。ブランチができたので、次はファイルを作成して最初のコミットをしてみましょう。

**コミットとは？**: _[コミット](https://docs.github.com/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits)_ は、プロジェクト内のファイルやフォルダーへの変更のまとまりです。コミットはブランチの中に存在します。詳しくは「[コミットについて](https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits)」を参照してください。

### :keyboard: アクティビティ: 最初のコミット

次の手順では、GitHub 上で変更をコミットする流れを学びます。コミットは、ファイルの追加・削除・名前変更や、ファイル内容の変更など、プロジェクトへの変更を記録します。この演習では、新しいブランチに新しいファイルを追加する変更をコミットします。

> [!NOTE]
> `.md` は Markdown ファイルを作るための拡張子です。Markdown について詳しく知りたい場合は、Docs の「[基本的な書き方と書式の構文](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)」を読むか、「[Markdown でコミュニケーションする](https://github.com/skills/communicate-using-markdown)」Skills 演習を受講してください。

1. リポジトリのヘッダーメニューにある **< > Code** タブで、新しいブランチ `my-first-branch` を表示していることを確認します。

2. **Add file** ドロップダウンを選択し、**Create new file** をクリックします。

   <img width="300" alt="新しいファイル作成オプションのスクリーンショット" src="https://raw.githubusercontent.com/tsato-cnlab/introduction-to-github/main/.github/images/create-new-file-option.png">

3. **Name your file...** フィールドに `PROFILE.md` と入力します。

4. **Enter file contents here** のエリアに、次の内容をコピーします。

   ```
   Welcome to my GitHub profile!
   ```

   ![profile.md ファイルを追加するスクリーンショット](https://raw.githubusercontent.com/tsato-cnlab/introduction-to-github/main/.github/images/add-profile-file.png)

5. 内容入力欄の右上にある **Commit changes...** をクリックします。ダイアログが表示されます。

6. GitHub はコミットメッセージを提案してくれますが、練習のため自分で設定しましょう。**Commit message** フィールドに `Add PROFILE.md` と入力します。

   - **コミットメッセージ** と任意の **extended description** は、変更内容をわかりやすくするのに役立ちます。複数のファイルを含むコミットでは特に便利です。

   <img width="400" alt="コミットメッセージ付きで新しいファイルを追加するスクリーンショット" src="https://raw.githubusercontent.com/tsato-cnlab/introduction-to-github/main/.github/images/commit-message-dialog.png">

7. このレッスンでは他のフィールドはいったん無視し、**Commit changes** をクリックします。

8. ファイルを変更したので、Mona があなたの作業を確認しているはずです。少し待って、コメント欄を見ていてください。進捗情報と次のレッスンが Mona から届きます。

<details>
<summary>うまくいきませんか？</summary><br/>

フィードバックが届かない場合は、次を確認してください。
- `my-first-branch` ブランチを表示していることを確認してください。
- `PROFILE.md` ファイルが作成され、ルートフォルダーにあることを確認してください。

</details>
