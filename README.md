# Gigante Rental Cars Liquidation and Distribution Summary 

Gigante is the largest rental car company in South America, with multiple offices spread across many Latin American countries. Unfortunately, a series of misfortunes has caused Gigante to enter bankruptcy.  Since credit is not available for a restructuring the court has accepted the liquidation plan submitted by the creditors. 

Under the liquidation plan, there will be two key parties which will act under the supervision of the court and the primary bankruptcy trustee. 

The Liquidation Trustee will oversee the sales of all of the Company’s assets.
The Distribution Trustee will oversee the distribution of the liquidation proceeds to the Company’s creditors, according to a plan that will be submitted to the court in the next several weeks as the Proof of Claim forms are submitted by the creditors and evaluated by the staff. 



The liquidation process is expected to take several months. Proceeds from liquidations are to be transferred into the Liquidation Trustee’s account.  After review of the liquidation proceeds and process, the Primary Bankruptcy Trustee will direct the Liquidation Trustee to transfer funds to the Distribution Trustee.  Upon receipt of funds, the Distribution Trustee will dispense funds to the creditor groups, according to the plan approved by the court. 



## Liquidation Trustee



The LT has hired Auction Agents in multiple countries to run auctions of Gigante’s vehicle’s and other assets. Sale proceeds will be transferred by each Auction Agent to the LT’s smart contract. Once funds are transferred to the Liquidation Trustee, funds can only be released to the Distribution Trustee. The Bankruptcy Trustee will oversee all transfers. 





## Distribution Trustee


The Distribution Trustee will handle making payments to each class of creditors. Funds will be transferred from the Distribution Trustee to one of six subsidiary smart contracts for further disbursement among the individual creditors. 

The priority of claims that the Distribution Trustee will adhere to is as follows: 
Administrative Fees - 50,000
Salaries owed to employees - 125,000
Taxes - 65,000
Senior Secured Creditors - 400,000
Bondholders - 200,000
The Junior Creditors and the equity have agreed to split any remainder on a 60/40 basis. 



## Implementation Mechanics


The Bankruptcy Court and the Trustee agree on the importance of transparency in the liquidation and distribution process. To that end, they have engaged BlockHeads LLC to implement the appropriate smart contracts and business processes to ensure the efficient resolution of this matter.  

### Step 1 - Enable Receipt of Funds 
Accept registration of Auction Agents
Accept receiving of funds only from registered auction agents
Emit events when funds are received
Allow querying of the funds received
Ensure that funds flow out 
Automatically =OR=
When the Liquidation Trustee approves distributions. 

### Step 2 - Enable Distribution of Funds 
Ensure that funds flow out based on priority
Ensure that funds flow out 
Automatically =OR=
When the Distribution Trustee approves distributions. 

### Step 3 - Enable Transfer of funds from Liquidation Trustee to Distribution Trustee
Ideally, these are two completely separate smart contracts. 



