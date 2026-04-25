# Term Structure of Interest Rates

The term structure of interest rates describes the relationship between a security's **term to maturity** and its **annualized yield**. This relationship is visualized as the **Treasury yield curve** — a plot of Treasury yields across different maturities.

## Three Theories Explaining the Term Structure

### 1. Pure Expectations Theory

The yield curve is determined **solely by market expectations of future interest rates**.

- If rates are expected to rise → long-term yields > short-term yields → **upward-sloping curve**
- If rates are expected to stay flat → long-term yields ≈ short-term yields → **flat curve**
- If rates are expected to fall → long-term yields < short-term yields → **downward-sloping (inverted) curve**

#### Forward Rate Concept

Investors can either:
- Buy a 2-year security now, OR
- Buy a 1-year security now and reinvest in another 1-year security later

In equilibrium, expected returns should be equal:

$$
(1 + {}_t i_2)^2 = (1 + {}_t i_1)(1 + {}_{t+1}r_1)
$$

Where:
- ${}_t i_2$ = known 2-year rate today
- ${}_t i_1$ = known 1-year rate today
- ${}_{t+1}r_1$ = one-year forward rate (expected 1-year rate one year from now)

Solving for the forward rate:

$$
{}_{t+1}r_1 = \frac{(1 + {}_t i_2)^2}{1 + {}_t i_1} - 1
$$

**Example:** If 1-year rate = 8% and 2-year rate = 10%:

$$
{}_{t+1}r_1 = \frac{(1.10)^2}{1.08} - 1 = 12.037\%
$$

This means the market expects the 1-year rate one year from now to be approximately **12.04%**.

#### Yield Curve Shapes and Expectations

| Forward Rate vs. Current Rate | Yield Curve Shape | Rate Expectation |
|-------------------------------|-------------------|------------------|
| ${}_{t+1}r_1 > {}_t i_1$ | Upward sloping | Rates expected to rise |
| ${}_{t+1}r_1 = {}_t i_1$ | Flat | Rates expected to stay same |
| ${}_{t+1}r_1 < {}_t i_1$ | Downward sloping | Rates expected to fall |

#### Extended Forward Rates

For longer horizons:

$$
(1 + {}_t i_3)^3 = (1 + {}_t i_1)(1 + {}_{t+1}r_1)(1 + {}_{t+2}r_1)
$$

This allows chaining forward rates to estimate expected rates further into the future.

#### Stability of Long-Term Rates

Long-term rates are the geometric average of expected short-term rates. Because averaging smooths out fluctuations, **long-term rates are more stable than short-term rates**.

### 2. Liquidity Premium Theory

Some investors prefer short-term securities because they are more liquid. To hold long-term securities, they demand a **liquidity premium**.

With liquidity premium, the forward rate formula becomes:

$$
(1 + {}_t i_2)^2 = (1 + {}_t i_1)(1 + {}_{t+1}r_1) + LP_2
$$

Or rearranged:

$$
{}_{t+1}r_1 = \frac{(1 + {}_t i_2)^2}{1 + {}_t i_1} - 1 - \frac{LP_2}{1 + {}_t i_1}
$$

**Key insight:** Forward rates derived from pure expectations theory **overstate** expected future rates because they ignore the liquidity premium. Accounting for it gives lower, more accurate forecasts.

**Impact on yield curve:**
- Even if rates are expected to stay flat, the liquidity premium creates an **upward slope**
- If rates are expected to rise, the curve slopes up even more steeply
- If rates are expected to fall, the liquidity premium partially offsets the decline

### 3. Segmented Markets Theory (and Preferred Habitat)

Different maturity markets operate somewhat independently based on the **preferences and needs** of participants.

#### Market Participants by Maturity Preference

- **Pension funds & life insurance companies** → prefer long-term bonds (match long-term liabilities)
- **Commercial banks** → prefer short-term investments (match short-term deposits)
- **Corporations** → choose maturities based on funding needs, not rate expectations

#### How Imbalances Shape the Curve

| Scenario | Investor Supply | Borrower Demand | Result on Curve |
|----------|-----------------|-----------------|-----------------|
| Upward slope | Short-term funds abundant | Long-term borrowing heavy | Short yields down, long yields up |
| Downward slope | Long-term funds abundant | Short-term borrowing heavy | Short yields up, long yields down |
| Balanced | Matched across maturities | Matched across maturities | Relatively flat |

#### Preferred Habitat Theory

A compromise: investors and borrowers normally stay in their preferred maturity segments, but **certain events or sufficiently attractive yields** can entice them to switch. This acknowledges that both maturity preferences AND interest rate expectations matter.

## Integrating All Three Theories

Research suggests all three theories have validity. The actual yield curve reflects:

1. **Expectations** about future rates (expectations theory)
2. **Liquidity preferences** (liquidity premium theory)
3. **Maturity market imbalances** (segmented markets theory)

When all three push in the same direction (e.g., expected rising rates + investor preference for short-term liquidity + borrowers needing long-term funds), the yield curve becomes very steep.

## Practical Applications

### Forecasting Interest Rates
- Upward slope → higher rates expected
- Inverted slope → lower rates expected

### Forecasting Recessions
- Flat or inverted yield curves often precede recessions
- March 2007 slight inversion preceded the December 2007 recession
- An **upward-sloping curve** is generally a normal/healthy signal (growth expectations)
- An **inverted curve** is a warning sign that rates are expected to fall due to economic weakness

### Investment Strategy: "Riding the Yield Curve"
- Buy longer-term securities for higher yields even with short-term horizons
- Sell in secondary market when cash is needed

### Financing Decisions
- Upward-sloping curve → firms may prefer short-term borrowing with plans to refinance
- But this carries risk if rates rise

## Related Topics

- [[Loanable Funds Theory]] — macro framework for interest rate determination
- [[Why Debt Security Yields Vary]] — term to maturity is one of the four key yield drivers
- [[Modeling the Yield to be Offered on a Debt Security]] — uses the risk-free rate, which depends on term structure
- [[Factors That Affect Interest Rates]] — how Fed policy shapes the baseline rate
- [[Week 2 - Determination of Interest Rates and Structure of Interest Rates|Week 2 Hub]]

---

> **Course**: Financial Markets — Week 2
> **Status**: Learned
> **Date**: 2026-04-25
