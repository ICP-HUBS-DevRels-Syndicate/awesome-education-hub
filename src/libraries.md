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