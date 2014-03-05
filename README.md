# vagrant-couchbase
This Vagrant project will set you up with 4 Couchbase nodes on Ubuntu Precise64 VMs.  They have the IP addresses 192.168.56.10[1-4].

### running the project:

    vagrant up

Then you can load up the web UI for your cluster by going to:

	http://192.168.56.101:8091

Note that you will have to add each node to your cluster explicity though the couchbase web UI.