#!/bin/bash
# Returns the IP address of a running KVM guest VM
# Assumes a working KVM/libvirt environment
#
# Install:
#   Add this bash function to your ~/.bashrc and `source ~/.bashrc`.
# Usage: 
#   $ virt-ipaddr --all
#   $ virt-ipaddr --hosts (to display like /etc/hosts)
# Credits : Vincent Freret <vfreret@redhat.com>
#
