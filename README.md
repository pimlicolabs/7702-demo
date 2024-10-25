# 7702 Demo

This repo showcases a simple demo that uses EIP-7702 to send a sponsored userOperation originating from a EOA.

## Running the demo

install dependencies

```bash
pnpm install
```

Sending the authorization transaction to set our EOA's code

```bash
pnpm run authorize
```

Sending a sponsored userOperation from our EOA

```bash
pnpm run send
```

## Aknowledgements

- [Destiner/smart-eoa](https://github.com/Destiner/smart-eoa)
