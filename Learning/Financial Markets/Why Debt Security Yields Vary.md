# Why Debt Security Yields Vary

Not all debt securities offer the same yield, even in the same interest rate environment. Four key characteristics explain why quoted yields differ across securities.

## Four Key Characteristics

### 1. Credit Risk (Default Risk)

The risk that the issuer fails to make promised interest or principal payments.

- Higher credit risk → investors demand a **credit risk premium** (higher yield)
- Treasury bonds are the baseline: virtually no default risk, so they offer the lowest yields
- Corporate bonds must offer yields above Treasuries to compensate for default risk

**Example:**
- Treasury bond yield = 7%
- Zanstell Co. bond yield = 8% (1% credit risk premium)

**Bond Ratings:** Agencies like Moody's and S&P assess creditworthiness:

| Quality | Moody's | S&P |
|---------|---------|-----|
| Highest | Aaa | AAA |
| High | Aa | AA |
| High-medium | A | A |
| Medium (investment grade) | Baa | BBB |
| Medium-low | Ba | BB |
| Low (speculative) | B | B |
| Poor | Caa | CCC |
| Very poor | Ca | CC |
| In default | C | D |

Investment grade threshold: Baa/BBB or better. Below that is "junk" or speculative grade.

Credit risk premiums vary: ~1% for highly rated bonds, ~2.5% for medium quality, ~5% for low quality.

### 2. Liquidity

How easily a security can be sold quickly without significant loss of value.

- More liquid securities → lower yield needed (investors accept less because they can exit easily)
- Less liquid securities → **liquidity premium** required (higher yield to compensate for exit difficulty)
- Short-term securities and those with active secondary markets are more liquid
- Treasury bonds are the most liquid; small corporate issues may be illiquid

### 3. Tax Status

Tax treatment of interest income affects the yield investors actually keep.

**After-tax yield formula:**

$$
Y_{at} = Y_{bt}(1 - T)
$$

Where:
- `Y_at` = after-tax yield
- `Y_bt` = before-tax yield
- `T` = investor's marginal tax rate

**Key tax treatments:**
- Treasury interest: federally taxable, **state tax-exempt**
- Municipal bonds: often **federally and state tax-exempt**
- Corporate bonds: fully taxable

To match a tax-exempt yield, a taxable security must offer:

$$
Y_{bt} = \frac{Y_{at}}{1 - T}
$$

### 4. Term to Maturity

The length of time until the security matures. Longer maturities typically require higher yields due to greater uncertainty and price sensitivity to rate changes.

This is so important it gets its own detailed treatment in [[Term Structure of Interest Rates]].

## Core Principle

> If all other characteristics are equal, securities with **unfavorable characteristics** must offer **higher yields** to entice investors to buy them.

Investors constantly trade off: "Is the extra yield worth the extra risk, lower liquidity, or worse tax treatment?"

## Yield Gap Dynamics

The difference in yield between a risky/illiquid bond and a Treasury bond represents the market's **"price of risk and inconvenience."** When a borrower's credit rating improves (e.g., from B to BB), the **credit risk premium shrinks**, causing the yield gap to narrow. Conversely, if creditworthiness deteriorates, the gap widens.

## Related Topics

- [[Debt Securities]] — types and characteristics of debt instruments
- [[Term Structure of Interest Rates]] — detailed analysis of how maturity affects yields
- [[Loanable Funds Theory]] — the macro framework for interest rate determination
- [[Liquidity]] — concept from Week 1 on ease of converting to cash
- [[Modeling the Yield to be Offered on a Debt Security]] — practical application of these premiums
- [[Week 2 - Determination of Interest Rates and Structure of Interest Rates|Week 2 Hub]]

---

> **Course**: Financial Markets — Week 2
> **Status**: Learned
> **Date**: 2026-04-25
