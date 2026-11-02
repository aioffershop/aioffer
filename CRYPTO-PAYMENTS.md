# Buying digital products with crypto on AIOFFER

This guide describes the checkout sequence. The live checkout is the source of truth for supported currencies, networks, destination addresses and amounts.

## 1. Review the selected product

Select the product, plan and duration before checkout. Confirm the account type, regional requirements and delivery terms on its listing. Use the [product directory](PRODUCTS.md) to find a listing.

## 2. Select currency and network

Choose an option offered by checkout. A token name alone is not enough: USDT on Tron and USDT on Ethereum use different networks. Match the network shown by checkout to the withdrawal network in your sending wallet or exchange.

## 3. Check the minimum payment

New crypto deposits have a $10 minimum. When an order costs less than $10, the remaining value is credited to the AIOFFER account wallet after the payment is verified. For example, a $6 order funded with the required $10 leaves $4 as account wallet credit. This is an internal account balance, distinct from the external wallet sending the transaction.

Use the exact cryptocurrency amount displayed by checkout; the dollar example is not a cryptocurrency conversion quote. Account for any withdrawal fee so the destination receives the required amount.

## 4. Send payment

Continue to see the destination address, network and amount. Copy the details or scan the QR code, then check them in the sending app before confirming. Do not reuse an address from this repository or from another customer's order.

## 5. Submit the TXID

After sending the transaction, enter its transaction ID and submit payment. Follow any additional wallet connection and authorization step shown for the selected plan. Read the actual authorization in the wallet before signing.

An external wallet connection or token authorization is a separate operation from transferring the order payment. Entering a plausible-looking TXID is not proof of payment.

## 6. Follow payment and delivery status

The order can remain pending while the network, recipient address, amount and duplicate transaction checks are completed. Payment confirmation and product delivery are separate statuses. Keep the order reference and use the support channel on the website for order-specific help.

Never put recovery phrases, private keys or customer payment details in public GitHub issues. For more buying questions, read the [FAQ](FAQ.md).
