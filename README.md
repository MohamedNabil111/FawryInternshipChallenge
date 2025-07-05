# FawryInternshipChallenge
This is my C++ solution to the Fawry internship challenge which represents a console application simulating a shopping cart and checkout experience, supporting:
- Perishable (Expirable) and shippable products
- Quantity management and stock limits
- Expiry date checking
- Weight-based shipping fees
- Customer balance validation
- Test cases covering all scenarios
Features:
- Add Products to Cart: Ensures stock availability
- Perishable Products: Raises error if expired at checkout
- Shippable Products: Calculates shipping based on total weight
- Shipping Fee: 30 EGP per kg
- Customer Balance Check: Blocks purchase if insufficient funds
- Detailed Receipt Output: Product summary, fees, total, remaining balance
Test cases in main.cpp file:
- test_successful_checkout
- test_perishable_and_shippable_product
- test_non_shippable_checkout
- test_expired_product
- test_insufficient_balance
- test_empty_cart
- test_quantity_limit
- test_zero_or_negative_quantity
