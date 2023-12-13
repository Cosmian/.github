![Cosmian Logo](https://cosmian.com/wp-content/uploads/2022/10/Logo-2.svg)

## Open source Github repository

Cosmian provides API to secure the storage and processing of sensitive data in zero-trust environments such as the public cloud. These APIs use advanced cryptographic techniques. Since one must know what protects its sensitive data, everything Cosmian does is open source and available in this repository.

APIs and usage documentation are available at [docs.cosmian.com](https://docs.cosmian.com)

We encourage developers to explore, learn, and collaborate with us to build secure applications that protect their sensitive data.

### Advanced cryptography

These libraries are available in multiple languages and provide the building blocks to build privacy by default applications with advanced encryption ([Covercrypt](https://github.com/Cosmian/cover_crypt): post-quantum, access policies, etc.) and encrypted indexes ([Findex](https://github.com/Cosmian/findex)).
The user API libraries follow the naming convention `cloudproof_[LANGUAGE]`: [`cloudproof_js`](https://github.com/Cosmian/cloudproof_js), [`cloudproof_java`](https://github.com/Cosmian/cloudproof_java), [`cloudproof_python`](https://github.com/Cosmian/cloudproof_python), [`cloudproof_rust`](https://github.com/Cosmian/cloudproof_rust), [`cloudproof_spark`](https://github.com/Cosmian/cloudproof_spark).

All code related to the libraries is tagged with the [`cloudproof`](https://github.com/search?q=topic%3Acloudproof+org%3ACosmian+fork%3Atrue&type=repositories) topic.

### Cosmian Enclave (formerly MSE) and Cosmian VM

The libraries are the Cosmian Enclave's building blocks that let you run encrypted Python code over encrypted data. Visit the [console](https://console.cosmian.com) to create a freemium account for our SaaS offering or our [docs](https://docs.cosmian.com) to run Cosmian Enclave on bare metal machines and understand the differences with Cosmian VM.

All code related to Cosmian Enclave is tagged with the [`mse`](https://github.com/search?q=topic%3Amse+org%3ACosmian+fork%3Atrue&type=repositories) topic.

### Cosmian KMS
[Check out](https://github.com/Cosmian/kms) this open-source, highly scalable, KMIP 2.1-compliant Key Management Server written in Rust. We will soon update the license so that it can be run for **FREE** on small-sized machines in production. Stay tuned.
