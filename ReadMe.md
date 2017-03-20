# このソフトウェアについて

GitHubリポジトリ作成スクリプトをリファクタリングした。

以下の改良版。

* [GitHub.Upload.ByPython.201703090838](https://github.com/ytyaru/GitHub.Upload.ByPython.201703090838)
* [GitHub.Upload.ByPython.DeleteRepo.201703091329](https://github.com/ytyaru/GitHub.Upload.ByPython.DeleteRepo.201703091329)
* [GitHub.Upload.ByPython.EditRepo.201703101422](https://github.com/ytyaru/GitHub.Upload.ByPython.EditRepo.201703101422)

# 開発環境

* Linux Mint 17.3 MATE 32bit
* [Python 3.4.3](https://www.python.org/downloads/release/python-343/)
    * [requests](http://requests-docs-ja.readthedocs.io/en/latest/)
    * [dataset](https://github.com/pudo/dataset)

## WebService

* [GitHub](https://github.com/)
    * [アカウント](https://github.com/join?source=header-home)
    * [AccessToken](https://github.com/settings/tokens)
    * [Two-Factor認証](https://github.com/settings/two_factor_authentication/intro)
    * [API v3](https://developer.github.com/v3/)

# 準備

[前回](https://github.com/ytyaru/GitHub.Upload.ByPython.201703090838#%E6%BA%96%E5%82%99)の手順に従い、リポジトリ作成と`call.sh`配置までしておくこと。

# 実行

[前回](https://github.com/ytyaru/GitHub.Upload.ByPython.201703090838#%E3%83%AA%E3%83%9D%E3%82%B8%E3%83%88%E3%83%AA%E8%A8%AD%E5%AE%9A)の手順に従い、`call.sh`の値を指定すること。

1. ターミナルを起動する
1. 以下のコマンドを実行する（今回のスクリプトを実行する）

```sh
bash call.sh
```

# 結果

CUI対話にある通りとなる。

* 作成: [GitHub.Upload.ByPython.201703090838](https://github.com/ytyaru/GitHub.Upload.ByPython.201703090838#2-cui%E3%81%A7%E5%AF%BE%E8%A9%B1%E3%81%99%E3%82%8B)
* 削除: [GitHub.Upload.ByPython.DeleteRepo.201703091329](https://github.com/ytyaru/GitHub.Upload.ByPython.DeleteRepo.201703091329#%E5%AE%9F%E8%A1%8C)
* 編集: [GitHub.Upload.ByPython.EditRepo.201703101422](https://github.com/ytyaru/GitHub.Upload.ByPython.EditRepo.201703101422#%E5%AE%9F%E8%A1%8C)

# ライセンス #

このソフトウェアはCC0ライセンスである。

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")](http://creativecommons.org/publicdomain/zero/1.0/deed.ja)

Library|License|Copyright
-------|-------|---------
[requests](http://requests-docs-ja.readthedocs.io/en/latest/)|[Apache-2.0](https://opensource.org/licenses/Apache-2.0)|[Copyright 2012 Kenneth Reitz](http://requests-docs-ja.readthedocs.io/en/latest/user/intro/#requests)
[dataset](https://dataset.readthedocs.io/en/latest/)|[MIT](https://opensource.org/licenses/MIT)|[Copyright (c) 2013, Open Knowledge Foundation, Friedrich Lindenberg, Gregor Aisch](https://github.com/pudo/dataset/blob/master/LICENSE.txt)
[bs4](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)|[MIT](https://opensource.org/licenses/MIT)|[Copyright © 1996-2011 Leonard Richardson](https://pypi.python.org/pypi/beautifulsoup4),[参考](http://tdoc.info/beautifulsoup/)
[pytz](https://github.com/newvem/pytz)|[MIT](https://opensource.org/licenses/MIT)|[Copyright (c) 2003-2005 Stuart Bishop <stuart@stuartbishop.net>](https://github.com/newvem/pytz/blob/master/LICENSE.txt)
