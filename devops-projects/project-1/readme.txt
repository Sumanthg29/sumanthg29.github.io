Live AWS Project using SHELL SCRIPTING for DevOps



#!/bin/bash

echo "==================================================="


# Author: SumanthG
# Date: 29-04-2024

#

# this script outputs the health

#

# version: v1

set -x #debug mod

echo "It shows the partition details of my server"
df -h

echo "It shows the memory details of my server"
free

free -g

free -k

echo "It shows the Hardware details of my server"
dmidecode
