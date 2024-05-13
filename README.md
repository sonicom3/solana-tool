# jito-kit

This package exports a series of toolkits that you can use jito to create pool

## Installation

```bash
npm install jito-kit
or
yarn add jito-kit
```

## Example Usage

```js
await createToken(
  connection,
  token_owner,
  token_name,
  token_symbol,
  token_decimal,
  token_supply,
  token_logo_path,
  token_description
);

await createOpenBookMarket(
  connection,
  token_owner,
  process.env.MINT_ADDRESS!
);

await createPool(
  connection,
  token_owner,
  token_address,
  lp_token_amount,
  lp_sol_amount
);
```

## License

This project is licensed under the terms of the
[MIT license](/LICENSE).
