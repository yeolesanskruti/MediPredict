# MediPredict
MediPredict is a cutting-edge web application powered by artificial intelligence to assist users in managing their health and wellness. By analyzing symptoms provided by users, MediPredict predicts potential diseases, provides descriptions, suggests precautions, recommends medications, and offers personalized workout and diet plans.

# Features
1.Symptom Analysis: Input symptoms to get AI-driven medical predictions.

2.Disease Prediction: Identify potential health conditions with detailed descriptions.

3.Precautionary Advice: Receive actionable precautions for better health.

4.Medication Suggestions: AI-powered recommendations for medications.

5.Personalized Plans: Customized workout and diet suggestions based on health conditions.

6.User-Friendly Interface: Clean and responsive UI for seamless interaction.

7.Secure Platform: User data is handled securely and confidentially.

# Tech Stack

Frontend :

HTML: Creating the structural foundation of web pages, including forms for symptom input and other interactive elements.

CSS: Styling the application with layouts, colors, and responsive designs for an engaging user interface.

JavaScript: Adding interactivity and dynamic behavior to the application, ensuring a seamless user experience.

Jinja2: Rendering dynamic templates, allowing the integration of Python backend logic with HTML for data visualization and interaction.

Backend :

Flask: A lightweight Python framework used to manage the server-side logic, API creation, and the integration of the machine learning model.

Machine Learning :

Scikit-learn: Building and training the machine learning model (Support Vector Classifier) to predict diseases from symptoms.

Pickle: Serializing and saving the trained model, enabling efficient reuse without retraining.

Data Handling :

Pandas: Manipulating and analyzing datasets like symptoms, precautions, medications, and diets for accurate predictions.

NumPy: Performing numerical operations and preprocessing data for machine learning.

Database :

CSV Files: Storing static data (symptom-disease mappings, recommendations, etc.) for quick and easy access without requiring complex database setups.
