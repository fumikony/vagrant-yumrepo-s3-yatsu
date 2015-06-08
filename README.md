# vagrant-yumrepo-s3-yatsu
VagrantでS3にyumrepo作るやつ

## TODO
- `vagrant provision`で`createrepo`とか`repoview`をする
- `vagrant push`でs3に送るようにする
  - 環境変数でs3のtokenとsecretをもらう(Vagrantfile)
- yumのconfファイル(/etc/yum.repos.d/hoge.conf)をいい感じに吐く

## 参考
- http://yuuki.hatenablog.com/entry/docker-package-repository
- http://dev.classmethod.jp/cloud/yum-repo-s3cf-redirect/
- http://lab.sonicmoov.com/development/private-yum-repository/
- http://blog.kenichikat.org/2013/02/s3websitehostingyum.html
- http://blog.suz-lab.com/2010/02/s3yum.html
