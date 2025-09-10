# monerosms

[![basher install](https://www.basher.it/assets/logo/basher_install.svg)](https://www.basher.it/package/)

monerosms.com cli for sms verification

## install

```bash
basher install gnomegl/monerosms
```

## usage

```bash
monerosms [command] [options]
```

purchase and manage sms numbers with monero.

## commands

- `balance` - check account balance
- `numbers` - list available numbers
- `buy` - purchase number
- `messages` - check received sms
- `history` - view purchase history

## config

```bash
export MONEROSMS_API_KEY="your_key"
```

## requirements

- curl
- jq