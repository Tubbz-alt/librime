# slackbuild for librime

RIME: Rime Input Method Engine

rimes with your keystrokes.

## dependencies

* [glog](https://slackbuilds.org/repository/14.2/libraries/glog/)
* [leveldb](https://slackbuilds.org/repository/14.2/development/leveldb/)
* [yaml-cpp](https://slackbuilds.org/repository/14.2/libraries/yaml-cpp/)
* [opencc](https://slackbuilds.org/repository/14.2/misc/opencc/)
* [kyotocabinet](https://slackbuilds.org/repository/14.2/system/kyotocabinet/)

**NOTE:**

You need download leveldb source code from [github](https://github.com/google/leveldb/archive/v1.9.tar.gz)

Just like that

```
wget https://github.com/google/leveldb/archive/v1.9.tar.gz
tar xf v1.9.tar.gz
mv leveldb leveldb-1.9.0
tar cf leveldb-1.9.0.tar.gz leveldb-1.9.0
wget https://slackbuilds.org/slackbuilds/14.2/development/leveldb.tar.gz
tar xf leveldb.tar.gz
cd leveldb
ln -s ../leveldb-1.9.0.tar.gz .
sudo sh leveldb.SlackBuild
```

## usage

```
git clone https://github.com/slackwarecn-slackbuilds/librime-slackbuild.git
cd librime-slackbuild
source librime-slackbuild.info
wget $DOWNLOAD
./librime-slackbuild
```
