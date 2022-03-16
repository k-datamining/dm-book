# study-data-analysis

[Youtube の動画](https://www.youtube.com/channel/UCFy3VBvZBeE9bN0F2sxF8rg)で使用したコードを公開するためのリポジトリ

# セットアップ

## Python のインストール

[Python3.8.5](https://www.python.org/downloads/release/python-385/) で動作を確認しています。

## poetry のインストール

[Poetry: Dependency Management for Python](https://github.com/python-poetry/poetry#installation)に従ってインストールします。

```
curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/install-poetry.py | python -
```

この後で `export PATH=$HOME/.poetry/bin:$PATH` を `.bash_profile` 等に書き込み、パスを通します。
そして、コードの実行に必要な依存関係をインストールします。

```
poetry shell
poetry install
```

正しくインストールできているならば、[jupyter notebook](https://jupyter.org/) を起動できます。

```
jupyter notebook
```
