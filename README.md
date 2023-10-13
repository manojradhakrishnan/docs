# Payments Switch - Documentation

This is a documentation for open source payments switch.

## What is a Payment Switch?

The Payments switch is a unified protocol to connect with dozens of different payment processors with very different internal APIs and SDKs. In other words, the payment switch is a set of domain abstractions built with functional programming concepts over leading payment processors, wallets, buy now pay later and banks.

Key features 0f the payment switch are
- Lightweight: Sub 20 millisecond additional overhead and works like a microservice in you cloud environment
- Compliant: Incorporated all best practices for achieving PCI compliance
- Scalable: Engineered for scale and reliability to support enterprise businesses

## Running the docs on Developer environment

### Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command

```
npm i -g mintlify
```

Run the following command at the root of your documentation (where mint.json is)

```
mintlify dev
```

#### Troubleshooting

- Mintlify dev isn't running - Run `mintlify install` it'll re-install dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `mint.json`
