### 1. Payback Period Method

The Payback Period is a simple way to figure out how long it takes for an investment (like buying a machine) to pay back its initial cost through the money it earns (cash inflows). It's like asking, "How many years until I get my money back?"

#### Key Formula for Equal Cash Flows:
Payback Period = Initial Investment / Annual Cash Inflow

#### Step-by-Step Explanation:
1. **Understand the Basics**: You start with the total cost of the project (initial cash outflow). Then, look at the money coming in each year (cash inflows). The payback period is the time needed for the inflows to equal the outflow.
2. **For Equal Cash Flows (same amount every year)**:
   - Divide the initial cost by the yearly cash inflow.
   - Example: Initial cost = Rs. 350,000. Annual cash inflow = Rs. 50,000 for 10 years.
     - Calculation: 350,000 / 50,000 = 7 years.
     - Meaning: It takes 7 years to recover the cost.
3. **Another Example**: Initial cost = Rs. 12,500. Annual cash inflow = Rs. 50,000 for 7 years? Wait, that seems off in the text, but assuming Rs. 50,000 inflow and Rs. 12,500 cost: 12,500 / 50,000? No, the text says for Rs. 50,000 inflow and Rs. 12,500 cost? Actually, in the image: Assume inflow of Rs. 12,500 for 7 years, payback = Rs. 50,000 / 12,500 = 4 years. (The numbers are swapped in the text, but the idea is the same: divide cost by inflow.)
4. **Why Use It?**: It's quick and focuses on getting money back fast, good for risky projects.

#### Payback Period - Unequal Cash Flows
When cash inflows are different each year, you can't just divide. You add up the inflows year by year until you cover the cost.

#### Step-by-Step:
1. **List the Cash Flows**: Initial cost and yearly inflows.
2. **Add Cumulatively**: Keep adding inflows until the total matches or exceeds the cost.
3. **Calculate the Exact Period**:
   - Find the year where the cumulative inflow just covers the cost.
   - If there's a remainder, add a fraction: (Remaining cost / Next year's inflow) in months or years.
   - Example: Initial cost = Rs. 20,000. Inflows: Year 1 = Rs. 8,000; Year 2 = Rs. 7,000; Year 3 = Rs. 4,000; Year 4 = Rs. 3,000.
     - Cumulative: After Year 1 = 8,000 (remaining 12,000).
     - After Year 2 = 15,000 (remaining 5,000).
     - After Year 3 = 19,000 (remaining 1,000).
     - In Year 4, you need only 1,000 out of 3,000.
     - Fraction: 1,000 / 3,000 = 1/3 year = 4 months.
     - Total: 3 years + 4 months.

#### Acceptance Rule:
1. **For Single Project**: Accept if payback period is less than or equal to the company's maximum allowed period (e.g., if max is 5 years, accept if 4 years or less).
2. **For Ranking Projects**: Choose the one with the shortest payback period (quicker recovery is better).

#### Merits (Advantages) of Payback Period:
- Simple to calculate.
- Cost-effective (no complex math needed).
- Focuses on short-term recovery.
- Reduces risk by shielding from long-term uncertainties.
- Improves liquidity (quick cash back).

#### Demerits (Disadvantages):
- Ignores cash flows after the payback period (misses long-term profits).
- Doesn't consider the time value of money (money today is worth more than later).
- Ignores patterns of cash flows.
- Can be inconsistent with shareholder value (doesn't maximize wealth).

### Payback Reciprocal and the Rate of Return
This is a quick way to estimate the rate of return using payback.

#### Step-by-Step:
1. **What It Is**: Payback Reciprocal = 1 / Payback Period (or Annual Cash Inflow / Initial Investment).
2. **When It Works**: It's a close guess for Internal Rate of Return (IRR) if:
   - Project life is long (at least twice the payback period).
   - Equal annual cash inflows.
3. **Example**: If payback = 7 years, reciprocal = 1/7 ≈ 14.29%. This approximates IRR under those conditions.

### Discounted Payback Period
This is like regular payback but accounts for the time value of money by discounting future cash flows.

#### Step-by-Step:
1. **Discount Cash Flows**: Use a discount rate (e.g., 10%) to find present value (PV) of each inflow.
   - PV = Cash Flow / (1 + rate)^year.
2. **Add Cumulatively**: Add discounted inflows until they equal the initial cost.
3. **Calculate Period**: Similar to unequal payback, but with discounted values.
4. **Example from Table**:
   - Initial cost = Rs. 4,000 (assuming C0 = -4,000).
   - Discounted inflows: Year 1 = 3,000 → PV=2,727; Year 2=1,000→PV=826, etc.
   - Cumulative PV: Add until it covers 4,000.
   - It still ignores post-payback flows.

### 3. Net Present Value (NPV) Method
NPV calculates if a project is worth it by comparing the present value of money coming in vs. going out. It considers time value of money.

#### Step-by-Step Explanation:
1. **Forecast Cash Flows**: Estimate outflows (costs) and inflows (earnings).
2. **Choose Discount Rate**: This is the opportunity cost (e.g., 10% - what you could earn elsewhere).
3. **Calculate Present Value (PV)**:
   - For each cash flow: PV = Cash Flow / (1 + rate)^year.
   - Example: Cash inflow Rs. 1,000 in Year 1 at 10%: PV = 1,000 / 1.10 = 909.
4. **NPV Formula**:
   - NPV = Sum of PV of Inflows - PV of Outflows.
   - Or: NPV = [C1/(1+k) + C2/(1+k)^2 + ... + Cn/(1+k)^n] - C0 (initial cost).
5. **Example 4**: Initial outflow Rs. 1,00,000. Inflows: Year 1=20,000 (PV=18,018 at 10%); Year 2=25,000 (PV=20,650); etc.
   - Total PV inflows = 97,441. NPV = 97,441 - 1,00,000 = -2,559 (negative, so reject).
6. **Another Example**: Project X: Outflow 20,000. Inflows 30,000 (Y1), 20,000 (Y2), 10,000 (Y3).
   - PVs at 10%: 27,027 + 16,052 + 7,510 = 50,589. NPV = 50,589 - 20,000 = 30,589 (positive).
7. **For Unequal Flows**: Use the formula with summation.

#### Present Value Table:
- It's a chart showing PV factors for different rates and years (e.g., at 10% Year 1=0.909, Year 2=0.826).
- Multiply cash flow by factor to get PV.

#### Acceptance Rule for NPV:
- Accept if NPV > 0 (adds value).
- Reject if NPV < 0 (loses value).
- Indifferent if NPV = 0.
- For multiple projects: Choose the one with highest NPV (if exclusive).

#### Merits (Advantages) of NPV:
- Most acceptable rule.
- Considers time value.
- Measures true profitability.
- Value-additive (adds to firm value).
- Maximizes shareholder value.

#### Demerits (Disadvantages):
- Hard to estimate cash flows accurately.
- Choosing discount rate is tricky.
- Mutually exclusive projects hard to rank if different sizes.
- Ranking issues.

### Internal Rate of Return (IRR) Method
IRR is the discount rate that makes NPV zero. It's the project's "return rate."

#### Step-by-Step:
1. **Formula**: Set NPV = 0 and solve for r (rate).
   - 0 = Sum [Ct / (1+r)^t] - C0.
2. **For Level (Equal) Cash Flows**:
   - Use annuity formula: PVA = C * [1 - (1/(1+r)^n)] / r.
   - Example: Cost Rs. 20,000, annual inflow Rs. 5,430 for 6 years.
     - PVA factor = 20,000 / 5,430 ≈ 3.683.
     - Look up in table for 6 years: Around 15% (factor 3.784, close).
3. **For Uneven Cash Flows**: Trial and Error.
   - Guess a low rate, calculate NPV (if positive, try higher rate).
   - Guess high rate (if NPV negative).
   - Interpolate: IRR = Low rate + [(NPV low / (NPV low - NPV high)) * (High - Low)].
4. **NPV Profile**: Plot NPV vs. discount rates. IRR is where it crosses zero.

#### Acceptance Rule for IRR:
- Accept if IRR > k (cost of capital).
- Reject if IRR < k.
- Indifferent if IRR = k.
- For independent projects: IRR and NPV usually agree.
- For mutually exclusive: Higher IRR may not mean better if scales differ.

This covers all topics from the images in a simple, step-by-step way! If you need more examples or clarification, let me know.
