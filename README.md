# 🧱Smart Cement & Brick Calculator

![Smart Cement Calculator](https://github.com/Darshan0244/Smart-cement-and-brick-calculator/blob/ec246392a69334ffad2d70a22aa3345471674a2a/bit_Wizard%20(1).png?raw=true)

This project helps calculate materials required for construction...


## 🏗️ Description
This project was created as a Hackathon project by a team of 4 members.

The Smart Cement & Brick Calculator is a web-based application designed to simplify the process of estimating construction material requirements for building walls. This tool goes beyond basic calculations, offering AI-powered insights to help users make informed decisions. It provides not only the quantities of bricks, cement, and sand needed but also cost estimations and environmental impact assessments. User authentication, calculation history, and Excel export capabilities are also included.

## ✨ Features

-   **Material Calculation:** Accurately calculates the required amount of bricks, cement, and sand based on user-provided wall dimensions (length, height, thickness).
-   **AI Insights:** Delivers valuable insights, including:

    -   **Cost Estimation:** Provides a breakdown of material costs based on current market prices.
    -   **Environmental Impact Assessment:** Estimates the environmental footprint (CO2 emissions) associated with the required materials.
    -   **Material Recommendations:** Suggests optimized material choices based on the project's specific needs.
-   **Location-Based Recommendations:** Leverages weather information to offer smart recommendations tailored to the project's location. For example, it may recommend heat-resistant materials in hot climates.
-   **User Authentication:** Enables users to create accounts, log in securely, and personalize their experience.
-   **Calculation History:** Stores a history of calculations for logged-in users, allowing them to review and reuse previous estimates.
-   **Excel Export:** Allows users to export their entire calculation history to an Excel (`.xlsx`) file for record-keeping or further analysis.
-   **Weather recommendations:** The app uses a weather API to provide recommendations based on weather conditions.
-   **Responsive Design:** The web app is designed to work on different screens.

## 💻 Technologies Used

-   **Frontend:**
    -   HTML
    -   CSS
    -   JavaScript
-   **Backend:**
    -   Node.js
    -   Express.js
-   **Dependencies:**
    -   CORS: For enabling Cross-Origin Resource Sharing.
    -   dotenv: For managing environment variables.
    -   jsonwebtoken: For creating and verifying JSON Web Tokens.

    -   bcryptjs: For password hashing.
    -   mongoose: For managing the user database.
    -   xlsx: For handling Excel file creation and export.
-   **Data storage:**
    -   Excel files (`.xlsx`).

## ⚙️ Setup Instructions
1. **Clone the Repository:**
```
bash
    git clone <repository-url>
    
```
2.  **Navigate to the Project Directory:**
```
bash
    cd <project-directory>
    
```
3.  **Install Dependencies:**
```
bash
    npm install
    
```
4. **Set the enviroment variables:**
    - Create a file named `.env`.
    - Add `PORT=3000` and `JWT_SECRET=your-secret-key` to the file. You can change the value of both variables.
5.  **Start the Server:**
```
bash
    npm start
    
```
## Usage

1.  **Open in Browser:** Launch the application in your preferred web browser.
2.  **Input Data:** Enter the wall dimensions (length, height), wall thickness, wastage percentage, and the project's location in the provided form fields.
3.  **Calculate:** Click the "Calculate Materials" button to perform the calculations.
4.  **View Results:** Review the calculated quantities of bricks, cement, and sand, which will be displayed on the screen.
5.  **AI Insights:** Explore the AI Insights section, which presents the cost estimation, environmental impact assessment, and location-based recommendations.
6.  **Export to Excel:** Click the "Save to Excel" button to download an Excel file containing a detailed history of your calculations.

## Future Improvements

-   Use a database instead of excel files to store the information.
-   Add more calculations.
-   Improve the AI insights and recommendations.

## Contact

If you have any questions, suggestions, or feedback, please feel free to reach out!
