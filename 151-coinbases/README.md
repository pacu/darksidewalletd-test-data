# 151 blocks of coinbases

## What is this?

This is a darksidewalletd dataset composed of 151 blocks of 1 transparent coinbase to the legacy t-address of zcashd and 150 shielded coinbases to sapling address.

## Folder and files
`blocks` contains all the raw blocks from the regtest zcashd each one on its own file. Not needed for darksidewalletd, but for your convenience.
`Scripts` contains the Python sacrileges that can't really be called scripts that generated this dataset
`transactions` all the raw transactions in hex-enconded strings named by their Tx IDs. one per txt file
`treestates` the tree state json files that are needed to spend these notes
`UTXOs` the UTXOs present in the chain
`zcashd-data` the `regtest` folder of zcashd for reproducibility and correction of this dataset in time
`blocks.txt` the blocks in `DarksideBlocksURL` format
`list_of_block_hashes.txt` contains just that for informational purposes
`list_of_transaction_ids.txt` contains just that for informational purposes
`zcashd_backup.txt` the backup file of zcashd extracted with `zcashd-wallet-tool`