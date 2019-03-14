# Slicing Exercise

This is an exercise about narrowly slicing features into tiny stories that can be rapidly built and released. This will feel "extreme"... but if the business would benefit from an approach like this, could you do it? Would you?

Rules:
* Pair up with a buddy
* Decide your test strategy: Test First (TDD), Test After, or No Tests
* Read the Acceptance Criteria below and write as many small-but-meaningful deliverable stories as you can.
* We will code in 7-minute segments. After each segment, you must demo your code to another team (and it should work!).
* Be thinking about the experience. How does it feel to work this way? Pros and cons?

## Acceptance Criteria

Write a program that accepts 3 inputs from the user:
* How many items
* Price per item
* 2-letter state code

The program should output the total price. Give a discount based on the total price, add state tax based on the state and the discounted price. **Apply discount first, tax second.**

**Discount Rates**

| Order Value | Discount Rate |
|---|---|
| $1,000 | 3% |
| $5,000 | 5% |
| $7,000 | 7% |
| $10,000 | 10% |
| $50,000 | 15% |

**Taxes**

| State | Tax Rate |
|---|---|
| UT | 6.85% |
| NV | 8.00% |
| TX | 6.25% |
| AL | 4.00% |
| CA | 8.25% |

## Run the Code

Run the script: `python slicing.py`

Run the unit tests: `python tests.py`