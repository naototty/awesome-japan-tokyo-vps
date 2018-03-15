# awesome vps in Japan region (tokyo region)


* 2017/08/24調べ

|クラウド|価格/月|DISK|性能など|
|:--------|:------|:-------|:---------:|
|WebARENA|360円|20gb|512,1コア|
|IDCF|500円|15gb|1gb,1cpu|
|DigitalOcean|\$0.007/h,\$5/mo|20gb|512,1cpu|


* 1GB memory

|cloud                                |price/month(vm)  |boot           |DISK        |spec                                  |UnixBench  |API        |region               |UnixBench   |API  |docker-machine  |vagrant  |terraform  |
|:--------                            |:------          |:----          |:-------    |:---------:                           |:---------:|:---------:|:--:                 |:--:        |     |                |         |           |
|AWS Lightsail (Linux)                |\$5/month        |block storage  |SSD 20GB    |0.5GBmem,1core, 1TB transfer/???Mbps  |           |sdk,api    |[tokyo 3 location](https://aws.amazon.com/jp/lightsail/)  |237.6円|423.8|
|AWS Lightsail (Linux)                |\$10/month       |block storage  |SSD 30GB    |1GBmem,1core, 2TB transfer/???Mbps    |           |           |[tokyo 3 location](https://aws.amazon.com/jp/lightsail/)  |237.6円|423.8|
|AWS Lightsail (Linux)                |\$20/month       |block storage  |SSD 40GB    |2GBmem,1core, 3TB transfer/???Mbps    |           |           |[tokyo 3 location](https://aws.amazon.com/jp/lightsail/)  |237.6円|423.8|
|AWS Lightsail (Linux)                |\$40/month       |block storage  |SSD 60GB    |4GBmem,2core, 4TB transfer/???Mbps    |           |           |[tokyo 3 location](https://aws.amazon.com/jp/lightsail/)  |237.6円|423.8|
|AWS Lightsail (Linux)                |\$40/month       |block storage  |SSD 60GB    |4GBmem,2core, 4TB transfer/???Mbps    |           |           |[tokyo 3 location](https://aws.amazon.com/jp/lightsail/)  |237.6円|423.8|
                                                                                                                                                    
|AWS Lightsail (Windows)              |\$10/month       |block storage  |SSD 30GB    |0.5GBmem,1core, 1TB transfer/???Mbps  |           |           |[tokyo 3 location](https://aws.amazon.com/jp/lightsail/)  |237.6円|423.8|
|AWS Lightsail (Windows)              |\$17/month       |block storage  |SSD 40GB    |1GBmem,1core, 2TB transfer/???Mbps    |           |           |[tokyo 3 location](https://aws.amazon.com/jp/lightsail/)  |237.6円|423.8|
|AWS Lightsail (Windows)              |\$30/month       |block storage  |SSD 50GB    |2GBmem,2core, 3TB transfer/???Mbps    |           |           |[tokyo 3 location](https://aws.amazon.com/jp/lightsail/)  |237.6円|423.8|
|AWS Lightsail (Windows)              |\$55/month       |block storage  |SSD 60GB    |4GBmem,2core, 4TB transfer/???Mbps    |           |           |[tokyo 3 location](https://aws.amazon.com/jp/lightsail/)  |237.6円|423.8|

|IDCF Light-S1                        |\$1.93|(HDD1GB)  |1GB,1コア,3240GB/10Mbps<br>0.8GHz|[福島](http://www.idcf.jp/datacenter/shirakawa/)|237.6円|423.8|
|IDCF Light-S1|\$4.54|(HDD15GB)|1GB,1コア,3240GB/10Mbps<br>0.8GHz|[福島](http://www.idcf.jp/datacenter/shirakawa/)|[url](https://www.idcf.jp/cloud/simulation.php?cl=cl_price)|同上|
|OVH VPS SSD|\$3.49|込(SSD10GB)|2GB,2.4GHz,転送10TB/月,KVM|[カナダ](http://www.ovh.com/us/vps/faq-help.xml)|[url](http://www.ovh.com/us/vps/vps-classic.xml)|
|AWS t2.nano|\$5.475|$0.96(SSD8GB)|0.5GB|東京|[url]((https://aws.amazon.com/jp/ec2/pricing/))|
|AWS t2.micro|\$14.64|\$0.96(SSD8GB)|1GB|東京|[url]((https://calculator.s3.amazonaws.com/index.html?lng=ja_JP))|1905.0|
|GCE f1-micro|\$4.60|\$0.40(HDD10GB)|600MB|台湾|[url](https://cloud.google.com/products/calculator/)|
|GCE g1-micro|\$15.33|\$0.40(HDD10GB)|1.7GB|台湾|-|
|GCE n1-standard-1|\$28.11|\$0.40(HDD10GB)|3.75GB|台湾|-|
|Azure A0|\$11.11|込(20GB)|0.75GB|東京?|[url](http://azure.microsoft.com/ja-jp/pricing/details/virtual-machines/)|
|SoftLayer|\$27.60|込(HDD25GB)|1GB|東京?|[url](http://www.softlayer.com/jp/virtual-servers#configure)|
|exoscale tiny|\$32.08|込(10GB)|1GB|スイス|[url](https://www.exoscale.ch/pricing/)|
|Rackspace General1-1|\$27.36|込(SSD20GB)|1GB|?|[url](http://www.rackspace.com/cloud/public-pricing)|
|DigitalOcean 512|\$5|込(SSD20GB)|512M,転送1TB/月,KVM|ｼﾝｶﾞﾎﾟｰﾙ|[url](https://www.digitalocean.com/pricing/)|
|DigitalOcean 1G|\$10|込(SSD30GB)|1GB,転送2TB/月,KVM|ｼﾝｶﾞﾎﾟｰﾙ|-|
|Vultr|\$4.99|込(SSD15GB)|768M,転送200GB/月,KVM|東京|[url](https://www.vultr.com/pricing/)|
|Linode 1G|\$10|込(SSD24GB)|1GB,転送2TB/月|?|[url](https://www.linode.com/pricing)|
|さくら512|685円|込(SSD20GB)|512M,1コア|東京|[url](http://vps.sakura.ad.jp/specification/)|
|さくら1G|972円|込(SSD30GB)|1GB,2コア|東京|-|
|さくら2G|1706円|込(SSD50GB)|2GB,3コア|東京|-|
|ConoHa512MB|630円|込(SSD20GB)|512MB,1コア|東京|[url](https://www.conoha.jp/pricing)|
|ConoHa1GB|765円|込(SSD50GB)|1GB,2コア|東京|[url](https://www.conoha.jp/pricing)|
|ConoHa2GB|1487円|込(SSD50GB)|2GB,3コア|東京|-|
|Scaleway|\$3.34|込(SSD50GB)|2GB,ARM4ｺｱ,転送無制限<br>RPi2より早い<br>docker対応|[パリ](http://www.iliad-datacenter.fr/datacenters)|[url](https://www.scaleway.com/pricing/)|354.0|


* other


## memo

* OVH VPS Clasic : \$2.99。レーテンシーは要確認。
* Vultr : PayPalでのチャージ対応
* カゴヤ : \$7.27, CPU3コアでHDD200GB,メモリ1GB
* DTI ServerMan@VPS : \$4.22, HDD50GB, 1GB と安いが、dockerは動かない。
* Digital Ocean : docker-machine対応。利用者多い

----

* [便利なUSドル(USD)の計算機](http://usd.keisanki.me/)
* [Low End Box - Cheap VPS Hosting Providers Listing & Reviews](http://lowendbox.com/)が低価格VPS特集サイトで良い。
* [レンタルサーバ比較.jp](http://レンタルサーバ比較.jp/vps/index.html#vps_ranking)
* [Linode, DigitalOcean and VULTR 比較](http://blog.due.io/2014/linode-digitalocean-and-vultr-comparison/)
* [PaaSの説明](https://gist.github.com/nota-ja/66ec5d391ba49e761468)によると、VPSはIaaSになるようですね。
* http://w3bin.com/hosting_infographic


