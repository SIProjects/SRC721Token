# SRC721-sicashjs-cli
A JS client For SRC721 contract.

# How to use
Install dependencies.
```
npm install
```

Show contract information. The argument *sicash_rpc* is the RPC parameters of SICash node, and *solar_file* is the json file generated by Solar when deploying SRC721.
```
node cli.js --sicash_rpc=http://lickey:sicash@127.0.0.1:25118 --solar_file=../../solar.development.json getinfo
```

Mint a token. *mint toAddress tokenId*.
```
node cli.js --sicash_rpc=http://lickey:sicash@127.0.0.1:25118 --solar_file=../../solar.development.json mint 8aefb4b0ff32c65e9dc4d8036cd6cec0b4c7fe9f 123
```

Mint a token with URI. *mint toAddress tokenId tokenUri*.
```
node cli.js --sicash_rpc=http://lickey:sicash@127.0.0.1:25118 --solar_file=../../solar.development.json mint 8aefb4b0ff32c65e9dc4d8036cd6cec0b4c7fe9f 123 myuri
```
