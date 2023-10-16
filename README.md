# IPLD Batch Signature Specification v1.0.0-rc. 1

## Editors

- [Brooklyn Zelenka], [Fission]
- [Irakli Gozalishvili], [DAG House]

## Authors

- [Brooklyn Zelenka], [Fission]
- [Irakli Gozalishvili], [DAG House]
- [Quinn Wilton], [Fission]

## Depends On

- [IPLD]
- [DID]

## Language

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "NOT RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be interpreted as described in [BCP 14] when, and only when, they appear in all capitals, as shown here.

# 0 Abstract


# 1 Introduction

# 4 Prior Art

# 5 Acknowledgements

<!-- Footnotes -->
 
<!-- Internal Links -->

[Arguments]: #312-arguments
[Command]: #311-command
[Execution Proxy]: #41112-proxy-execution
[Executor]: #212-executor
[Invocation Payload]: #331-invocation-payload
[Invocation Signature]: #331-invocation-envelope
[Invocation]: #33-invocation
[Invoker]: #211-invoker
[Nonce]: #314-nonce
[Receipt Payload]: #411-receipt-payload
[Receipt]: #42-receipt
[Response]: #4-response
[Result]: #41-result
[Subject]: #313-subject
[Task]: #32-task
[enqueue]: #4111-enqueue
[lazy-vs-eager]: #112-lazy-vs-eager-evaluation

<!-- External Links -->

[Ability]: https://github.com/ucan-wg/delegation#33-abilities
[Agoric]: https://agoric.com/
[BCP 14]: https://www.rfc-editor.org/info/bcp14
[Bacalhau]: https://www.bacalhau.org/
[Blaine Cook]: https://github.com/blaine
[Brooklyn Zelenka]: https://github.com/expede/
[CapTP]: https://capnproto.org/rpc.html#specification
[Christine Lemmer-Webber]: https://github.com/cwebber
[DAG House]: https://dag.house
[DAG-CBOR]: https://ipld.io/specs/codecs/dag-cbor/spec/
[DID]: https://www.w3.org/TR/did-core/
[Delegation]: https://github.com/ucan-wg/delegation
[E-lang Mailing List, 2000 Oct 18]: http://wiki.erights.org/wiki/Capability-based_Active_Invocation_Certificates
[Electronic Rights Transfer Protocol (ERTP)]: https://docs.agoric.com/guides/ertp/
[Fission]: https://fission.codes/
[Haskell]: https://en.wikipedia.org/wiki/Haskell
[IPVM]: https://github.com/ipvm-wg
[Irakli Gozalishvili]: https://github.com/Gozala
[JS Number]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number
[Luke Marsen]: https://github.com/lukemarsden
[Marc-Antoine Parent]: https://github.com/maparent
[Mark Miller]: https://github.com/erights
[OCapN]: https://github.com/ocapn/
[Philipp Krüger]: https://github.com/matheus23/
[Quinn Wilton]: https://github.com/QuinnWilton
[Robust Composition]: http://www.erights.org/talks/thesis/markm-thesis.pdf
[Rod Vagg]: https://github.com/rvagg/
[Simon Worthington]: https://github.com/simonwo
[Spritely Institute]: https://spritely.institute/news/introducing-a-distributed-debugger-for-goblins-with-time-travel.html
[UCAN Ability]: https://github.com/ucan-wg/delegation/#23-ability
[UCAN Delegation]: https://github.com/ucan-wg/delegation/
[UCAN Promise]: https://github.com/ucan-wg/promise/
[URI]: https://en.wikipedia.org/wiki/Uniform_Resource_Identifier
[Zeeshan Lakhani]: https://github.com/zeeshanlakhani
[`data`]: https://en.wikipedia.org/wiki/Data_URI_scheme
[`ipfs`]: https://docs.ipfs.tech/how-to/address-ipfs-on-web/#native-urls
[`magnet`]: https://en.wikipedia.org/wiki/Magnet_URI_scheme
[capability systems]: https://en.wikipedia.org/wiki/Capability-based_security
[distributed promise pipelines]: http://erights.org/elib/distrib/pipeline.html
[eRights]: https:/erights.org
[erights]: https://erights.org
[ucanto RPC]: https://github.com/web3-storage/ucanto
