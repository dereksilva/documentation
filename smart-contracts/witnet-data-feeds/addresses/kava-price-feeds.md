---
description: Price feeds currently supported by the Witnet Foundation on the Kava ecosystem
---

# Kava Price Feeds

### Kava EVM Mainnet

**WitnetPriceRouter**: [`0xD39D4d972C7E166856c4eb29E54D3548B4597F53`](https://explorer.kava.io/address/0xD39D4d972C7E166856c4eb29E54D3548B4597F53)

| **Caption**                                                                  | **ID4**      | **Heartbeat** | **Deviation** | **Cooldown** |
| ---------------------------------------------------------------------------- | ------------ | :-----------: | :-----------: | :----------: |
| [Price-BTC/USD-6](https://feeds.witnet.io/kava/kava-mainnet\_btc-usd\_6)     | `0x24beead4` |    24 hours   |      3.5%     |      15'     |
| [Price-ETH/USD-6](https://feeds.witnet.io/kava/kava-mainnet\_eth-usd\_6)     | `0x3d15f701` |    24 hours   |      3.5%     |      15'     |
| [Price-KAVA/USD-6](https://feeds.witnet.io/kava/kava-mainnet\_kava-usd\_6)   | `0xde77dd55` |    24 hours   |      0.5%     |      15'     |
| [Price-KAVA/USDT-6](https://feeds.witnet.io/kava/kava-mainnet\_kava-usdt\_6) | `0x465eb519` |    24 hours   |      0.5%     |      15'     |
| [Price-USDC/USD-6](https://feeds.witnet.io/kava/kava-mainnet\_usdc-usd\_6)   | `0x4c80cf2e` |    24 hours   |      0.1%     |      15'     |
| [Price-USDT/USD-6](https://feeds.witnet.io/kava/kava-mainnet\_usdt-usd\_6)   | `0x538f5a25` |    24 hours   |      0.1%     |      15'     |

### Kava EVM Testnet

**WitnetPriceRouter**: [`0xB4B2E2e00e9d6E5490d55623E4F403EC84c6D33f`](https://explorer.evm-alpha.kava.io/address/0xB4B2E2e00e9d6E5490d55623E4F403EC84c6D33f/read-contract)``

| **Caption**                                                                   | **ID4**      | **Heartbeat** | **Deviation** | **Cooldown** |
| ----------------------------------------------------------------------------- | ------------ | :-----------: | :-----------: | :----------: |
| [Price-BTC/USD-6](https://feeds.witnet.io/kava/kava-testnet\_btc-usd\_6)      | `0x24beead4` |    24 hours   |      3.5%     |      15'     |
| [Price-ETH/USD-6](https://feeds.witnet.io/kava/kava-testnet\_eth-usd\_6)      | `0x3d15f701` |    24 hours   |      3.5%     |      15'     |
| [Price-KAVA/USD-6](https://feeds.witnet.io/kava/kava-testnet\_kava-usd\_6)    | `0xde77dd55` |    24 hours   |      0.5%     |      15'     |
| [Price-KAVA/USDT-6](https://feeds.witnet.io/feeds/kava-testnet\_kava-usdt\_6) | `0x465eb519` |    24 hours   |      0.5%     |      15'     |
| [Price-USDC/USD-6](https://feeds.witnet.io/kava/kava-testnet\_usdc-usd\_6)    | `0x4c80cf2e` |    24 hours   |      0.1%     |      15'     |
| [Price-USDT/USD-6](https://feeds.witnet.io/kava/kava-testnet\_usdt-usd\_6)    | `0x538f5a25` |    24 hours   |      0.1%     |      15'     |

{% hint style="success" %}
Clicking on any of the captions above will take you to the corresponding view in the [**Data Feeds Explorer** website](https://feeds.witnet.io), where not only the whole price timeline can be checked for the corresponding currency pair, but also the **Price Feed** contract currently serving the price updates, as well as the hashes of the Witnet transactions that solved every single update.
{% endhint %}

{% content-ref url="../price-feeds-registry.md" %}
[price-feeds-registry.md](../price-feeds-registry.md)
{% endcontent-ref %}

{% content-ref url="../triggering-conditions.md" %}
[triggering-conditions.md](../triggering-conditions.md)
{% endcontent-ref %}
