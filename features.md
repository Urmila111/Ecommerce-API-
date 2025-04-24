Ecommerce API using mongoose and express. Features:

FEATURES
1. Product Features
Product Catalog: Retrieve a list of all products with filtering, sorting, and pagination options.
Product Details: View detailed information about a specific product (description, price, images, stock, etc.).
Product Search: Search products by keywords, brand, category, or other attributes.
Stock Management: Update product quantity automatically after each purchase.
Related Products: Display products that are similar or often bought together.

2. Category Features
Category Listing: List all product categories for easy browsing.
Category Filtering: Filter products by category.
Category Management (Admin): Add, update, and delete categories as needed.

3. Brand Features
Brand Listing: Show available brands for filtering purposes.
Brand Filtering: Allow users to filter products by brand.
Brand Management (Admin): Add, update, and remove brands for product association.

4. Coupon Features
Coupon Application: Apply a coupon code at checkout to receive a discount.
Coupon Validation: Validate the coupon's expiration date and conditions (e.g., minimum order amount).
Coupon Management (Admin): Create, update, and deactivate coupons.
Discount Calculation: Calculate and apply the discount from a valid coupon to the order total.

5. Payment Features
Payment Processing: Integrate with payment gateways (e.g., Stripe, PayPal) to handle payments securely.
Payment Status: Track whether the payment is pending, completed, or failed.
Refund Processing: Allow admins to issue refunds for orders, if necessary.
Payment History: Record each payment transaction associated with orders for user and admin reference.

6. Review Features
Product Reviews: Allow customers to leave a review for purchased products.
Ratings: Enable a rating system (e.g., 1–5 stars) alongside textual reviews.
Review Moderation (Admin): Approve, edit, or delete reviews to maintain quality.
Aggregate Ratings: Show the average rating for each product based on user reviews.

7. Order Features
Order Placement: Allow users to place an order by adding products to the cart and proceeding with payment.
Order Status Tracking: Update and display the status of each order (e.g., pending, confirmed, shipped, delivered).
Order History: Display past orders for users to view details.
Order Details: Include product details, shipping info, payment status, and total amount in each order.

8. 