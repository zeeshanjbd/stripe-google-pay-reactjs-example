This repository contains a sample React.js application that demonstrates how to integrate Stripe and Google Pay for handling online payments. The application uses the @stripe/stripe-js and react-google-pay libraries to set up the payment flow.

The application first initializes Stripe with the user's publishable key, which allows the application to communicate with the Stripe API. Then, it renders the Google Pay button, which is used to initiate the payment process.
When a user clicks the Google Pay button, the application uses the google.payments.api.PaymentsClient object to create a payment request and show the Google Pay sheet.
Once the user completes the payment, the application uses the Stripe API to handle the payment and process the transaction.

The repository includes detailed instructions on how to set up and run the application, as well as the necessary code snippets to handle the Stripe and Google Pay integration.

This is a sample code and you need to use your own Publishable key, Merchant id and other credentials.Make sure you have setup google pay setting by adding your self into group see more details here 

https://developers.google.com/pay/api/android/guides/resources/test-card-suite

You are free to leave or join our test card suite group as needed. To leave, select My membership settings and click Leave group.
https://groups.google.com/forum/#!forum/googlepay-test-mode-stub-data
