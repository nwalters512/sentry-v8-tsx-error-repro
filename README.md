# sentry-v8-tsx-error-repro

Reproduces a bug in Sentry when using `tsx`.

## Steps to reproduce

1. Clone this repository
2. Install dependencies with `yarn`
3. Run `yarn tsx src/index.ts`
4. Observe that the process fails with the error `TypeError [ERR_INVALID_URL_SCHEME]: The URL must be of scheme file`
