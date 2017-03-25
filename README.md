# nds51
発表会資料



## anaconda
[公式サイト](https://www.continuum.io/downloads)
[AnacondaとDockerについて](https://www.continuum.io/blog/developer-blog/anaconda-and-docker-better-together-reproducible-data-science)

### 触れるJupyter Notebook
[デモインスタンス](http://52.199.199.242:8888/?token=82bd6370fe3dcc8e72f420c6d697e38b933c261fdbf5ea51)
```
# AWSのインスタンスで売ったコマンドはこれだけ！
yum install -y docker && /etc/init.d/docker start
docker pull continuumio/anaconda3
docker run -i -t -p 8888:8888 continuumio/anaconda3 /bin/bash -c "/opt/conda/bin/conda install jupyter -y --quiet && mkdir /opt/notebooks && /opt/conda/bin/jupyter notebook --notebook-dir=/opt/notebooks --ip='*' --port=8888 --no-browser"
```

## pandas
[pandas cheatsheet](https://github.com/pandas-dev/pandas/blob/master/doc/cheatsheet/Pandas_Cheat_Sheet.pdf)

## matplotlib
[matplotlib gallery](http://matplotlib.org/gallery.html)

## Scikit-learn
[本家チートシート](http://scikit-learn.org/stable/tutorial/machine_learning_map/)

[日本語チートシート](https://raw.githubusercontent.com/sakapun/nds51/master/scikit-learn%E6%97%A5%E6%9C%AC%E8%AA%9E%E5%8C%96%E3%83%81%E3%83%BC%E3%83%88%E3%82%B7%E3%83%BC%E3%83%88.jpg)


## 分類と回帰
[分類と回帰についてわかりやすい説明｜learning.ikeay.net：機械学習ってなんだろう](http://learning.ikeay.net/entry/2016/05/02/200503)