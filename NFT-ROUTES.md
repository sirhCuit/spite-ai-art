# NFT Edition Routes — Comparison (checked 2026-11-08)

Goal: sell a fixed number of editions of each piece (starting CORE SERIES #001 and PASTEL SERIES #001), keep the 3840 master gated, retain copyright.

## Route A — XRPL via xrp.cafe
- NFTs are native to the protocol (XLS-20), no smart contract to deploy or audit.
- Royalties: TransferFee set at mint, immutable, up to 50%, enforced by the ledger itself on sales through the offer system. No marketplace can route around it. (Caveat: a purely private off-ledger deal can settle elsewhere, same as any chain.)
- Costs: network fee ~0.000012 XRP per transaction (under a cent); a small XRP reserve per 32 NFTs held (0.2 XRP). xrp.cafe: 1.589% marketplace fee on sales; collection launch 3 XRP + 0.03 XRP per NFT.
- Editions: supported through the launchpad as a lazy mint. You set the total, price, mint window, per-wallet limit; collectors mint their own copy, stamped "Edition X of N".
- Audience: nearly all XRPL NFT volume runs through xrp.cafe, but the whole market is small (network-wide royalties were about 5.3K XRP in the week before this check). Buyers are XRP natives, which matches the Circuit Research crowd.
- Wallet: Xaman or Crossmark.

## Route B — Base (Ethereum L2) via Manifold
- You deploy your own ERC-721/1155 contract through Manifold Studio: the collection lives in a contract you own, portable across marketplaces. Manifold takes 0% platform fee; you pay gas.
- Costs: Base gas is cents (an ERC-721 mint runs about $0.04–0.05). If collectors mint through Manifold Claim Pages, they pay a delivery fee of 0.0005 ETH per standard claim plus gas, so your upfront cost can be near zero.
- Royalties: the weak point. EIP-2981 royalties are a signal, not a rule. OpenSea made creator fees optional in Aug 2023 and stopped enforcing them in early 2024. Enforcement is possible with creator-enforced contracts (ERC721-C / ERC1155-C via Seaport 1.6 + Payment Processor), capped at 10% and only on participating venues. Plan around primary sale income; treat royalties as a bonus.
- Selling through OpenSea's own drop tooling instead of Manifold costs a 10% primary drop fee, versus OpenSea's normal 1% secondary sale fee. Use Manifold for the drop.
- Audience: the Ethereum-side collector pool (OpenSea OS2 spans 20+ chains) is far larger than XRPL's, but colder for a new artist with no ETH-native following.
- Note: Zora now turns posts into tradeable coins, not classic NFTs. Not this use case.

## Shared rules either way
- Store art + metadata on IPFS or Arweave, never a single company's server.
- Listing terms: buyer gets the token + personal display rights; copyright and commercial rights stay with Sirhc. The full-res 3840 file can be gated as owner-only unlockable content.
- Market as art collectibles, never as investments.
- Sales are taxable income; keep records of each sale.

## Recommendation on record
First drop on XRPL: near-zero cost, guaranteed royalties, and his existing audience is XRPL-leaning. Treat it as the proving run. Keep Base/Manifold in the back pocket for a later drop aimed at the bigger collector pool, once the series has sales history. Decision is Sirhc's.
