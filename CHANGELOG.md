# Changelog

## 1.1.0 (2023-02-24)

- Exposes `createPostmarkClientAccount` to call `new postmark.AccountClient`
- `accountApiToken` prop to configure account client
- Exposes postmark account client (`getPostmarkClientAccount`)
- Updates from `postmark` npm package from 2.7.7 to 3.0.15

## 1.0.4 (2023-02-24)

- Exposes `createPostmarkClient` to call `new postmark.ServerClient`
- Option to create postmark client (`postmarkClient` prop) to `sendEmail`

## 1.0.3 (2023-02-24)

- Resting all params to `sendEmail` call

## 1.0.2 (2023-02-24)

- Exposes postmark client (`getPostmarkClient`)

## 1.0.0 (2021-09-30)

- Initial version.
