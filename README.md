# ManualMultiPay (MMP) Gateway Extension

This is a gateway extension for Paymenter that allows you to accept payments through various methods: UPI Address, Bank Account, Aadhaar Number, and Mobile Number. The extension displays a QR code and payment information such as the payment address and other relevant details to the user. It also provides a button which, when clicked, automatically opens the user's payment app with the payment details pre-filled. **Only payments in INR are available.**

The order ID is added as a transaction note to the payment. This makes it easy for both you and the user to keep track of payments and ensure that everything is processed correctly.

Please note that this extension **does not** handle payment confirmation or invoice marking. After a user makes a payment, you must manually confirm that the payment has been made and mark the invoice as paid. This extension is designed to facilitate the payment process, but the confirmation and invoice marking processes are still your responsibility.

<details>
<summary>Sample Screenshots

UPI Payment:
<img src="assets/sample-upi-payment.png" alt="Sample UPI Payment" />
</summary>
Bank Account Payment:
<img src="assets/sample-bank-payment.png" alt="Sample Bank Payment" />
Aadhaar Payment:
<img src="assets/sample-aadhaar-payment.png" alt="Sample Aadhaar Payment" />
Mobile Payment:
<img src="assets/sample-mobile-payment.png" alt="Sample Mobile Payment" />
</details>

## Getting Started
1. Install the extension
1. Enable the extension
1. Set the Merchant Name (Payee Name)
1. Select the Payment Address Type (UPI Address, Bank Account Number, Aadhaar Number, Mobile Number)
1. Fill the relevant payment address field and set the unused payment address fields to NA.
1. Set an order ID prefix (optional)
1. Set a payment confirmation ETA which will be shown to the user (optional)
1. Done! You are ready to accept payments.

![Settings](assets/settings.png)

## Settings
- If you are not using the required payment information fields, you can set them to NA.
- **Order ID Prefix (optional):** This is added before the order ID.
- **Payment Confirmation ETA (optional):** Estimated time for confirmation of payment (eg- 24 Hours).
- **Merchant Name:** Name of the Merchant/Payee.
- **Payment Address Type:** The payment address on which you want to receive payments. Available Options- UPI Address, Bank Account Number, Aadhaar Number, Mobile Number.
- **UPI Address:** The UPI Address which will be used for receiveing payments.
- **Bank Account Number:** The Bank Account Number which will be used for receiving payments.
- **IFSC Code:** IFSC code of the bank account mentioned above.
- **Aadhaar Number:** Aadhaar Number which will be used for receiving payments.
- **Mobile Number:** Mobile Number which will be used for receiving payments.

## Additional Information
This project is licensed under the terms of the MIT license. For more details, see the [LICENSE](LICENSE) file in the repository.

The source code for this project is available on GitHub. You can access it [here](https://github.com/VaibhavSys/ManualMultiPay).