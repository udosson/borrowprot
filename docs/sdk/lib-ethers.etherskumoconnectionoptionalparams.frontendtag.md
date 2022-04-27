<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@liquity/lib-ethers](./lib-ethers.md) &gt; [EthersKumoConnectionOptionalParams](./lib-ethers.etherskumoconnectionoptionalparams.md) &gt; [frontendTag](./lib-ethers.etherskumoconnectionoptionalparams.frontendtag.md)

## EthersKumoConnectionOptionalParams.frontendTag property

Address that will receive KUMO rewards from newly created Stability Deposits by default.

<b>Signature:</b>

```typescript
readonly frontendTag?: string;
```

## Remarks

For example [depositKUSDInStabilityPool(amount, frontendTag?)](./lib-ethers.etherskumo.depositkusdinstabilitypool.md) will tag newly made Stability Deposits with this address when its `frontendTag` parameter is omitted.
