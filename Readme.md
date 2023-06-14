# DataExtension Maker in CloudPages

Salesforce Marketing CloudのData Extensionをエクセルから貼り付けで作成可能なツール
エクセスなどの定義書を貼り付けてサクッとDE作成できます。
HTMLは、CloudPagesとして実装する必要があります。

SSOを利用する場合は、インストールパッケージを作成の上、以下を設定。
※SSO不要の場合は、nologin=1

//Intalled Package Etc  ----------------------------------

var baseurl = "https://TSE.auth.marketingcloudapis.com/";

var redirecturl = "[REDIRECT URL]";

var tse = "[END POINT]"; /* End Point */

var cid = "[CLIENT ID]"; /* client ID */

var csecret = "[CLIENT SECRET]"; /* client secret */

var nologin = 0; // 1: ログイン不要

//----------------------------------------------------------

イメージ
![image](https://github.com/masaru-kato/CloudPages-DE-Maker/assets/43125997/5b7282f1-63bc-4260-895a-88800073fc74)
