# nds51
発表会資料



### anaconda
[公式サイト](https://www.continuum.io/downloads)
[AnacondaとDockerについて](https://www.continuum.io/blog/developer-blog/anaconda-and-docker-better-together-reproducible-data-science)

## 触れるJupyter Notebook
[デモインスタンス](http://52.199.199.242:8888/?token=773d8b6b68e8594ac432e0425178a50044b9c422378726af)
```
yum install -y docker && /etc/init.d/docker start
docker pull continuumio/anaconda3
docker run -i -t -p 8888:8888 continuumio/anaconda3 /bin/bash -c "/opt/conda/bin/conda install jupyter -y --quiet && mkdir /opt/notebooks && /opt/conda/bin/jupyter notebook --notebook-dir=/opt/notebooks --ip='*' --port=8888 --no-browser"
```

### pandas
[pandas cheatsheet](https://github.com/pandas-dev/pandas/blob/master/doc/cheatsheet/Pandas_Cheat_Sheet.pdf)

### matplotlib
[matplotlib gallery](http://matplotlib.org/gallery.html)

### 分類と回帰
[分類と回帰についてわかりやすい説明｜learning.ikeay.net：機械学習ってなんだろう](http://learning.ikeay.net/entry/2016/05/02/200503)