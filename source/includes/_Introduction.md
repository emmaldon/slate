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
<br>
 <b>Withdrawals</b> Also Known As <i>"Requesting a withdrawal"</i> is synonymous with <i>"scheduling a transfer"</i> (as a withdrawal is a transfer of funds from your PayStand account to your bank account) and "initiating settlement" (as the transfer of funds from your PayStand account to your bank account is looked at, by accountants and ledgers, as settling the accounts). Another term used often is "funding instructions", which is the vehicle PayStand uses to tell one account to transfer funds to another account.
</aside>

### 4. Go Live!
All development for Sandbox is leverageable for Production. By updating Sandbox to Production links and credentials, your implementation is ready for live activity.

Once you've completed your development, we'll certify your implementation and schedule a go-live date.

### 5. Events & Webhooks
Events, sent via webhook, enable timely receipt of updates on payment statuses. While information may also be pulled via API, these push notifications activate triggers and custom workflows the moment information is made available. Notifications are delivered via HTTP POST to a destination endpoint on your server. Each event payload is a JSON object, and contains the full PayStand reference and data that the notification is reporting on.

To configure an event listening point, you'll need to:

Create a webhook destination URL on your server
Add the destination webhook URL to PayStand via the dashboard.
Set up your server to capture webhooks.

### 6. Creating an Account
To enable businesses or organizations to receive funds, you will need to create a “customer account” for each child merchant of your platform. The financial term for creating this account is “underwriting.” The process of underwriting can be automated and supported entirely within your application with PayStand.

Gather the inputs for your merchants and submit to PayStand through the onboarding endpoint. Work with your PayStand implementation manager to determine what values are required for your platform.

Once PayStand receives key data points about each desired recipient of funds, we will return an approval or an error message with details explaining why the merchant was not approved.

PayStand will instantly return a publishable key and transactions can begin immediately.

### 7. Fraud Prevention & Risk
Financial transactions require you adhere to financial industry KYC and compliance standards. PayStand’s team is available to both assist with compliance and advise you on best practices to ensure you meet standards for KYC processes. We will leverage our technology to your benefit, but this is in addition to and not instead of your own education and KYC process.

## The Payment Interface
To collect the information for a payment (whether by card, echeck, bank account, or other means), PayStand provides you a versatile, robust interface. Most developers from our partners get this interface copied & running in under 5 minutes.

### Include in your Page
Copy and paste PayStand's Basic Checkout tags.



`html
<script
 type="text/javascript"
  id="paystand_checkout"
  src="https://checkout.paystand.co/v4/js/paystand.checkout.js"
  ps-mode="embed"
  ps-show="true"
  ps-amount="100.12"
  ps-publishable-key="<your publishable key from your PayStand Dashboard>"
  ps-env="sandbox"
</script>
`

## Dashboard Walkthrough





<figure class="video_container">
  <iframe src="https://www.youtube.com/embed/z5Oi5cFLSmM" frameborder="0" allowfullscreen="true"> </iframe>
</figure>






