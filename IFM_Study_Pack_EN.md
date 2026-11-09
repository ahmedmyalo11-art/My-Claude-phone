# International Financial Management – Study Pack (English)
Covers: (A) Formula sheet, (B) Practice exam with solutions, (C) Presentation walkthrough, (D) Likely questions from the lecturer.
Project: USD/EGP, Oct 2016 – Oct 2026. Exam content is inferred from the lecturer's materials; confirm the format with classmates.

---
# PART A – FORMULA SHEET (exam)

## A1. Interest (Seminar 1, Financial Markets lecture)
- Simple interest: `I = FaceValue × i × Days / YearDays`  (money market convention usually 360)
- Final value (simple): `FV = FaceValue × (1 + i × Days/YearDays)`
- Compound: `FV = PV × (1 + i)^n`
- Rule of 72: years to double ≈ `72 / (rate in %)`  (3% → 24y, 6% → 12y, 12% → 6y, 15% → 4.8y)
- Overnight deposit: Wednesday → Thursday = 1 day. **Friday → Monday = 3 days of interest.**
- Key idea: simple = linear growth, compound = exponential (10% for 30y: 40,000 vs 174,494 on 10,000).
- "Risk-free 19% for 20 years" = warning sign; theory is useless if the investment is not genuine (George example: answer $0).

## A2. Quotations and the base currency
- `EUR/USD = 1.1240` → **1 EUR = 1.1240 USD**. First currency = **base**, second = **variable (quote)**. You always buy/sell the BASE.
- **Direct quote** = home-currency price of 1 unit of foreign currency (EUR/RON = 4.55 for a Romanian). **Indirect quote** = reciprocal (RON/EUR = 1/4.55).
- For an Egyptian: USD/EGP = 53.93 is a *direct* quote. USD = base (foreign), EGP = variable (local).
- **Bid** = rate at which the bank (market maker) BUYS the base. **Ask/Offer** = rate at which the bank SELLS the base. Bid < Ask.
- You (the company) deal on the opposite side: you SELL base at the bid, you BUY base at the ask.
- **Pip** = 4th decimal (0.0001). On EUR 10,000, 1 pip = USD 1. On EUR 1,000,000, 1 pip = USD 100.
- **Spread** = Ask − Bid (in pips). Spread % = spread / rate.
- **Big figure** = the rest of the quote; pips = last digits.

## A3. Percentage changes (Seminar FOREX – recommended formulas)
For a quote with base currency X (e.g. EUR/USD or USD/EGP):
- Base currency: `% Δ = (End / Start − 1) × 100`
- Variable currency: `% Δ = (Start / End − 1) × 100`
- Exchange rate index: `(End / Start) × 100` (base) and `(Start / End) × 100` (variable)
- Rate goes UP → base **appreciates**, variable **depreciates**. Rate goes DOWN → opposite.
- **The same move gives two different percentages** (+25% for EUR ⇔ −20% for USD).

## A4. Nominal vs real exchange rate
- Nominal = no inflation adjustment. Real = nominal change + inflation differential.
- Example: RON nominal depreciation −5%, inflation RO 11% vs EUR area 1% → `(1.11/1.01) × 0.95 = 1.044` → **real appreciation ≈ +4.5%** (not the approximation 10% − 5% = 5%).
- Real appreciation = domestic products become relatively more expensive, **less competitive**, even though the currency fell nominally.

## A5. Exposure types (Lecture 7)
| Type | What | Horizon | Hedgeable? |
|---|---|---|---|
| **Economic (operating)** | change in expected future cash flows / competitive position | long run, permanent change | difficult / impossible |
| **Transaction** | settling a foreign-currency obligation signed before the rate moved | short run (contract period) | yes (forward, futures, options, money market) |
| **Translation (accounting)** | converting subsidiaries' statements for consolidation | reporting dates | accounting exposure |

Transaction exposure arises from: buying/selling on credit in foreign currency; borrowing/lending in foreign currency; holding foreign-currency assets/liabilities.

## A6. Economic exposure – effects table
| | Own currency **depreciates** | Own currency **appreciates** |
|---|---|---|
| Exports | cheaper abroad, more competitive (GOOD) | more expensive abroad, less competitive (BAD) |
| Imports | more expensive in local currency (BAD for importers) | cheaper (GOOD for importers) |
| Balance of payments | helps trade balance | risk of trade deficit |
| Prices | inflation via imports | helps price stability |
| FX debt | higher cost of repaying FX loans, bank NPLs | lower cost |

Exporter nuance: after depreciation the exporter can (a) cut the foreign price and keep the same local revenue, or (b) keep the foreign price and earn more local currency. It is a **possibility, not a certainty**.

**Worked templates (use these on the exam)**
- Exporter, EUR depreciates (EUR/USD 1.6 → 1.2): price EUR 100,000 → USD 160,000 → USD 120,000. EUR −25%, USD +33%. At the old USD price 160,000 the firm earns 160,000/1.2 = EUR 133,333.
- Importer, EUR depreciates: USD 16,000 → EUR 10,000 → EUR 13,333 (+33%).
- Exporter, EUR appreciates (1.2 → 1.5): EUR 100,000 → USD 120,000 → USD 150,000 (+25%). To keep USD 120,000 the price must fall to EUR 80,000.
- Importer, EUR appreciates: USD 1,200,000 → EUR 1,000,000 → EUR 800,000 (−20%).

## A7. Transaction exposure – gain/loss rule
- Exporter invoicing in foreign currency: result = `FC amount × (End − Start)` when the quote is local per 1 FC. Local currency falls → **gain**. Local currency rises → **loss**.
- Importer owing foreign currency: result = `FC amount × (Start − End)`. Local currency falls → **loss**. Local currency rises → **gain**.
- If the contract is in LOCAL currency, the foreign counterparty takes the FX effect.

## A8. Forward rates (Lecture 5)
- Forward = a contract today to exchange at a fixed rate on a future value date. It **freezes** the rate; it is NOT a forecast.
- **Interest rate parity:** `F = S × (1 + i_variable × d/Y) / (1 + i_base × d/Y)`
- Forward pips = `F − S`.
- Currency with the **higher** interest rate is at a **discount**; the one with the **lower** rate is at a **premium**. F > S → base at premium. F < S → base at discount.
- Quoting: `Forward = Spot ± pips`. Pips **low/high (20/30)** → ADD. Pips **high/low (25/15)** → SUBTRACT.
- Forward is binding: it removes the loss and also removes the gain.
- Value date = Spot is **T+2** business days; trade date = rate agreed; value date = currencies actually exchanged.
- Other products: Spot, Outright forward, **FX Swap** (spot + reverse forward), **FX Option** (right not obligation; buyer pays premium), **FX Futures** (exchange-traded, CME, standard sizes).

## A9. Cross rates
- Rule: to build X/Z from X/Y and Y/Z: multiply **left-left** and **right-right** when both are quoted the same way; invert otherwise.
- Always think as the company: which side do I trade, and use the less favourable side.

## A10. Financial system (Lecture 1–2)
- Direct finance (borrowers sell securities to lenders in markets) vs indirect finance (via intermediaries).
- Debt = fixed income (T-bills, bonds); Equity = variable income (shares, no maturity).
- **Money market** = debt < 1 year, sets benchmark rates. **Capital market** = ≥ 1 year debt and equity.
- Primary vs secondary markets (secondary: liquidity + price discovery). Exchanges vs OTC.
- Intermediaries lower transaction costs (economies of scale).
- **Adverse selection** = before the deal, information gap, risk of choosing the worst partner/product. **Moral hazard** = after the deal, the borrower takes more risk because the lender bears part of the loss.

## A11. FX market characteristics (Lecture 3)
- Largest, most liquid market: about **USD 9.5 trillion/day** (BIS Triennial 2025).
- USD is on one side of ~89% of trades (the quoted share is out of 200%); EUR ~29%; USD = main vehicle currency; renminbi 8.5% share, 5th most traded.
- Geography: UK 38%, USA 19%, Singapore 12%, Hong Kong 7%, Japan 3.5%, Switzerland 3%.
- Least regulated: OTC, no central clearing; FX Global Code (2017); manipulation risk (benchmark rigging cases).
- 24h, 5 days a week; leverage up to 200:1 with brokers.
- Functions: currency conversion (only about 5–7%), hedging, speculation/arbitrage.
- Modern FX market began in the 1970s after Bretton Woods (1944–1970) ended.
- Transaction rate vs reference rate: you can trade at the first; the second is for calculations, accounting and contract valuation.

---
# PART B – PRACTICE EXAM WITH SOLUTIONS
Try each question before reading the answer.

## Q1. Interest
a) EUR 10,000 deposit at 3% for 30 days (360-day year). Interest and final amount?
b) LEI 300,000 at 5%: interest for a 1-day deposit and a 7-day deposit?
c) Initial EUR 10,000 at 12% compounded for 6 years?
d) Rule of 72: years to double at 24%? At 10%?

**Answer**
a) 10,000 × 0.03 × 30/360 = **EUR 25**; final amount **EUR 10,025**.
b) 300,000 × 0.05 × 1/360 = **LEI 41.67**; × 7/360 = **LEI 291.67**.
c) 10,000 × 1.12^6 = **EUR 19,738**.
d) 72/24 = **3 years**; 72/10 = **7.2 years**.

## Q2. Percentage changes
a) USD/JPY goes from 150 to 140. Change for USD and JPY?
b) EUR/CHF goes from 1.20 to 0.95. Change for EUR and CHF?
c) EUR/USD goes from 1.2000 to 1.5000. Change for EUR and USD? Which one appreciated?

**Answer**
a) USD: 140/150 − 1 = **−6.67%** (depreciates). JPY: 150/140 − 1 = **+7.14%** (appreciates).
b) EUR: 0.95/1.20 − 1 = **−20.83%**. CHF: 1.20/0.95 − 1 = **+26.32%**.
c) EUR: 1.5/1.2 − 1 = **+25%** (appreciates). USD: 1.2/1.5 − 1 = **−20%** (depreciates).

## Q3. Time series (EUR/RON, base Dec 2001 = 2.815)
Oct 2004 = 4.1082, Jul 2007 = 3.1345. Compute % change for EUR and RON vs Dec 2001.

**Answer**
- Oct 2004: EUR **+45.94%**, RON **−31.48%**.
- Jul 2007: EUR **+11.35%**, RON **−10.19%**.

## Q4. Nominal vs real
RON depreciates 5% nominally. Inflation: Romania 11%, euro area 1%. Real change? Effect on exporters?

**Answer**
Real index = (1.11/1.01) × 0.95 = 1.044 → **real appreciation of about 4.5%**. Romanian exports become more expensive relative to foreign products and **less competitive**, even though the leu fell nominally.

## Q5. Economic exposure
A German exporter sells a product at EUR 100,000. EUR/USD moves from 1.6 to 1.2.
a) Price in USD before and after? b) What does it mean for the firm? c) Which type of exposure?

**Answer**
a) USD 160,000 → USD 120,000.
b) EUR depreciates 25% (USD +33%). The firm can cut the USD price by 25% to gain competitiveness while keeping EUR 100,000, or keep USD 160,000 and receive 160,000/1.2 = **EUR 133,333**.
c) **Economic (operating) exposure**: competitive position and future cash flows change. It is long-term and hard to hedge.

## Q6. Economic exposure – appreciation, importer
A German importer buys a machine for USD 1,200,000. EUR/USD moves from 1.2 to 1.5. Cost in EUR before and after? Effect on the economy?

**Answer**
USD 1.2m/1.2 = **EUR 1,000,000** → 1.2m/1.5 = **EUR 800,000** (−20%). Importers benefit (cheaper technology and inputs), inflation is lower, but the trade balance may move towards a deficit and import-competing producers suffer.

## Q7. Transaction exposure (use the same method as the project)
An Egyptian importer signs a USD 500,000 contract when USD/EGP = 30.84 and pays six months later when USD/EGP = 48.90.
a) Budgeted cost? b) Actual cost? c) Gain or loss? d) What if the rate at payment had been 25 instead?

**Answer**
a) 500,000 × 30.84 = **EGP 15,420,000**.
b) 500,000 × 48.90 = **EGP 24,450,000**.
c) 15.42m − 24.45m = **−EGP 9,030,000** (loss, 58.6% more).
d) 500,000 × 25 = 12.5m → **gain of EGP 2.92m**. The risk is two-sided; a hedge removes both.

## Q8. Forward calculation
USD/EGP spot 30.84. EGP rate 21.25% p.a., USD rate 5.09% p.a. Six-month forward? Which currency is at a premium?

**Answer**
F = 30.84 × (1 + 0.2125×0.5) / (1 + 0.0509×0.5) = 30.84 × 1.10625 / 1.02545 = **33.27**.
F > S, so the **USD (base) is at a premium** (about 7.9%) and the EGP is at a discount, because EGP has the higher interest rate. The forward is not a forecast.

## Q9. Forward quote and outcome
EUR/USD spot 1.1230/35. 6M forward pips 80/85. Business Star wants to buy EUR 1,000,000 in 6 months.
a) Forward rates? b) At which rate and how much USD? c) What happens at the value date? d) If spot at maturity is 1.1760 or 1.0640, should the manager celebrate?

**Answer**
a) Pips low/high → add: **1.1310 / 1.1320**.
b) Company buys EUR → bank sells at the **ask 1.1320** → USD 1,132,000.
c) Value date (about 6 months later, spot rules apply): **+EUR 1,000,000, −USD 1,132,000**.
d) At 1.1760: without the hedge the cost would be USD 1,176,000, so the forward **saved USD 44,000** → celebrate. At 1.0640: it would have cost USD 1,064,000, so the forward **cost USD 68,000 extra** → regret, but it gave certainty. The forward is a protection, not a profit strategy.

## Q10. Pips and spread
EUR/USD bid 1.0507, ask 1.0510.
a) Spread in pips? b) Market maker trades EUR 100,000,000 on both sides, spread income? c) Spread as % of rate? d) A speculator buys EUR 100,000 at 1.1261 and sells at 1.1220: pips and loss in USD?

**Answer**
a) **3 pips**. b) 100,000,000 × 0.0003 = **USD 30,000**. c) 0.0003/1.0507 = **0.0286%**.
d) 1.1261 − 1.1220 = 0.0041 = **41 pips**; loss = 100,000 × 0.0041 = **USD 410**.

## Q11. Bid/ask trading
Bank EUR/USD: bid 1.1040, ask 1.1045.
a) You must buy EUR 1,000,000 to pay an invoice, how many USD? b) You sell EUR 1,000,000 to the bank, how many USD? c) You need USD 1,105,000, how many EUR must you sell?

**Answer**
a) Bank sells EUR at the ask: **USD 1,104,500**.
b) Bank buys EUR at the bid: **USD 1,104,000**.
c) Company gets USD, so it **buys USD / sells EUR**: bank buys EUR at the bid: 1,105,000 / 1.1040 = **EUR 1,000,906**. (The slide's own answer depends on its rate convention; be ready to explain which side you use.)

## Q12. Cross rate
International: EUR/USD 1.1250–1.1255. Local: EUR/RON 5.3520–5.3540.
a) You sell USD 1,000,000 against RON: which USD/RON rate? b) You buy USD 1,000,000 against RON?

**Answer**
a) Sell USD, buy RON → bid USD/RON = 5.3520 / 1.1255 = **4.7552** → RON 4,755,200.
b) Buy USD, sell RON → ask USD/RON = 5.3540 / 1.1250 = **4.7591** → RON 4,759,100.

## Q13. Value dates
A spot EUR/USD trade is agreed on Tuesday 24 November 2026. Value date? When must you have the money?

**Answer**
Spot = T+2 business days → **Thursday 26 November 2026**. Money must be available on the **value date** (when the exchange happens), not the trade date.

## Q14. Theory (short answers)
1. Define transaction, economic and translation exposure. → see A5.
2. Why is a forward not a prediction? → It reflects the **interest rate differential**, not expected spot.
3. Difference between money market and capital market. → under vs over one year; money market sets benchmark rates.
4. Adverse selection vs moral hazard. → before vs after the transaction (see A10).
5. Why does the USD dominate FX? → vehicle currency, on one side of about 89% of trades, deep and liquid markets.
6. Pros and cons of options vs forwards. → Option keeps the upside but costs a premium; forward is free upfront but locks in both gain and loss.

---
# PART C – PRESENTATION WALKTHROUGH (USD/EGP project)

**Slide 1 – Title.** USD/EGP is quoted as EGP per 1 USD, so **USD is the base currency** and EGP is the variable currency. Data: Oct 2016 – Oct 2026 (121 monthly averages). Sources: BIS to July 2026, CBE for Aug–Oct 2026 (the ECB does not publish an EGP reference rate). Two companies: Oriental Weavers (exporter), Edita (importer).

**Slide 2 – 8.86 to 53.93 in steps.** `53.93/8.86 = 6.1×`. USD +508.7% (End/Start − 1). EGP −83.6% (Start/End − 1). The same move gives two percentages. The curve is a staircase: flat periods (15.6–15.7 from Feb 2020 to Feb 2022; 30.84 from Apr 2023 to Feb 2024) broken by four jumps: Nov 2016, Feb 2022–Mar 2023, Mar 2024, Mar 2026.

**Slide 3 – Each jump has a trigger.**
- Nov 2016: float of the pound under an IMF programme (USD 12bn loan); fuel prices +30% to 46.8%.
- Oct 2022–Mar 2023: USD 3bn IMF facility, pound −14.5% in one day; inflation 21.9%.
- Mar 2024: official rate to about 52; interest rate +600bp; inflation record 38%; enlarged IMF programme.
- Mar 2026: regional war, gas exports stopped, investor outflows (analyst estimate USD 2–5bn, unconfirmed).
- Objectivity: Egyptian state media were deliberately excluded; international agencies and IMF documents used.

**Slide 4 – Depreciation (Feb 2024 → Aug 2024, 30.84 → 48.90).**
- Exporter (Oriental Weavers): carpet EGP 1,000 → USD 32.43 → USD 20.45 (−36.9%). Can cut the price or earn about 59% more EGP. 1H2025 export revenue +44% in EGP on volume +3%. Caveat: polypropylene yarn is priced in USD, so costs also rise.
- Importer (Edita): input USD 600/tonne → EGP 18,504 → EGP 29,340 (+58.6%). Exports are a partial natural hedge.
- Economy: more export earnings and dollars, but import prices and inflation rise.

**Slide 5 – Appreciation (Apr 2025 → Oct 2025, 51.02 → 47.53).**
- Exporter: USD 19.60 → USD 21.04 (+7.3%), less competitive; to keep the USD price it must accept EGP 932 instead of 1,000.
- Importer: EGP 30,612 → EGP 28,518 (−6.8%), wider margin or lower prices.
- Economy: cheaper imports and lower inflation, but weaker export earnings and tougher competition for local producers. The move is far smaller than in 2024.

**Slide 6 – Transaction exposure (six-month USD contracts).**
| Case | Rates | Result |
|---|---|---|
| Depreciation, exporter | 30.84 → 48.90 | **+EGP 18.06m** |
| Depreciation, importer | 30.84 → 48.90 | **−EGP 9.03m** |
| Appreciation, exporter | 51.02 → 47.53 | **−EGP 3.49m** |
| Appreciation, importer | 51.02 → 47.53 | **+EGP 1.745m** |
Exporter result = END value − START value. Importer result = START cost − END cost. These gains are "timing", not business performance.

**Slide 7 – Hedging (Edita, USD 500,000 wheat flour).**
- Exposure: transaction exposure, a short position in EGP against USD (Edita must buy USD).
- Instrument: **forward**. F = 30.84 × (1 + 21.25%×6/12) / (1 + 5.09%×6/12) = **33.27**.
- Locked cost EGP 16.64m vs EGP 24.45m unhedged → **saving EGP 7.81m** in 2024. The forward costs EGP 1.22m more than the spot budget (price of certainty).
- Break-even 33.27. In the 2025 scenario (EGP stronger) the same forward would have lost money.
- Why not alternatives: futures lack suitable sizes/dates for EGP, options need an expensive upfront premium when devaluation is expected, money-market hedge ties up cash at EGP rates above 21%.
- A real bank quote would likely be higher than the theoretical parity rate.

**Slide 8 – Takeaways.** (1) EGP lost 84% in ten years in four steps tied to policy changes and shocks. (2) A falling pound helps exporters and hurts importers, and the reverse for a rising pound but far smaller. (3) On a USD contract the same move is a gain or a loss (+18.06m exporter, −9.03m importer in 2024). (4) A forward fixes the price: it removes the loss and also the gain.

---
# PART D – LIKELY QUESTIONS AND MODEL ANSWERS

1. **Why did you choose Feb 2024 as the start of the transaction example?** It is the month before the March 2024 float, so it shows the maximum effect. We also included 2025 (a small move) to show the opposite case.
2. **Why are the contract amounts assumed?** Company reports do not isolate the FX effect. The aim is to show the mechanics; this is stated in the Limits section.
3. **Why BIS and CBE instead of ECB?** The ECB does not publish an EGP reference rate. Over the 29 months where both exist, CBE is on average 0.11% above BIS, so the switch is immaterial.
4. **Are your results nominal or real?** Nominal. Egypt's inflation is much higher than the US (21.9% in Dec 2022, 38% record in 2023), so part of the nominal depreciation is offset by inflation; the real change in competitiveness is smaller than the nominal 37%–59% suggests.
5. **Why a forward and not an option?** Option premium in EGP would be very high when devaluation is expected, and it must be paid upfront; the forward has no upfront cost but fixes the rate.
6. **Was the hedge a good decision?** In 2024 yes (saved EGP 7.81m). In 2025 it would have cost money, because a hedge removes gains as well as losses. The goal is certainty and budgeting, not profit.
7. **Why is the forward rate 33.27 greater than spot?** Because EGP interest rates (21.25%) are higher than USD rates (5.09%): the USD is at a forward premium of about 7.9%.
8. **Is the forward a forecast of the future rate?** No. It reflects only the interest rate differential. The actual 2024 rate (48.90) was far above 33.27.
9. **Economic vs transaction exposure in your cases?** Economic: long-term competitiveness and cash flows (carpets priced in USD vs competitors; input costs). Transaction: a specific USD invoice settled in six months.
10. **How did you use AI and how did you verify?** Claude was used for double-checking and research under our supervision; the rates were cross-checked against IMF IFS and Penn World Table (within 0.04% for 2016–2023), and key news facts against IMF press releases.
11. **Why only two companies?** One exporter and one importer used for both directions; stated in the Limits section.
12. **What is the difference between "the pound lost 84%" and "the dollar gained 509%"?** Same move, two denominators: USD uses End/Start − 1, EGP uses Start/End − 1.
