Idea is to run full-stack dapps on chain.

Main things included in the internet computer, ..

Reburse gas model,

We have to preload our contract with 'gas' so that users get to use it.

There are additional features as well. Smart contracts here can sign transactions destined to other blockchains.
Native bitcoin integration is also there, allowing users to tap into bitcoin's liquidity while having smart contracts as the governing logic.

And the smart contracts here can do HTTPS calls... have also seen smart contracts hosted as websites.

Can fetch data from web2 systems or trigger actions.

(Tech behind: Horizontal scaling with subnets
*Rapid evolution with on-chain governance
*Chain key cryptography
* Canister Smart contracts)

Nodes are partitioned into subnets- Each subnet is a replicated state machine, (a blockchain)
Canister SCs are assigned to different subnets.
Canisters can interact with other canisters transparently across subnets.

Chain key cryptography is used allowing scaling of the system and easier verifications.
*Canister Smart contracts*
Contracts are called canisters... they are webAssembly code + data.
They are upgradable, composable, and can run in parallel. We can mention controllers, who can modify the code of the canister.
If we want it to be immutable, we just have to remove all the controllers, and now we have a canister that can't be updated.
Canister SCs are implemented in actor model, hence they can run asynchronously... so in parallel.

Consume cycles to pay for resources.

Won't update as I read/listen line by line. 
Just see this video.
https://youtu.be/nvgzxedJtfE
