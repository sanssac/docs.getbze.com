---
icon: file-circle-info
---

# Blockchain Params

It provides details about the fees and their destinations within the DEX - Tradebin module of the BZE blockchain.&#x20;

<figure><img src="../../.gitbook/assets/image (51).png" alt=""><figcaption></figcaption></figure>

Here's a breakdown of each section:

#### Create Market Fee :&#x20;

#### **Fee Amount**: 25,000 BZE

* **Description**:&#x20;
* Users can create their own market pairs between two denominations.&#x20;
* The process is permissionless and incurs a fee set by the blockchain.
* &#x20;Pricing is controlled by the community and can be modified through a governance proposal.
  * The fee is directed to the community pool.
  * Users can suggest a lower fee or request a grant for the fee via Twitter or Discord.

#### Market Maker Fee

* **Fee Amount**: 0.001 BZE
* **Description**:
  * Charged to users who provide liquidity by placing limit orders that do not fill immediately.
  * Typically lower than taker fees to incentivize adding liquidity to the market.
  * Fees maintain operational integrity and enhance liquidity of the DEX.
  * Ensures smoother trading experiences for participants.
  * Can be adjusted via community governance proposal.

#### Market Taker Fee

* **Fee Amount**: 0.1 BZE
* **Description**:
  * Applied to trades executed against existing orders, effectively taking liquidity from the market.
  * Generally higher than maker fees to balance the ecosystem by encouraging liquidity provision.
  * Helps manage trade volume and pace, ensuring liquidity availability.
  * Can be revised through governance proposal.

#### Maker Fee Destination

* **Destination**: Burner Module
* **Description**:
  * Market fees can be directed to the Burner module for burning or to the community pool.
  * Fee redirection is permitted through a governance proposal.
  * Stakeholders decide the most beneficial use of accumulated funds.
  * Supports continuous platform improvement and aligns with community interests.

#### Taker Fee Destination

* **Destination**: Burner Module
* **Description**:
  * Similar to the Maker Fee Destination, market fees can be directed to the Burner module or community pool.
  * Governance proposals allow stakeholders to determine fund usage.
  * This flexibility promotes platform enhancement and community alignment.

This detailed explanation of the fees and their destinations helps users understand the financial dynamics within the DEX - Tradebin module and the community's role in governance and decision-making.

<figure><img src="../../.gitbook/assets/image (52).png" alt=""><figcaption></figcaption></figure>

#### Token Factory

**Create Denomination Fee**

* **Fee Amount**: 25,000 BZE
* **Description**:
  * The Token Factory module allows users to create their own denominations.
  * These denominations function like any other coin on the blockchain, with capabilities for sending and using them both within and across other blockchains via Inter-Blockchain Communication (IBC).
  * The fee for creating a token acts as a deterrent against network spam and is directed to the community pool.

#### Earn - Rewards Module

**Create Staking Reward Fee**

* **Fee Amount**: 25,000 BZE
* **Description**:
  * Users can create staking reward programs for specific denominations of their choice.
  * Setting up these programs requires a fee payment and the provision of funds to be used as rewards.
  * Collected fees are directed to the community pool.

**Create Trading Reward Fee**

* **Fee Amount**: 50,000 BZE
*   **Description**:

    * Users can establish trading reward programs for specific DEX markets of their choice.
    * Setting up these programs requires a fee payment and the provision of funds to be used as rewards.
    * Collected fees are directed to the community pool.



Please move to the next page for overview of the various types of fees.
