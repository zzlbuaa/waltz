[Vagrant Google]

#======================================================================
# Configurations in this section is used by Vagrantfile

# Waltz common GCE configuration (Please fill in all fields)
GoogleProjectId=mythic-crane-708
GoogleClientEmail=waltz-517@mythic-crane-708.iam.gserviceaccount.com
GoogleJsonKeyLocation=/home/travis/build/zzlbuaa/waltz/mythic-crane-708-cbabaaf6e125.json
GoogleNetwork=poc
GoogleSubnetwork=mythic-crane-internal-network

# GCE SSH configuration (Please fill in all fields)
WaltzSshUsername=zhengliangz
WaltzSshPrivateKeyPath=/Users/zhengliangz/.ssh/bb_new

# Waltz storage GCE configuration (Please fill in all fields)
WaltzStorageInstanceName=waltz-storage-zhengliangz
WaltzStorageInstanceMachineType=n1-standard-1
WaltzStorageInstanceZones=["us-west1-c", "us-central1-c", "us-east1-c", "us-central1-c"]
WaltzStorageImage=wp-waltz-server-b89-1586915968
WaltzStorageBootDiskSizeGb=30
WaltzStorageAdditionalDisks=[{"image_family": "waltz", "image_project_id": "mythic-crane-708", "disk_size": 100}]

# Waltz server GCE configuration (Please fill in all fields)
WaltzServerInstanceName=waltz-server-zhengliangz
WaltzServerInstanceMachineType=n1-standard-1
WaltzServerInstanceZone=us-central1-c
WaltzServerImage=wp-waltz-server-b89-1586915968
WaltzServerBootDiskSizeGb=30

# Waltz client GCE configuration (Please fill in all fields)
WaltzClientInstanceName=waltz-client-zhengliangz
WaltzClientInstanceMachineType=n1-standard-1
WaltzClientInstanceZone=us-central1-c
WaltzClientImage=wp-waltz-server-b89-1586915968
WaltzClientBootDiskSizeGb=30

#======================================================================

[Zookeeper]

#======================================================================
# Configurations in this section are shared by tests

ZkUrl=10.73.0.30:2181
ZkSessionTimeout=40000
ClusterRoot=/waltz-cluster-root
ClusterName=waltz-cluster
ClusterNumPartitions=4

#======================================================================

[Waltz Storage]

#======================================================================
# Configurations in this section are shared by tests

# WaltzStorage Service configuration
NumCpuCores=1
MemSize=1GB
DiskSize=25GB
AdditionalDisks={"/dev/sdb": "100GB"}
NumNodes=3
Port=7071
AdminPort=7073
JettyPort=7072
LibDir=/usr/local/waltz
DataDir=/usr/local/waltz/data
ConfigFileDir=/etc/waltz

#======================================================================

[Waltz Server]

#======================================================================
# Configurations in this section are shared by tests

# WaltzSever Service configuration
NumCpuCores=1
MemSize=3GB
DiskSize=15GB
NumNodes=2
Port=6060
JettyPort=6062
LibDir=/usr/local/waltz
ConfigFileDir=/etc/waltz
SslKeystoreLoc=/etc/waltz/keystore.jks
SslKeystorePwd=devops
SslTruststoreLoc=/etc/waltz/truststore.jks
SslTruststorePwd=devops

#======================================================================

[Waltz Client]

#======================================================================
# Configurations in this section are shared by tests

# WaltzClient configuration
NumCpuCores=1
MemSize=1GB
DiskSize=25GB
NumNodes=1
SslKeystoreLoc=/etc/waltz/keystore.jks
SslKeystorePwd=devops
SslTruststoreLoc=/etc/waltz/truststore.jks
SslTruststorePwd=devops
LibDir=/usr/local/waltz
ConfigFileDir=/etc/waltz

#======================================================================
