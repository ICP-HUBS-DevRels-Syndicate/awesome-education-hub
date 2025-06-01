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

#### Beginner Level
- [Hello World HTTP Server](https://github.com/demergent-labs/azle/tree/main/examples/experimental/demo/hello_world_http_server) - Basic example demonstrating Azle setup and HTTP server functionality on ICP. `[backend]` `[http]`

#### Expert Level
- [Basic Bitcoin](https://github.com/demergent-labs/azle/tree/main/examples/experimental/demo/basic_bitcoin) - Implementation of Bitcoin integration showing how to send and receive BTC on ICP. `[backend]` `[bitcoin]` `[chain fusion]`
- [Bitcoin PSBT](https://github.com/demergent-labs/azle/tree/main/examples/experimental/demo/bitcoin_psbt) - Advanced Bitcoin example demonstrating Partially Signed Bitcoin Transactions (PSBT) and SegWit integration. `[backend]` `[bitcoin]` `[chain fusion]` `[segwit]`
- [ckBTC](https://github.com/demergent-labs/azle/tree/main/examples/experimental/demo/ckbtc) - Complete ckBTC implementation with ledger, Internet Identity, KYT, minter, and Bitcoin integration. `[frontend+backend]` `[bitcoin]` `[authentication]` `[token]` `[ckBTC]`

### Frontend Integration Templates

ICP provides frontend canister templates when creating new projects with `dfx new`. These templates include options for SvelteKit, React, Vue, and Vanilla JS frameworks, available in dfx versions 0.17.0 and newer.

Here are some of the community-created templates and examples:

- [Vite + React + Motoko template](https://github.com/rvanasa/vite-react-motoko) - Template for Vite + React + Motoko integration. `[frontend]` `[react]` `[motoko]`
- [Vite + SvelteKit + Motoko template](https://github.com/letmejustputthishere/vite-sveltekit-motoko-ii/tree/main) - Template for Vite + SvelteKit + Motoko integration. `[frontend]` `[svelte]` `[motoko]`
