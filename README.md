Intrinsic Value Calculator
The Intrinsic Value Calculator is a fast, interactive web tool designed for fundamental investors to determine the fair value of a stock using a discounted earnings/terminal P/E model. This helps estimate a stock's potential upside and downside based on user-defined growth and discount rates.


🛑 Licensing & Commercial Use Notice
This software is protected under the Pavlo Lomakin Commercial License.
Strictly Non-Commercial Use Only: Use of this software for personal or educational purposes is permitted. 
Commercial use, including sale, sublicensing, or inclusion in paid products or services, is strictly prohibited.
For complete license details, please review the LICENSE.md file in the root of this repository.

Commercial Inquiries
If you are interested in using this software for a commercial purpose, please contact the copyright holder to arrange a licensing agreement:

📧 Email: lomak.pavlo@gmail.com 🛑
 

Technologies
Frontend: HTML5, CSS3 (Custom-styled, responsive layout), JavaScript (ES6+ for logic and API calls).
Styling: Custom CSS with a financial/professional theme (Roboto and Roboto Mono fonts).
Icons: Font Awesome.

Getting Started
Prerequisites
A web browser (Chrome, Firefox, Edge, Safari).

Features
Intrinsic Value Calculation: Estimates a stock's fair value based on current EPS, projected growth, expected future P/E, and a required discount rate.
Scenario Analysis: Provides immediate results for Pessimistic, Base, and Optimistic scenarios.
Dual-Mode Growth Input: Supports Simple (single annual growth rate) and Pro (year-by-year growth rate) estimation.
Real-Time Stock Data: Fetches live Current Price, P/E, EPS (TTM), Market Cap, and Analyst Recommendations using a financial data API.
Detailed Valuation Breakdown: Displays the step-by-step calculation, including Discounted Future Earnings and Discounted Terminal Value.
Bilingual Support: Full interface support for English and Russian 

How to Use
Enter Stock Symbol: Input the ticker (e.g., AAPL, MSFT).

Input Projections:

Estimated Annual Growth Rate (%): Your expected growth rate for EPS over the next 5 years (in Simple Mode). Switch to Pro Mode to enter individual growth rates for Year 1 through Year 5.
Expected Future P/E Ratio: The P/E multiple you expect the stock to trade at after the projection period (Year 5).
Discount Rate (%): Your minimum required annual rate of return (e.g., 10% to outperform SP500, or a higher rate for riskier stocks).
Click "Calculate Intrinsic Value": The application will fetch live data and perform the analysis for the three scenarios.

Calculation Scenarios
The calculator automatically derives two additional scenarios from your Base inputs:

Scenario	Growth Rate	Future P/E
Pessimistic	Base Growth - 2.0%	Base P/E - 2.0
Optimistic	Base Growth + 2.0%	Base P/E + 2.0

Note: If you use Pro (per-year) growth, the difference (e.g., ±2.0%) is applied to the average of your 5-year growth rates.

Contact
For support, questions, or commercial licensing, please reach out directly:
PavloLomakin
Email: lomak.pavlo@gmail.com
