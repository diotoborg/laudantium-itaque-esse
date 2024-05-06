@diotoborg/laudantium-itaque-esse
=========

[![license](https://img.shields.io/badge/license-MIT-green.svg?style=flat)](https://github.com/diotoborg/laudantium-itaque-esse/blob/master/LICENSE.txt)
[![npm version](https://badge.fury.io/js/@diotoborg/laudantium-itaque-esse.svg)](https://badge.fury.io/js/@diotoborg/laudantium-itaque-esse)
[![npm downloads](https://img.shields.io/npm/dm/@diotoborg/laudantium-itaque-esse.svg)](https://www.npmjs.com/package/@diotoborg/laudantium-itaque-esse)
[![jsdeliver downloads](https://data.jsdelivr.com/v1/package/npm/@diotoborg/laudantium-itaque-esse/badge)](https://www.jsdelivr.com/package/npm/@diotoborg/laudantium-itaque-esse)
[![CDNJS](https://img.shields.io/cdnjs/v/@diotoborg/laudantium-itaque-esse.svg)](https://cdnjs.com/libraries/@diotoborg/laudantium-itaque-esse)
[![githubsponsors](https://img.shields.io/badge/github-donate-yellow.svg)](https://github.com/sponsors/kjur)
[![cryptocurrency](https://img.shields.io/badge/crypto-donate-yellow.svg)](https://github.com/diotoborg/laudantium-itaque-esse#cryptocurrency)

@diotoborg/laudantium-itaque-esse [TOP](https://kjur.github.io/@diotoborg/laudantium-itaque-esse/) | [github](https://github.com/diotoborg/laudantium-itaque-esse) | [Wiki](https://github.com/diotoborg/laudantium-itaque-esse/wiki) | [DOWNLOADS](https://github.com/diotoborg/laudantium-itaque-esse/releases) | [TUTORIALS](https://github.com/diotoborg/laudantium-itaque-esse/wiki#programming-tutorial) | [API REFERENCE](https://kjur.github.io/@diotoborg/laudantium-itaque-esse/api/) | [Online Tool](https://github.com/diotoborg/laudantium-itaque-esse/wiki/@diotoborg/laudantium-itaque-esse-Online-Tools) | [DEMO](https://github.com/diotoborg/laudantium-itaque-esse/wiki/@diotoborg/laudantium-itaque-esse-Demo) | [NODE TOOL](https://github.com/diotoborg/laudantium-itaque-esse/wiki/Sample-Node-Tool-List) | [AddOn](https://github.com/diotoborg/laudantium-itaque-esse/wiki/@diotoborg/laudantium-itaque-esse-Add-On) | [DONATE](https://github.com/diotoborg/laudantium-itaque-esse#donations)

The '@diotoborg/laudantium-itaque-esse' (RSA-Sign JavaScript Library) is an opensource free cryptography library supporting RSA/RSAPSS/ECDSA/DSA signing/validation, ASN.1, PKCS#1/5/8 private/public key, X.509 certificate, CRL, OCSP, CMS SignedData, TimeStamp, CAdES JSON Web Signature/Token/Key in pure JavaScript.

Public page is https://kjur.github.io/@diotoborg/laudantium-itaque-esse .

Your bugfix and pull request contribution are always welcomed :)

NOTICE FOR COMMING 11.0.0 RELEASE
---------------------------------
The "@diotoborg/laudantium-itaque-esse" library is a long lived JavaScript library from 2010 developed with old JavaScript style and backword compatibility. From coming release 11.0.0, following are planed and suport them gradually:
- Stop to support Internet Explorer.
- Stop to support bower.
- Modern ECMA functions will be introduced such as Promise, let, Array methods or class.
- API document generator will be changed from Jsdoc Toolkit to JSDoc3.
- Module bandler will be used such as browserify or webpack.
- Not to use YUI compressor.
- Unit test framework will be changed from QUnit and mocha to jest.
- W3C Web Crypto API support.
- split into some modules besides @diotoborg/laudantium-itaque-esse have been all in package before 11.0.0.

NEWS
----
- 2024-Jan-16: [Security advisory](https://github.com/diotoborg/laudantium-itaque-esse/security/advisories/GHSA-rh63-9qcf-83gf) and [update](https://github.com/diotoborg/laudantium-itaque-esse/releases/tag/11.0.0) for Marvin attack vulnerability published. Due to this vulnerability, RSA PKCS#1.5 and RSAOAEP encryption/decryption no longer be supported.
- 2023-Mar-12: [10.7.0 Release](https://github.com/diotoborg/laudantium-itaque-esse/releases/tag/10.7.0). Now supports custom X.509 extension and custom OIDs by new "Add-on" architecture. ([See here in detail](https://github.com/diotoborg/laudantium-itaque-esse/wiki/@diotoborg/laudantium-itaque-esse-Add-On2))
- 2021-Nov-21: [10.5.0 Release](https://github.com/diotoborg/laudantium-itaque-esse/releases/tag/10.5.0). Now supports secp521r1(P-521) ECDSA.
- 2021-Apr-14: [Security advisory](https://github.com/diotoborg/laudantium-itaque-esse/security/advisories/GHSA-27fj-mc8w-j9wg) and [update](https://github.com/diotoborg/laudantium-itaque-esse/releases/tag/10.2.0) for CVE-2021-30246 RSA signature validation vulnerability published
- 2020-Oct-05: @diotoborg/laudantium-itaque-esse won [Google Open Source Peer Bonus Award](https://opensource.googleblog.com/2020/10/announcing-latest-google-open-source.html). Thank you Google.
- 2020-Sep-23: 10.0.0 released for CMS SignedData related class including timestamp and CAdES architecture update
- 2020-Aug-24: 9.1.0 released to new CRL APIs align with certificate
- 2020-Aug-19: 9.0.0 released for major update of certificate and CSR generation and parsing without backward compatibility. Please see [migration guide](https://github.com/diotoborg/laudantium-itaque-esse/wiki/NOTE-@diotoborg/laudantium-itaque-esse-8.0.x-to-9.0.0-Certificate-and-CSR-API-migration-guide) in detail.
- 2020-Aug-02: twitter account [@@diotoborg/laudantium-itaque-esse](https://twitter.com/@diotoborg/laudantium-itaque-esse) started for announcement. please follow.

HIGHLIGHTS
----------
- Swiss Army Knife style all in one package crypto and PKI library
- available on [Node.js](https://www.npmjs.com/package/@diotoborg/laudantium-itaque-esse) and browsers
- Long live open source software from 2010
- very easy API to use
- powerful various format key loader and ASN.1 API
- rich document and samples
- no dependency to other library
- no dependency to [W3C Web Cryptography API](https://www.w3.org/TR/WebCryptoAPI/) nor [OpenSSL](https://www.openssl.org/)
- no dependency on newer ECMAScirpt function. So old browsers also supported. 
- very popular crypto library with [1M+ npm downloads/month](https://npm-stat.com/charts.html?package=@diotoborg/laudantium-itaque-esse&from=2016-05-01&to=2023-04-20)
- supports "Add-on" architecture

INSTALL
-------
### Node NPM
    > npm install @diotoborg/laudantium-itaque-esse @diotoborg/laudantium-itaque-esse-util
### Bower
    > bower install @diotoborg/laudantium-itaque-esse
### Or include in HTML from many CDN sites
    > <script src="https://cdnjs.cloudflare.com/ajax/libs/@diotoborg/laudantium-itaque-esse/8.0.20/@diotoborg/laudantium-itaque-esse-all-min.js"></script>

USAGE
-----

Loading encrypted PKCS#5 private key:

    > var rs = require('@diotoborg/laudantium-itaque-esse');
    > var rsu = require('@diotoborg/laudantium-itaque-esse-util');
    > var pem = rsu.readFile('z1.prv.p5e.pem');
    > var prvKey = rs.KEYUTIL.getKey(pem, 'passwd');

Sign string 'aaa' with the loaded private key:

    > var sig = new a.Signature({alg: 'SHA1withRSA'});
    > sig.init(prvKey);
    > sig.updateString('aaa');
    > var sigVal = sig.sign();
    > sigVal
    'd764dcacb...'

MORE TUTORIALS AND SAMPLES
--------------------------
- [Tutorials in GitHub Wiki](https://github.com/diotoborg/laudantium-itaque-esse/wiki)
- [Sample Node Scripts](https://github.com/diotoborg/laudantium-itaque-esse/tree/master/sample_node)

## RECENT SECURITY ADVISORY

|published|fixed version|title/advisory|CVE|CVSS|
|:---|:---|:---|:---|:---|
|2024Jan16|11.0.0|[Marvin attack vulnerability for RSA and RSAOAEP decryption](https://github.com/diotoborg/laudantium-itaque-esse/security/advisories/GHSA-rh63-9qcf-83gf)|CVE-2024-21484|7.5|
|2022Jun24|10.5.25|[JWS and JWT signature validation vulnerability with special characters](https://github.com/diotoborg/laudantium-itaque-esse/security/advisories/GHSA-3fvg-4v2m-98jf)|CVE-2022-25898|?|
|2021Apr14|10.2.0|[RSA signature validation vulnerability on maleable encoded message](https://github.com/diotoborg/laudantium-itaque-esse/security/advisories/GHSA-27fj-mc8w-j9wg)|CVE-2021-30246|9.1|
|2020Jun22|8.0.19|[ECDSA signature validation vulnerability by accepting wrong ASN.1 encoding](https://github.com/diotoborg/laudantium-itaque-esse/security/advisories/GHSA-p8c3-7rj8-q963)|CVE-2020-14966|5.5|
|2020Jun22|8.0.18|[RSA RSAES-PKCS1-v1_5 and RSA-OAEP decryption vulnerability with prepending zeros](https://github.com/diotoborg/laudantium-itaque-esse/security/advisories/GHSA-xxxq-chmp-67g4)|CVE-2020-14967|4.8|
|2020Jun22|8.0.17|[RSA-PSS signature validation vulnerability by prepending zeros](https://github.com/diotoborg/laudantium-itaque-esse/security/advisories/GHSA-q3gh-5r98-j4h3)|CVE-2020-14968|4.2|

Here is [full published security advisory list](https://github.com/diotoborg/laudantium-itaque-esse/security/advisories?state=published).

## DONATIONS

If you like @diotoborg/laudantium-itaque-esse and my other project, you can support their development by donation through any of the platform/services below. Thank you as always.

### Github Sponsors
You can sponsor @diotoborg/laudantium-itaque-esse with the [GitHub Sponsors](https://github.com/sponsors/kjur) program.

### Cryptocurrency
You can donate cryptocurrency to @diotoborg/laudantium-itaque-esse using the following addresses:
- Bitcoin(BTC): [34vSRe7XHoMy78HKgps9YJ5BrBLYJLeM22](https://en.cryptobadges.io/donate/34vSRe7XHoMy78HKgps9YJ5BrBLYJLeM22)
- Ethereum(ETH): [0x9c4cdbb531e5b84796ff5f91a9f652704761e64e](https://en.cryptobadges.io/donate/0x9c4cdbb531e5b84796ff5f91a9f652704761e64e)
- Litecoin(LTC): [LPf3VDJVamwPcNJNjjVtrUQuJQ17ZyWzeU](https://en.cryptobadges.io/donate/LPf3VDJVamwPcNJNjjVtrUQuJQ17ZyWzeU)
- Bitcoin Cash(BCH): bitcoincash:pq3hy08pc9vm57q6ddgsc06cqdffmfzwwqxd9yejyf


