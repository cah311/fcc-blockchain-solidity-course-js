# fcc-blockchain-solidity-course-js

# Web3, Full Stack Solidity, Smart Contract & Blockchain - Beginner to Expert ULTIMATE Course | Javascript Edition

<br/>
<p align="center">
<a href="https://www.youtube.com/watch?v=gyMwXuJrbJQ" target="_blank">
<img src="./img/blockchain1.png" width="500" alt="Solidity, Blockchain, and Smart Contract Course – Beginner to Expert Javascript Tutorial">
</a>
</p>
<br/>

Welcome to the repository for the Ultimate Web3, Full Stack Solidity, and Smart Contract - Beginner to Expert Full Course | Javascript Edition FreeCodeCamp Course!

# Link to video: https://www.youtube.com/watch?v=gyMwXuJrbJQ

All code references have both a javascript and a typescript edition.

Recommended Testnet: Sepolia

*We have updated the repos to work with Sepolia due to Rinkeby and Kovan being sunset, and Goerli being a disaster. Let us know if any of the changes break stuff!*

# [Testnet Faucets](https://faucets.chain.link)
Main Faucet:<a href="https://faucets.chain.link" target="_blank"> https://faucets.chain.link</a>
Backup Faucet:<a href="https://sepoliafaucet.com/" target="_blank"> https://sepoliafaucet.com/</a>

> ⚠️ All code associated with this course is for demo purposes only. They have not been audited and should not be considered production ready. Please use at your own risk. 

# Resources For This Course

### Questions

-   [Github Discussions](https://github.com/smartcontractkit/full-blockchain-solidity-course-js/discussions)
    -   Ask questions and chat about the course here!
-   [Stack Exchange Ethereum](https://ethereum.stackexchange.com/)
    -   Great place for asking technical questions about Ethereum
-   [StackOverflow](https://stackoverflow.com/)
    -   Great place for asking technical questions overall


# Table of Contents

<details>
<summary>Resources</summary>
<ol>
<li><a href="#testnet-faucets">Testnet Faucets</a></li>
<li><a href="#resources-for-this-course">Resources For This Course</a><ul>
<li><a href="#questions">Questions</a></li>
</ul>
</li>
<li><a href="#table-of-contents">Table of Contents</a></li>
</ol>
</details>
<details>
<summary> <a href="#lesson-0-the-edge-of-the-rabbit-hole">Lesson 0: The Edge of the Rabbit Hole</a></summary>
<ol>
  <li>
  <a href="#welcome-to-the-course">Welcome to the course! </a>
  </li>
  <li>
  <a href="#best-practices">Best Practices </a>
  </li>
</ol>
</details>
<details>
<summary> <a href="#lesson-1-blockchain-basics"> Lesson 1: Blockchain Basics </a> </summary>
<ol>
<li>
<a href="#what-is-a-blockchain-what-does-a-blockchain-do">What is a Blockchain? What does a blockchain do?</a>
</li>
<li><a href="#the-purpose-of-smart-contracts">The Purpose Of Smart Contracts</a></li>
<li><a href="#other-blockchain-benefits">Other Blockchain Benefits</a></li>
<li><a href="#what-have-smart-contracts-done-so-far">What have Smart Contracts done so far?</a></li>
<li><a href="#making-your-first-transaction">Making Your First Transaction</a></li>
<li><a href="#gas-i-introduction-to-gas">Gas I: Introduction to Gas</a></li>
<li><a href="#how-do-blockchains-work">How Do Blockchains Work?</a></li>
<li><a href="#signing-transactions">Signing Transactions</a></li>
<li><a href="#gas-ii">Gas II</a></li>
<li><a href="#high-level-blockchain-fundamentals">High-Level Blockchain Fundamentals</a></li>
</ol>
</details>
<details>
<summary><a href="#lesson-2-welcome-to-remix-simple-storage">Lesson 2: Welcome to Remix! Simple Storage</a></summary>
<ol>
<li><a href="#introduction">Introduction</a></li>
<li><a href="#setting-up-your-first-contract">Setting Up Your First Contract</a></li>
<li><a href="#basic-solidity-types">Basic Solidity: Types</a></li>
<li><a href="#basic-solidity-functions">Basic Solidity: Functions</a></li>
<li><a href="#basic-solidity-arrays--structs">Basic Solidity: Arrays &amp; Structs</a></li>
<li><a href="#basic-solidity-compiler-errors-and-warnings">Basic Solidity: Compiler Errors and Warnings</a></li>
<li><a href="#memory-storage-calldata-intro">Memory, Storage, Calldata (Intro)</a></li>
<li><a href="#mappings">Mappings</a></li>
<li><a href="#deploying-your-first-contract">Deploying your First Contract</a></li>
<li><a href="#the-evm--a-recap-of-lesson-2">The EVM &amp; A Recap of Lesson 2</a></li>
</ol>
</details>
<details>
<summary><a href="#lesson-3-remix-storage-factory">Lesson 3: Remix Storage Factory</a></summary>
<ol>
<li><a href="#introduction-1">Introduction</a></li>
<li><a href="#basic-solidity-importing-contracts-into-other-contracts">Basic Solidity: Importing Contracts into other Contracts</a></li>
<li><a href="#basic-solidity-interacting-with-other-contracts">Basic Solidity: Interacting with other Contracts</a></li>
<li><a href="#basic-solidity-inheritance--overrides">Basic Solidity: Inheritance &amp; Overrides</a></li>
<li><a href="#lesson-3-recap">Lesson 3 Recap</a></li>
</ol>
</details>
<details>
<summary><a href="#lesson-4-remix-fund-me">Lesson 4: Remix Fund Me</a></summary>
<ol>
<li><a href="#introduction-2">Introduction</a></li>
<li><a href="#sending-eth-through-a-function--reverts">Sending ETH Through a Function &amp; Reverts</a></li>
<li><a href="#chainlink--oracles">Chainlink &amp; Oracles</a></li>
<li><a href="#review-of-sending-eth-and-working-with-chainlink">Review of Sending ETH and working with Chainlink</a></li>
<li><a href="#interfaces--price-feeds">Interfaces &amp; Price Feeds</a></li>
<li><a href="#importing-from-github--npm">Importing from GitHub &amp; NPM</a></li>
<li><a href="#floating-point-math-in-solidtiy">Floating Point Math in Solidity</a></li>
<li><a href="#basic-solidity-arrays--structs-ii">Basic Solidity: Arrays &amp; Structs II</a></li>
<li><a href="#review-of-interfacs-importing-from-github--math-in-solidity">Review of Interfacs, Importing from GitHub, &amp; Math in Solidity</a></li>
<li><a href="#libraries">Libraries</a></li>
<li><a href="#safemath-overflow-checking-and-the-unchecked-keywork">SafeMath, Overflow Checking, and the &quot;unchecked&quot; keywork</a></li>
<li><a href="#basic-solidity-for-loop">Basic Solidity: For Loop</a></li>
<li><a href="#basic-solidity-resetting-an-array">Basic Solidity: Resetting an Array</a></li>
<li><a href="#sending-eth-from-a-contract">Sending ETH from a Contract</a></li>
<li><a href="#basic-solidity-constructor">Basic Solidity: Constructor</a></li>
<li><a href="#basic-solidity-modifiers">Basic Solidity: Modifiers</a></li>
<li><a href="#testnet-demo">Testnet Demo</a></li>
<li><a href="#advanced-solidity">Advanced Solidity</a><ul>
<li><a href="#immutable--constant">Immutable &amp; Constant</a></li>
<li><a href="#custom-errors">Custom Errors</a></li>
<li><a href="#receive--fallback-functions">Receive &amp; Fallback Functions</a></li>
<li><a href="#lesson-4-recap">Lesson 4 Recap</a></li>
</ol>
</details>
<details>
<summary><a href="#lesson-5-ethersjs-simple-storage">Lesson 5: Ethers.js Simple Storage</a></summary>
<ol>
<li><a href="#effective-debugging-strategies--getting-help">Effective Debugging Strategies &amp; Getting Help</a><ul>
<li><a href="#how-to-debug-anything-video">How to Debug Anything Video</a></li>
</ul>
</li>
<li><a href="#installation--setup">Installation &amp; Setup</a><ul>
<li><a href="#mac--linux-setup">Mac &amp; Linux Setup</a></li>
<li><a href="#windows-setup">Windows Setup</a></li>
<li><a href="#gitpod">Gitpod</a></li>
</ul>
</li>
<li><a href="#local-development-introduction">Local Development Introduction</a><ul>
<li><a href="#optional-javascript-crash-courses">Optional Javascript Crash Courses</a></li>
</ul>
</li>
<li><a href="#tiny-javascript-refresher">Tiny Javascript Refresher</a></li>
<li><a href="#asynchronous-programming-in-javascript">Asynchronous Programming in Javascript</a></li>
<li><a href="#compiling-our-solidity">Compiling our Solidity</a></li>
<li><a href="#ganache--networks">Ganache &amp; Networks</a></li>
<li><a href="#introduction-to-ethersjs">Introduction to Ethers.js</a><ul>
<li><a href="#a-note-on-the-await-keyword">A Note on the await Keyword</a></li>
</ul>
</li>
<li><a href="#adding-transaction-overrides">Adding Transaction Overrides</a></li>
<li><a href="#transaction-receipts">Transaction Receipts</a></li>
<li><a href="#sending-a-raw-transaction-in-ethersjs">Sending a &quot;raw&quot; Transaction in Ethersjs</a></li>
<li><a href="#interacting-with-contracts-in-ethersjs">Interacting with Contracts in Ethersjs</a></li>
<li><a href="#environment-variables">Environment Variables</a></li>
<li><a href="#better-private-key-management">Better Private Key Management</a></li>
<li><a href="#optional-prettier-formatting">Optional Prettier Formatting</a></li>
<li><a href="#deploying-to-a-testnet-or-a-mainnet">Deploying to a Testnet or a Mainnet</a></li>
<li><a href="#verifying-on-block-explorers-from-the-ui">Verifying on Block Explorers from the UI</a></li>
<li><a href="#alchemy-dashboard--the-mempool">Alchemy Dashboard &amp; The Mempool</a></li>
<li><a href="#lesson-5-recap">Lesson 5 Recap</a><ul>
<li><a href="#typescript-ethers-simple-storage">Typescript Ethers Simple Storage</a></li>
</ul>
</li>
</ol>
</details>
<details>
<summary><a href="#lesson-6-hardhat-simple-storage">Lesson 6: Hardhat Simple Storage</a></summary>
<ol>
<li><a href="#introduction-3">Introduction</a></li>
<li><a href="#hardhat-setup">Hardhat Setup</a><ul>
<li><a href="#troubleshooting-hardaht-setup">Troubleshooting Hardaht Setup</a></li>
</ul>
</li>
<li><a href="#hardhat-setup-continued">Hardhat Setup Continued</a></li>
<li><a href="#deploying-simplestorage-from-hardhat">Deploying SimpleStorage from Hardhat</a></li>
<li><a href="#networks-in-hardhat">Networks in Hardhat</a></li>
<li><a href="#programatic-verification">Programatic Verification</a></li>
<li><a href="#interacting-with-contracts-in-hardhat">Interacting with Contracts in Hardhat</a></li>
<li><a href="#artifacts-troubleshooting">Artifacts Troubleshooting</a></li>
<li><a href="#custom-hardhat-tasks">Custom Hardhat Tasks</a></li>
<li><a href="#hardhat-localhost-node">Hardhat Localhost Node</a></li>
<li><a href="#the-hardhat-console">The Hardhat Console</a></li>
<li><a href="#hardhat-tests">Hardhat Tests</a></li>
<li><a href="#hardhat-gas-reporter">Hardhat Gas Reporter</a></li>
<li><a href="#solidity-coverage">Solidity Coverage</a></li>
<li><a href="#hardhat-waffle">Hardhat Waffle</a></li>
<li><a href="#lesson-6-recap">Lesson 6 Recap</a><ul>
<li><a href="#typescript-hardhat-simple-storage">Typescript Hardhat Simple Storage</a></li>
</ul>
</li>
</ol>
</details>
<details>
<summary><a href="#lesson-7-hardhat-fund-me">Lesson 7: Hardhat Fund Me</a></summary>
<ol>
<li><a href="#introduction-4">Introduction</a></li>
<li><a href="#hardhat-setup---fund-me">Hardhat Setup - Fund Me</a></li>
<li><a href="#linting">Linting</a></li>
<li><a href="#hardhat-setup---fund-me---continued">Hardhat Setup - Fund Me - Continued</a></li>
<li><a href="#importing-from-npm">Importing from NPM</a></li>
<li><a href="#hardhat-deploy">Hardhat Deploy</a></li>
<li><a href="#mocking">Mocking</a></li>
<li><a href="#utils-folder">Utils Folder</a></li>
<li><a href="#testnet-demo---hardhat-fund-me">Testnet Demo - Hardhat Fund Me</a></li>
<li><a href="#solidity-style-guide">Solidity Style Guide</a></li>
<li><a href="#testing-fund-me">Testing Fund Me</a></li>
<li><a href="#breakpoints--debugging">Breakpoints &amp; Debugging</a></li>
<li><a href="#gas-iii">Gas III:</a></li>
<li><a href="#consolelog--debugging">console.log &amp; Debugging</a></li>
<li><a href="#testing-fund-me-ii">Testing Fund Me II</a></li>
<li><a href="#storage-in-solidity">Storage in Solidity</a></li>
<li><a href="#gas-optimizations-using-storage-knowledge">Gas Optimizations using Storage Knowledge</a></li>
<li><a href="#solidity-chainlink-style-guide">Solidity Chainlink Style Guide</a></li>
<li><a href="#storage-review">Storage Review</a></li>
<li><a href="#staging-tests">Staging Tests</a></li>
<li><a href="#running-scripts-on-a-local-node">Running Scripts on a Local Node</a></li>
<li><a href="#adding-scripts-to-your-packagejson">Adding Scripts to your package.json</a></li>
<li><a href="#pushing-to-github">Pushing to GitHub</a></li>
<li><a href="#-tweet-me-add-your-repo-in">🐸🐦 Tweet Me (add your repo in)!</a></li>
</ol>
</details>
<details>
<summary><a href="#lesson-8-html--javascript-fund-me-full-stack--front-end">Lesson 8: HTML / Javascript Fund Me (Full Stack / Front End)</a></summary>
<ol>
<li><a href="#introduction-5">Introduction</a></li>
<li><a href="#how-websites-work-with-web3-wallets">How Websites work with Web3 Wallets</a></li>
<li><a href="#html-setup">HTML Setup</a></li>
<li><a href="#connecting-html-to-metamask">Connecting HTML to Metamask</a></li>
<li><a href="#javascript-in-its-own-file">Javascript in it&#39;s own file</a></li>
<li><a href="#es6-vs-nodejs">ES6 vs Nodejs</a></li>
<li><a href="#sending-a-transaction-from-a-website">Sending a transaction from a Website</a></li>
<li><a href="#resetting-an-account-in-metamask">Resetting an Account in Metamask</a></li>
<li><a href="#listening-for-events-and-completed-transactions">Listening for Events and Completed Transactions</a></li>
<li><a href="#input-forms">Input Forms</a></li>
<li><a href="#reading-from-the-blockchain">Reading from the Blockchain</a></li>
<li><a href="#withdraw-function">Withdraw Function</a></li>
<li><a href="#lesson-8-recap">Lesson 8 Recap</a><ul>
<li><a href="#optional-links">Optional Links</a></li>
</ul>
</li>
</ol>
</details>
<details>
<summary><a href="#lesson-9-hardhat-smart-contract-lottery">Lesson 9: Hardhat Smart Contract Lottery</a></summary>
<ol>
<li><a href="#introduction-6">Introduction</a></li>
<li><a href="#hardhat-setup---smart-contract-lottery">Hardhat Setup - Smart Contract Lottery</a></li>
<li><a href="#rafflesol-setup">Raffle.sol Setup</a></li>
<li><a href="#introduction-to-events">Introduction to Events</a></li>
<li><a href="#events-in-rafflesol">Events in Raffle.sol</a></li>
<li><a href="#introduction-to-chainlink-vrf">Introduction to Chainlink VRF</a><ul>
<li><a href="#sub-lesson-chainlink-vrf">Sub-Lesson: Chainlink VRF</a></li>
</ul>
</li>
<li><a href="#implementing-chainlink-vrf---introduction">Implementing Chainlink VRF - Introduction</a><ul>
<li><a href="#hardhat-shorthand">Hardhat Shorthand</a></li>
</ul>
</li>
<li><a href="#implementing-chainlink-vrf---the-request">Implementing Chainlink VRF - The Request</a></li>
<li><a href="#implementing-chainlink-vrf---the-fulfill">Implementing Chainlink VRF - The FulFill</a><ul>
<li><a href="#modulo">Modulo</a></li>
</ul>
</li>
<li><a href="#introduction-to-chainlink-keepers">Introduction to Chainlink Keepers</a></li>
<li><a href="#implementing-chainlink-keepers---checkupkeep">Implementing Chainlink Keepers - checkUpkeep</a><ul>
<li><a href="#enums">Enums</a></li>
</ul>
</li>
<li><a href="#implementing-chainlink-keepers---checkupkeep-continued">Implementing Chainlink Keepers - checkUpkeep continued</a></li>
<li><a href="#implementing-chainlink-keepers---performupkeep">Implementing Chainlink Keepers - performUpkeep</a></li>
<li><a href="#code-cleanup">Code Cleanup</a></li>
<li><a href="#deploying-rafflesol">Deploying Raffle.sol</a><ul>
<li><a href="#mock-chainlink-vrf-coordinator">Mock Chainlink VRF Coordinator</a></li>
<li><a href="#continued">Continued</a></li>
</ul>
</li>
<li><a href="#rafflesol-unit-tests">Raffle.sol Unit Tests</a><ul>
<li><a href="#testing-events--chai-matchers">Testing Events &amp; Chai Matchers</a></li>
<li><a href="#continued-i">Continued I</a></li>
</ul>
</li>
<li><a href="#hardhat-methods--time-travel">Hardhat Methods &amp; Time Travel</a><ul>
<li><a href="#continued-ii">Continued II</a></li>
</ul>
</li>
<li><a href="#callstatic">Callstatic</a><ul>
<li><a href="#continued-iii">Continued III</a></li>
<li><a href="#massive-promise-test">Massive Promise Test</a></li>
<li><a href="#continued-iv">Continued IV</a></li>
</ul>
</li>
<li><a href="#rafflesol-staging-tests">Raffle.sol Staging Tests</a></li>
<li><a href="#testing-on-a-testnet">Testing on a Testnet</a><ul>
<li><a href="#recommended-link-amounts-for-sepolia-staging-test">Recommended LINK amounts for Sepolia Staging Test:</a></li>
</ul>
</li>
<li><a href="#conclusion">Conclusion</a></li>
<li><a href="#typescript---smart-contract-lottery">Typescript - Smart Contract Lottery</a></li>
</ol>
</details>
<details>
<summary><a href="#lesson-10-nextjs-smart-contract-lottery-full-stack--front-end">Lesson 10: NextJS Smart Contract Lottery (Full Stack / Front End)</a></summary>
<ol>
<li><a href="#introduction-7">Introduction</a><ul>
<li><a href="#optional-sub-lesson-full-stack-development--other-libraries">Optional Sub-Lesson: Full Stack Development &amp; Other Libraries</a></li>
</ul>
</li>
<li><a href="#nextjs-setup">NextJS Setup</a></li>
<li><a href="#manual-header-i">Manual Header I</a><ul>
<li><a href="#react-hooks">React Hooks</a></li>
</ul>
</li>
<li><a href="#manual-header-ii">Manual Header II</a></li>
<li><a href="#useeffect-hook">useEffect Hook</a></li>
<li><a href="#local-storage">Local Storage</a></li>
<li><a href="#isweb3enabledloading">isWeb3EnabledLoading</a></li>
<li><a href="#web3uikit">web3uikit</a></li>
<li><a href="#introduction-to-calling-functions-in-nextjs">Introduction to Calling Functions in Nextjs</a><ul>
<li><a href="#automatic-constant-value-ui-updater">Automatic Constant Value UI Updater</a></li>
<li><a href="#runcontractfunction">runContractFunction</a></li>
</ul>
</li>
<li><a href="#usestate">useState</a></li>
<li><a href="#calling-functions-in-nextjs">Calling Functions in NextJS</a></li>
<li><a href="#usenotification">useNotification</a></li>
<li><a href="#reading--displaying-contract-data">Reading &amp; Displaying Contract Data</a></li>
<li><a href="#a-note-about-onsuccess">A Note about <code>onSuccess</code></a></li>
<li><a href="#a-challenge-to-you">A Challenge to You</a></li>
<li><a href="#tailwind--styling">Tailwind &amp; Styling</a></li>
<li><a href="#introduction-to-hosting-your-site">Introduction to Hosting your Site</a></li>
<li><a href="#ipfs">IPFS</a></li>
<li><a href="#hosting-on-ipfs">Hosting on IPFS</a></li>
<li><a href="#hosting-on-ipfs--filecoin-using-fleek">Hosting on IPFS &amp; Filecoin using Fleek</a></li>
<li><a href="#filecoin-overview">Filecoin Overview</a></li>
<li><a href="#lesson-10-recap">Lesson 10 Recap</a></li>
</ol>
</details>
<details>
<summary><a href="#lesson-11-hardhat-starter-kit">Lesson 11: Hardhat Starter Kit</a></summary>
<ol>
</details>
<details>
<summary><a href="#lesson-12-hardhat-erc20s">Lesson 12: Hardhat ERC20s</a></summary>
<ol>
<li><a href="#what-is-an-erc-what-is-an-eip">What is an ERC? What is an EIP?</a></li>
<li><a href="#what-is-an-erc20">What is an ERC20?</a></li>
<li><a href="#manually-creating-an-erc20-token">Manually Creating an ERC20 Token</a></li>
<li><a href="#creating-an-erc20-token-with-openzeppelin">Creating an ERC20 Token with Openzeppelin</a></li>
<li><a href="#lesson-12-recap">Lesson 12 Recap</a></li>
</ul>
</ol>
</details>
<details>
<summary><a href="#lesson-13-hardhat-defi--aave">Lesson 13: Hardhat DeFi &amp; Aave</a></summary>
<ol>
<li><a href="#what-is-defi">What is DeFi?</a></li>
<li><a href="#what-is-aave">What is Aave?</a></li>
<li><a href="#programatic-borrowing--lending">Programatic Borrowing &amp; Lending</a></li>
<li><a href="#weth---wrapped-eth">WETH - Wrapped ETH</a></li>
<li><a href="#forking-mainnet">Forking Mainnet</a></li>
<li><a href="#depositing-into-aave">Depositing into Aave</a></li>
<li><a href="#borrowing-from-aave">Borrowing from Aave</a></li>
<li><a href="#repaying-with-aave">Repaying with Aave</a></li>
<li><a href="#visualizing-the-transactions">Visualizing the Transactions</a></li>
<li><a href="#lesson-13-recap">Lesson 13 Recap</a></li>
<li><a href="#happy-bow-tie-friday-with-austin-griffith">Happy Bow-Tie Friday with Austin Griffith</a><ul>
<li><a href="#more-defi-learnings">More DeFi Learnings:</a></li>
</ul>
</li>
</ul>
</ol>
</details>
<details>
<summary><a href="#lesson-14-hardhat-nfts-everything-you-need-to-know-about-nfts">Lesson 14: Hardhat NFTs (EVERYTHING you need to know about NFTs)</a></summary>
<ol>
<li><a href="#what-is-an-nft">What is an NFT?</a></li>
<li><a href="#code-overview">Code Overview</a></li>
<li><a href="#hardhat-setup-1">Hardhat Setup</a></li>
<li><a href="#basic-nft">Basic NFT</a><ul>
<li><a href="#write-tests">Write Tests</a></li>
</ul>
</li>
<li><a href="#random-ipfs-nft">Random IPFS NFT</a><ul>
<li><a href="#mapping-chainlink-vrf-requests">Mapping Chainlink VRF Requests</a></li>
<li><a href="#creating-rare-nfts">Creating Rare NFTs</a></li>
<li><a href="#setting-the-nft-image">Setting the NFT Image</a></li>
<li><a href="#setting-an-nft-mint-price">Setting an NFT Mint Price</a></li>
<li><a href="#deploy-script">Deploy Script</a></li>
<li><a href="#uploading-token-images-with-pinata">Uploading Token Images with Pinata</a></li>
<li><a href="#uploading-token-uris-metadata-with-pinata">Uploading Token URIs (metadata) with Pinata</a></li>
<li><a href="#deploying">Deploying</a></li>
<li><a href="#tests">Tests</a></li>
</ul>
</li>
<li><a href="#dynamic-svg-on-chain-nft">Dynamic SVG On-Chain NFT</a><ul>
<li><a href="#what-is-an-svg">What is an SVG?</a></li>
<li><a href="#initial-code">Initial Code</a></li>
<li><a href="#base64-encoding">Base64 Encoding</a></li>
</ul>
</li>
<li><a href="#advanced-evm-opcodes-encoding-and-calling">Advanced: EVM Opcodes, Encoding, and Calling</a><ul>
<li><a href="#abiencode--abiencodepacked">abi.encode &amp; abi.encodePacked</a></li>
<li><a href="#introduction-to-encoding-function-calls-directly">Introduction to Encoding Function Calls Directly</a></li>
<li><a href="#introduction-to-encoding-function-calls-recap">Introduction to Encoding Function Calls Recap</a></li>
<li><a href="#encoding-function-calls-directly">Encoding Function Calls Directly</a></li>
<li><a href="#creating-an-nft-tokenuri-on-chain">Creating an NFT TokenURI on-Chain</a></li>
<li><a href="#making-the-nft-dynamic">Making the NFT Dynamic</a></li>
<li><a href="#deploy-script-1">Deploy Script</a></li>
</ul>
</li>
<li><a href="#deploying-the-nfts-to-a-testnet">Deploying the NFTs to a Testnet</a></li>
<li><a href="#lesson-14-recap">Lesson 14 Recap</a></li>
</ul>
</ol>
</details>
<details>
<summary><a href="#lesson-15-nextjs-nft-marketplace-if-you-finish-this-lesson-you-are-a-full-stack-monster">Lesson 15: NextJS NFT Marketplace (If you finish this lesson, you are a full-stack MONSTER!)</a></summary>
<ol>
<li><a href="#introduction-8">Introduction</a></li>
<li><a href="#part-i-nft-marketplace-contracts">Part I: NFT Marketplace Contracts</a><ul>
<li><a href="#hardhat-setup-2">Hardhat Setup</a></li>
<li><a href="#nftmarketplacesol">NftMarketplace.sol</a></li>
</ul>
</li>
<li><a href="#reentrancy">Reentrancy</a><ul>
<li><a href="#nftmarketplacesol---continued">NftMarketplace.sol - Continued</a></li>
<li><a href="#nftmarketplacesol---deploy-script">NftMarketplace.sol - Deploy Script</a></li>
<li><a href="#nftmarketplacesol---tests">NftMarketplace.sol - Tests</a></li>
<li><a href="#nftmarketplacesol---scripts">NftMarketplace.sol - Scripts</a></li>
</ul>
</li>
<li><a href="#part-ii-moralis-front-end">Part II: Moralis Front End</a><ul>
<li><a href="#what-is-moralis">What is Moralis?</a></li>
<li><a href="#nextjs-setup-1">NextJS Setup</a></li>
<li><a href="#adding-tailwind">Adding Tailwind</a></li>
<li><a href="#introduction-to-indexing-in-web3">Introduction to Indexing in Web3</a></li>
<li><a href="#connecting-moralis-to-our-local-hardhat-node">Connecting Moralis to our Local Hardhat Node</a></li>
<li><a href="#moralis-event-sync">Moralis Event Sync</a><ul>
<li><a href="#reset-local-chain">Reset Local Chain</a></li>
</ul>
</li>
<li><a href="#moralis-cloud-functions">Moralis Cloud Functions</a><ul>
<li><a href="#practice-resetting-the-local-chain">Practice Resetting the Local Chain</a></li>
</ul>
</li>
<li><a href="#moralis-cloud-functions-ii">Moralis Cloud Functions II</a></li>
<li><a href="#querying-the-moralis-database">Querying the Moralis Database</a></li>
<li><a href="#rendering-the-nft-images">Rendering the NFT Images</a></li>
<li><a href="#update-listing-modal">Update Listing Modal</a></li>
<li><a href="#buy-nft-listing">Buy NFT Listing</a></li>
<li><a href="#listing-nfts-for-sale">Listing NFTs for Sale</a></li>
</ul>
</li>
<li><a href="#part-iii-thegraph-front-end">Part III: TheGraph Front End</a><ul>
<li><a href="#introduction-9">Introduction</a></li>
<li><a href="#what-is-the-graph">What is The Graph?</a></li>
<li><a href="#building-a-subgraph">Building a Subgraph</a></li>
<li><a href="#deploying-our-subgraph">Deploying our Subgraph</a></li>
<li><a href="#reading-from-the-graph">Reading from The Graph</a></li>
<li><a href="#hosting-our-dapp">Hosting our Dapp</a></li>
</ul>
</li>
</ul>
</ol>
</details>
<details>
<summary><a href="#lesson-16-hardhat-upgrades">Lesson 16: Hardhat Upgrades</a></summary>
<ol>
<li><a href="#upgradeable-smart-contracts-overview">Upgradeable Smart Contracts Overview</a></li>
<li><a href="#types-of-upgrades">Types of Upgrades</a></li>
<li><a href="#delegatecall">Delegatecall</a></li>
<li><a href="#small-proxy-example">Small Proxy Example</a></li>
<li><a href="#transparent-upgradeable-smart-contract">Transparent Upgradeable Smart Contract</a></li>
</ul>
</ol>
</details>
<details>
<summary><a href="#lesson-17-hardhat-daos">Lesson 17: Hardhat DAOs</a></summary>
<ol>
<li><a href="#introduction-10">Introduction</a></li>
<li><a href="#what-is-a-dao">What is a DAO?</a></li>
<li><a href="#how-to-build-a-dao">How to build a DAO</a></li>
</ol>
</details>
<details>
<summary><a href="#lesson-18-security--auditing">Lesson 18: Security &amp; Auditing</a></summary>
<ol>
<li><a href="#introduction-11">Introduction</a></li>
<li><a href="#slither">Slither</a></li>
<li><a href="#fuzzing-and-eth-security-toolbox">Fuzzing and Eth Security Toolbox</a></li>
<li><a href="#closing-thoughts">Closing Thoughts</a></li>
</ol>
</details>
