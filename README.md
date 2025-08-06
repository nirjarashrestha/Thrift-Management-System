🛍️ Thriftonic: Thrift Management System
Thriftonic is a web-based Thrift Store Management System designed to streamline second-hand product listings, rentals, purchases, and recommendations. Built with PHP, MySQL, and Bootstrap, the system emphasizes sustainability, user personalization, and efficient admin control. It integrates intelligent recommendation and sentiment analysis features to enhance user engagement and decision-making.

🚀 Key Features
🔐 User & Admin Authentication

🛒 Browse, Buy, and Rent Products

🎯 Product Recommendation Engine
Utilizes Cosine Similarity to suggest relevant products based on tags and preferences.

📈 Category Tracking & Session-Based Analytics
Analyzes user behavior to refine category suggestions.

💬 Sentiment Analysis on Reviews
Implements a basic Naïve Bayes model to classify feedback as Positive or Negative.

📁 Admin Product Management
Admins can add, update, delete products, and manage categories.

📸 Image Upload Support
Visual display of products for better UX.

📱 Responsive Design
Built using Bootstrap for cross-device compatibility.

⚙️ Technology Stack
Layer	Technology
Frontend	HTML, CSS, JavaScript, Bootstrap
Backend	PHP
Database	MySQL
Algorithms	Cosine Similarity, Naïve Bayes
Tools Used	XAMPP, Jupyter Notebook, Figma, Lucidchart

📐 Algorithms
Cosine Similarity
Used to compute similarity between user preferences and product tags.

Formula:
cos(θ) = (A · B) / (||A|| × ||B||)
Where A and B are vector representations of product features and user preferences.

Naïve Bayes Sentiment Classifier
Classifies review text into positive or negative categories using word probability.

🧪 Setup Instructions
Download and install XAMPP

Clone the repository into your htdocs directory.

Import the provided SQL file into phpMyAdmin.

Start Apache and MySQL via XAMPP Control Panel.

Navigate to http://localhost/thriftonic in your browser.

📊 Screenshots & Diagrams
Homepage & Product Display

Recommendation Results

Admin Dashboard

Cosine Similarity Result Graph

Sentiment Analysis Output (Positive/Negative)

(Insert images or diagrams here)

📌 Future Enhancements
Integration of real-time machine learning libraries for sentiment analysis

Wishlist, cart, and checkout functionalities

Notification system (email/SMS)

Advanced filtering and search options

API integrations for shipping and payment gateways
