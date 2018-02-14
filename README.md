#!/bin/sh


echo testing > /dev/null

pwd

ls -l

# Modify access

chmod 775 week3.sh

ls -l

# vew device files

ls /dev

#view attached devie based on their actual hardware atrributes

ls /sys/devices

#create a device files

mknod /dev/sda1 b 8 2

ls /dev

