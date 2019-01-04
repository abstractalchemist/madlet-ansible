Ansible Build for MADLET framework

Requires
- python >= 3.7
- pip == 9.0.3
- ansible-container
- ansible
- docker == 2.7.0
- docker

Installation Instructions
# Install conda
# conda create -n madlet
# pip install -U pip==9.0.3
# pip install docker==2.0.7 ansible-container[docker] ansible

Files
- dev - hosts file for local development
- production - hosts file for production deployment
- container.yml - service specification file for docker deployment
