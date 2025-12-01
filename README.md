# Greencart
It is a full-stack grocery delivery platform with product listings, cart management, secure  order placement, and real-time tracking along with an admin dashboard.

check out the project-
https://green-cart-eosin-phi.vercel.app/



Challenges-
A major challenge in this project was optimizing the slow API response times as the MongoDB database grew. The product listing and order APIs were becoming inefficient because of repetitive queries, unstructured filters, and the absence of proper indexing. To address this, I redesigned the backend logic using aggregation pipelines, compound indexes, and selective field projections, which reduced the response time significantly and made queries far more efficient under load.

In addition to performance issues, I improved the JWT-based authentication and role-management system to ensure secure, consistent session handling for both users and admins. Integrating Razorpay payments while maintaining a stable checkout flow also required careful handling of order validation, API failures, and data consistency. These optimizations resulted in a faster, more secure, and truly scalable system suitable for real-world deployment.
