# Three-Pillars-Project
“Three Pillars Project” for better validator operation of Tendermint/Cosmos-SDK based blockchains

--------------------

*Status*

This grant proposal is to request a grant from ICF to design and implement below 3 ADRs on Tendermint and Cosmos-SDK

--------------------

*Summary*

- title : “Three Pillars Project” for better validator operation of Tendermint/Cosmos-SDK based blockchains 
- grant proposer(validator operator) : B-Harvest(cosmosvaloper10e4vsut6suau8tk9m6dnrm0slgd6npe3jx5xpv)
- grant recipient address : cosmos10e4vsut6suau8tk9m6dnrm0slgd6npe3hjqndl
- grant proposer(keybase identity) : BFAAF68BD473D23958D452708957C5091FBF4192
- contact : telegram @dlguddus, email contact@bharvest.io
- proposed work : 3 projects(2 on Tendermint, 1 on Cosmos-SDK)
- work status(2019-12-18) : 1 project PR finished, 2 projects under implementation
- definition of work completion : Pull Request accepted by Tendermint team
- expected period of work : 12 weeks from now(subjective to be shorter or longer, depend on review process with Tendermint team)
- requested grant amount : 50,000 USD in total
- refund policy : if any project is not completed until 18 weeks after beginning date caused by due dilligence of B-Harvest, B-Harvest has responsibility to refund related grant back to ICF

--------------------

*Projects detail*

B-Harvest is working on 3 consecutive projects to strengthen the validator operation of Tendermint/Cosmos-SDK based blockchains. We want to share some progress on those projects.

1) Tendermint ADR 50 : [Improved Trusted Peering](https://github.com/tendermint/tendermint/blob/master/docs/architecture/adr-050-improved-trusted-peering.md)

- brief introduction : strengthening trusted, internal, persistent peers by introducing `unconditional_peer_ids` and `persistent_peers_max_dial_period`
- status : spec PR accepted, implementation PR accepted
- workloads : about 4 weeks
- grant : $10,000

2) Cosmos-SDK ADR 16 : [Validator Consensus Key Rotation](https://github.com/cosmos/cosmos-sdk/pull/5233)
- brief introduction : allow validators to replace their consensus key
- status : spec PR accepted, implementation on the way
- workloads : about 8 weeks
- grant : $20,000

3) Tendermint ADR 51 : [Double Signing Protection with Tendermint Mode](https://github.com/tendermint/tendermint/pull/4262)
- brief introduction : prevent double signing of validators by checking recent block data to check the existence of the validator's consensus key, and introducing "Tendermint Mode"
- status : spec on the way, implementation on the way
- workloads : about 8 weeks
- grant : $20,000


--------------------

*For the price calculation of our grant proposal*

Our projects are usually devoted by 2 people, each of person devoting about 50% of full time. As a team, we estimate 4 week contribution as $10,000. Total proposed grant is $50,000 for entire three projects with total 20 weeks contribution.

*Reference*
- projects documentation :
  - [Improved Trusted Peering](https://github.com/tendermint/tendermint/blob/master/docs/architecture/adr-050-improved-trusted-peering.md)
  - [Validator Consensus Key Rotation](https://github.com/cosmos/cosmos-sdk/pull/5233)
  - [Double Signing Protection with Tendermint Mode](https://github.com/tendermint/tendermint/pull/4262)
