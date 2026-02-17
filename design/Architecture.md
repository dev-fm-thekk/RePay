[ USER ]
          |
          | (1) Deposits Waste
          v
+---------------------------+
|   AI CLASSIFICATION HUB   | <--- [Computer Vision + Scales]
+---------------------------+
          |
          | (2) Classification Data
          |     [Type: Plastic/E-Waste] + [Mass: kg]
          v
+---------------------------+        +--------------------------+
|       REWARD.SOL          | <----- |   EXTERNAL PRICE ORACLE  |
| (ERC-20 Minting Contract) |        | (Market Rates for Waste) |
+---------------------------+        +--------------------------+
          |
          | (3) Mints Tokens (ERC-20)
          v
+---------------------------+        +--------------------------+
|    USER DIGITAL WALLET    | -----> |  DECENTRALIZED EXCHANGE  |
|  (Holds Utility Tokens)   |        |  (Swap for ETH / Fiat)   |
+---------------------------+        +--------------------------+
          |
          | (4) Spend 10 Tokens for Service
          v
+---------------------------+
|    MARKETPLACE.SOL        |
| (Service Payment Gateway) |
+---------------------------+
          |
          | (5) Token -> ETH Swap & Transfer
          v
+---------------------------+        +--------------------------+
|    INSTITUTION WALLET     | ---->  |     NFT TICKET ENGINE    |
| (Govt/Merchant Revenue)   |        |     (TICKET.SOL)         |
+---------------------------+        +--------------------------+
                                               |
                                               | (6) Mint Unique NFT
                                               v
                                     +--------------------------+
                                     |    USER SMARTPHONE       |
                                     | (NFT Ticket / QR Access) |
                                     +--------------------------+
