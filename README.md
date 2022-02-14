# Web Coding Challenge

Create a web app to enter receipts into an expense report.

Use any code editor, tools, 3rd party libraries and online resources you like.

## Requirements:

1. The expense report can have **up to 5 receipts**.

2. Each receipt should have a **description**, **amount** and **currency**.
  - Any receipt can be entered in any of the supported currencies.

3. Each receipt should show its **amount in EUR**
  - Get exchange rates from http://api.exchangeratesapi.io/v1/latest?access_key=ACCESS_KEY_GOES_HERE

4. There should be a **total for the entire expense report, in EUR**, which should be displayed at the bottom of all receipts.

5. It should **prevent you from submitting a report totalling over 1,000 EUR**
   - If the total amount of all receipts exceeds €1,000 it should disable the submit button and display a message stating that the expense report limit has been exceeded.

6. There should be a button to **submit the expense report**, which will log the receipt data to the browser's dev tool console.

## Time management

You'll have 60 minutes to complete as much as you can.  If you have less time then don't worry about it -- this will be taken into account when we evaluate your solution.

*Time-saving tip*: It's OK for the page to represent a single expense report with no options to reset it or create another one.  You also don't need to keep or show any previously submitted reports.

## Extra credit

If you have extra time, you can **optionally** try to complete one or more of the following:
- Make it look nice
- Cache the exchange rates for 10 seconds at a time


## Evaluation criteria

- Don't over-engineer just to show us that you know Framework X or Y.
   - It matters more that you get it done, and that the solution is sensible given the simple requirements and the time constraints
- Your code should be organized, and it should be something you're relatively proud to have done in the limited time available
   - Quality matters more than the sheer number of requirements you implemented
