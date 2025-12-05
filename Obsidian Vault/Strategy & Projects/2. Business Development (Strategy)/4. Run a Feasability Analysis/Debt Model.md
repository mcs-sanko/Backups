
Excellent — this is a deep and essential question.  
To **describe any type of debt comprehensively**, we need a **unified debt taxonomy** — a way of representing _all possible_ debt instruments using a consistent set of descriptive parameters.

Let’s build that framework step by step.

---

## 🧩 The Comprehensive Framework for Describing Any Debt Type

Every debt instrument, no matter how exotic, can be fully defined by describing the following **nine dimensions**:

---

### **1. Purpose & Seniority**

Defines **what the debt is for** and **where it sits in repayment priority**.

|Parameter|Description|Examples|
|---|---|---|
|**Purpose**|What the debt funds|CapEx loan, acquisition financing, working capital, refinancing|
|**Seniority**|Claim priority on cash flow/assets|Senior secured, subordinated, mezzanine, junior, shareholder loan|
|**Security**|Whether collateralized|Secured (asset pledge, mortgage), unsecured|
|**Recourse**|Who bears risk|Full recourse (to sponsor), limited recourse, non-recourse (project finance)|

---

### **2. Currency & Tenor**

Defines the **financial exposure** and **duration**.

| Parameter              | Description                  | Examples                     |
| ---------------------- | ---------------------------- | ---------------------------- |
| **Currency**           | Base currency of the loan    | USD, EUR, TRY, etc.          |
| **Tenor / Maturity**   | Total life of the debt       | 7 years, 15 years, perpetual |
| **Grace period**       | Time before repayments start | 2 years construction period  |
| **Refinancing option** | Can it be rolled over?       | Yes/No                       |

---

### **3. Drawdown & Commitment Structure**

Defines **how the borrower accesses the funds**.

| Parameter               | Description                        | Examples                                           |
| ----------------------- | ---------------------------------- | -------------------------------------------------- |
| **Availability period** | Period funds can be drawn          | During construction phase                          |
| **Drawdown method**     | Lump-sum, staged, or revolving     | Single draw, progress-based draw, revolving credit |
| **Undrawn fee**         | Fee on committed but undrawn funds | 0.5% p.a. commitment fee                           |

---

### **4. Interest & Yield Structure**

Defines the **cost of borrowing** and how it evolves.

| Parameter                  | Description                                    | Examples                                |
| -------------------------- | ---------------------------------------------- | --------------------------------------- |
| **Base rate**              | Reference rate for interest                    | Fixed rate, LIBOR, SOFR, CPI, repo rate |
| **Margin / Spread**        | Added to base rate                             | +200 bps                                |
| **Type**                   | Fixed, floating, step-up, or hybrid            | Fixed 5%, Floating SOFR+2%              |
| **Compounding convention** | How interest accrues                           | Simple, compounded monthly, quarterly   |
| **Capitalization**         | Whether interest is paid or added to principal | Pay-as-you-go, PIK (payment-in-kind)    |
| **Hedging**                | Interest rate swaps, caps, collars             | Optional overlay                        |

---

### **5. Repayment Profile**

Defines **how principal is repaid**.

| Parameter             | Description                             | Examples                                            |
| --------------------- | --------------------------------------- | --------------------------------------------------- |
| **Repayment start**   | After grace period                      | Month 25                                            |
| **Structure**         | Manner of repayment                     | Equal principal, annuity, bullet, balloon, sculpted |
| **Frequency**         | Interval between repayments             | Quarterly, semi-annual, annual                      |
| **Prepayment option** | Early repayment allowed?                | Yes/No, with or without penalty                     |
| **Cash sweep**        | Accelerated repayment with surplus cash | Optional/mandatory                                  |

---

### **6. Covenants & Tests**

Defines **conditions that protect the lender**.

|Parameter|Description|Examples|
|---|---|---|
|**Financial covenants**|Minimum coverage ratios|DSCR ≥ 1.20x, LLCR ≥ 1.40x|
|**Operational covenants**|Restrictions on borrower’s behavior|No dividend if DSCR < 1.10x|
|**Information covenants**|Reporting requirements|Quarterly financials, audited statements|
|**Default triggers**|Events that cause default|Missed payment, breach of ratio, insolvency|

---

### **7. Security Package & Reserves**

Defines **what protects repayment**.

|Parameter|Description|Examples|
|---|---|---|
|**Collateral**|Pledged assets|Power plant, shares, receivables|
|**Guarantees**|Support instruments|Parent guarantee, performance bond|
|**Reserves**|Dedicated cash accounts|DSRA (Debt Service Reserve Account), MRA (Maintenance Reserve)|
|**Escrow / Control accounts**|Waterfall-managed accounts|Revenue account, O&M account, debt service account|

---

### **8. Conversion & Optionality**

Defines **embedded options or hybrid features**.

|Parameter|Description|Examples|
|---|---|---|
|**Convertibility**|Can debt become equity?|Convertible bonds, warrants|
|**Subordination trigger**|Becomes junior upon condition|Covenant breach|
|**Step-up/down clauses**|Margin adjusts with performance|Margin +0.5% if DSCR < 1.10x|
|**Callable / Puttable**|Early redemption rights|Callable by borrower after 3 years|

---

### **9. Jurisdiction & Legal Terms**

Defines **the governing environment** and enforcement.

|Parameter|Description|Examples|
|---|---|---|
|**Governing law**|Legal system governing the contract|English law, Turkish law|
|**Jurisdiction**|Court for disputes|London courts|
|**Documentation standard**|LMA, ISDA, local form|LMA facility agreement|
|**Tax treatment**|Withholding tax, deductibility|WHT 10%, interest tax deductible|

---

## 🧠 Optional Analytical Dimensions

You can also add **model-oriented** descriptors:

|Category|Purpose|
|---|---|
|**Effective Interest Rate (EIR)**|For accounting under IFRS|
|**Debt Service Profile**|To compute DSCR, LLCR|
|**WACC contribution**|For blended financing cost|
|**Credit Rating / Risk Profile**|For cost of capital and sensitivity|
|**Scenario tags**|Base case, downside, upside|

---

## ✅ Putting It All Together

Any debt instrument — from a **plain vanilla term loan** to a **convertible subordinated inflation-linked mezzanine tranche** — can be expressed as:

> **Debt Instrument = {Purpose, Seniority, Currency, Tenor, Drawdown, Interest, Repayment, Covenants, Security, Optionality, Jurisdiction}**

---

### 📘 Example 1 — Senior Term Loan (Project Finance)

```
Purpose: Fund CapEx
Seniority: Senior secured, non-recourse
Currency: EUR
Tenor: 15 years, 3-year grace
Drawdown: Progressive during construction
Interest: EURIBOR + 2.25%, quarterly, floating
Repayment: Sculpted to 1.25x DSCR, semiannual
Covenants: DSCR ≥ 1.15x, dividend lock-up <1.25x
Reserves: 6-month DSRA
Optionality: No convertibility, callable after 5 years
Jurisdiction: English law
```

### 📘 Example 2 — Mezzanine Loan

```
Purpose: Bridge finance
Seniority: Subordinated, unsecured
Currency: USD
Tenor: 7 years
Drawdown: Lump sum
Interest: 10% fixed, PIK during grace period
Repayment: Bullet at maturity
Covenants: None beyond reporting
Optionality: Convertible to equity at IPO
Jurisdiction: Delaware law
```

---

Would you like me to turn this into a **parameter table schema or data structure** (for example, JSON, Excel field list, or Python class structure) so that any debt can be programmatically modeled or described?













Perfect — we’re now formalizing your **“universal debt definition library”**, the kind of backbone used in advanced financial modeling engines and structured finance databases.

Let’s go in **two steps**:

1. **A complete parameter schema**:  
    → All parameters, possible values, and what they _mean in practice_.
    
2. **Predefined parameter sets**:  
    → Ready-to-use templates for common real-world debt types.
    

---

## 🧩 1. Complete Debt Parameter Schema

Below is the **definitive list** of parameters that can describe _any_ debt instrument, grouped by category.

---

### **A. Purpose & Nature**

|Parameter|Possible Values|Meaning in Practice|
|---|---|---|
|**Purpose**|`Capex`, `Acquisition`, `WorkingCapital`, `Refinancing`, `Bridge`, `Guarantee`, `TradeFinance`|Defines what the loan funds. Influences drawdown and repayment structure.|
|**RecourseType**|`FullRecourse`, `LimitedRecourse`, `NonRecourse`|Determines who is liable. In project finance, _non-recourse_ means lenders only have claim on project cash flows and assets.|
|**Seniority**|`Senior`, `Subordinated`, `Mezzanine`, `Junior`, `ShareholderLoan`|Defines priority in repayment: • _Senior_ → paid first, lowest risk • _Subordinated_ → paid after senior • _Mezzanine_ → sits between senior and equity • _Junior_ → even lower priority • _Shareholder loan_ → treated as quasi-equity|
|**SecurityType**|`Secured`, `Unsecured`, `PartiallySecured`|_Secured_ loans have collateral; _unsecured_ rely on borrower creditworthiness.|

---

### **B. Currency & Tenor**

|Parameter|Possible Values|Meaning|
|---|---|---|
|**Currency**|ISO codes (USD, EUR, TRY, GBP, etc.)|Defines exposure and FX risk.|
|**TenorYears**|Integer (e.g., 5, 10, 20)|Total life of the debt until maturity.|
|**GracePeriodYears**|Integer|Period during which no principal is repaid. Common in construction phases.|
|**RefinanceOption**|`Yes`, `No`, `Conditional`|Whether the debt can be refinanced before maturity.|

---

### **C. Drawdown & Commitment**

|Parameter|Possible Values|Meaning|
|---|---|---|
|**DrawdownType**|`Single`, `Multiple`, `Revolving`, `ProgressBased`, `Contingent`|Defines how and when funds are drawn. Revolving = can re-borrow after repayment; Contingent = only drawn if event occurs.|
|**AvailabilityPeriodYears**|Integer|Period during which borrower can draw funds.|
|**CommitmentFeeRate**|%|Fee charged on undrawn but committed amounts.|

---

### **D. Interest & Yield**

|Parameter|Possible Values|Meaning|
|---|---|---|
|**BaseRateType**|`Fixed`, `Floating`, `Indexed`, `ZeroCoupon`|• _Fixed_ = static rate • _Floating_ = reference + margin (e.g., SOFR + 2%) • _Indexed_ = inflation or commodity linked • _ZeroCoupon_ = no interest, repaid at discount|
|**BaseRateReference**|`SOFR`, `EURIBOR`, `CPI`, `Repo`, `None`|Reference benchmark for floating or indexed rates.|
|**InterestMargin**|%|Margin added to base rate.|
|**Compounding**|`Simple`, `Monthly`, `Quarterly`, `SemiAnnual`, `Annual`, `Continuous`|Frequency and method of compounding.|
|**InterestPaymentFrequency**|`Monthly`, `Quarterly`, `SemiAnnual`, `Annual`, `Bullet`|Determines cash flow timing.|
|**InterestCapitalization**|`PayAsYouGo`, `PIK`, `PartialPIK`|_PIK_ (Payment-in-Kind) means unpaid interest is added to principal.|
|**Hedged**|`Yes`, `No`|Whether interest exposure is hedged via swaps, caps, etc.|

---

### **E. Principal Repayment**

|Parameter|Possible Values|Meaning|
|---|---|---|
|**RepaymentProfile**|`EqualPrincipal`, `Annuity`, `Sculpted`, `Bullet`, `Balloon`, `CashSweep`|Defines repayment shape: • _EqualPrincipal_: constant principal • _Annuity_: constant total debt service • _Sculpted_: adjusted to target DSCR • _Bullet_: all principal at maturity • _Balloon_: mostly at end • _CashSweep_: extra cash accelerates repayment|
|**RepaymentFrequency**|`Monthly`, `Quarterly`, `SemiAnnual`, `Annual`, `Custom`|Interval of payments.|
|**PrepaymentAllowed**|`Yes`, `No`, `WithPenalty`|Defines prepayment flexibility.|
|**AmortizationStart**|Date or year number|When principal repayments begin.|

---

### **F. Covenants**

|Parameter|Possible Values|Meaning|
|---|---|---|
|**MinDSCR**|Numeric (e.g., 1.2)|Minimum Debt Service Coverage Ratio; breach can cause default or lock-up.|
|**MinLLCR**|Numeric|Loan Life Coverage Ratio covenant.|
|**DividendLockupDSCR**|Numeric|Threshold below which dividends are blocked.|
|**DefaultTriggers**|List of conditions|e.g. “DSCR < 1.0x”, “missed payment”, “insolvency event”.|

---

### **G. Security & Reserves**

|Parameter|Possible Values|Meaning|
|---|---|---|
|**CollateralType**|`TangibleAsset`, `Receivables`, `Shares`, `Guarantee`, `None`|Specifies pledged security.|
|**GuaranteeProvider**|Name / `None`|Who provides a guarantee if any.|
|**ReserveAccounts**|List (`DSRA`, `MRA`, `OpexReserve`, etc.)|Dedicated reserve accounts required by lenders.|
|**DSRACoverageMonths**|Integer|Number of months of debt service covered by DSRA.|

---

### **H. Optionality / Embedded Features**

|Parameter|Possible Values|Meaning|
|---|---|---|
|**Convertibility**|`None`, `ConvertibleToEquity`, `Exchangeable`|Defines if the debt can turn into equity.|
|**Callability**|`Callable`, `NonCallable`, `CallableAfterNYears`|Borrower’s right to repay early.|
|**PutOption**|`Yes`, `No`|Lender’s right to demand early repayment.|
|**StepUpDown**|Formula|Margin changes with performance (e.g., +0.5% if DSCR < 1.10x).|

---

### **I. Jurisdiction & Documentation**

|Parameter|Possible Values|Meaning|
|---|---|---|
|**GoverningLaw**|`English`, `Turkish`, `NewYork`, `Local`|Determines which legal system applies.|
|**Jurisdiction**|Court or arbitration forum|e.g. “London Courts”.|
|**DocumentationStandard**|`LMA`, `ISDA`, `Local`, `Custom`|Type of legal template.|

---

### **J. Tradability & Accounting**

|Parameter|Possible Values|Meaning|
|---|---|---|
|**Tradability**|`Tradable`, `NonTradable`, `Syndicated`|Whether the debt can be sold/assigned.|
|**Contingency**|`OnBalance`, `OffBalance`, `Contingent`|Whether funding is guaranteed or conditional (e.g. guarantees, LCs).|
|**AccountingClass**|`AmortizedCost`, `FVOCI`, `FVTPL`, `EquityLike`|IFRS classification.|
|**RegulatoryTier**|`Tier1`, `Tier2`, `Tier3`, `N/A`|Basel regulatory classification (for bank capital).|

---

✅ **Total**: 10 core categories, ~40–45 parameters.  
Together they cover **all known debt instruments**, including structured, contingent, and hybrid instruments.

---

## 🏦 2. Ready-to-Use Parameter Sets (Templates)

Now we define practical “presets” for all standard debt instruments using the schema.

---

### **1. Senior Term Loan**

```
Purpose: Capex
RecourseType: NonRecourse
Seniority: Senior
SecurityType: Secured
Currency: EUR
TenorYears: 15
GracePeriodYears: 3
DrawdownType: Multiple
BaseRateType: Floating
BaseRateReference: EURIBOR
InterestMargin: 2.25%
Compounding: Quarterly
InterestPaymentFrequency: SemiAnnual
InterestCapitalization: PayAsYouGo
RepaymentProfile: Sculpted
RepaymentFrequency: SemiAnnual
PrepaymentAllowed: WithPenalty
MinDSCR: 1.20
CollateralType: TangibleAsset
ReserveAccounts: [DSRA]
DSRACoverageMonths: 6
GoverningLaw: English
Tradability: NonTradable
AccountingClass: AmortizedCost
```

---

### **2. Corporate Revolving Credit Facility**

```
Purpose: WorkingCapital
RecourseType: FullRecourse
Seniority: Senior
SecurityType: Unsecured
Currency: USD
TenorYears: 5
DrawdownType: Revolving
CommitmentFeeRate: 0.5%
BaseRateType: Floating
BaseRateReference: SOFR
InterestMargin: 1.75%
InterestPaymentFrequency: Quarterly
RepaymentProfile: Bullet
PrepaymentAllowed: Yes
GoverningLaw: NewYork
Tradability: Syndicated
```

---

### **3. Project Finance Mezzanine Loan**

```
Purpose: Capex
RecourseType: LimitedRecourse
Seniority: Mezzanine
SecurityType: Unsecured
Currency: EUR
TenorYears: 10
GracePeriodYears: 5
DrawdownType: Single
BaseRateType: Fixed
InterestMargin: 8%
InterestCapitalization: PIK
RepaymentProfile: Bullet
PrepaymentAllowed: No
MinDSCR: 1.0
DividendLockupDSCR: 1.1
Convertibility: ConvertibleToEquity
GoverningLaw: English
Tradability: NonTradable
```

---

### **4. Bond (Fixed-Rate)**

```
Purpose: Refinancing
RecourseType: FullRecourse
Seniority: Senior
SecurityType: Unsecured
Currency: USD
TenorYears: 7
DrawdownType: Single
BaseRateType: Fixed
InterestMargin: 5%
InterestPaymentFrequency: SemiAnnual
RepaymentProfile: Bullet
Tradability: Tradable
GoverningLaw: NewYork
AccountingClass: AmortizedCost
```

---

### **5. Convertible Bond**

```
Purpose: GeneralCorporate
RecourseType: FullRecourse
Seniority: Subordinated
SecurityType: Unsecured
Currency: USD
TenorYears: 5
BaseRateType: Fixed
InterestMargin: 4%
RepaymentProfile: Bullet
Convertibility: ConvertibleToEquity
Callability: CallableAfterNYears(3)
Tradability: Tradable
GoverningLaw: NewYork
```

---

### **6. Vendor / Equipment Lease**

```
Purpose: EquipmentFinance
RecourseType: FullRecourse
Seniority: Senior
SecurityType: Secured
Currency: TRY
TenorYears: 4
DrawdownType: Single
BaseRateType: Fixed
InterestMargin: 10%
RepaymentProfile: EqualPrincipal
RepaymentFrequency: Monthly
PrepaymentAllowed: No
CollateralType: Equipment
AccountingClass: AmortizedCost
```

---

### **7. Bridge Loan**

```
Purpose: Bridge
RecourseType: FullRecourse
Seniority: Senior
SecurityType: Secured
Currency: USD
TenorYears: 1
DrawdownType: Single
BaseRateType: Floating
BaseRateReference: SOFR
InterestMargin: 4%
InterestPaymentFrequency: Quarterly
RepaymentProfile: Bullet
PrepaymentAllowed: Yes
Tradability: NonTradable
```

---

### **8. Subordinated Shareholder Loan**

```
Purpose: Capex
RecourseType: NonRecourse
Seniority: ShareholderLoan
SecurityType: Unsecured
Currency: EUR
TenorYears: 20
BaseRateType: Fixed
InterestMargin: 12%
InterestCapitalization: PIK
RepaymentProfile: Bullet
PrepaymentAllowed: Conditional
DividendLockupDSCR: 1.2
Tradability: NonTradable
AccountingClass: EquityLike
```

---

✅ With this set you can model **nearly any debt** by tweaking parameters — or use them as **presets** in your model’s debt module.

---

Would you like me to now format this schema and presets as a **machine-readable JSON structure or Excel table** (so you can plug it directly into your modeling system)?