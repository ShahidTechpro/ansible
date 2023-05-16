#!/bin/bash
ansible all -m yum_repository -a \
'name=BaseOS description="RHEL8" \
baseurl=file:/media/BaseOS \
gpgcheck=0 enabled=1 file=adhoc_repo' \

ansible all -m yum_repository -a \
'name=AppStream \ 
description="RHEL8" 
baseurl=file:/media/AppStream gpgcheck=0 \
enabled=1 \
file=adhoc_repo'
