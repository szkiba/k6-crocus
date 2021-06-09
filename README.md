# k6-crocus

Custom k6 build with [xk6-dashboard](https://github.com/szkiba/xk6-dashboard), [xk6-cache](https://github.com/szkiba/xk6-cache), [xk6-dotenv](https://github.com/szkiba/xk6-dotenv), [xk6-mock](https://github.com/szkiba/xk6-mock), [xk6-faker](https://github.com/szkiba/xk6-faker), [xk6-jose](https://github.com/szkiba/xk6-jose), [xk6-crypto](https://github.com/szkiba/xk6-crypto), [xk6-yaml](https://github.com/szkiba/xk6-yaml), [xk6-toml](https://github.com/szkiba/xk6-toml), [xk6-csv](https://github.com/szkiba/xk6-csv), [xk6-ansible-vault](https://github.com/szkiba/xk6-ansible-vault) and [xk6-prometheus](https://github.com/szkiba/xk6-prometheus).

Built using [xk6bundler](https://github.com/szkiba/xk6bundler). This is not an official [k6](https://k6.io) build. The main reason for creating this distribution is to make it easy to use the xk6 extensions mentoined above.

## Features:

- [xk6-dashboard](https://github.com/szkiba/xk6-dashboard) A k6 extension that enables creating web based metrics dashboard for k6.
- [xk6-cache](https://github.com/szkiba/xk6-cache) A k6 extension enables vendoring remote HTTP modules to single source control friendly file.
- [xk6-dotenv](https://github.com/szkiba/xk6-dotenv) A k6 extension that loads env vars from a .env file.
- [xk6-mock](https://github.com/szkiba/xk6-mock) A k6 extension for mocking HTTP(S) servers during test development.
- [xk6-faker](https://github.com/szkiba/xk6-faker) A k6 extension for random fake data generation.
- [xk6-jose](https://github.com/szkiba/xk6-jose) A k6 extension for Javascript Object Signing and Encryption (JOSE) standards.
  - JSON Web Token (JWT) support
  - JSON Web Key (JWK) support
- [xk6-crypto](https://github.com/szkiba/xk6-crypto) A k6 extension for using extended crypto functions, mostly from [golang.org/x/crypto](https://pkg.go.dev/golang.org/x/crypto).
  - HKDF key derivation function (RFC 5869) implementation.
  - Password-Based Key Derivation Function 2 (PBKDF2) implementation.
  - Elliptic-curve Diffie–Hellman (ECDH) implementation.
- [xk6-yaml](https://github.com/szkiba/xk6-yaml) A k6 extension enables to encode and decode YAML values
- [xk6-toml](https://github.com/szkiba/xk6-toml) A k6 extension enables to encode and decode TOML values
- [xk6-csv](https://github.com/szkiba/xk6-csv) A k6 extension enables to parse CSV values
- [xk6-ansible-vault](https://github.com/szkiba/xk6-ansible-vault) A k6 extension enables to encrypt and decrypt ansible vaults and make it possible to publish secrets with tests in a safe way
- [xk6-prometheus](https://github.com/szkiba/xk6-prometheus) A k6 extension implements Prometheus HTTP exporter as k6 output extension.

## Install

You can install the pre-compiled binary or use Docker.

### Install the pre-compiled binary

Download the pre-compiled binaries from the [releases page](https://github.com/szkiba/k6-crocus/releases) and
copy to the desired location.

### Running with Docker

You can also use it within a Docker container. To do that, you'll need to
execute the following:

```sh
docker run szkiba/k6-crocus
```
