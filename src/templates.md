### Motoko Templates

#### Beginner Level
- [Hello World](https://github.com/dfinity/examples/tree/master/motoko/hello_world) - Introduction to Motoko with basic frontend-backend communication. `[frontend+backend]`
- [Counter](https://github.com/dfinity/examples/tree/master/motoko/counter) - Basic counter demonstrating persistent state in Motoko and stable memory for upgrades. `[backend]`
- [Hello Cycles](https://github.com/dfinity/examples/tree/master/motoko/hello_cycles) - Simple demonstration of receiving, transferring, and checking cycle balances. `[backend]` `[cycles]`
- [Superheroes CRUD](https://github.com/dfinity/examples/tree/master/motoko/superheroes) - Full-stack example showing how to build a CRUD application with React frontend. `[frontend+backend]` `[react]`

#### Intermediate Level
- [Actor Classes](https://github.com/dfinity/examples/tree/master/motoko/classes) - Demonstrates dynamic canister creation and inter-canister communication using actor classes. `[backend]` `[multi-canister]`
- [Composite Query](https://github.com/dfinity/examples/tree/master/motoko/composite_query) - Shows how to implement composite queries for efficient data retrieval. `[backend]` `[query optimizations]`
- [Parallel Calls](https://github.com/dfinity/examples/tree/master/motoko/parallel_calls) - Demonstrates parallel vs sequential inter-canister calls for improved performance. `[backend]` `[multi-canister]`
- [ICP Transfer](https://github.com/dfinity/examples/tree/master/motoko/icp_transfer) - Example showing how to transfer ICP tokens using the ledger canister. `[backend]` `[token]` `[ledger]`
- [ICRC-2 Swap](https://github.com/dfinity/examples/tree/master/motoko/icrc2-swap) - Demonstrates depositing, swapping, and withdrawing ICRC-2 tokens. `[backend]` `[token]` `[ICRC-2]`
- [Internet Identity Integration](https://github.com/dfinity/examples/tree/master/motoko/internet_identity_integration) - Shows how to integrate Internet Identity for authentication. `[frontend+backend]` `[authentication]`
- [Game of Life](https://github.com/dfinity/examples/tree/master/motoko/life) - Demonstrates state preservation during canister upgrades using stable memory. `[backend]` `[stable memory]`
- [Random Maze](https://github.com/dfinity/examples/tree/master/motoko/random_maze) - Shows how to use cryptographic randomness and async requests. `[backend]` `[randomness]`
- [HTTP GET](https://github.com/dfinity/examples/tree/master/motoko/send_http_get) - Demonstrates implementing HTTP GET requests. `[backend]` `[http outcalls]`
- [HTTP POST](https://github.com/dfinity/examples/tree/master/motoko/send_http_post) - Demonstrates implementing HTTP POST requests. `[backend]` `[http outcalls]`
- [Token Transfer](https://github.com/dfinity/examples/tree/master/motoko/token_transfer) - Shows how to transfer ICRC-1 tokens between accounts. `[backend]` `[token]` `[ICRC-1]`
- [Token Transfer From](https://github.com/dfinity/examples/tree/master/motoko/token_transfer_from) - Demonstrates ICRC-2 approve functionality to transfer tokens on behalf of others. `[backend]` `[token]` `[ICRC-2]`

#### Expert Level
- [Encrypted Notes](https://github.com/dfinity/examples/tree/master/motoko/encrypted-notes-dapp) - Full-stack application for storing confidential information with client-side encryption. `[frontend+backend]` `[encryption]` `[security]`
- [IC-POS](https://github.com/dfinity/examples/tree/master/motoko/ic-pos) - Point of Sale application demonstrating how to accept ckBTC payments. `[frontend+backend]` `[bitcoin]` `[payments]` `[ckBTC]`
- [Threshold ECDSA](https://github.com/dfinity/examples/tree/master/motoko/threshold-ecdsa) - Demonstrates the Threshold ECDSA API for creating cryptographic signatures. `[backend]` `[cryptography]` `[chain fusion]`
- [Threshold Schnorr](https://github.com/dfinity/examples/tree/master/motoko/threshold-schnorr) - Shows how to use the Threshold Schnorr API for creating Schnorr signatures. `[backend]` `[cryptography]` `[chain fusion]`

### Rust Templates

#### Beginner Level
- [Counter](https://github.com/dfinity/examples/tree/master/rust/counter) - Basic counter implementation in Rust demonstrating state management. `[backend]`
- [Basic DAO](https://github.com/dfinity/examples/tree/master/rust/basic_dao) - Simple decentralized autonomous organization with proposal and voting mechanisms. `[backend]` `[governance]`
- [Canister Info](https://github.com/dfinity/examples/tree/master/rust/canister-info) - Example showing how to retrieve information about canisters using IC's canister_info management call. `[backend]` `[system]`
- [Canister Logs](https://github.com/dfinity/examples/tree/master/rust/canister_logs) - Demonstrates how to display and use canister logs for debugging purposes. `[backend]` `[debugging]`
- [Periodic Tasks](https://github.com/dfinity/examples/tree/master/rust/periodic_tasks) - Shows how to execute smart contract functions after a specific time period. `[backend]` `[timers]`

#### Intermediate Level
- [Basic Ethereum](https://github.com/dfinity/examples/tree/master/rust/basic_ethereum) - Canister that can send and receive ETH (Ether) using threshold ECDSA and HTTPS outcalls. `[backend]` `[chain fusion]` `[ethereum]`
- [Canister Snapshots](https://github.com/dfinity/examples/tree/master/rust/canister-snapshots) - Demonstrates taking and loading canister snapshots to restore data from simulated data loss. `[backend]` `[data recovery]`
- [Encrypted Notes](https://github.com/dfinity/examples/tree/master/rust/encrypted-notes-dapp) - Example for creating and storing confidential information on IC. `[frontend+backend]` `[encryption]` `[security]`
- [Guards and Async Code](https://github.com/dfinity/examples/tree/master/rust/guards) - Demonstrates use of asynchronous code and inter-canister call implementation. `[backend]` `[async]`
- [Parallel Calls](https://github.com/dfinity/examples/tree/master/rust/parallel_calls) - Shows how to implement parallel inter-canister calls and the differences from sequential calls. `[backend]` `[multi-canister]` `[optimization]`
- [Performance Counters](https://github.com/dfinity/examples/tree/master/rust/performance_counters) - Demonstrates how to query performance counters to profile and optimize canister performance. `[backend]` `[optimization]`
- [Query Statistics](https://github.com/dfinity/examples/tree/master/rust/query_stats) - Example of working with the query stats feature. `[backend]` `[metrics]`
- [HTTP GET](https://github.com/dfinity/examples/tree/master/rust/send_http_get) - Shows how to use IC's HTTPS outcalls feature to make GET requests. `[backend]` `[http outcalls]`
- [HTTP POST](https://github.com/dfinity/examples/tree/master/rust/send_http_post) - Demonstrates how to use IC's HTTPS outcalls feature to make POST requests. `[backend]` `[http outcalls]`
- [WebAssembly SIMD](https://github.com/dfinity/examples/tree/master/rust/simd) - Example showing how ICP supports WebAssembly SIMD instructions for parallel data processing. `[backend]` `[performance]`
- [Token Transfer](https://github.com/dfinity/examples/tree/master/rust/token_transfer) - Canister that can transfer ICRC-1 tokens to other accounts. `[backend]` `[token]` `[ICRC-1]`
- [Token Transfer From](https://github.com/dfinity/examples/tree/master/rust/token_transfer_from) - Example of transferring ICRC-1 tokens on behalf of other accounts using ICRC-2 approve functionality. `[backend]` `[token]` `[ICRC-2]`
- [VetKD API](https://github.com/dfinity/examples/tree/master/rust/vetkd) - Canister that offers the vetKD (verifiably encrypted threshold key derivation) system API. `[backend]` `[cryptography]`

#### Expert Level
- [Basic Bitcoin](https://github.com/dfinity/examples/tree/master/rust/basic_bitcoin) - Canister that can send and receive Bitcoin using ECDSA API, Schnorr API, and Bitcoin API. `[backend]` `[bitcoin]` `[chain fusion]`
- [DEX Example](https://github.com/dfinity/examples/tree/master/rust/defi) - Decentralized exchange implementation demonstrating interaction with token and ledger canisters. `[backend]` `[defi]` `[token]`
- [Face Recognition](https://github.com/dfinity/examples/tree/master/rust/face-recognition) - Advanced example showing face detection and recognition from user photos. `[frontend+backend]` `[machine learning]`
- [NFT Wallet](https://github.com/dfinity/examples/tree/master/rust/nft-wallet) - Wallet that can register NFTs, transfer NFTs, and track contained NFTs. `[backend]` `[nft]`
- [QR Code Generator](https://github.com/dfinity/examples/tree/master/rust/qrcode) - Demonstrates long-running computations using Deterministic Time Slicing (DTS). `[backend]` `[computation]` `[image processing]`
- [Threshold ECDSA](https://github.com/dfinity/examples/tree/master/rust/threshold-ecdsa) - Example of using threshold ECDSA API to create signatures with keys derived from input. `[backend]` `[cryptography]` `[chain fusion]`
- [Threshold Schnorr](https://github.com/dfinity/examples/tree/master/rust/threshold-schnorr) - Shows how to use threshold Schnorr API for signature creation. `[backend]` `[cryptography]` `[chain fusion]`
- [X.509](https://github.com/dfinity/examples/tree/master/rust/x509) - Minimal canister smart contract showcasing X.509 certificate use cases. `[backend]` `[security]` `[certificates]`

### TypeScript Templates (Azle)
- [Azle](https://demergent-labs.github.io/azle/) - Azle lets you write Internet Computer canisters using TypeScript. `[backend]` `[frontend]` `[Typescript`

#### Beginner Level
- [Hello World HTTP Server](https://github.com/demergent-labs/azle/tree/main/examples/experimental/demo/hello_world_http_server) - Basic example demonstrating Azle setup and HTTP server functionality on ICP. `[backend]` `[http]`

- [Azle + NextJS Starter](https://github.com/mzurs/ic_template-Azle-NextJS) - Build Full-stack Dapp on IC with Typescript CDK and NextJS.

#### Expert Level
- [Basic Bitcoin](https://github.com/demergent-labs/azle/tree/main/examples/experimental/demo/basic_bitcoin) - Implementation of Bitcoin integration showing how to send and receive BTC on ICP. `[backend]` `[bitcoin]` `[chain fusion]`
- [Bitcoin PSBT](https://github.com/demergent-labs/azle/tree/main/examples/experimental/demo/bitcoin_psbt) - Advanced Bitcoin example demonstrating Partially Signed Bitcoin Transactions (PSBT) and SegWit integration. `[backend]` `[bitcoin]` `[chain fusion]` `[segwit]`
- [ckBTC](https://github.com/demergent-labs/azle/tree/main/examples/experimental/demo/ckbtc) - Complete ckBTC implementation with ledger, Internet Identity, KYT, minter, and Bitcoin integration. `[frontend+backend]` `[bitcoin]` `[authentication]` `[token]` `[ckBTC]`

### Frontend Integration Templates

ICP provides frontend canister templates when creating new projects with `dfx new`. These templates include options for SvelteKit, React, Vue, and Vanilla JS frameworks, available in dfx versions 0.17.0 and newer.

Here are some of the community-created templates and examples:

- [Vite + React + Motoko template](https://github.com/rvanasa/vite-react-motoko) - Template for Vite + React + Motoko integration. `[frontend]` `[react]` `[motoko]`
- [Vite + SvelteKit + Motoko template](https://github.com/letmejustputthishere/vite-sveltekit-motoko-ii/tree/main) - Template for Vite + SvelteKit + Motoko integration. `[frontend]` `[svelte]` `[motoko]`
-- [Azle + NextJS Starter](https://github.com/mzurs/ic_template-Azle-NextJS) - Build Full-stack Dapp on IC with Typescript CDK and NextJS.`[typescript]`

### Chainfusion Templates

#### Intermediate Level

- [Alloy Toolkit](https://github.com/kristoferlund/ic-alloy-toolkit) - Examples of interacting with Ethereum from a Rust canister using the Alloy EVM support libraries`[chainfusion]`
- [SIWE starter](https://github.com/kristoferlund/ic-siwe-react-demo-rust) - Login in to ICP using Metamask and other Ethereum wallets.`[rust]``[chainfusion]`
- [Chain Fusion Starter](https://github.com/letmejustputthishere/chain-fusion-starter) – starter template leveraging chain fusion technology to build EVM coprocessors on the Internet Computer Protocol
- [ic-evm-utils](https://crates.io/crates/ic-evm-utils) – Utils for interacting with Ethereum from ICP canisters.
- [evm-rpc-canister-types](https://crates.io/crates/evm-rpc-canister-types) – Types for interacting with the EVM RPC canister.`[rust]``[chainfusion]`
- [Chain-key ECDSA](https://internetcomputer.org/how-it-works/threshold-ecdsa-signing/) - Tech that allows creating transactions targeting various chains from canisters on the Internet Computer.`[chainfusion]`
- [B3Wallet](https://github.com/B3Pay/b3-wallet) - A decentralized wallet supporting multiple blockchains, including Ethereum, Bitcoin, and ICP.`[chainfusion]`

### Bitcoin

- [Bitcoin Integration](https://internetcomputer.org/bitcoin-integration) - Landing page of the direct integration with the Bitcoin network.`[chainfusion]`
- [ckBTC](https://github.com/dfinity/ic/tree/master/rs/bitcoin/ckbtc) - Canister-controlled BTC twin on ICP with 1:1 backing.`[chainfusion]``[rust]`
- [Internet Computer Bitcoin Library](https://github.com/Benjamin-Loison/Internet-Computer-Bitcoin-Library) - Utility libraries for Motoko/Rust to simplify building on the Bitcoin Integration.`[chainfusion]``[motoko]`
- [Multi-Subnet Bitcoin Wallet](https://github.com/sardariuss/ic_btc_multisig) - Proof-of-Concept of multi-subnet Bitcoin custody for increased secruty.`[chainfusion]`
- [Loka](https://github.com/lokaverse/loka_canister) - Trustless Non-Custodial Bitcoin Mining Platform built on ICP.`[chainfusion]`
- [runes-indexer](https://github.com/octopus-network/runes-indexer) – An onchain runes indexer on the Internet Computer.`[chainfusion]`
- [Ordinals Canister](https://github.com/sardariuss/ordinals_canister) - A canister that enables the retrieval of BTC ordinals and their corresponding inscriptions.`[chainfusion]`
- [Inscription Canister](https://github.com/domwoe/inscription_canister) - A canister to create Ordinal inscriptions.
`[chainfusion]`
### Ethereum

- [Bitfinity EVM](https://bitfinity.network) - An Ethereum Virtual Machine (EVM) on ICP.`[chainfusion]`
- [CCAMP](https://github.com/usherlabs/ccamp) - General-purpose, modular, and custom data-driven Cross-chain Asset Management Protocol.`[chainfusion]`
- [ChainSight](https://docs.chainsight.network/chainsight-overview/introduction) - Composable cross-chain data oracles built on HTTPS Outcalls and Chain-key ECDSA.`[chainfusion]`
- [ckETH](https://github.com/dfinity/ic/tree/master/rs/ethereum/cketh) - Canister-controlled ETH twin on ICP with 1:1 backing.`[chainfusion]`
- [ckNFT](https://github.com/b3hr4d/cknft) - A PoC to bridge ICRC-7 NFTs to ERC-1155 NFTs on EVMs.`[chainfusion]`
- [ERC20-ICP](https://github.com/dfinity/erc20-icp) - Contracts and canisters enabling ICP tokens as ERC20 on Ethereum.`[chainfusion]`
- [EVM RPC Canister](https://github.com/internet-computer-protocol/evm-rpc-canister) - Interact with EVM blockchains from the Internet Computer.`[chainfusion]`
- [Ethereum Canister](https://github.com/eigerco/ethereum-canister) - Ethereum Light Client (Helios) running inside a canister.`[chainfusion]`
- [EVM Utility Canister](https://github.com/icopen/evm_utils_ic) - Utility canister to create and parse EVM-compliant transactions`[chainfusion]`.
- [ic-alloy-basic-eth](https://github.com/kristoferlund/ic-alloy-basic-eth-frontend) - A multiuser Ethereum wallet starter/template using the Alloy EVM support libraries.
- [ic-alloy-toolkit](https://github.com/kristoferlund/ic-alloy-toolkit) - Example code for using Alloy with the Internet Computer.`[chainfusion]`
- [ic-solidity-bindgen](https://github.com/horizonx-tech/ic-solidity-bindgen) - Generate Rust bindings for Solidity contracts from ABIs to use with the Internet Computer.`[chainfusion]`
- [ic-eth-starter](https://github.com/dfinity/ic-eth-starter) - An advanced starter project for interacting with Ethereum on the Internet Computer (Beta).`[chainfusion]`
- [ic-web3-rs](https://github.com/horizonx-tech/ic-web3-rs) - Utility library to interact with EVM networks.`[chainfusion]`
- [Oisy](https://github.com/dfinity/oisy-wallet) - A novel Ethereum wallet that is hosted on the Internet Computer, is browser-based, fully on-chain, and secured by Chain-key cryptography and Internet Identity.`[chainfusion]`
- [Omnic](https://github.com/rocklabs-io/omnic) - Cross-chain messaging protocol to connect EVM-compatible chains via the Internet Computer.`[chainfusion]`
- [Orally](https://github.com/orally-network/oracle) - Cross-chain oracle factory built on HTTPS Outcalls and Chain-key ECDSA.`[chainfusion]`
- [Gitcoin Passport Client](https://github.com/vporton/passport-client-dfinity) - a sample app for securely retrieving Gitcoin Passport scores and store them into a DB.`[chainfusion]`
- [Evm Rust Bridge](https://github.com/Stephen-Kimoi/icp-evm-rust-bridge) - A seamless Rust-based starter template for integrating ICP canisters with EVM-based smart contracts.`[chainfusion]`
- [Ethereum-lightclient-canister](https://github.com/octopus-network/ethereum-lightclient-canister) - An Ethereum light client canister that is compatible with newer versions of the Ethereum RPC protocol and adapted from the Helios project.`[chainfusion]`
### Solana

- [Galactic Bridge](https://github.com/weichain/galactic-bridge-icp) - Canister-controlled SOL bridge using Chain Fusion tech.`[chainfusion]`
- [Solana RPC Canister](https://github.com/mfactory-lab/ic-solana) - Interact with Solana blockchain from the Internet Computer.`[chainfusion]`


### SNS and DAO Templates

#### Beginner Level
- [Axon](https://github.com/icdevs/axon) - A multi-user, multi-neuron management canister.
- [Service Nervous System](https://internetcomputer.org/sns) - Framework inspired by the Network Nervous System.
- [Threshold Canister](https://github.com/dfinity/threshold) - Threshold voting and execution for the IC.
- [ICP Governance Canister](https://github.com/redsteep/dfinity-icp-governor) - A fully-fledged single DAO governance solution inspired by the Compound smart contracts.

## Game Development Templates

#### Intermediate Level

- [ICPGameKit by Morgan Page](https://github.com/morganpage/ic-gamekit) - A drop-in solution for adding achievements, and game and user data saves on-chain using ICP.
- [BoomDAO World Protocol](https://github.com/BoomDAO/world-protocol) - An on-chain game server protocol weaving together ICP games into one universally accessible database.
- [BoomDAO Unity template](https://github.com/BoomDAO/unity-template) - Unity template with wallet integration and NFT fetching.
- [Internet Computer GameKit](https://github.com/dfinity/ic-gamekit) - Toolkit for building games on the IC.
- [Unity Play To Earn Sample](https://github.com/therealbryanho/IC-Code-Sample-Unity-Play-to-Earn-Game) - Example of how to deploy a Unity play to earn game on the IC.
- [WebGL Sample](https://internetcomputer.org/docs/current/samples/host-a-webgame) - Example of how to host a WebGL game on the IC.
- [Wheel of Fortune](https://github.com/temokoki/IC_Wheel_of_Fortune) - Example of II authentication, self-controlling canister (waits for players and chooses winner randomly) and ICP coin transferring (sub-account creation for participants and withdrawal functionality)


## Wallets and Authentication Templates

#### Beginner Level

- [AstroX Me](https://astrox.me/#/) - Canister-based mobile/web multi-chain wallet.
- [Bitfinity](https://wallet.infinityswap.one/) - Chrome extension.
- [ICRC-1 Wallet](https://github.com/research-ag/wallet) - Canister-based wallet for ICRC-1 compliant tokens.
- [Internet Identity](https://github.com/dfinity/internet-identity) - Pseudoymous authentication system for the Internet Computer.
- [NFID](https://nfid.one/) - Digital identity for signing in to applications privately and securely.
- [NNS Dapp](https://nns.ic0.app/) - Stake ICP in neurons, participate in governance and decentralization sales.
- [Plug](https://plugwallet.ooo/) - Chrome extension and mobile wallet.
- [Stoic](https://www.stoicwallet.com/) - Web wallet.