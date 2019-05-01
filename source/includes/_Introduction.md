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

## Dashboard Walkthrough




<iframe   width="460" height="315" src="https://www.youtube.com/embed/z5Oi5cFLSmM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<div>

<iframe   width="460" height="315"
<script
  type="text/javascript"
  id="ps_checkout"
  src="https://checkout.paystand.co/v4/js/paystand.checkout.js"
  ps-env="sandbox"
  ps-publishableKey="w41l3su3kf99jd7u9bxjntcz"
></script>

<button
  class="ps-button ps-button-style"
  ps-checkoutType="checkout_payment"
  ps-paymentAmount="100.00"
  ps-fixedAmount="false"
  ps-paymentCurrency="USD"
>Pay Now!</button> ></iframe>
</div>