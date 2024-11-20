<div align="center">
  <p align="center">
    <a href="https://rounds.wtf/" target="blank"><img src="https://i.imgur.com/WJb8mWi.png" width="200" alt="Rounds Logo" /></a>
  </p>
  <h1>Rounds Contracts</h1>
  <p>The smart contracts powering <a href="https://rounds.wtf/" target="blank">rounds.wtf</a></p>
</div>


```shell
source ~/.zshenv
foundryup
forge --version
cast --version
```

## Contract Development

### Build

```shell
$ forge build
```

### Test

```shell
$ forge test
```

### Format

```shell
$ forge fmt
```

### Gas Snapshots

```shell
$ forge snapshot
```

### Anvil

```shell
$ anvil
```

### Script

#### Deploy

```shell
forge script script/DeployRoundFactory.s.sol:DeployRoundFactory --chain <chain_id> --rpc-url <rpc_url> --priority-gas-price 50 --broadcast --verify
```

### Cast

```shell
$ cast <subcommand>
```

### Help

```shell
$ forge --help
$ anvil --help
$ cast --help
```
