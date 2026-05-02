## Financial Freedom — Beginner Guidebook

## Project Description: 
Financial Freedom is a beginner-friendly personal finance website designed to help people build money confidence without needing a financial background. The site breaks down six core topics — budgeting, debt payoff, saving, spending, investing, and retirement — into clear, jargon-free guides paired with interactive calculators and tools. The goal is to give anyone a practical starting point for understanding and managing their money, one step at a time.

## Live Demo:
🔗 https://julisam101.github.io/financialfreedom/

## Features:

Personalized Plan Builder — Users select the financial topics they want to work on and receive a custom one-page action plan tailored to their selections
50/30/20 Budget Calculator — Enter income and a pay schedule to instantly see a split across needs, wants, and savings with a live-updating chart
Debt Payoff Comparator — Input real debt balances, APRs, and minimum payments to compare Snowball vs. Avalanche payoff timelines and total interest paid
Emergency Fund & Savings Goal Tracker — Calculate how much of a safety net you need and how long it will take to reach your savings goal with compound interest projections
Spending Snapshot Tool — Log monthly spending by category to see a live breakdown, a health meter, and personalized "what if" coaching
Investment Growth Projector — Explore how $100 grows over time across stocks, bonds, and balanced mixes with low, mid, and high return scenarios
Retirement Nest Egg Calculator — Input 401(k), IRA, and employer match details to project your retirement balance and estimated monthly income
Excel Export — Every calculator page includes a downloadable Excel file with your personalized numbers
Fully Responsive Design — Works across desktop and mobile devices
No login or account required — All tools run entirely in the browser


## Technologies Used: 
HTML5 — Page structure and semantic markup
CSS3 — Custom styling, layout, and responsive design
JavaScript (Vanilla) — All calculator logic, dynamic UI updates, and chart rendering
Chart.js — Interactive, live-updating charts on every tool page
SheetJS (xlsx.js) — Client-side Excel file generation for data exports
GitHub Pages — Static site hosting and deployment


## AI Tools Used: 
Claude — Used throughout the project for content writing, debugging JavaScript logic, and refining the calculator formulas. Claude helped draft the plain-language explanations on each topic page, suggested the structure for the personalized plan builder, and assisted with fixing edge cases in the debt payoff and compound interest calculators. It also helped improve accessibility language and write the step-by-step guides on each page.
ChatGPT (OpenAI) — Used for early brainstorming of the site structure and topic organization. Helped generate initial ideas for the "Your First 3 Steps" section on the homepage and explored different approaches to the budget framework selector.


## Challenges: 
1. Making the calculators feel connected, not isolated
Each tool page has multiple calculators (for example, the saving page has an emergency fund calculator, a goal tracker, and a compound interest projector). Getting them to share inputs and update each other in real time required careful JavaScript state management and was one of the more complex technical challenges of the project.
2. Designing for true beginners
The hardest editorial challenge was writing content that a first-generation college student with zero financial background could understand, without being condescending to someone with more experience. Every page went through multiple rewrites to remove jargon and replace technical terms with plain-language explanations.
3. The personalized plan builder
Building logic that generates a meaningfully different plan based on which combination of topics a user selects — rather than just showing all topics every time — required thinking carefully about how the topics relate to each other and what advice actually makes sense in each scenario.
4. Excel exports on the client side
Generating downloadable Excel files entirely in the browser without a backend was a new technical challenge. SheetJS made it possible, but formatting the output to be clean and immediately usable took significant iteration.
5. Responsive layout across all pages
With seven navigation links and complex multi-column calculator layouts, keeping the site readable and functional on mobile required reworking the nav and restructuring several page layouts for smaller screens.

## Future Improvements: 

localStorage persistence — Save a user's calculator inputs between sessions so they don't have to re-enter their numbers every visit
Live API integration — Pull in real current data such as high-yield savings account rates, federal interest rates, or financial news headlines
Debt-free date display — Show a specific month and year (not just number of months) in the debt payoff calculator to make the goal feel more real and motivating
"Which topic is right for me?" quiz — A short 3-question quiz on the homepage that routes new users to the most relevant starting page based on their situation
More budget frameworks — Add Zero-Based Budgeting and Pay Yourself First as options alongside the existing 50/30/20 and custom slider frameworks