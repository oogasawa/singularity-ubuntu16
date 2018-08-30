# Ubuntu16 Singularity

Ubuntu Linux 16.04 (Xenial) のSingularityコンテナ


## 前提

- Singularityがインストールされていること。
    - [Singularityのインストール方法（Official Document)](https://www.sylabs.io/guides/2.6/user-guide/installation.html) 
    

## 使い方

    # コンテナのビルド
    git clone http://gitlab.ddbj.nig.ac.jp/oogasawa/ubuntu16-singularity
    sudo singularity build --sandbox your-container-name ubuntu16-singularity/ubuntu16.txt
    
    # コンテナ内での作業
    sudo singularity shell --write your-container-name
    
    
    