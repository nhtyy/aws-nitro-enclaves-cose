[![status]][actions] [![version]][crates.io] [![docs]][docs.rs] ![msrv]

[status]: https://img.shields.io/github/actions/workflow/status/awslabs/aws-nitro-enclaves-cose/ci.yml?branch=main
[actions]: https://github.com/awslabs/aws-nitro-enclaves-cose/actions?query=branch%3Amain
[version]: https://img.shields.io/crates/v/aws-nitro-enclaves-cose.svg
[crates.io]: https://crates.io/crates/aws-nitro-enclaves-cose
[docs]: https://img.shields.io/docsrs/aws-nitro-enclaves-cose
[docs.rs]: https://docs.rs/aws-nitro-enclaves-cose
[msrv]: https://img.shields.io/badge/MSRV-1.71.1-blue

## COSE for AWS Nitro Enclaves

This library aims to provide a safe Rust implementation of COSE.
Currently, only COSE Sign1 is implemented, with the ability to sign and verify
COSE Sign1 objects.

It uses openssl to provide the required crypto primitives.

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This project is licensed under the Apache-2.0 License.

