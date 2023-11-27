<img alt="Banner" src="https://github.com/33bits-xyz/.github/blob/main/banner.png?raw=true">


## 33bits.xyz - Post Privately on Farcaster

Zk prove that your FID (Farcaster ID) ≤ 10001 and cast on the [@33bits](https://warpcast.com/33bits) feed without revealing your personal account. This project is built with the intention to provoke open dialogues and explore how the Farcaster community will use or abuse their privacy.

### Cast: [33bits.xyz](https://33bits.xyz/)


### How it works? 

When a user signs in with Warpcast, the 33bits app links their FID with a new signer. To post a cast, the user must prove that their FID is ≤ 10001 through zero-knowledge (zk) proofs. This proof is generated using the user’s new signer. The entire process, including authentication and proof generation, occurs in the user's browser, keeping their FID private. Once the proof is created, it's verified on the app's backend. If the proof is valid, the user's cast is sent through the API to the [@33bits](https://warpcast.com/33bits) account and published on the feed anonymously.

- [Architecture & top-level tech explained:](https://github.com/33bits-xyz/docs) sign in, merkle tree, zk, casting. 
- [ZK & Circuit:](https://github.com/33bits-xyz/app) Current version uses Noir DSL. 

We will add a proper README soon. In the meantime, feel free to reach out to [@fastfourier.eth](https://warpcast.com/fastfourier.eth) and [@kugusha.eth](https://warpcast.com/kugusha.eth). 


33bits.xyz is licensed under the [MIT License](https://github.com/33bits-xyz/app/blob/main/LICENSE).
