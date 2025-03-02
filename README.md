# Extracted Attributes from Blockchain Parsing Tools

This document provides a summary of attributes that can be extracted using various blockchain parsing tools. The listed attributes help in understanding the structure and details of blockchain transactions.

## Tools and Extracted Attributes

| **Tools** | **List of Attributes** |
|-----------|------------------------|
| **blockparser** ([blockparser](https://github.com/znort987/blockparser)) | id, hash, time, blockid, dstAddress, value, txID, offset, outputID |
| **blockchain-parser** ([blockchain-parser](https://github.com/ragestack/blockchain-parser)) | Magic number, Block size, SHA256 hash of the current block hash, Version number, SHA256 hash of the previous block hash, MerkleRoot hash, Timestamp, Difficulty, Random number, Transactions count, TX version number, Inputs count, TX from hash, N output, Input script, Sequence number, Outputs count, Value, Output script, Lock time, TX hash |
| **python-bitcoin-blockchain-parser** ([python-bitcoin-blockchain-parser](https://github.com/alecalve/python-bitcoin-blockchain-parser)) | _hash, _locktime, _size, _txid, _version, from_hex, hash, hex, inputs, is_coinbase, is_segwit, locktime, n_inputs, n_outputs, outputs, size, txid, uses_bip69, uses_replace_by_fee, version, vsize |
| **blockchain-parser** ([blockchain-parser](https://github.com/rmull/blockchain-parser)) | block, magic, size, version, prev block, merkle root, time, bits, nonce, tx count, prev output, index, script len, sequence, value, script len, version, txin cnt, txout cnt, lock time |
| **BitcoinDatabaseGenerator** ([BitcoinDatabaseGenerator](https://github.com/ladimolnar/BitcoinDatabaseGenerator)) | BitcoinTransactionId, blockId, TransactionHash, TransactionVersion, TransactionLockTime, BlockId, BlockchainField, BlockVersion, BlockHash, PreviousBlockHash, BlockTimeStamp, BlockchainField, BlockchainFileName, PropertyName, Property Value, TransactionInputId, BitcoinTransactionId, SourceTransactionOutput, TransactionInputId, SourceTransactionHash, SourceTransactionOutputIndex, TransactionOutputId, BitcoinTransactionId, OutputIndex, OutputValueBTC, OutputScript |
| **BlockSci** ([BlockSci](https://github.com/citp/BlockSci)) | Height, Hash, Timestamp, Number of Transactions, Size, Version, Merkle Root, Nonce, Difficulty, Previous Block Hash, Inputs, Outputs, Fee, Locktime, Block Height, Block Hash, ScriptSig, Sequence Number, Address, Spent, Spent By Transaction Hash, Spent By Input Index, Type, Balance, Associated Transactions, Total Received, Total Sent, First Seen, Last Seen |
| **Bitcoin Core** ([Bitcoin Core](https://github.com/bitcoin/bitcoin)) | getblockchaininfo, getblockhash, getblock, getblockcount, getchaintips, getdifficulty, getmempoolinfo, getrawmempool, gettxout, getbestblockhash, getnetworkinfo, getconnectioncount, getpeerinfo, ping, getnettotals, getwalletinfo, getbalance, listunspent, getnewaddress, dumpprivkey, listtransactions, getreceivedbyaddress, gettransaction, getmininginfo, getblocktemplate, getnetworkhashps, prioritisetransaction, getrawtransaction, decoderawtransaction, sendrawtransaction, createrawtransaction, signrawtransactionwithwallet |

