### Development Environment

- [dfx (DFINITY Canister SDK)](https://internetcomputer.org/docs/building-apps/developer-tools/dfx/) - The primary command-line tool for creating, deploying, and managing dapps on the Internet Computer.
   - Supports local development, deployment, and interaction with canisters.
   - Provides commands for building, deploying, and calling canister methods. 

- [dfxvm](https://internetcomputer.org/docs/building-apps/developer-tools/dfxvm/dfxvm-default) - A version manager for dfx, allowing developers to switch between different dfx versions easily. 

- [Motoko VS Code Extension](https://marketplace.visualstudio.com/items?itemName=dfinity-foundation.vscode-motoko) - Provides syntax highlighting and language support for Motoko in Visual Studio Code

TODO: Strongly consider removing, Vessel is significantly outdated and deprecated in favor of MOPs, which strangely you don't mention here.
- [Vessel Package Manager](https://github.com/dfinity/vessel) - A package manager for the Motoko programming language.

TODO: Consider removing. Don't feel this would be the recommended way, for either hackathon or startup. The best is the "dfx new", ICP Ninja and the Boilerplates we recommend.
- [Create IC App](https://github.com/peterpeterparker/create-ic) -  A command-line tool to quickly create projects. 

- [ICP Ninja](https://internetcomputer.org/docs/building-apps/developer-tools/icp-ninja) - A web-based IDE for developing and deploying ICP smart contracts.

TODO: This tool seems outdated and not recommended, could we replace it for Juno please?
- [Easy ICP](https://easyicp.site/) - A web tool for creating and hosting websites on ICP 

### Testing and Debugging

TODO: on this section:
   - could we remove canistergeek in favor of cycleops (that one should be the recommended one due to expanding features and active maintenance).
   - Could you Add Pocket IC, both Typescript (Pic JS) and Rust libraries / tools.   

- [IC Inspector](https://chromewebstore.google.com/detail/ic-inspector/meaadkenfkhjakkkdapaallimhbdofck) - A tool to decode network responses from the Internet Computer blockchain.

- [Canistergeek](https://cusyh-iyaaa-aaaah-qcpba-cai.raw.ic0.app/) - An open-source tool to track your project canisters' cycles and memory status.

### Deployment and CI/CD

- [GitHub Workflows](https://internetcomputer.org/docs/tutorials/developer-liftoff/level-2/2.5-unit-testing#integration-testing) - Setting up GitHub workflows for automated testing

### Wallet and Identity

TODO: consider to add Oisy and move Quill to last item

- [Quill](https://github.com/dfinity/quill) - A minimalistic ledger and governance toolkit for cold wallets.

- [Internet Identity](https://github.com/dfinity/internet-identity) - The Internet Computer's native authentication system.

- [NFID](https://nfid.one/) - Non-fungible Identity tooling on ICP that provides a more user-friendly and secure authentication experience. 

TODO: it's no longer this github, because Psychadelic moved out and it's funded team taking care of it.
   - The right link should maybe be the docs: https://docs.plugwallet.ooo/
   - The server code is not public, but the client on mobile is: https://github.com/funded-labs/plug-mobile-sdk and an E2E test: https://github.com/funded-labs/plug-e2e
   - Be aware that there is also an NPM Package, but that is deprecated and not needed to connect, since Plug is a Browser Extension.
   
- [Plug Wallet](https://github.com/Psychedelic/plug) - Browser based extension wallet for ICP. 

Check out more over [here](https://internetcomputer.org/tooling)
