
# embeddable python ライブラリインストールする方法

## 設定方法

### PowerShell

``` bash
cd python-3.9.0-embed-amd64
[System.Net.ServicePointManager]::SecurityProtocol = [System.Net.SecurityProtocolType]::Tls12;
wget "https://bootstrap.pypa.io/get-pip.py" -O "get-pip.py"
```

### コマンドプロンプト

``` bash
.\python.exe get-pip.py
# ライブラリインストール
.\python.exe -m pip install selenium python-redmine beautifulsoup4 schedule intelhex simplejson
```

# 以下参考
https://qiita.com/mm_sys/items/1fd3a50a930dac3db299
