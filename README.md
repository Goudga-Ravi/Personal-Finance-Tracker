# Personal-Finance-Tracker
 AI to provide users with insights into their spending habits, predict future expenses, and offer personalized financial advice.

 
**Features**
---------

- **AI-Powered Insights**: Utilizes machine learning models to categorize transactions and predict future expenses.
- **Interactive Dashboard**: A detailed summary of financial data, including future spending predictions.
- **Responsive Design**: A seamless experience across devices, thanks to a Bootstrap-designed interface.
- **User-Friendly Interface**: A clean and modern design that simplifies navigation through financial data.

**Technology Stack**
--------------

- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Backend**: Flask, Python
- **Machine Learning**: Scikit-learn, Pandas, Numpy
- **Database**: CSV file for transaction data

**Installation & Setup**
-------------------

1. **Clone the Repository**

   ```
   git clone https://github.com/yourusername/finance_tracker.git
   cd finance_tracker
   Create a Virtual Environment and Install Dependencies

   Create a Virtual Environment

   ```
   python3 -m venv venv
   ```

   Activate the Virtual Environment

   ```
   source venv/bin/activate
   ```

   On Windows:

   ```
   venv\Scripts\activate
   ```

   Install the Required Dependencies

   ```
   pip install -r requirements.txt
   ```

   Run the Application

   ```
   python app.py
   ```

   Access the Application

   ```
   http://127.0.0.1:5000/
   ```


**Project Structure**
------------------

```
finance_tracker/
│
├── app.py                   # Main application file
├── models.py                # Machine learning models
├── static/                  # Static files (CSS, JS, images)
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── main.js
│   └── assets/
│       └── logo.png
├── templates/               # HTML templates
│   ├── index.html
│   ├── dashboard.html
├── requirements.txt         # Project dependencies
└── data/
    └── transactions.csv     # Sample transaction data
```

**Development Process**
---------------------

Initial Planning (1 Week)

* Discussed project requirements with the client.
* Created a detailed project plan, including milestones and deadlines.

Backend Development (3 Weeks)

* Set up Flask backend.
* Developed machine learning models for transaction categorization and expense prediction.
* Integrated models with the Flask application.

Frontend Development (2 Weeks)

* Designed a responsive UI using Bootstrap.
* Created interactive elements for the dashboard.

Testing & Refinement (1 Week)

* Conducted thorough testing to ensure all features were working as expected.
* Made necessary refinements based on client feedback.

Final Review & Delivery (1 Week)

* Presented the final product to the client.
* Made minor adjustments and delivered the project.
