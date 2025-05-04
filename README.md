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

TODO: Select recommended templates

[See full templates list](https://github.com/ICP-HUBS-DevRels-Syndicate/awesome-education-hub/blob/main/src/templates.md)

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

### JavaScript Libraries: 

- [Agent JS](https://github.com/dfinity/agent-js) - This is a collection of libraries and tools for building software around the Internet Computer in JavaScript. 
It includes several sub-packages:
   - ``@dfinity/agent``: Core library for interacting with the Internet Computer.
   - ``@dfinity/authentication``: Handles authentication with Internet Identity.
   - ``@dfinity/identity``: Manages user identities.
   - ``@dfinity/principal``: Utilities for working with IC principals.
   - ``@dfinity/candid``: JavaScript implementation of the Candid interface description language.
- [IC JS](https://github.com/dfinity/ic-js) - A library collection for interfacing with the Internet Computer. 
It includes several sub-packages:
    - ``nns``: interfacing with the governance canisters of the Network Nervous System (NNS)
    - ``sns``: interacting with a Service Nervous System (SNS) project
    - ``cmc``: interfacing with the cmc canister of the IC
    - ``ledger-icp``: interfacing with the ICP ledger
    - ``ledger-icrc``: interacting with ICRC compatible ledgers
    - ``ckBTC``: interfacing with ckBTC
    - ``ckETH``: interfacing with ckETH
    - ``ic-management``: interfacing with the IC management canister
    - ``utils``: a collection of utilities and constants
    - ``zod-schemas``: a collection of reusable Zod schemas and validators for common data patterns in ICP applications
    - ``nns-proto``: the protobuf source used by nns-js to support hardware wallets
- [IC Websocket JS](https://www.npmjs.com/package/ic-websocket-js) - A library for implementing WebSocket functionality on the Internet Computer. 
- [Azle](https://github.com/demergent-labs/azle) - A WebAssembly runtime for TypeScript and JavaScript on ICP. 

## DevTools

*Tools that improve the development experience, including debugging utilities, testing frameworks, and deployment scripts.*

### Development Environment

- [dfx (DFINITY Canister SDK)](https://internetcomputer.org/docs/building-apps/developer-tools/dfx/) - The primary command-line tool for creating, deploying, and managing dapps on the Internet Computer.
   - Supports local development, deployment, and interaction with canisters.
   - Provides commands for building, deploying, and calling canister methods. 

- [dfxvm](https://internetcomputer.org/docs/building-apps/developer-tools/dfxvm/dfxvm-default) - A version manager for dfx, allowing developers to switch between different dfx versions easily. 

- [Motoko VS Code Extension](https://marketplace.visualstudio.com/items?itemName=dfinity-foundation.vscode-motoko) - Provides syntax highlighting and language support for Motoko in Visual Studio Code

- [Vessel Package Manager](https://github.com/dfinity/vessel) - A package manager for the Motoko programming language.

- [Create IC App](https://github.com/peterpeterparker/create-ic) -  A command-line tool to quickly create projects. 

- [ICP Ninja](https://internetcomputer.org/docs/building-apps/developer-tools/icp-ninja) - A web-based IDE for developing and deploying ICP smart contracts.

- [Easy ICP](https://easyicp.site/) - A web tool for creating and hosting websites on ICP 

### Testing and Debugging

- [IC Inspector](https://chromewebstore.google.com/detail/ic-inspector/meaadkenfkhjakkkdapaallimhbdofck) - A tool to decode network responses from the Internet Computer blockchain.

- [Canistergeek](https://cusyh-iyaaa-aaaah-qcpba-cai.raw.ic0.app/) - An open-source tool to track your project canisters' cycles and memory status.

### Deployment and CI/CD

- [GitHub Workflows](https://internetcomputer.org/docs/tutorials/developer-liftoff/level-2/2.5-unit-testing#integration-testing) - Setting up GitHub workflows for automated testing

### Wallet and Identity

- [Quill](https://github.com/dfinity/quill) - A minimalistic ledger and governance toolkit for cold wallets.

- [Internet Identity](https://github.com/dfinity/internet-identity) - The Internet Computer's native authentication system.

- [NFID](https://nfid.one/) - Non-fungible Identity tooling on ICP that provides a more user-friendly and secure authentication experience. 

- [Plug Wallet](https://github.com/Psychedelic/plug) - Browser based extension wallet for ICP. 

Check out more over [here](https://internetcomputer.org/tooling)

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
