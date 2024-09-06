# ベースとなるコンテナ(ubuntu)のイメージ取得
FROM ubuntu:20.04

RUN apt-get update

# 必要なツールのインストール
# C/C++test
ADD parasoft_cpptest_standard-2023.2.1-linux.x86_64.tar.gz /opt

# build tools
RUN apt-get install -y build-essential

# その他便利なツール
RUN apt-get install -y \
                    vim \
                    bzip2 \
                    git

