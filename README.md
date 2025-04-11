# Payment Processor
A PHP framework for creating and processing non-custodial debit card transactions using a cryptocurrency wallet.

## Payment Scenario
A user has a large balance in a cryptocurrency but in order to use those funds for merchandising, they would need to convert to a usable currency, incurring unregulated exchnage fees. Getting merchants to adopt to accepting cryptocurrency can be challenging unless the process is streamline similar to accepting credit and debit cards?

A payment processor associates a cryptocurrency wallet with a 16-19 digit debit card number with an expiry and cvv code.

A customer on a merchant eccommerce website is ready to check out and presented with the option to pay using your cryptocurrency, the merchant prompts the user to connect to accepted cryptocurrency network, then prompts the user for their PAN with EXP and CVV numbers.

Payment processing is transfered to the payment processor which verifies the PAN and WALLET, checks the onchain balance for the WALLET ensuring anough funds are available to complete the purchase, then initiates client side transfer transactions to transfer funds from the user WALLET to the merchant ad payment processor wallet in real time.

## Regulatory
Even though the payment processor does not hold customer funds as any time, under the current regulations they are still considered a money transamitter/money service business, requiring a 50 state license.

Howvere under FINCEN definition of a Money Service Business at [](https://www.fincen.gov/money-services-business-definition), 

Notwithstanding the previous discussion, the term "money services business" does not include:

- A bank, as that term is defined in 31 CFR 1010.100(d) (formerly 31 CFR 103.11(c)), or
- A person registered with, and regulated or examined by, the Securities and Exchange Commission or the Commodity Futures Trading Commission.

meaning if your are a bank, even a WY SPDI, or an entity registered with the SEC, you can operate this payment processor without state registration (verify with your legal counsel).

# ELMX SRO Non-Custodial Payment Processor Licensure Compliance Framework
A third option in the making is where the ELMX Exchange, a future NMS/SRO exchange for exempt and intrastate offerings is creating a regulatory framework where a non-custoodial payment processor can register with this SRO and not require 50 state registration.


## 1. **Objective**
To establish a **non-custodial payment processor licensure** under the **ELMX Self-Regulatory Organization (SRO)** framework that enables businesses to create **blockchain-based debit cards and payment networks** while ensuring exemption from **Money Services Business (MSB) and Money Transmitter License (MTL) requirements**.

## 2. **Regulatory Exemptions & Justifications**

### 2.1 **FinCEN Exemption (31 CFR 1010.100(ff))**
Under FinCEN's regulations, a payment processor is **not considered an MSB** if it meets the following criteria:
- **No Custody of Funds**: The processor does not hold, control, or have access to customer funds.
- **Peer-to-Peer Transactions**: Transactions are executed directly between sender and recipient using blockchain smart contracts or third-party banks.
- **Technology Service Provider Role**: The processor operates purely as a technology infrastructure provider, facilitating transactions but not engaging in money transmission.

### 2.2 **Money Transmitter License (MTL) Exemption**
Most U.S. states require an MTL for businesses engaging in money transmission, but exemptions exist for:
- **Agents of the Payee**: The processor acts as an agent for merchants or users without holding funds.
- **Decentralized Ledger Processing**: Blockchain-based transactions where funds do not flow through the processor.

### 2.3 **SEC and CFTC Regulatory Considerations**
- **SEC Regulation**: If securities-based transactions occur, the processor falls under SEC oversight and is **not an MSB**.
- **CFTC Regulation**: If digital assets are classified as commodities, the processor would comply with **CFTC oversight instead of FinCEN MSB rules**.

## 3. **Licensure Requirements**
To qualify for an ELMX SRO **Non-Custodial Payment Processor License**, businesses must:
- **Operate on a Non-Custodial Basis**: Transactions must be conducted directly on blockchain networks without intermediary fund control.
- **Utilize Smart Contracts**: Automated transactions using self-executing smart contracts ensure compliance with non-custodial operations.
- **Integrate Third-Party Banking Partners**: If fiat conversions are required, partner with a regulated bank or financial institution.
- **Ensure Compliance with SEC or CFTC**: If securities or commodities are involved, register accordingly to avoid MSB classification.
- **Undergo SRO Review & Audits**: Licensed processors must maintain transparency, undergo periodic compliance audits, and adhere to KYC/AML requirements for fraud prevention.

## 4. **Prohibited Activities**
Licensed payment processors under ELMX SRO may **not**:
- **Hold or control customer funds at any stage**.
- **Engage in fiat-to-fiat remittances**.
- **Act as a traditional money transmitter**.
- **Issue stablecoins or function as a custodial wallet**.

## 5. **Conclusion**
By ensuring non-custodial operation, leveraging blockchain smart contracts, and aligning with SEC/CFTC oversight, the **ELMX SRO Non-Custodial Payment Processor License** provides businesses with a legally compliant path to issue blockchain-based debit cards and payment networks while avoiding **MSB and MTL licensing requirements**.

Using the ELMX SRO licensing of non-custodial payment processor, creates a regulatory buffer and gudieline from state registration.
