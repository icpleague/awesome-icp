[EN](https://github.com/icpleague/awesome-icp) | [中文](https://github.com/icpleague/awesome-icp/blob/main/readme_ch.md)
****
- [Doc](#doc)
- [IDEs](#ides)
- [Deploy](#deploy)
- [CDK&Agent](#cdkagent)
- [Front-end](#front-end)
    - [II authentication](#ii-authentication)
    - [Starter&Template](#startertemplate)
- [Lib](#lib)
    - [Storage](#storage)
    - [Cryptography](#cryptography)
    - [Algorithms](#algorithms)
    - [Log](#log)
    - [Token&NFT](#tokennft)
  - [ICP & Cycles](#icp--cycles)
- [DAPP](#dapp)
    - [Game](#game)
    - [Blog](#blog)
    - [Music](#music)
    - [Kanban](#kanban)
    - [Video](#video)
- [Other](#other)
****

## Doc

* [NnsDao/dfinity-sdk-docs](https://github.com/NnsDao/dfinity-sdk-docs) Dfinity Rust develop doc

* [COS666/Dfinity-Whitepaper-Chinese-Version](https://github.com/COS666/Dfinity-Whitepaper-Chinese-Version) Dfinity Whitepaper ChineseVersion 

* [machenjie/dfinity-study](https://github.com/machenjie/dfinity-study) Dfinity study

* [QiuYeDx/Dfinity_Chinese_Guidelines](https://github.com/QiuYeDx/Dfinity_Chinese_Guidelines) Dfinity chinese guidelines

* [AnubisAwooo/awooo-dfinity](https://github.com/AnubisAwooo/awooo-dfinity) simple guide

* [CodingDay/2022.03.26](https://github.com/rebase-network/CodingDay/tree/main/2022.03.26) 

## IDEs

* [Visual Studio Code](https://code.visualstudio.com/)
  * [Motoko](https://marketplace.visualstudio.com/items?itemName=dfinity-foundation.vscode-motoko) offical motoko plug

* [IntelliJ IDEA Motoko support](https://github.com/ununhexium/idea-motoko-plugin) IntelliJ IDEA plug

* [motoko-playground](https://github.com/dfinity/motoko-playground)  motoko online playground

* [Blocks-Editor/blocks](https://github.com/Blocks-Editor/blocks) An online drag-and-drop smart contract builder.

* [chainide](https://chainide.com/s/createTempProject/dfinity/) A tool to help learn, code, build, and deploy smart contracts and decentralized applications.

## Deploy

* [FleekHQ/IC-Deploy-Action](https://github.com/FleekHQ/IC-Deploy-Action) Github action that wraps dfx commands to deploy canisters to Dfinity on push 

* [aviate-labs/setup-dfx](https://github.com/aviate-labs/setup-dfx)  Set up your GitHub Actions workflow with a specific version of the Internet Computer SDK 

## CDK&Agent

* [ic4j/ic4j-agentJ](https://github.com/ic4j/ic4j-agent) Java Agent

* [rckprtr/cdk-as](https://github.com/rckprtr/cdk-as) AssemblyScript CDK

* [AstroxNetwork/agent_dart](https://github.com/AstroxNetwork/agent_dart) Dart Agent

* [seniorjoinu/candid-kt](https://github.com/seniorjoinu/candid-kt)  Kotlin CDK

* [aviate-labs/agent-go](https://github.com/aviate-labs/agent-go) Golang Agent library

* [rocklabs-io/ic-py](https://github.com/rocklabs-io/ic-py) Python Agent Library

* [demergent-labs/azle](https://github.com/demergent-labs/azle) TypeScript/JavaScript CDK

* [mix-labs/IC-Go](https://github.com/mix-labs/IC-Go) Golang CDK


## Front-end

#### II authentication

* [krpeacock/auth-client-demo](https://github.com/krpeacock/auth-client-demo)  Example demo of how to use https://www.npmjs.com/package/@dfinity/auth-client to make authenticated calls to an IC app

* [InternetIdentityLabs/react-ic-ii-auth](https://github.com/InternetIdentityLabs/react-ic-ii-auth) : React components to use DFINITYs Internet Identity Authentication

* [michielpost/Dfinity.Blazor](https://github.com/michielpost/Dfinity.Blazor) Blazor library to work with Dfinity Internet Computer 

* [gabrielnic/dfinity-react](https://github.com/gabrielnic/dfinity-react) Boilerplate ReactJS/Typescript with authentication to a local II

#### Starter&Template
* React
  * [NnsDAO-tech/NnsDao-Frontend-template-React](https://github.com/NnsDAO-tech/NnsDao-Frontend-template-React) NnsDao-Frontend-template-React

  * [MioQuispe/create-ic-app](https://github.com/MioQuispe/create-ic-app) Use your favourite frontend framework with the Internet Computer 

  * [taylorham/cra-template-dfx](https://github.com/taylorham/cra-template-dfx) A template for frontend development on DFINITY's Internet Computer
  
  * [ORIGYN-SA/todos-react-native-dfinity](https://github.com/ORIGYN-SA/todos-react-native-dfinity) simple react native todo list app powered by dfinity 

  * [rbolog/dfinity_reactJs_reactRouter_babel](https://github.com/rbolog/dfinity_reactJs_reactRouter_babel) A template that includes Dfinity, ReactJS, React-Router. 

  * [ferMartz/ic-firestarter](https://github.com/ferMartz/ic-firestarter)  Modern starter for Internet Computer built with Create IC App + Vite + React + Material UI 

* Vue

  * [nop33/dfinity-vue](https://github.com/nop33/dfinity-vue) : 🌱 Vue.js integration with DFINITY SDK bootstrap webpack project. 

  * [ferMartz/ic-mui](https://github.com/ferMartz/ic-mui) Modern starter for Internet Computer + Material UI + Vite

  * [MioQuispe/create-ic-app](https://github.com/MioQuispe/create-ic-app) Use your favourite frontend framework with the Internet Computer 

* nextjs

  * [Magvin/nextjs-icp](https://github.com/Magvin/nextjs-icp) Next.js Quick BlankUI with Dfinity

  * [warashibe/nextdapp](https://github.com/warashibe/nextdapp) (D)App Development Kit powered by Next.js and Facebook Recoil 

  * [beyond009/nextjs-ic-starter](https://github.com/beyond009/nextjs-ic-starter) Next.js Internet Computer Starter Template 

  * [dappblock/nextjs-ic-starter](https://github.com/dappblock/nextjs-ic-starter) Next.js Internet Computer Starter Template

  * [gbonumore/index-calculator](https://github.com/gbonumore/index-calculator) Starter Nextjs Template for Internet Computer 

* Angular

  * [shawnrmoss/dangular](https://github.com/shawnrmoss/dangular) Dfinity Angular starter 

  * [shawndotey/hello-angular-motoko](https://github.com/shawndotey/hello-angular-motoko) An example of implementing the Internet Computer's motoko project along side Angular. 

* svelte

  * [MioQuispe/create-ic-app](https://github.com/MioQuispe/create-ic-app) Use your favourite frontend framework with the Internet Computer

* vanilla

  * [MioQuispe/create-ic-app](https://github.com/MioQuispe/create-ic-app) Use your favourite frontend framework with the Internet Computer 

## Lib

#### Storage

* [gabrielnic/motoko-cdn](https://github.com/gabrielnic/motoko-cdn) Motoko cdn/storage solution. ie: mini big-map 

* [IC-Drive/ic-drive](https://github.com/IC-Drive/ic-drive) An open-source decentralized storage app built on the internet computer. 

* [sudograph/sudograph](https://github.com/sudograph/sudograph) GraphQL database for the Internet Computer 

* [Di-Box/Bucket](https://github.com/Di-Box/Bucket) Bucket is a storage standard applied to canisters.

* [open-ic/open-storage](https://github.com/open-ic/open-storage) A scalable storage solution built on the Internet Computer.

* [paulyoung/icfs](https://github.com/paulyoung/icfs) Internet Computer File System

#### Cryptography

* [enzoh/motoko-sha](https://github.com/enzoh/motoko-sha) The SHA Package 

#### Algorithms

* [DepartureLabsIC/revo](https://github.com/DepartureLabsIC/revo) L Systems on the IC 

* [enzoh/motoko-qr](https://github.com/enzoh/motoko-qr) The Motoko QR Package 

#### Log

* [ninegua/ic-logger](https://github.com/ninegua/ic-logger) Motoko library to help create an append-only logger actor

#### Token&NFT

* [DepartureLabsIC/non-fungible-token](https://github.com/DepartureLabsIC/non-fungible-token) (DepartureLabsIC) NFT 
* [rocklabs-io/ic-nft](https://github.com/rocklabs-io/ic-nft) (rocklabs-io)Non-fungible token standard for the DFINITY Internet Computer

* [SuddenlyHazel/dfinity_nft](https://github.com/SuddenlyHazel/dfinity_nft) (SuddenlyHazel) NFT

* [Toniq-Labs/extendable-token](https://github.com/Toniq-Labs/extendable-token) (Toniq-Labs)This token standard provides a ERC1155/multi-token-like approach with extensions that can add additional functionality based on the purpose of the token

* [rocklabs-io/ic-token](https://github.com/rocklabs-io/ic-token) DIP20: A fungible token standard for the DFINITY Internet Computer. New repo: https://github.com/Psychedelic/DIP20

* [flyq/motoko_token](https://github.com/flyq/motoko_token) Follow the ERC20

* [Psychedelic/DIP20](https://github.com/Psychedelic/DIP20) DIP20: A fungible token standard for the DFINITY Internet Computer. 

* [rocklabs-io/erc20](https://github.com/rocklabs-io/ic-token/blob/templates/motoko/erc20)ERC20 style token template for the IC

* [rocklabs-io/dtoken](https://github.com/rocklabs-io/dtoken) One-click token issuance app for the DFINITY Internet Computer. 

* [Deland-Labs/dfinity-fungible-token-standard](https://github.com/Deland-Labs/dfinity-fungible-token-standard) Dfinity's fungible token standard. Any PRs and comments are welcome,collaborate with us to build this standard

* [iclighthouse/DRC_standards](https://github.com/iclighthouse/DRC_standards) Dfinity Request for Comments standards

### ICP & Cycles

* [aviate-labs/icp-canister](https://github.com/aviate-labs/icp-canister) A canister that holds ICP 

* [Toniq-Labs/wrapped_cycles](https://github.com/Toniq-Labs/wrapped_cycles) Motoko code for a Wrapped ICP Cycles canister on DFINITY's IC 

* [ninegua/tipjar](https://github.com/ninegua/tipjar) Donate cycles to canisters of your choice.

* [perun-network/perun-icp-canister](https://github.com/perun-network/perun-icp-canister) Perun Payment Channels Canister for the Dfinity Internet Computer 

## DAPP

#### Game

* [jesssekeogh/bonsai_dapp](https://github.com/jesssekeogh/bonsai_dapp) Repository for the Kontribute Internet Computer Dapp 

* [ninegua/reversi](https://github.com/ninegua/reversi) Multiplayer Reversi Game on Internet Computer 

* [NnsDao/ICTexas-UI](https://github.com/NnsDao/ICTexas-UI) Texas Game Web Front 

* [liqMix/DPlay](https://github.com/liqMix/DPlay) A small betting game for the Dfinity Internet Computer Platform 

#### Blog

* [Mulander-J/dfinity-starter](https://github.com/Mulander-J/dfinity-starter) blog demo

* [kristoferlund/ic-wall](https://github.com/kristoferlund/ic-wall) The Wall is a crossover Ethereum/Internet Computer demo app. Use Metamask to login to Internet Computer. Then, write on the wall! 

* [hansl/journey](https://github.com/hansl/journey) An open blog engine written for the Internet Computer. See http://twitch.tv/dfinitydev

#### Music

* [muses-fm/muses](https://github.com/muses-fm/muses) MUSES.FM is a community-owned music promotion platform centered around playlists and built on DFINITY. 

#### Kanban

* [aedile-ic/landing]https://github.com/aedile-ic/landing A project management tool on the Internet Computer made by @esensconsulting

* [krpeacock/ic-vcf-gatsby](https://github.com/krpeacock/ic-vcf-gatsby) Contact card demo app with Internet Computer backend 

#### Video 

* [dfinity/cancan](https://github.com/dfinity/cancan) A scalable video sharing service. 

## Other

* [hyplabs/dfinity-oracle-framework](https://github.com/hyplabs/dfinity-oracle-framework) Dfinity Oracles is a framework for building blockchain oracles for the Internet Computer.

* [spencerbug/motoko_httpstream_test](https://github.com/spencerbug/motoko_httpstream_test) Debugging httpstream with callbacks in dfinity IC 

* [peterpeterparker/icstreaming](https://github.com/peterpeterparker/icstreaming) https://forum.dfinity.org/t/http-request-streaming-callback-does-not-stream-chunks-anymore/11298

* [rdobrik/DfinityAndroidSample](https://github.com/rdobrik/DfinityAndroidSample) Native Android Application calling the IC 

* [seniorjoinu/ic-cron](https://github.com/seniorjoinu/ic-cron) Task scheduler for the Internet Compute


* [BerkeleyBlockchain/dfinity-dao-consulting](https://github.com/BerkeleyBlockchain/dfinity-dao-consulting) dfinity dao consulting

* [RikusWiehahn/internet-computer-web-2-bridge](https://github.com/RikusWiehahn/internet-computer-web-2-bridge)  A simple bridge to allow on-chain dapps on IC to send requests to regular 3rd party APIs. Send requests to the bridge canister, where they are fetched by a Node.js server, processed and results returned. 

* [chmllr/qu](https://github.com/chmllr/qu) A minimalistic governance & ledger toolkit for Internet Computer cold wallets, forked from Quill

* [HassenSaidi/IC_sqlite](https://github.com/HassenSaidi/IC_sqlite) Port of the SQL database engine SQLite to the Internet Computer 
