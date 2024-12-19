

# Telecom Customer Data Management System

This project aims to design and implement a comprehensive customer data management system for a telecom company. The system handles subscriber information, payment details, and service usage, providing a seamless and personalized digital service experience for customers.

## System Requirements

**2.1 Customer Profile:**

* Detailed records of customer profiles, including:
    * National ID
    * Full Name
    * Email
    * Address
    * Date of Birth

**2.2 Customer Account:**

* Unique account tied to each mobile number.
* Attributes:
    * Mobile Number (Unique Identifier)
    * Line Balance
    * Account Type
    * Account Start Date
    * Account Status
    * Total Points Earned

**2.3 Service Plan:**

* Offers a set of services (SMS, Minutes, Mobile Internet).
* Attributes:
    * Plan ID (Unique Identifier)
    * Name
    * Price
    * Description
    * SMS Limit
    * Internet Data Limit
    * Call Minutes Limit

* Each account must subscribe to at least one plan.
* A single plan can be linked to multiple accounts.
* Subscription attributes:
    * Subscription Date
    * Subscription Status (Active/On Hold)

**2.4 Plan Usage:**

* Tracks customer usage of services within their subscription plans.
* Attributes:
    * Usage ID (Unique Identifier)
    * Account ID
    * Plan ID
    * Start Date
    * End Date
    * Data Consumption
    * Minutes Used
    * SMS Sent

**2.5 Payment:**

* Records all transactions made by the customer account.
* Attributes:
    * Payment ID (Unique Identifier)
    * Account ID
    * Transaction Amount
    * Date of Payment
    * Payment Method
    * Payment Status

**2.6 Wallet:**

* Tracks customer financial interactions and enables money transfers.
* Attributes:
    * Wallet ID (Unique Identifier)
    * Customer ID
    * Current Balance
    * Currency
    * Last Modified Date

* Each customer has one wallet.
* Supports sending and receiving money between users.
* Transfer transaction attributes:
    * Amount
    * Date of Transaction

**2.7 Benefits:**

* Represents advantages offered to customer accounts.
* Includes:
    * Points Group
    * Cashback
    * Exclusive Offers

* Attributes:
    * Benefit ID (Unique Identifier)
    * Description
    * Validity Date
    * Status (Active/Expired)

* **2.7.1 Points Group:**
    * Points earned based on transaction amount.
    * Attributes:
        * Points Group ID
        * Amount

* **2.7.2 Exclusive Offer:**
    * Promotional deals or packages.
    * Attributes:
        * Offer ID
        * Internet Data
        * SMS
        * Call Minutes

* **2.7.3 Cashback:**
    * Percentage of spending credited back to the wallet.
    * Attributes:
        * Cashback ID
        * Amount
        * Credit Date

**2.8 Voucher:**

* Redeemable using accumulated points.
* Attributes:
    * Voucher ID (Unique Identifier)
    * Account ID
    * Voucher Value
    * Expire Date
    * Points Required

**2.9 Shop:**

* Represents physical stores or e-shops.
* Attributes:
    * Shop ID (Unique Identifier)
    * Name
    * Type (Physical/E-shop)
    * Address (Physical Shop)
    * Website URL (E-shop)
    * Rating (E-shop)

**2.10 Technical Support Ticket:**

* Tracks issues related to services or network performance.
* Attributes:
    * Ticket ID (Unique Identifier)
    * Account ID
    * Issue Description
    * Priority Level
    * Status (Open/In Progress/Resolved/Closed)

This document outlines the key requirements for the Telecom Customer Data Management System. 

**Note:** This is a basic outline. Further details and specific requirements will need to be defined during the design and development phases.
