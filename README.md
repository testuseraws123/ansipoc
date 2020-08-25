# ansipoc
by using r6full.yml we can install below packages into target (ubuntu in this case) host servers
- javajdk8
- pip3
- python3.6
- h2o3.30.0.4
- steam1.0.2
- jupyterhub1.1
- driverlessai1.8
- teradata

to install the above packages we need to add some dependiencies
- future
- tabulate
- coloroma 0.3.8

by using tomcatinit.yml we can install tomcat9 on target host(ubuntu in this case)

finally in the main.yml we have included all the ymls into  single yml file.
by using this yml file we can execute all above tasks.
