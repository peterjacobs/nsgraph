# nsgraph
Netscaler configuration file parser that shows load balancers in graph-like diagrams


dependencies for Debian:
- sudo apt-get install python-pip  // for convenience
- sudo apt-get install graphviz
- sudo apt-get install graphviz-dev
- sudo apt-get install python-pygraphviz

install procedure for Redhat 7:
- yum install python36-devel graphviz-devel 

install python dependencies and nsgraph
- git clone https://github.com/peterjacobs/nsgraph.git nsgraph
- cd nsgraph
- python3.6 -m venv .
- bin/pip install --upgrade pip
- bin/pip install pygraphviz

run nsgraph
- bin/python3 nsgraph.py -u -c netscalerconfigfile

