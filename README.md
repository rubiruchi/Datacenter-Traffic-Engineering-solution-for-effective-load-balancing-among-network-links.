# Datacenter-Traffic-Engineering-solution-for-effective-load-balancing-among-network-links.
Designed custom routing for network flows to minimize the collision problem between data center traffic using Mininet along with OpenVswitch.


leaf-spine
==============

* install_iperf3.sh --> install iperf3.1 from debian packages
* cleanup.py --> clean up after creating mininet topology
* gen_leaf_spine.py --> creates a leaf spine topology, with a host attached to each leaf host. Also, sets up ssh daemon on each host.
* gen_traffic.py --> Create concurrent flows based on traffic matrix using iperf3 and measure output
* traffic_matrix --> Example of a traffic matrix file. Format: src_leaf dst_leaf
