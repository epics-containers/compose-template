# services-template-compose
A copier template for creating a new repository for deploying EPICS IOCs and other services in containers using docker-compose.

To make a new beamline (or other grouping of services) repository, use the following steps:
```bash
# these steps not requried if you have already installed copier
python -mvenv venv
source venv/bin/activate
pip install copier
# create a new repository
copier gh:copier-org/services-template-compose `my-new-repo-folder-name`
# answer the copier questions

```

To pull in the latest updates this template in an existing repository, use the following steps:
```bash
cd `my-existing-repo-folder-name`
copier update
```
