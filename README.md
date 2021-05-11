# k6-crocus

Custom k6 build with [xk6-jose](https://github.com/szkiba/xk6-jose), [xk6-crypto](https://github.com/szkiba/xk6-crypto) and [xk6-prometheus](https://github.com/szkiba/xk6-prometheus).

Built using [xk6](https://github.com/k6io/xk6). This is not an official [k6](https://k6.io) build. The main reason for creating this distribution is to make it easy to use the xk6 extensions mentoined above.

## Features:

- [xk6-jose](https://github.com/szkiba/xk6-jose) A k6 extension for Javascript Object Signing and Encryption (JOSE) standards.
  - JSON Web Token (JWT) support
  - JSON Web Key (JWK) support
- [xk6-crypto](https://github.com/szkiba/xk6-crypto) A k6 extension for using extended crypto functions, mostly from [golang.org/x/crypto](https://pkg.go.dev/golang.org/x/crypto).
  - HKDF key derivation function (RFC 5869) implementation.
  - Password-Based Key Derivation Function 2 (PBKDF2) implementation.
  - Elliptic-curve Diffie–Hellman (ECDH) implementation.
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