# net-speeder-new-hosted-new



这个虽然说不是我写的但是也同样好用以前有人托管过这个是我自用的没事闲的，那个还有以后我会改一些锐速什么之类的非常好用敬请期待

# 使用方法是
# wget https://codeload.github.com/weiwenxuanhosts/net-speeder-new-hosted-new/zip/master



# unzip master.zip解压

# CentOS 系统 64 位
# wget http://dl.fedoraproject.org/pub/epel/6/x86_64/epel-release-6-8.noarch.rpm
# rpm -ivh epel-release-6-8.noarch.rpm
# yum install libnet libpcap libnet-devel libpcap-devel
# CentOS 系统 32 位
# wget http://dl.fedoraproject.org/pub/epel/6/i386/epel-release-6-8.noarch.rpm
# rpm -ivh epel-release-6-8.noarch.rpm
# yum install libnet libpcap libnet-devel libpcap-devel


# debian/ubuntu系统


# apt-get install libnet1-dev
# apt-get install libpcap0.8-dev


# openvz

# cd net-speeder-master/
# sh build.sh -DCOOKED

# kvm

# cd net-speeder-master/
# sh build.sh


# 加速

# ./net_speeder venet0 "ip"
