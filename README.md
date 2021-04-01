# Xenios Coin Official Mobile Web Wallet



## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

```

```

```
  $ npm install
  $ cordova platform add android
  $ cordova run android
```

Security Features Added:
* Privacy against autogenerated screenshots [MSTG-STORAGE-9](https://github.com/OWASP/owasp-mstg/blob/1.1.3-excel/Document/0x05d-Testing-Data-Storage.md#finding-sensitive-information-in-auto-generated-screenshots-mstg-storage-9): Solution [cordova-privacyscreen-plugin](https://www.npmjs.com/package/cordova-privacyscreen-plugin)
* SSL Certificate Pinning [MSTG-NETWORK-4](https://github.com/OWASP/owasp-mstg/blob/1.1.3-excel/Document/0x05g-Testing-Network-Communication.md#testing-custom-certificate-stores-and-certificate-pinning-mstg-network-4): Solution [cordova-plugin-sslcertificatechecker](https://www.npmjs.com/package/cordova-plugin-sslcertificatechecker)