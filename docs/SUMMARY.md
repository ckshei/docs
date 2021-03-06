# Table of contents

* [Overview](README.md)
* [Apply for the Beta Program now!](https://nearprotocol.com/beta/)
* [Prerequisites](prerequisites/README.md)
  * [Smart Contract Basics](prerequisites/the_basics.md)
  * [Writing Smart Contracts in Typescript](prerequisites/language-typescript.md)
* [Quick Start](quick-start/README.md)
  * [Creating a NEAR Account](quick-start/create-a-near-account.md)
  * [NEAR Studio IDE](quick-start/near-studio-ide.md)
  * [Local Development](quick-start/local-development.md)
  * [NEAR Project File Structure](quick-start/file-structure.md)
* [Working with Smart Contracts](working-smart-contracts/README.md)
  * [Writing Contracts](working-smart-contracts/writing-contracts.md)
  * [Calling Contracts](working-smart-contracts/calling-contracts.md)
* [Tutorials](tutorials/README.md)
  * [Hello World from scratch](tutorials/hello-world-from-scratch.md)
  * [Zero to Hero: Writing an Oracle](tutorials/zero-to-hero.md)
  * [How to issue your own token \(ERC-20\)](tutorials/token.md)
  * [How to write contracts that talk to each other](tutorials/how-to-write-contracts-that-talk-to-each-other.md)
* [Running a node](running-a-node.md)
* [NEAR Economics + constants](economics-faq.md)
* [Validator FAQ](validator-faq.md)

## API Documentation

* [NEARlib.js](api-documentation/nearlib.js/README.md)
  * ["account"](api-documentation/nearlib.js/_account_/README.md)
    * [Account](api-documentation/nearlib.js/_account_/_account_.account.md)
    * [AccountState](api-documentation/nearlib.js/_account_/_account_.accountstate.md)
  * ["account\_creator"](api-documentation/nearlib.js/_account_creator_/README.md)
    * [AccountCreator](api-documentation/nearlib.js/_account_creator_/_account_creator_.accountcreator.md)
    * [LocalAccountCreator](api-documentation/nearlib.js/_account_creator_/_account_creator_.localaccountcreator.md)
    * [UrlAccountCreator](api-documentation/nearlib.js/_account_creator_/_account_creator_.urlaccountcreator.md)
  * ["connection"](api-documentation/nearlib.js/_connection_/README.md)
    * [Connection](api-documentation/nearlib.js/_connection_/_connection_.connection.md)
  * ["contract"](api-documentation/nearlib.js/_contract_/README.md)
    * [Contract](api-documentation/nearlib.js/_contract_/_contract_.contract.md)
  * ["key\_stores/browser\_local\_storage\_key\_store"](api-documentation/nearlib.js/_key_stores_browser_local_storage_key_store_/README.md)
    * [BrowserLocalStorageKeyStore](api-documentation/nearlib.js/_key_stores_browser_local_storage_key_store_/_key_stores_browser_local_storage_key_store_.browserlocalstoragekeystore.md)
  * ["key\_stores/in\_memory\_key\_store"](api-documentation/nearlib.js/_key_stores_in_memory_key_store_/README.md)
    * [InMemoryKeyStore](api-documentation/nearlib.js/_key_stores_in_memory_key_store_/_key_stores_in_memory_key_store_.inmemorykeystore.md)
  * ["key\_stores/keystore"](api-documentation/nearlib.js/_key_stores_keystore_/README.md)
    * [KeyStore](api-documentation/nearlib.js/_key_stores_keystore_/_key_stores_keystore_.keystore.md)
  * ["key\_stores/merge\_key\_store"](api-documentation/nearlib.js/_key_stores_merge_key_store_/README.md)
    * [MergeKeyStore](api-documentation/nearlib.js/_key_stores_merge_key_store_/_key_stores_merge_key_store_.mergekeystore.md)
  * ["key\_stores/unencrypted\_file\_system\_keystore"](api-documentation/nearlib.js/_key_stores_unencrypted_file_system_keystore_/README.md)
    * [UnencryptedFileSystemKeyStore](api-documentation/nearlib.js/_key_stores_unencrypted_file_system_keystore_/_key_stores_unencrypted_file_system_keystore_.unencryptedfilesystemkeystore.md)
    * [AccountInfo](api-documentation/nearlib.js/_key_stores_unencrypted_file_system_keystore_/_key_stores_unencrypted_file_system_keystore_.accountinfo.md)
  * ["near"](api-documentation/nearlib.js/_near_/README.md)
    * [Near](api-documentation/nearlib.js/_near_/_near_.near.md)
  * ["providers/json-rpc-provider"](api-documentation/nearlib.js/_providers_json_rpc_provider_/README.md)
    * [JsonRpcProvider](api-documentation/nearlib.js/_providers_json_rpc_provider_/_providers_json_rpc_provider_.jsonrpcprovider.md)
  * ["providers/provider"](api-documentation/nearlib.js/_providers_provider_/README.md)
    * [FinalTransactionStatus](api-documentation/nearlib.js/_providers_provider_/finaltransactionstatus.md)
    * [Provider](api-documentation/nearlib.js/_providers_provider_/_providers_provider_.provider.md)
    * [FinalTransactionResult](api-documentation/nearlib.js/_providers_provider_/_providers_provider_.finaltransactionresult.md)
    * [TransactionLog](api-documentation/nearlib.js/_providers_provider_/_providers_provider_.transactionlog.md)
  * ["signer"](api-documentation/nearlib.js/_signer_/README.md)
    * [InMemorySigner](api-documentation/nearlib.js/_signer_/_signer_.inmemorysigner.md)
    * [Signer](api-documentation/nearlib.js/_signer_/_signer_.signer.md)
  * ["transaction"](api-documentation/nearlib.js/_transaction_.md)
  * ["utils/key\_pair"](api-documentation/nearlib.js/_utils_key_pair_/README.md)
    * [KeyPair](api-documentation/nearlib.js/_utils_key_pair_/_utils_key_pair_.keypair.md)
    * [KeyPairEd25519](api-documentation/nearlib.js/_utils_key_pair_/_utils_key_pair_.keypaired25519.md)
    * [Signature](api-documentation/nearlib.js/_utils_key_pair_/_utils_key_pair_.signature.md)
  * ["utils/network"](api-documentation/nearlib.js/_utils_network_/README.md)
    * [Network](api-documentation/nearlib.js/_utils_network_/_utils_network_.network.md)
  * ["utils/serialize"](api-documentation/nearlib.js/_utils_serialize_.md)
  * ["utils/web"](api-documentation/nearlib.js/_utils_web_/README.md)
    * [ConnectionInfo](api-documentation/nearlib.js/_utils_web_/_utils_web_.connectioninfo.md)
  * ["wallet-account"](api-documentation/nearlib.js/_wallet_account_/README.md)
    * [WalletAccount](api-documentation/nearlib.js/_wallet_account_/_wallet_account_.walletaccount.md)
* [RPC](api-documentation/rpc.md)
* [Rust Bindings](api-documentation/rust-bindgen.md)
* [TypeScript Runtime](api-documentation/runtime-ts/README.md)
  * [Modules](api-documentation/runtime-ts/modules/README.md)
    * [Collections](api-documentation/runtime-ts/classes/collections/README.md)
      * [Map](api-documentation/runtime-ts/classes/collections/map.md)
      * [Deque](api-documentation/runtime-ts/classes/collections/deque.md)
      * [Vector](api-documentation/runtime-ts/classes/collections/vector.md)
      * [TopN](api-documentation/runtime-ts/classes/collections/topn.md)
    * [Base64](api-documentation/runtime-ts/modules/base64.md)
    * [Utility module: near](api-documentation/runtime-ts/modules/utility-module-near.md)
  * [Classes](api-documentation/runtime-ts/classes/README.md)
    * [Collections](api-documentation/runtime-ts/classes/collections/README.md)
      * [Map](api-documentation/runtime-ts/classes/collections/map.md)
      * [Deque](api-documentation/runtime-ts/classes/collections/deque.md)
      * [Vector](api-documentation/runtime-ts/classes/collections/vector.md)
      * [TopN](api-documentation/runtime-ts/classes/collections/topn.md)
    * [Context](api-documentation/runtime-ts/classes/context.md)
    * [MapEntry](api-documentation/runtime-ts/classes/mapentry.md)
    * [ContractPromise ContractPromiseResult](api-documentation/runtime-ts/classes/contractpromise-contractpromiseresult.md)
    * [Storage](api-documentation/runtime-ts/classes/storage.md)

## Contribution

* [Contribution Guidelines](contribution/contribution/README.md)
  * [NEARCore](contribution/contribution/nearcore.md)
* [Github](https://github.com/nearprotocol)
* [Discord](https://discordapp.com/invite/gBtUFKR)

## Hackathon

* [Hackathon Startup Guide \(10 min\)](hackathon/hackathon-startup-guide-10-min.md)

