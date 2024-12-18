![Cosmian Logo](https://cosmian.com/wp-content/uploads/2024/03/Cosmian-Logo.svg) 

## Open source Github repository

Cosmian provides next-generation cryptography to secure data and applications in zero-trust environments like the public cloud. 

Everything Cosmian does is **open source** and available in this repository.
APIs and usage documentation are available at [docs.cosmian.com](https://docs.cosmian.com)

We encourage developers to explore, learn, and collaborate with us to build secure applications that protect their sensitive data.

### Advanced cryptography

These libraries are available in multiple languages and provide the building blocks to build applications with client-side and application-layer encryption: 

 - [Cosmian Covercrypt](https://github.com/Cosmian/cover_crypt): a fast post-quantum scheme with access policies in traceable user decryption keys.
 - and [Cosmian Findex](https://github.com/Cosmian/findex): to search on encrypted data.

The user API libraries follow the naming convention `cloudproof_[LANGUAGE]`: [`cloudproof_js`](https://github.com/Cosmian/cloudproof_js), [`cloudproof_java`](https://github.com/Cosmian/cloudproof_java), [`cloudproof_python`](https://github.com/Cosmian/cloudproof_python), [`cloudproof_rust`](https://github.com/Cosmian/cloudproof_rust), [`cloudproof_spark`](https://github.com/Cosmian/cloudproof_spark).
All code related to the libraries is tagged with the [`cloudproof`](https://github.com/search?q=topic%3Acloudproof+org%3ACosmian+fork%3Atrue&type=repositories) topic.

### Cosmian Enclave and Cosmian VM

Cosmian Enclave (formerly MSE) lets you run encrypted Python code in SGX enclave, while Cosmian VM lets you secure any application in the cloud using Confidential VMs.

All code related to Cosmian Enclave is tagged with the [`enclave`](https://github.com/search?q=topic%3Aenclave+org%3ACosmian+fork%3Atrue&type=repositories) topic.

### Cosmian KMS

[Check out](https://github.com/Cosmian/kms) this open-source, highly scalable, KMIP 2.1-compliant Key Management Server written in Rust. We will soon update the license so that it can be run for **FREE** on small-sized machines in production. Stay tuned.
