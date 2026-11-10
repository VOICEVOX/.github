# Security Policy

脆弱性が見つかったリポジトリの非公開報告機能から報告してください。

リポジトリの「Security and quality」で「Report a vulnerability」を選ぶと、報告フォームが開きます。詳しくは[報告手順](https://docs.github.com/ja/code-security/how-tos/report-and-fix-vulnerabilities/report-privately)を参照してください。

コマンドラインからは、`gh api`で`POST /repos/VOICEVOX/{repo}/security-advisories/reports`を呼び出して報告できます。`{repo}`には対象のリポジトリ名を指定してください。詳しくは[APIの仕様](https://docs.github.com/en/rest/security-advisories/repository-advisories#privately-report-a-security-vulnerability)を参照してください。
