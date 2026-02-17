[ PHYSICAL WORLD ]          [ ORACLE LAYER ]          [ BLOCKCHAIN LAYER ]
       |                           |                          |
+--------------+            +--------------+          +-----------------------+
|  AI SENSOR   |---(Data)-->| API / RELAY  |--signed->|      REWARD.SOL       |
|  (Camera/Kg) |            |  (Trusted)   |  tx      | (ERC-20 Minting Logic)|
+--------------+            +--------------+          +-----------------------+
                                   |                          |
                                   | (Price Feed)             | (Mints Tokens)
                                   v                          v
                            +--------------+          +-----------------------+
                            | OFF-CHAIN DB |          |     USER WALLET       |
                            | (Waste Rates)|          |  (Holds Reward Coins) |
                            +--------------+          +-----------------------+
                                                              |
                                           +------------------+
                                           | (Spend Tokens)
                                           v
+--------------+            +--------------+          +-----------------------+
|  GOVT INFRA  |            | INSTITUTION  |          |    MARKETPLACE.SOL    |
| (Bus/Metro)  |<--(NFT)----|    WALLET    |<-(ETH)-- | (Service Processing)  |
+--------------+            +--------------+          +-----------------------+
                                                              |
                                                              | (Triggers)
                                                              v
                                                      +-----------------------+
                                                      |      TICKET.SOL       |
                                                      |  (ERC-721 NFT Mint)   |
                                                      +-----------------------+