# Tron ABI Coder

It is responsible for encoding and decoding the Application Binary Interface (ABI)
used by most smart contracts to interoperate between other smart contracts and clients.

For more information, see the [documentation](https://docs.tron.io/v5/api/utils/abi/).

## Importing

Most users will prefer to use the [umbrella package](https://www.npmjs.com/package/tron),
but for those with more specific needs, individual components can be imported.

```javascript
const {
  ConstructorFragment,
  EventFragment,
  Fragment,
  FunctionFragment,
  ParamType,
  FormatTypes,

  AbiCoder,
  defaultAbiCoder,

  Interface,
  Indexed,

  /////////////////////////
  // Types

  CoerceFunc,
  JsonFragment,
  JsonFragmentType,

  Result,
  checkResultErrors,

  LogDescription,
  TransactionDescription
} = require('@tronproject/abi');
```

## License

MIT License
