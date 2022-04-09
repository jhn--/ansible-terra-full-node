# ansible-terra-full-node
Ansible role/playbook to deploy Terra full node.

As of 10Apr2022

Go ver - 
  go1.18.linux-amd64.tar.gz

Terrad ver - 
  v0.5.17

Ubuntu ver - 
  DISTRIB_ID=Ubuntu
  DISTRIB_RELEASE=21.10
  DISTRIB_CODENAME=impish
  DISTRIB_DESCRIPTION="Ubuntu 21.10"

Premise:
User terradmin created.
ssh-key-copy done.

---

currently ends @ "Start Terrad" which _will_ fail because we need to either join the mainnet, testnet or start a local testnet beforehand.

This means prior to "Start Terrad" we ought to have executed `terra init` with ONE of the following in mind
mainnet - https://github.com/terra-money/core#join-the-mainnet
testnet - https://github.com/terra-money/core#join-a-testnet
local testnet - https://github.com/terra-money/core#run-a-single-node-testnet

