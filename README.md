# 🛠️ Awesome Education Hub

A curated list of high-quality resources to help any ICP HUB or DevRel teach about building on the Internet Computer Protocol (ICP).

## 📚 Contents

- [Courses](#courses)
- [Templates](#templates)
- [Libraries](#libraries)
- [DevTools](#devtools)
- [Contributing](#contributing)
- [Feature-Specific Implementations](#feature-specific-implementations)

## Courses

*Courses that teach about ICP and it's capabilities, helping developers understand about key features.*

#### Motoko Recommended
- [Motoko Bootcamp](https://nnri3-7qaaa-aaaaj-qa3qa-cai.icp0.io/)
#### Rust Recommended
- [Elna Bootcamp](https://elna-ai.github.io/bootcamp/)
- [Raise In](https://www.risein.com/courses/build-on-internet-computer-with-icp-rust-cdk)
#### Typescript Recommended
- [Dacade - Typescript 101](https://dacade.org/communities/icp/challenges/256f0a1c-5f4f-495f-a1b3-90559ab3c51f)
- [Dacade - Typescript 201](https://dacade.org/communities/icp/challenges/0c140f50-2c47-412b-985c-092c1eece05b)
#### Vibe Coding Recommended
- [PT HUB - Vibe Coding](https://github.com/pt-icp-hub/ICP-Bootcamp-Vibe-Coding-Index)

[See full courses list](https://github.com/ICP-HUBS-DevRels-Syndicate/awesome-education-hub/blob/main/src/courses.md)

## Templates

*Code examples that demonstrate ICP capabilities, helping developers understand and implement key features.*

#### Motoko Recommended
- [Counter](https://github.com/dfinity/examples/tree/master/motoko/counter) - Basic counter demonstrating persistent state in Motoko and stable memory for upgrades. `[backend]`
- [Superheroes CRUD](https://github.com/dfinity/examples/tree/master/motoko/superheroes) - Full-stack example showing how to build a CRUD application with React frontend. `[frontend+backend]` `[react]`
- [Internet Identity Integration](https://github.com/dfinity/examples/tree/master/motoko/internet_identity_integration) - Shows how to integrate Internet Identity for authentication. `[frontend+backend]` `[authentication]`

#### Rust Recommended
- [Counter](https://github.com/dfinity/examples/tree/master/rust/counter) - Basic counter implementation in Rust demonstrating state management. `[backend]`
- [Basic DAO](https://github.com/dfinity/examples/tree/master/rust/basic_dao) - Simple decentralized autonomous organization with proposal and voting mechanisms. `[backend]` `[governance]`
- [Encrypted Notes](https://github.com/dfinity/examples/tree/master/rust/encrypted-notes-dapp) - Example for creating and storing confidential information on IC. `[frontend+backend]` `[encryption]` `[security]`

#### TypeScript Recommended
- [Hello World HTTP Server](https://github.com/demergent-labs/azle/tree/main/examples/experimental/demo/hello_world_http_server) - Basic example demonstrating Azle setup and HTTP server functionality on ICP. `[backend]` `[http]`
- [ckBTC](https://github.com/demergent-labs/azle/tree/main/examples/experimental/demo/ckbtc) - Complete ckBTC implementation with ledger, Internet Identity, KYT, minter, and Bitcoin integration. `[frontend+backend]` `[bitcoin]` `[authentication]` `[token]` `[ckBTC]`

#### Frontend Integration Recommended
- [Vite + React + Motoko template](https://github.com/rvanasa/vite-react-motoko) - Template for Vite + React + Motoko integration. `[frontend]` `[react]` `[motoko]`
- [Vite + SvelteKit + Motoko template](https://github.com/letmejustputthishere/vite-sveltekit-motoko-ii/tree/main) - Template for Vite + SvelteKit + Motoko integration. `[frontend]` `[svelte]` `[motoko]`

[See full templates list](https://github.com/ICP-HUBS-DevRels-Syndicate/awesome-education-hub/blob/main/src/templates.md)

## Libraries

*Reusable modules that support development in various CDKs, languages, and frameworks.*

#### Rust Recommended
- [IC CDK](https://crates.io/crates/ic-cdk) - Core Rust Canister development kit (CDK) for ICP
- [IC CDK Macros](https://crates.io/crates/ic-cdk-macros) - Procedural macros for the Rust CDK
- [IC Stable Structures](https://github.com/dfinity/stable-structures) - Data structures for stable memory in Rust canisters

#### Motoko Recommended
- [Motoko Base Library](https://internetcomputer.org/docs/motoko/main/base/) - Core library for Motoko development
- [Motoko Stable Memory](https://github.com/dfinity/stable-structures) - Data structures for stable memory in Motoko canisters
- [IC Certification](https://github.com/nomeata/ic-certification) - Library for working with certified data in Motoko

#### JavaScript Recommended
- [Agent JS](https://github.com/dfinity/agent-js) - Collection of libraries for building software around the Internet Computer
- [IC JS](https://github.com/dfinity/ic-js) - Library collection for interfacing with the Internet Computer
- [Azle](https://github.com/demergent-labs/azle) - WebAssembly runtime for TypeScript and JavaScript on ICP

[See full libraries list](https://github.com/ICP-HUBS-DevRels-Syndicate/awesome-education-hub/blob/main/src/libraries.md)

## DevTools

*Tools that improve the development experience, including debugging utilities, testing frameworks, and deployment scripts.*

#### Development Environment Recommended
- [dfx (DFINITY Canister SDK)](https://internetcomputer.org/docs/building-apps/developer-tools/dfx/) - Primary command-line tool for creating, deploying, and managing dapps
- [dfxvm](https://internetcomputer.org/docs/building-apps/developer-tools/dfxvm/dfxvm-default) - Version manager for dfx
- [Motoko VS Code Extension](https://marketplace.visualstudio.com/items?itemName=dfinity-foundation.vscode-motoko) - Syntax highlighting and language support for Motoko

#### Testing and Debugging Recommended
- [IC Inspector](https://chromewebstore.google.com/detail/ic-inspector/meaadkenfkhjakkkdapaallimhbdofck) - Tool to decode network responses from the Internet Computer blockchain
- [Pocket IC](https://github.com/dfinity/pocket-ic) - Local testing environment for Internet Computer canisters

#### Wallet and Identity Recommended
- [Internet Identity](https://github.com/dfinity/internet-identity) - The Internet Computer's native authentication system
- [NFID](https://nfid.one/) - Non-fungible Identity tooling on ICP
- [Plug Wallet](https://docs.plugwallet.ooo/) - Browser based extension wallet for ICP

[See full devtools list](https://github.com/ICP-HUBS-DevRels-Syndicate/awesome-education-hub/blob/main/src/devtools.md)

## Contributing

We welcome contributions! Please read our [contributing guidelines](CONTRIBUTING.md) before submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.