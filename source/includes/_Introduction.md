#Introduction

## Getting Started

Starting with PayStand is as easy as...

Sign Up & receive your Sandbox credentials
Take a Payment
Manage Settlement
Go Live!
To take full advantage of PayStand, you should also be familiar with these topics...

Reporting & Event Notifications
Creating accounts for your customers
Fraud Prevention & Risk

### 1. Sign Up and Receive your Sandbox Credentials
Work with a PayStand Implementation Manager who knows your requirements & objectives. Our team can recommend and create a plan to optimize development timelines.

Once your plan is created, your implementation manager will provide you with your Sandbox credentials, including your Dashboard. We will also deliver your development private and publishable keys.

The Sandbox environment is where all your initial development will take place. All development for Sandbox is leverageable for Production. By updating Sandbox to Production links and credentials, your implementation is ready for live activity.



<aside class="warning">
Do not use personal, sensitive, or financial information in the Sandbox.
While we work hard to keep Sandbox parallel to Productions, including in matters of security, it is just never a good idea to have non-test data in a test environment.
</aside>

<aside class="notice">
All URLs in Sandbox and Production have only a single difference: their TLD. Sandbox URLs use paystand.<b>CO</b>, whereas the equivalent URLs in Production use paystand.<b>COM</b>.
</aside>

### 2. Take a Payment
Copy and Paste the code block for the payment interface, ensure the amount you desire is configured correctly, and be sure to include your publishable key.

Then, using PayStand provided test credentials, run sample transactions to ensure proper functionality. We strongly encourage you to establish capturing webhook events, but it is not a requirement to get started.

### 3. Manage Settlement
Decide which method to requesting a withdrawal of funds: API or Dashboard.

PayStand's Withdrawal API permits platforms to programmatically initiate withdrawals on each “customer account” at their discretion. Funds may remain in escrow until a trigger or workflow on the platform is completed, or for up to 6 months from the original transaction date. PayStand's API requires you to have an Enterprise account.

If a member of your staff manages withdrawals (a bookkeeper, accountant, or finance department), it may be best to use the dashboard to issue withdrawals. This is most often done with singular accounts on PayStand.

Automated Settlement – Unless otherwise specified, PayStand will settle transactions automatically and according to industry best practices. This enables end-to-end transactions with the minimum amount of development work.

<aside class="notice">
 Withdrawals Also Known As <i>"Requesting a withdrawal"<i> is synonymous with <i>"scheduling a transfer"<i> (as a withdrawal is a transfer of funds from your PayStand account to your bank account) and "initiating settlement" (as the transfer of funds from your PayStand account to your bank account is looked at, by accountants and ledgers, as settling the accounts). Another term used often is "funding instructions", which is the vehicle PayStand uses to tell one account to transfer funds to another account.
</aside>

## Dashboard Walkthrough





<figure class="video_container">
  <iframe src="https://www.youtube.com/embed/z5Oi5cFLSmM" frameborder="0" allowfullscreen="true"> </iframe>
</figure>



