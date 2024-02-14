# Proposal for funding the development of CurveDocs (in-progress)

# Sentence Summary

CurveDocs requests funding the [CurveDocs 2-of-5 Multisig](https://app.safe.global/settings/setup?safe=eth:0x960B77DAf61Ac184D396db23A77Ec391c9454605) with a grant amount of USD 144,000 or 320,000 CRV tokens at a rate of 0.45 USD per CRV token, for 12 months to hire two full-time paid maintainers for maintaining [Curve Docs](https://www.docs.curve.fi), [Curve Resources](https://www.resources.curve.fi) and Curve Notebooks (a collection of Jupyter Notebooks that interactively explain Curve contracts).

# History of Grant Applications

CurveDocs, currently comprising one full-time paid maintainer and a part-time unpaid advisor, was [previously awarded 100,000 CRV tokens](https://etherscan.io/tx/0xddfc04666662bc94ab00520020dbce5502f8168076b0752cdbeea861abcde9e4) estimated at approximat3ely USD 80,000. The maintainer(s) (starting with two contributors and eventually one full-time contributor) set out to create and maintain [Curve Docs](https://www.docs.curve.fi) and [Curve Resources](https://www.resources.curve.fi), among other significant contributions.

As of date, approximately USD 20,000 remains. These funds can sustain current work for approximately four more months.

Initial contributors:

- Mo: https://github.com/mo-anon (currently the only full-time contributor)
- Marco: https://github.com/MarcoWorms

# Proposed Topics

The Proposal entails work on appending/extending and improving Documentation involving the Curve platform (where platform: a set of smart contracts). On that note, there are three aspects:

- Maintaining existing documentation.
    - Gathering feedback from community to improve existing docs, resources on the Curve plaform.
    - Liason with Curve core contributors to gauge improvements to existing documentation.
- Adding missing documentation (docs and resourceS) on existing and upcoming extensions to Curve's plaform.
    - Add documentation on Curve x-gov, x-dao (Existing applications that are undocumented).
    - Add documentation on upcoming Curve lending platform.
- Creating an interactive hub with hosted jupyter notebooks for understanding and interacting with Curve's smart contracts, encompassing:
    - smart contract navigation: showcasing smart contract functionalities.
    - data analyses and research notebooks.
    - integration guidelines for smart contract functionalities such as (e.g.) oracles.

All code written is publicly hosted on the CurveDocs organization: https://github.com/CurveDocs, and hosted on:
- Technical docs: https://docs.curve.fi/ 
- Resources: https://resources.curve.fi/ 
- Notebooks: A first rough version of these notebooks (yet to be hosted) can be found here (https://github.com/CurveDocs/curve-notebook)

Workload will involve two fulltime maintainers. Proposers are actively seeking and have found potential second full-time contributor from the WenLlama community.

# Achievements

## Curve Resources
- Transitioned the documentation platform from GitBook to MkDocs and gave it a new look.
- Made continuous changes/updates throughout the existing documentation and added new sections for previously undocumented features like crvUSD.

## Curve Technical Documentation
- Migrated existing documentation from ReadTheDocs to MkDocs, essentially rebuilding the entire documentation to address previous incompleteness. Key Updates Include:
    - CurveDAO: coverage of all relevant core contracts.
    - StableswapExchange: overhaul of the existing Stableswap documentation, and adding stableswap-ng.
    - CryptoSwap: added regular cryptoswap, tricrypto-ng, and twocrypto-ng (pretty much done) documentation.
    - crvUSD: added technical documentation for all relevant contracts.
    - Pool Factory: Added detailed overviews for all factories, deployment apis, etc.
    - Metaregistry
    - New section dedicated to public audits, whitepapers, and a comprehensive list of deployed contracts.

# Budget

## Maintainers

- Mo (https://github.com/mo-anon), interested in web3 and blockchain, is currently working on technical docs as well as the resources of curve. Contributions outside of docs include:
    - Couch Cushions API, an API that gives unclaimed/unburnt fees across all Curve platforms: https://api-py.llama.airforce/curve/v1/protocol/couch/cushions
    - Curve Lock Monitor: https://t.me/crvlockbot
    - Contributions to curve-dao-operations, titanoboa and vyper
        - https://github.com/curvefi/curve-dao-operations/pull/11
        - https://github.com/pygments/pygments/pull/2579
        - https://github.com/vyperlang/titanoboa/pull/122

- Saint Rat, Bachelor in Mechatronic engineering, internship with a trading firm from September-November last year doing dev work in python, made some arb trading bots, and runs some eth validators. Besides that, always been active and interested in Curve. Contributions include:
    - crvUSD infographic: https://twitter.com/saint_rat/status/1709142294644048308
    - EF grant to submit entropy to their KZG Ceremony: https://twitter.com/saint_rat/status/1647598125480284161 

The proposal is endorsed by [fiddyresearch](https://github.com/bout3fiddy), who maintain a consistent track record of contributing to Curve.

The ask is: USD 144,000 or 320,000 CRV tokens at a rate of 0.45 USD per CRV token (a buffer taken to account for CRV token's price volatility). This entails a payment of USD 6,000 per contributor per month, payable in any way the contributors deem fit for their accounting purposes.


# Payment Details

[CurveDocs 2-of-5 Multisig](https://app.safe.global/settings/setup?safe=eth:0x960B77DAf61Ac184D396db23A77Ec391c9454605) with a grant amount of USD 144,000 or 320,000 CRV tokens at a rate of 0.45 USD per CRV token (since the start of writing this proposal at 14th Feb 2024, CRV is priced on Binance at USD 0.52 per CRV token. A buffer has been established to account for volatility).

Signers involve:

2-of-5 Multisig: 

- [fiddyresearch.eth](https://etherscan.io/address/eth:0xE6DA683076b7eD6ce7eC972f21Eb8F91e9137a17)
- [Chanho (CurveResearch)](https://etherscan.io/address/0x1B177D4BE61Bf8f28154B121acf3bbEdB6178ff0)
- [Mo (CurveDocs)](https://etherscan.io/address/0x163E427123125ca77D194634Cf7DD39698225393)
- [PilotVietnam (Curve, StakeDAO)](https://etherscan.io/address/0xC2D201037bDF8F7fe905F1073106Bf4385b65A6f)
- [Mimaklas (Curve)](https://etherscan.io/address/0xf7Bd34Dd44B92fB2f9C3D2e31aAAd06570a853A6)

