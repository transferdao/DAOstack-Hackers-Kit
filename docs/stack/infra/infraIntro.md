**[Infra](https://github.com/daostack/infra) is a Solidity smart contract library containing the core building blocks of decentralized governance.** Infra contracts can be integrated into any application regardless of its architecture.

Infra has two main components:

- **Voting Machines** - A voting machine is a universal contract which can operate the voting process for any organization. Each voting machine follows its own predefined rules for the decision making and execution process. Rules for voting machines can be implemented for any voting process, from a simple protocol like an "Absolute Vote" (where 51% of the voting power should approve it in order for the decision to pass), or more sophisticated protocols like the [Holographic Consensus](https://www.youtube.com/watch?v=1De0MoStSkY) voting protocol.

- **Voting Rights Management** - A voting rights management system determines how voting rights are distributed. Any voting rights management system must have "balances" which represents the voting power each participant holds. There are 2 main approaches for managing voting rights: token-based voting and reputation-based voting. The main technical difference between the two is that tokens are transferable (i.e. tradable) while reputation is non-transferable. Another big difference which may appear (depending on implementation) is that a token is a property which cannot be taken while reputation may be redistributed by the organization itself. For most cases, we reccomend using the reputation-based voting model, however, Infra allows any voting right management system to be built.

### Should I work at this level?

Build on Infra if you need new or modified decentralized governance primitives, such as voting machines and voting rights management systems.
