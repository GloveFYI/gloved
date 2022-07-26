# Preamble

Gloved is a specialized service node to power the glove network. By initial assumptions, the network is not expected to have any semblance of throughput.

Primary purposes:

- Co-ordinate and deliver aggregation of on-chain transactional data by set of blocks

Secondary purposes:

- Delegate provable compute

Initial system can be thought of an on-demand ration delivery system, with probable and slow finality.

Competition: There is none yet, Glove may give The Graph vibes, but by principle, it will likely be killed instead of going the path of statism. Its co-ordination theory aims to be token-averse, but still open to settlement of digital payments, more will be documented on this.

Precedents: There is clear motivation and ongoing work under The Portal Network to create very light nodes purposed to query historical data.

----

To establish some sense of scale, we refer to an existing indexer: trueblocks.

Trueblocks indexes appearances of on-chain addresses within set of blocks, employing bloom filters.

Its current algo amounts the chunk files to at least 2500 totaling at least 2.6 GB in size.

