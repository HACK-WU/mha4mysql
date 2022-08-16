# MHA -MYSQL服务高可用架构软件包

* **mha4mysql-manager-0.57-0.el7.noarch.rpm**
* **mha4mysql-node-0.57-0.el7.noarch.rpm**

# 适用系统

* **Centos 7.6**

  

# 依赖安装

```she
yum -y install epel-release.noarch		
yum -y install perl-DBD-MySQL \			
perl-Config-Tiny \
perl-Time-HiRes \
perl-Mail-Sender \
perl-Mail-Sendmail \
perl-MIME-Base32 \
perl-MIME-Charset \
perl-MIME-EncWords \
perl-Params-Classify \
perl-Params-Validate.x86_64 \
perl-Log-Dispatch \
perl-Parallel-ForkManager \
net-tools 
```

# 软件安装

```she
rpm -ivh mha4mysql-manager-0.57-0.el7.noarch.rpm
rpm -ivh mha4mysql-node-0.57-0.el7.noarch.rpm
```

