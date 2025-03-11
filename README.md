# 🛠️ Awesome ICP Development Resources

A curated list of high-quality repositories for building on the Internet Computer Protocol (ICP).

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

## 📚 Contents

- [Templates](#templates)
- [Libraries](#libraries)
- [DevTools](#devtools)
- [Contributing](#contributing)
- [Feature-Specific Implementations](#feature-specific-implementations)

## Templates

*Code examples that demonstrate ICP capabilities, helping developers understand and implement key features.*

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

- [React Template](https://github.com/dfinity/examples/tree/master/motoko/react-ui) - Template for React integration with canisters. `[frontend]` `[react]`
- [Vue.js Template](https://github.com/dfinity/examples/tree/master/motoko/vue-todos) - Template for Vue.js integration. `[frontend]` `[vue]`
- [Next.js Template](https://github.com/dfinity/ic-nextjs-starter) - Starter for Next.js projects on ICP. `[frontend]` `[nextjs]`
- [Svelte Template](https://github.com/dfinity/examples/tree/master/svelte/svelte-motoko-starter) - Starter for Svelte projects. `[frontend]` `[svelte]`

## Libraries

*Reusable modules that support development in various CDKs, languages, and frameworks.*

### Rust Libraries

- [IC CDK](https://crates.io/crates/ic-cdk) - Core Rust Canister development kit (CDK) for ICP  
- [IC CDK Macros](https://crates.io/crates/ic-cdk-macros) - This library provides procedural macros for the Rust CDK. It defines macros like ``update``, ``query``, and ``import`` that facilitate building operation endpoints and APIs. 
- [IC CDK Timers](https://crates.io/crates/ic-cdk-timers) - This library provides timer functionality for Rust canisters. It offers an API to schedule multiple timers and periodic tasks within a canister.
- [IC Agent](https://github.com/dfinity/agent-rs) - A collection of Rust libraries for building canisters that interact with the IC. It provides functionality to call canister methods, sign messages, and manage identities. 
- [IC Stable Structures](https://github.com/dfinity/stable-structures) - This library provides data structures for use with stable memory in Rust canisters. It offers efficient, upgradeable data structures that persist across canister upgrades. 
- [IC Certified Map](https://github.com/dfinity/cdk-rs/tree/main/library/ic-certified-map) - This library provides certified data structures for use in Rust canisters. It's useful for implementing certified variables and certified HTTP assets. 
- [Serde](https://crates.io/crates/serde) - While not specific to ICP, serde is commonly used in Rust canisters for serialization and deserialization. It's particularly useful when working with Candid types and stable memory.
- [IC Ledger Types](https://github.com/dfinity/cdk-rs/tree/main/library/ic-ledger-types) - This library provides Rust types for interacting with the ICP ledger. It includes definitions for accounts, transactions, and other ledger-related data structures.

### Motoko Libraries

- [Motoko Base Library](https://internetcomputer.org/docs/motoko/main/base/) - his is the core library for Motoko development, providing essential modules and types:
  - It includes modules for common data structures, text processing, time, debugging, and more.
  - Some key modules include:
    - Array, Buffer, Deque, HashMap, List, TrieMap for data structures
Debug for logging and debugging
    - Time for time-related operations
    - Principal for working with IC principals
    - Blob for binary data handling
    - Error for error handling
    - Nat, Int for number operations
- [Motoko Stable Memory](https://github.com/dfinity/stable-structures) - This library provides data structures for use with stable memory in Motoko canisters.
   - It offers efficient, upgradeable data structures that persist across canister upgrades.
- [Motoko Bitcoin](https://github.com/tgalal/motoko-bitcoin) - A Motoko Bitcoin integration library.
   - It provides functionality for working with Bitcoin transactions and addresses on the Internet Computer.
- [IC Certification](https://github.com/nomeata/ic-certification) - A library for working with certified data in Motoko. 
   - It allows canisters to create certified data that can be verified by clients.
- [Motoko Matchers](https://github.com/kritzcreek/motoko-matchers) - A library for writing expressive tests in Motoko.
   - It provides a set of matchers for common testing scenarios.
- [Motoko Inter Tools](https://github.com/NatLabs/Itertools) - A library that provides additional iterator combinators for Motoko.

### JavaScript/TypeScript Libraries

- [Agent-JS](https://github.com/dfinity/agent-js) - JavaScript agent for IC development
- [Azle](https://github.com/demergent-labs/azle) - TypeScript CDK for the Internet Computer
- [IC React Kit](https://github.com/dfinity/ic-react-kit) - React components for IC apps
- [StoicWallet.js](https://github.com/Psychedelic/stoicwallet.js) - JavaScript library for Stoic Wallet integration

### Multiple Language Support

- [Candid](https://github.com/dfinity/candid) - Interface description language supporting multiple programming languages
- [DIP Standards](https://github.com/dfinity/DIPS) - DFINITY Interface Protocol Standards

## DevTools

*Tools that improve the development experience, including debugging utilities, testing frameworks, and deployment scripts.*

### Development Environment

- [DFX CLI](https://github.com/dfinity/sdk) - Command-line tool for developing ICP applications
- [Vessel Package Manager](https://github.com/dfinity/vessel) - Package manager for Motoko
- [IC Repl](https://github.com/chenyan2002/ic-repl) - REPL for interacting with the Internet Computer
- [Motoko Playground](https://github.com/dfinity/motoko-playground) - Web-based development environment
- [Motoko VS Code Extension](https://github.com/dfinity/vscode-motoko) - VS Code support for Motoko

### Testing and Debugging

- [Motoko Test](https://github.com/dfinity/motoko-test) - Testing framework for Motoko
- [Wasmtime Debugger](https://github.com/dfinity/wasmtime-debugger) - Debugger for WebAssembly
- [Candid UI](https://github.com/dfinity/candid-ui) - UI for interacting with canisters
- [IC Inspector](https://github.com/dfinity/ic-inspector) - Tool for inspecting canisters

### Deployment and CI/CD

- [IC Deploy Action](https://github.com/dfinity/ic-deploy-action) - GitHub action for deploying to IC
- [IC Canister Monitor](https://github.com/dfinity/ic-canister-monitor) - Monitoring tool for canisters
- [IC Gitlab CI](https://github.com/dfinity/ic-gitlab-ci) - CI/CD templates for GitLab

### Wallet and Identity

- [Internet Identity](https://github.com/dfinity/internet-identity) - Authentication library for IC apps
- [NFID](https://github.com/nfid) - Non-fungible Identity tooling
- [Plug Wallet](https://github.com/Psychedelic/plug) - Browser extension wallet

## Contributing

We welcome contributions! Please read our [contributing guidelines](CONTRIBUTING.md) before submitting pull requests.

### Requirements for Inclusion

To be listed in the curated collection, repositories must meet the following criteria:

1. Publicly available on GitHub
2. Up-to-date with the latest versions of CDKs, SDKs, and relevant frameworks
3. Include a README.md with clear instructions on setup, dependencies, and usage
4. Directly related to ICP development, showcasing how to interact with its ecosystem

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

⭐️ If you find this resource helpful, please consider giving it a star! 