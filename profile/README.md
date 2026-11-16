# Zeqron

**The Semantic Coordination Network**

Zeqron is a coordination protocol where people, organizations and autonomous agents keep their own state, agree directly, and anchor only the proof.

Each party holds its own records. Two or more parties reach an agreement between themselves, and what is written to the shared record graph is a commitment to that agreement, not its contents. Agents can be AI agents, software bots or industrial machines.

## Status

Private pre-testnet. The protocol is implemented as internal libraries and is being validated on an internal devnet. There is no public network, no public testnet yet, and no token has been issued or offered.

The source code is not public yet. It will be published in this organization; until then, what exists and how far each part has got is listed, with its limits, in the Evidence Pack:

- [Evidence Pack (November 2026)](https://www.zeqron.com/evidence/zeqron-evidence-pack-2026-11.html)

No external audit has been completed. Nothing here is a certification.

## Parts of the protocol

| Part | What it is |
|---|---|
| **Node** | A participant that keeps its own state: a person, an organization, a service, a device or an agent. |
| **Contract** | An agreement reached directly between the parties to it. |
| **QronGraph** | The record graph where commitments are ordered (a DAG with BFT ordering). |
| **ZAXON** | Identity and policy for autonomous agents, bound to an accountable operator. |
| **ZNA** | Native assets, typed by the protocol. |
| **Hologram** | Selective disclosure: proving a statement about data without handing over the data. In design. |

Signatures are post-quantum from the first version (ML-DSA-87, FIPS 204), with ML-KEM-1024 (FIPS 203) for key establishment.

## Read more

- Site: [zeqron.com](https://www.zeqron.com)
- Whitepaper: [whitepaper.zeqron.io](https://whitepaper.zeqron.io)
- Technical documentation: [zeqron.io](https://www.zeqron.io)

## Who builds it

[Encrypia Labs](https://www.encrypia.com) develops the protocol. The Zeqron Foundation, in formation, is intended to govern it.

## Security

To report a vulnerability, follow the [security disclosure policy](https://www.zeqron.com/legal/security). Please do not open a public issue for a security report.
