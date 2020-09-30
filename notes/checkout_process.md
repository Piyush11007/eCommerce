# CHECKOUT PROCCESS

1. Cart -> Checkout View
    ?
    - Login/Register or Enter an Email (as Guest)
    - Shipping Address
    - Billing Info
        - Billing Address
        - Credit Card / Payment

2. Billing App/Component
    - Billing Profile
        - User or Email (Guest Email)
        - Generate Payment Processor Token (Stripe or Braintree)


3. Orders / Invoices Component
    - Connecting The Billing Profile
    - Shipping / Billing Address
    - Cart
    - Status -- Shipped? Cancelled?



4. Backup Fixtures
    python manage.py dumpdata products  --format json --indent 4 > products/fixtures/products.json
