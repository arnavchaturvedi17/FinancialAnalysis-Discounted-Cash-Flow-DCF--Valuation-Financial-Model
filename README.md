# Financial Analysis: Full DCF (Discounted Cash Flow) of Valuation Financial Model.
### Arnav Chaturvedi
### Project Role: Financial Analyst – Retail Industry.

## DCF (Discounted Cash Flow) Financial Model of Valuation:
The Discounted Cash Flow (DCF) model is a method of valuation used to estimate the value of an investment based on its expected future cash flow. It essentially calculates the present value of future cash flows, considering the "time value of money" principle, meaning that money received today is worth more than the same amount received in the future. 
Analysts use DCF to determine the value of an investment today, based on projections of how much money that investment will generate in the future. The DCF formula takes into account how much return you expect to earn, and the resulting value is how much you would be willing to pay for something to receive exactly that rate of return. If you pay less than the DCF value, your rate of return will be higher than the discount rate.

## Key Components of DCF:
* Free Cash Flow (FCF):
  * Represents the cash flow available to the company's investors after all expenses and reinvestment needs are met.
* Discount Rate:
  * The rate used to discount future cash flows to their present value. It reflects the investor's required rate of return or the cost of capital.
* Terminal Value:
  * Represents the value of the investment beyond the explicit forecast period, often calculated using a perpetuity growth model or a multiple of the terminal year's cash flow.

![image](https://github.com/user-attachments/assets/763b6d64-4285-4e7e-99b8-12dc7e8de9aa)

## Portfolio Project Overview:
A retail company is seeking to estimate the value of an investment based on its expected future cash flow.  
As a financial analyst, I created this DCF model for this retail company to analyze the company's Free Cash Flow, Revenue, COGS, Expenses, Current Assets, Current Liabilities, Accounts Payable, Accounts Receivables, etc.
As a Financial Analyst, I used DCF modeling to determine the value of an investment today, based on projections of how much money that investment will generate in the future.

## Business Problem Scenarios, Objectives and KPIs:
The finance manager in this retail company would like to assess the company’s current investment valuation based on projections of how much money that investment will generate in the future.

## Target Stakeholders:
This financial analysis tool will be used for the following job roles to increase their productivity and achieve business goals:
* Finance Manager
* Chief Finance Officer (CFO)
* Financial Analysts
* Business Analysts
* Financial Auditors

## Skills and Applications used: 
* Microsoft Excel 
  * Knowledge of formulae and functions to be used in any typical financial data analytical solutions.
  * Manipulations of Excel’s Table component to create DCF’s ‘Sensitivity Table’ 

* SME (Subject Matter Expertise)
  * Business requirement gathering skill and techniques.
  * Finance knowledge and expertise.
    * Free Cash Flow
    * Fixed Assets
    * Net Working Capital
    * Discounted Cash Flow
    * Weighted Average Cost of Capital
    * Income Statements
    * Balance Sheets
    * Statement of cash flows
    * Related all key line items
    * Types of assumptions: making forecast figures for future years.

## Solution Approach and Process to build this project:
I created a Discounted Cash Flow (DCF) model in the Worksheet’s DCF tab by referencing various line items from other worksheet tabs as described below. 

## Solution Steps (Discounted Cash Flow):
1.	Forecast the Free Cash Flow.
2.	Calculate the WACC (Weighted Average Cost of Capital).
3.	Calculate the Terminal Value.
4.	Discount the Free Cash Flow and Terminal Value.
5.	Calculate the Evaluation, Implied Share Price and a Sensitivity Table.


## Notes (for DCF Model):
### For “Forecasting the Free Cash Flow”:
* Please refer to the “Free Cash Flow” worksheet tab in the solution MS-Excel file (Uploaded in this portfolio).
* FCF (Free Cash Flows), I calculated for estimated years. A FCF is the cash flow available to both debt and equity holders after the business pays for everything it needs to continue operating (i.e. expenses, expenditure, etc.)
* Calculation for ‘Depreciation and Amortization’ is done in another worksheet tab (Fixed Asset). In this, I calculated ‘Beginning PP&E’, ‘D&A’, ‘CapEx’ etc. After calculations in the ‘Fixed Asset’ tab, I came back to the ‘Free Cash Flow’ tab to use these calculated values.
* Calculation for the NWC (Net-Working Capital) lines is done in another worksheet tab (Net Working Capital). I calculated Current Assets and Current Liabilities (Accounts Receivables, Accounts Payables, Inventory, Other Current Assets/Liabilities, etc.). After the calculations in the ‘Net-Working Capital’ tab, I came back to the ‘Free Cash Flow’ tab to use these calculated values.

### Calculation for the “Fixed Assets” worksheet tab:
* Please refer to the “Fixed Assets” worksheet tab in the solution MS-Excel file (Uploaded in this portfolio).
* In this, I calculated ‘Beginning PP&E’, ‘D&A’, ‘CapEx’, etc. After the calculations in this ‘Fixed Asset’ tab, I went back to the Free Cash Flow tab to use these calculated values in the ‘Depreciation and Amortization’ line.
* Made a few D&A and CapEx assumptions for the calculations in same worksheet.

### Calculation for the “Net Working Capital” worksheet tab:
* Please refer to the “Net Working Capital” worksheet tab in the solution MS-Excel file (Uploaded in this portfolio).
* I calculated Current Assets and Current Liabilities (Accounts Receivables, Accounts Payables, Inventory, Other Current Assets/Liabilities, etc.).  After the calculations in this ‘Net-Working Capital’ tab, I went back to the ‘Free Cash Flow’ tab to use these calculated values in the NWC (Net-Working Capital) lines.
* For the calculations, I created some simplified assumptions in the related worksheets which are being used in my analysis calculations. More sophisticated assumptions can also be used to enhance this DCF financial model.
  * Days Sales Outstanding (DSO) is the number of days it takes for a company to collect the payment on a sale.
  * Days Inventory Outstanding (DIO) is the number of days it takes a company to sell its inventory.
  * Days Payable Outstanding (DPO) is the number of days it takes a company to pay for its bills.


### Calculation for the “DCF” worksheet tab. (Discounted Cash Flow):
* I calculated the ‘Unlevered Free Cash Flow’ line values (actual and estimated). I also discounted these values using assumed discounted rates. This is related to step #2 of this solution, i.e., calculating the WACC (Weighed Average Cost of Capital).
* Financial formula for WACC can be referred to in the screenshots below.
* Financial formula for Terminal Value can be referred to in the screenshots below.

### Calculation for the “WACC” worksheet tab (Weighted Average Cost of Capital):
* I made a few assumed calculations for the debt using balance sheet data. Also, I used some data from Bloomberg as a source (Equity, Tax Rate, Market Return, etc.)
* I calculated line items such as ‘After tax cost of debt’ and ‘Cost of equity’. I calculated Cost of Equity; I used CAPM (Capital Asset Pricing Model).  In the CAPM formula, the 'Beta' measures the volatilities of an asset relative to the market.
* After calculating the WACC value, I went back to the ‘DCF’ worksheet tab and plugged-in the WACC line item over there.

### Calculation for the “Terminal Value” (for Step #3):
* There are various methods of calculating the ‘Terminal Value. In this project, I used the ‘Perpetuity Growth Method’.
* I made a few assumptions such as ‘Growth Rate’.

### Calculation for Discounting the “Free Cash Flow” and “Terminal Value” (for Step#4):
* I used previously calculated values such as the ‘sum of present values of FCF’, ‘Present value of terminal value’, and ‘Enterprise value’. 


### Calculation for the “Implied Share Price” (for Step #5):
* To calculate the implied share price, I used ‘Equity value’. For this I calculated few line items in the “DCF” worksheet tab first (such as Cash, Debt, Minority Interest). Based on the situation, some companies may not have ‘Minority Interest’.
  * Cash is calculated from the ‘Balance Sheet’ worksheet. (‘Cash and Cash Equivalents’ line item).
  * Debt is calculated from the ‘WACC’ worksheet. (‘Debt(mm)’ line item). 
  * Minority Interest is calculated from the ‘Balance Sheet’ worksheet. (‘Non-Controlling Interests’ line item).
* After calculating Enterprise Value, Cash, Debt, and Minority Interest values- I calculated the “Implied Share Price”.
* For the above calculations, I made a few assumptions such as ‘Growth Rate’. So, if I change the growth rate value in my model, it changes the Implied share Price accordingly. These calculations also get impacted when we change the WACC value assumption. This makes my model dynamic for financial analysis. 

### Calculation for the “Sensitivity Table” (in DCF worksheet tab):
* This “Sensitivity Table” analysis implies share prices with respect to the “Growth Rate” & “Weighted Average Cost of Capital” 
  * I plugged in values for the Growth Rate (in X-Axis) and WACC (in Y-Axis) for the table.
  * I used MS-Excel’s “What-If Analysis” tool. I chose the ‘Data Table’ with input row and column cell.
  * Now, this sensitivity table shows all Implied Share prices depending on how the Growth Rate changes or how WACC changes.

## Data Preparation Process (Data gathering, Data Cleaning, Data Transformation): 
* Data Gathering – The Dataset (Microsoft Excel/ CSV File).
  * Data Sheet: 5 tabs in the MS-Excel workbook (Free Cash Flow, Fixed Assets, Net Working Capital, DCF, and WACC).
  * Few Data Sources for calculations: (Income Statement, Balance Sheet, Cash Flow Statement)
  * Few assumptions in each tab for modeling.
* Data Pre-Processing and Transformation.
  * Cell formatting and proper cell indentation, as per financial reports standards.
  * Calculations for totals and sub-totals for report line items.
  * Creating new custom formatting for columns

## Data Analysis & Visualization –Reports, Charts, Key findings, Data Insights:
* This “Sensitivity Table” analysis implies share prices with respect to “Growth Rate” & “Weighted Average Cost of Capital” 
  * I plugged in values in the Growth Rate (in X-Axis) and WACC (in Y-Axis) for the table.
  * I used MS-Excel’s “What-If Analysis” tool.  I chose the ‘Data Table’ with an input row and column cell.
  * Now, this sensitivity table shows all “Implied Share prices” depending on how Growth Rate changes or how WACC changes.
* Used proper visual formatting as per financial reports standards – Totals, Sub-Totals, Bold, Underlines, etc.
* No visualization charts were required for this project.
* Refer to the screenshots below for reports on this solution.

## Portfolio Project Documentation (Final Conclusion):
### Documentation: 
* ReadMe-Financial-Analysis-DCF Financial Model-Excel.docx
### Output File:
* Financial-Analysis-DCF Financial Model.xlsx

## Blank/Empty DCF Modeling Template File (starting point for DCF modelling):
![image](https://github.com/user-attachments/assets/1706dfbc-2af5-4a5c-a16b-34ca34890d4f)

## Completed/Processed Model: (Discounted Cash Flow)
![image](https://github.com/user-attachments/assets/7e3813dd-0c46-4675-83ee-d9ab7b128e4a)

## Completed/Processed Model: (DCF Model – Sensitivity Table for Implied Share Prices)
![image](https://github.com/user-attachments/assets/4a822531-da26-4893-8b3b-658769dde94f)

## Completed/Processed Worksheet: (Free Cash Flow)
![image](https://github.com/user-attachments/assets/cfa4d743-b554-4fa6-8a9c-2434247b6fc8)

## Completed/Processed Worksheet: (Fixed Assets)
![image](https://github.com/user-attachments/assets/2f6a9860-9a7a-49e6-b5af-686a3a58980e)

## Completed/Processed Worksheet: (Net Working Capital)
![image](https://github.com/user-attachments/assets/bd505f8a-e41a-486c-b621-76749cb8ef98)

## Completed/Processed Worksheet: (Weighted Average Cost of Capital)
![image](https://github.com/user-attachments/assets/d1029943-8e8d-4283-b6e7-1afb031f31ac)

## Other Data Sources for Calculations: (Income Statement, Balance Sheet, Cash Flow statement)
![image](https://github.com/user-attachments/assets/385e4d0d-fb5a-4f9d-ad4f-435b67b37faf)

## Discounted Cash Flow Steps:
![image](https://github.com/user-attachments/assets/5227d497-c836-4f88-a059-78525f74ed2c)

## Formula: CAPM (Capital Asset Pricing Model)
![image](https://github.com/user-attachments/assets/a7c7c2f5-fe93-42bf-895d-e2ec95b41153)

## Formula: WACC (Weighted Average Cost of Capital)
![image](https://github.com/user-attachments/assets/cd003150-e933-499d-846f-338f95f214ee)

## Formula: Non-Cash Working Capital
![image](https://github.com/user-attachments/assets/a0974e41-9fb8-494e-b40b-b9238412a977)

## Formula: Free Cash Flow 
![image](https://github.com/user-attachments/assets/91a96f8b-e2ea-43ef-8617-124c9ff660db)























