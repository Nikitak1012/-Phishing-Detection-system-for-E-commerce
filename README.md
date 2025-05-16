# Phishing-Detection-system-for-E-commerce
E- Commerce website is a prime target for phishing attacks, where scammers create fake websites with  deceptive URLs that mimic legitimate ones (like "amaz0n.com" instead of "amazon.com")  to steal sensitive data. Machine learning offers a smarter solution by automatically analyzing URL patterns to detect new phishing attempts in real time.

# Feature:
The system automatically detects and blocks phishing URLs in real-time to protect users on e-commerce platforms from scams and data theft.

# How It Works:
URL Input Collection:

When a user clicks a link, the system extracts the URL for analysis.

Feature Extraction: Extracts features from the URL such as length of URL, use of HTTP vs HTTPS, presence of “@” symbols, special characters, subdomains, domain age and DNS records, use of shortening services (e.g., bit.ly).

Machine Learning Model: The system uses a trained machine learning model such as KNN, ANN, CNN and RNN) to classify the URL as legitimate, suspicious, phishing.

Real-time Warning: If the URL is detected as phishing, the system blocks access, displays a warning to the user.

Continuous Learning: The model is periodically retrained using updated datasets to improve accuracy and detect new phishing strategies.

