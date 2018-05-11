#WebLogic 12.1.3 infra (JRF) with SOA, OSB Cluster

##Details
- CentOS 6.5 vagrant box
- Puppet 3.5.0
- Vagrant >= 1.41
- Oracle Virtualbox >= 4.3.6

Download & Add the all the Oracle binaries to /software

edit Vagrantfile and update the software share to your own local folder
- soadb.vm.synced_folder "/Users/asinha/software", "/software"
- soa2admin2.vm.synced_folder "/Users/asinha/software", "/software"

Vagrant boxes
- vagrant up soadb
- vagrant up soa2admin2
- vagrant up mft1admin

## Database
- soadb 10.10.10.5, 11.2.0.4 with Welcome01 as password

###operating users
- root vagrant
- vagrant vagrant
- oracle oracle

###software
- Oracle Database 12.1.0.2 SE Linux
- linuxamd64_12102_database_se2_1of2.zip
- linuxamd64_12102_database_se2_2of2.zip

## Middleware

### default soa osb domain with 1 node
- soa2admin2 10.10.10.21, WebLogic 12.1.3 with Infra ( JRF, ADF, SOA, OSB ) requires RCU
- oim1admin 10.10.10.71, WebLogic 12.1.3 with Infra ( MFT ) requires RCU

http://10.10.10.21:7001/em with weblogic1 as password

###operating users
- root vagrant
- vagrant vagrant
- oracle oracle

###software
- JDK 1.7u55 jdk-7u55-linux-x64.tar.gz
- JDK 7 JCE policy UnlimitedJCEPolicyJDK7.zip
- fmw_12.1.3.0.0_infrastructure.jar
- fmw_12.1.3.0.0_osb_Disk1_1of1.zip
- fmw_12.1.3.0.0_soa_Disk1_1of1.zip
- fmw_12.1.3.0.0_mft_Disk1_1of1.zip
- p20423408_121300_Generic.zip soa bundle patch

