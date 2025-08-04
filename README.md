> [!WARNING]
> This repo was made before the Pectra hardfork and is out of date. For a up to date example on how to send a UserOp using EIP-7702, refer to the Pimlico docs at https://docs.pimlico.io/guides/eip7702/demo

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

## Acknowledgements

- [Destiner/smart-eoa](https://github.com/Destiner/smart-eoa)
