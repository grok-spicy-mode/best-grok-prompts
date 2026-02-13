# Data Analysis Grok Prompts

Advanced prompts for data analysts, researchers, and business intelligence professionals. Leverage Grok's analytical capabilities and real-time data access.

---

## 1. Dataset Explorer

**Category:** Data Analysis
**Difficulty:** ⭐⭐
**Works with:** All Grok tiers

> Analyze this dataset:
>
> [paste data or describe dataset]
>
> Provide:
> 1. **Overview:**
>    - Dimensions (rows x columns)
>    - Data types for each column
>    - Missing values (count + percentage)
>    - Duplicate records
>
> 2. **Descriptive statistics:**
>    - Mean, median, mode
>    - Standard deviation
>    - Min/max, quartiles
>    - Outliers (IQR method)
>
> 3. **Distribution analysis:**
>    - Normality check
>    - Skewness, kurtosis
>    - Visualization suggestions
>
> 4. **Patterns found:**
>    - Top 3 interesting insights
>    - Unexpected findings
>    - Data quality issues
>
> 5. **Next steps:**
>    - Cleaning recommendations
>    - Analysis opportunities
>
> Explain for business stakeholders, not data scientists.

**Why it works:** Comprehensive data profiling reveals insights and quality issues upfront.

---

## 2. Correlation Finder

**Category:** Data Analysis
**Difficulty:** ⭐⭐⭐
**Works with:** All Grok tiers

> Find correlations in this data:
>
> [paste dataset or variables]
>
> **Target variable:** [what you're trying to predict/understand]
>
> Analyze:
> 1. **Correlation matrix:**
>    - Pearson coefficients
>    - Significance levels
>    - Top 10 strongest correlations
>
> 2. **Interesting relationships:**
>    - Positive correlations (>0.7)
>    - Negative correlations (<-0.7)
>    - Weak but significant correlations
>
> 3. **Multicollinearity check:**
>    - VIF scores
>    - Redundant variables
>
> 4. **Causation warnings:**
>    - Correlation ≠ causation notes
>    - Confounding variables to investigate
>
> 5. **Business implications:**
>    - What these relationships mean
>    - Actionable insights
>    - Hypotheses for testing
>
> Visualize top 5 correlations with heatmap specs.

**Why it works:** Systematic correlation analysis prevents spurious conclusions.

---

## 3. A/B Test Statistical Analyzer

**Category:** Data Analysis
**Difficulty:** ⭐⭐⭐
**Works with:** All Grok tiers

> Analyze this A/B test:
>
> **Variant A:**
> - Sample size: [n]
> - Conversions: [x]
> - Conversion rate: [%]
>
> **Variant B:**
> - Sample size: [n]
> - Conversions: [x]
> - Conversion rate: [%]
>
> **Test duration:** [days]
> **Significance level:** 0.05
>
> Calculate:
> 1. **Statistical significance:**
>    - P-value
>    - Z-score
>    - Confidence interval (95%)
>    - Result: significant or not?
>
> 2. **Effect size:**
>    - Relative lift (%)
>    - Absolute difference
>    - Practical significance
>
> 3. **Sample size validation:**
>    - Was sample large enough?
>    - Power analysis (did we avoid Type II error?)
>
> 4. **Recommendation:**
>    - Declare winner or continue test?
>    - Expected impact at scale
>    - Risks and considerations
>
> 5. **Next test suggestions:**
>    - Winning variation to iterate
>    - New hypotheses

**Why it works:** Proper statistical analysis prevents false positives in testing.

---

## 4. Time Series Trend Analyst

**Category:** Data Analysis
**Difficulty:** ⭐⭐⭐
**Works with:** All Grok tiers

> Analyze this time series data:
>
> [paste time series or describe]
>
> **Metric:** [revenue, users, etc]
> **Timeframe:** [daily/weekly/monthly, duration]
>
> Perform:
> 1. **Trend analysis:**
>    - Overall trend (upward/downward/flat)
>    - Trend line equation
>    - Rate of change
>
> 2. **Seasonality detection:**
>    - Seasonal patterns (daily, weekly, monthly, yearly)
>    - Peak periods
>    - Trough periods
>
> 3. **Decomposition:**
>    - Trend component
>    - Seasonal component
>    - Residual (irregular)
>
> 4. **Anomaly detection:**
>    - Outliers (dates + values)
>    - Possible causes
>    - Impact assessment
>
> 5. **Forecasting:**
>    - Next [period] prediction
>    - Confidence interval
>    - Assumptions
>
> 6. **Business insights:**
>    - What's driving changes
>    - Actionable patterns
>    - Risks to watch

**Why it works:** Complete time series analysis reveals patterns and enables forecasting.

---

## 5. Customer Segmentation Analyzer

**Category:** Data Analysis
**Difficulty:** ⭐⭐⭐
**Works with:** All Grok tiers

> Segment customers based on this data:
>
> [describe customer dataset: demographics, behavior, transactions]
>
> **Segmentation goal:** [increase retention/target marketing/etc]
> **Available variables:** [list]
>
> Create:
> 1. **RFM Analysis:**
>    - Recency scoring
>    - Frequency scoring
>    - Monetary scoring
>    - RFM segments (Champions, Loyal, At-Risk, etc.)
>
> 2. **Clustering analysis:**
>    - Suggest clustering method (K-means, hierarchical)
>    - Optimal number of clusters
>    - Cluster characteristics
>
> 3. **Segment profiles:**
>    For each segment:
>    - Size (% of total)
>    - Key characteristics
>    - Average LTV
>    - Behavior patterns
>    - Revenue contribution
>
> 4. **Marketing strategies:**
>    - Personalized approach for each segment
>    - Priority ranking
>    - Expected ROI
>
> 5. **Implementation:**
>    - How to identify new customers into segments
>    - Monitoring metrics

**Why it works:** Data-driven segmentation enables personalized marketing.

---

## 6. Survey Data Interpreter

**Category:** Data Analysis
**Difficulty:** ⭐⭐
**Works with:** All Grok tiers

> Analyze survey responses:
>
> [paste survey data or summary]
>
> **Survey topic:** [subject]
> **Sample size:** [n]
> **Response rate:** [%]
>
> Analyze:
> 1. **Response distribution:**
>    - For each question
>    - Frequencies and percentages
>    - Mode, median (for scale questions)
>
> 2. **Cross-tabulation:**
>    - Segment by demographics
>    - Identify subgroup differences
>    - Statistical significance
>
> 3. **Sentiment analysis:**
>    - Open-ended responses themes
>    - Positive/negative/neutral split
>    - Word cloud top terms
>
> 4. **Key findings:**
>    - Top 5 insights
>    - Surprising results
>    - Consensus areas
>    - Polarized topics
>
> 5. **Recommendations:**
>    - Actionable next steps
>    - Areas needing deeper investigation
>    - Follow-up questions
>
> **Reporting:**
> - Executive summary (3 bullet points)
> - Visual chart specifications

**Why it works:** Systematic survey analysis extracts maximum value from feedback.

---

## 7. Cohort Retention Analyzer

**Category:** Data Analysis
**Difficulty:** ⭐⭐⭐
**Works with:** All Grok tiers

> Analyze cohort retention:
>
> **Product/Service:** [describe]
> **Cohort definition:** [signup date, first purchase, etc]
> **Retention event:** [login, purchase, usage]
> **Timeframe:** [by day/week/month]
>
> [paste cohort data if available]
>
> Create:
> 1. **Retention table:**
>    - Cohorts in rows
>    - Time periods in columns
>    - Retention percentages
>
> 2. **Retention curves:**
>    - Overlay multiple cohorts
>    - Identify improving/declining cohorts
>
> 3. **Analysis:**
>    - Average Day 1/7/30/90 retention
>    - Retention plateau point
>    - Churn rate by period
>    - Best/worst performing cohorts
>
> 4. **Pattern detection:**
>    - Seasonal effects
>    - Impact of product changes (if dates known)
>    - Acquisition channel differences
>
> 5. **Recommendations:**
>    - When to intervene (critical drop-off points)
>    - Strategies for each cohort stage
>    - Target retention benchmarks
>
> 6. **LTV projection:**
>    - Based on retention curves
>    - Revenue implications

**Why it works:** Cohort analysis reveals user behavior patterns over time.

---

## 8. Competitor Benchmark Analyzer

**Category:** Data Analysis
**Difficulty:** ⭐⭐
**Works with:** Grok Premium, Spicy Mode

> Benchmark against competitors:
>
> **Your company:** [name]
> **Competitors:** [list 3-5]
> **Industry:** [sector]
> **Metrics to compare:** [revenue, users, features, pricing, etc]
>
> Using real-time data, analyze:
>
> 1. **Competitive positioning:**
>    - Market share estimates
>    - Positioning matrix
>    - Differentiation factors
>
> 2. **Metric comparison:**
>    - Your performance vs competitors
>    - Industry averages
>    - Leaders in each category
>
> 3. **Gap analysis:**
>    - Where you lag
>    - Where you lead
>    - Catch-up difficulty assessment
>
> 4. **Trend analysis:**
>    - Who's growing fastest
>    - Market momentum shifts
>    - Recent strategic moves
>
> 5. **SWOT relative to competition:**
>    - Competitive strengths
>    - Vulnerabilities
>    - Market opportunities
>    - Competitive threats
>
> 6. **Strategic recommendations:**
>    - Compete or differentiate
>    - Priority improvements
>    - Positioning strategy

**Why it works:** Real-time competitive data enables informed strategy.

---

## 9. Funnel Conversion Optimizer

**Category:** Data Analysis
**Difficulty:** ⭐⭐
**Works with:** All Grok tiers

> Analyze this conversion funnel:
>
> **Funnel stages:**
> 1. [Stage 1]: [X users]
> 2. [Stage 2]: [Y users]
> 3. [Stage 3]: [Z users]
> ...
> N. [Final stage]: [W conversions]
>
> **Time period:** [duration]
>
> Calculate:
> 1. **Conversion rates:**
>    - Each stage to next
>    - Overall funnel conversion
>    - Benchmark comparison
>
> 2. **Drop-off analysis:**
>    - Biggest leaks (% and absolute)
>    - Cumulative drop-off
>    - Recovery potential
>
> 3. **Bottleneck identification:**
>    - Worst-performing stages
>    - Expected vs actual conversion
>    - Impact if fixed (revenue model)
>
> 4. **Segment analysis:**
>    - Conversion by source/channel
>    - Device differences
>    - Geographic variations
>
> 5. **Optimization priorities:**
>    - Quick wins (high impact, low effort)
>    - Long-term improvements
>    - Testing roadmap
>
> 6. **Projections:**
>    - Impact of 10% improvement per stage
>    - Revenue uplift scenarios

**Why it works:** Funnel analysis pinpoints exact optimization opportunities.

---

## 10. Predictive Model Validator

**Category:** Data Analysis
**Difficulty:** ⭐⭐⭐
**Works with:** All Grok tiers

> Validate this predictive model:
>
> **Model type:** [regression/classification/etc]
> **Target variable:** [what you're predicting]
> **Features:** [list predictors]
> **Training data:** [size, timeframe]
>
> **Model performance:**
> [paste accuracy metrics, confusion matrix, etc]
>
> Evaluate:
> 1. **Performance metrics:**
>    - Appropriate for model type
>    - Train vs test performance
>    - Overfitting detection
>
> 2. **Business metrics:**
>    - Precision vs recall trade-off
>    - Cost of false positives/negatives
>    - ROI of model deployment
>
> 3. **Feature importance:**
>    - Top predictors
>    - Redundant features
>    - Missing features to explore
>
> 4. **Model diagnostics:**
>    - Residual analysis
>    - Assumption violations
>    - Edge case performance
>
> 5. **Bias check:**
>    - Fairness across segments
>    - Discriminatory patterns
>    - Ethical considerations
>
> 6. **Deployment readiness:**
>    - Production requirements
>    - Monitoring plan
>    - Retraining strategy
>
> **Recommendation:** Deploy, improve, or redesign?

**Why it works:** Comprehensive validation prevents poor model deployment.

---

## 11. Financial Statement Analyzer

**Category:** Data Analysis
**Difficulty:** ⭐⭐
**Works with:** All Grok tiers

> Analyze these financial statements:
>
> [paste income statement, balance sheet, cash flow]
>
> **Company:** [name]
> **Industry:** [sector]
> **Time period:** [quarters/years]
>
> Calculate:
> 1. **Profitability ratios:**
>    - Gross margin
>    - Operating margin
>    - Net profit margin
>    - ROE, ROA, ROIC
>
> 2. **Liquidity ratios:**
>    - Current ratio
>    - Quick ratio
>    - Cash ratio
>
> 3. **Leverage ratios:**
>    - Debt-to-equity
>    - Interest coverage
>    - Debt service coverage
>
> 4. **Efficiency ratios:**
>    - Asset turnover
>    - Inventory turnover
>    - Days sales outstanding
>
> 5. **Trend analysis:**
>    - YoY growth rates
>    - Quarterly trends
>    - Comparison to industry benchmarks
>
> 6. **Red flags:**
>    - Financial distress indicators
>    - Accounting anomalies
>    - Cash flow concerns
>
> 7. **Investment perspective:**
>    - Financial health score (1-10)
>    - Strengths/weaknesses
>    - Risk assessment

**Why it works:** Comprehensive financial analysis for investment decisions.

---

## 12. Web Analytics Interpreter

**Category:** Data Analysis
**Difficulty:** ⭐⭐
**Works with:** All Grok tiers

> Analyze web analytics data:
>
> [paste Google Analytics/similar metrics]
>
> **Website:** [URL]
> **Time period:** [date range]
> **Goals:** [conversions, engagement, etc]
>
> Analyze:
> 1. **Traffic overview:**
>    - Total sessions/users
>    - New vs returning visitors
>    - Traffic sources breakdown
>    - Growth trends
>
> 2. **User behavior:**
>    - Average session duration
>    - Pages per session
>    - Bounce rate (by page)
>    - Exit pages analysis
>
> 3. **Acquisition performance:**
>    - Best/worst channels
>    - Cost per acquisition (if available)
>    - Channel conversion rates
>
> 4. **Content performance:**
>    - Top pages (traffic, engagement)
>    - Underperforming pages
>    - Content gaps
>
> 5. **Conversion analysis:**
>    - Goal completion rates
>    - Assisted conversions
>    - Attribution analysis
>
> 6. **Audience insights:**
>    - Demographics
>    - Devices/browsers
>    - Geographic distribution
>
> 7. **Actionable recommendations:**
>    - Quick wins
>    - Testing priorities
>    - Content strategy

**Why it works:** Translates analytics data into actionable insights.

---

## 13. Pricing Analytics Optimizer

**Category:** Data Analysis
**Difficulty:** ⭐⭐⭐
**Works with:** All Grok tiers

> Analyze pricing data to optimize strategy:
>
> **Product/Service:** [describe]
> **Current price points:** [list]
> **Sales data:** [volume by price, revenue, margins]
> **Competitor prices:** [range]
>
> Analyze:
> 1. **Price elasticity:**
>    - Demand curve estimation
>    - Elasticity coefficient
>    - Price-sensitivity
>
> 2. **Revenue optimization:**
>    - Current revenue
>    - Optimal price point (max revenue)
>    - Revenue at different price points
>
> 3. **Profit optimization:**
>    - Current profit margin
>    - Optimal price for max profit
>    - Volume/margin trade-offs
>
> 4. **Competitive positioning:**
>    - Price vs competitors
>    - Value perception
>    - Market share implications
>
> 5. **Segmentation opportunities:**
>    - Willingness-to-pay segments
>    - Pricing tiers recommendation
>    - Discount strategy
>
> 6. **Testing framework:**
>    - Price points to test
>    - Expected impact
>    - Risk assessment
>
> **Recommendation:** Pricing strategy with projected impact

**Why it works:** Data-driven pricing maximizes revenue and profit.

---

## 14. Churn Prediction Analyzer

**Category:** Data Analysis
**Difficulty:** ⭐⭐⭐
**Works with:** All Grok tiers

> Predict and prevent churn:
>
> **Business model:** [subscription/SaaS/etc]
> **Customer data:** [describe available features]
> **Current churn rate:** [%]
> **Target churn rate:** [%]
>
> Analyze:
> 1. **Churn indicators:**
>    - Leading indicators (early warning signs)
>    - Lagging indicators (late stage)
>    - Behavioral patterns before churn
>
> 2. **Risk segmentation:**
>    - High-risk customers (characteristics)
>    - Medium-risk
>    - Low-risk (retention patterns)
>
> 3. **Churn reasons:**
>    - Main drivers (ranked by impact)
>    - Preventable vs unpreventable
>    - Category breakdown
>
> 4. **Customer lifetime value:**
>    - LTV of churned vs retained
>    - Revenue at risk
>    - Cost of prevention vs acquisition
>
> 5. **Intervention strategies:**
>    - When to intervene (optimal timing)
>    - What to offer (personalized)
>    - Channel to use
>    - Expected success rate
>
> 6. **Predictive model:**
>    - Features to track
>    - Scoring system
>    - Automation opportunities
>
> **ROI projection:** Cost of retention program vs saved revenue

**Why it works:** Proactive churn prevention is cheaper than acquisition.

---

## 15. Market Basket Analysis

**Category:** Data Analysis
**Difficulty:** ⭐⭐⭐
**Works with:** All Grok tiers

> Perform market basket analysis:
>
> **Transaction data:** [retail/e-commerce transactions]
> **Products:** [number of SKUs]
> **Transactions:** [time period, count]
>
> Analyze:
> 1. **Association rules:**
>    - Frequent itemsets
>    - Support (how often together)
>    - Confidence (probability)
>    - Lift (strength of association)
>
> 2. **Product affinity:**
>    - Top product pairs
>    - Product bundles (3+ items)
>    - Unexpected associations
>
> 3. **Segmentation:**
>    - Basket types (small, medium, large)
>    - Occasion-based purchases
>    - Customer segments by basket
>
> 4. **Business applications:**
>    - Cross-sell recommendations
>    - Product placement strategy
>    - Bundle pricing opportunities
>    - Inventory planning
>
> 5. **Seasonality:**
>    - Time-based associations
>    - Event-driven patterns
>
> 6. **Implementation:**
>    - Recommendation engine logic
>    - A/B test plan
>    - Expected revenue uplift
>
> **Minimum thresholds:** Support > 1%, Confidence > 20%, Lift > 1.2

**Why it works:** Association analysis drives cross-selling and merchandising.

---

## 16. Experimental Design Validator

**Category:** Data Analysis
**Difficulty:** ⭐⭐⭐
**Works with:** All Grok tiers

> Review this experimental design:
>
> **Hypothesis:** [what you're testing]
> **Independent variable:** [what you'll change]
> **Dependent variable:** [what you'll measure]
> **Sample size:** [planned]
> **Duration:** [timeframe]
> **Significance level:** [alpha]
>
> Evaluate:
> 1. **Hypothesis quality:**
>    - Testable and specific?
>    - Measurable outcome?
>    - Realistic timeframe?
>
> 2. **Sample size:**
>    - Power analysis (80% power minimum)
>    - Minimum detectable effect
>    - Is sample adequate?
>
> 3. **Design validity:**
>    - Internal validity threats
>    - External validity concerns
>    - Confounding variables
>    - Randomization strategy
>
> 4. **Measurement:**
>    - Metric appropriateness
>    - Tracking implementation
>    - Guardrail metrics
>
> 5. **Statistical approach:**
>    - Correct test (t-test, chi-square, etc)
>    - Assumptions met?
>    - Multiple comparison corrections
>
> 6. **Ethical considerations:**
>    - User impact
>    - Informed consent
>    - Data privacy
>
> **Recommendation:** Proceed, modify, or redesign?

**Why it works:** Validates experiments before costly execution.

---

## 17. Text Analytics Engine

**Category:** Data Analysis
**Difficulty:** ⭐⭐
**Works with:** All Grok tiers

> Analyze text data:
>
> [paste customer reviews/survey responses/social media comments]
>
> **Source:** [where text came from]
> **Volume:** [number of entries]
> **Time period:** [date range]
>
> Perform:
> 1. **Sentiment analysis:**
>    - Overall sentiment (positive/negative/neutral %)
>    - Sentiment over time
>    - Sentiment by topic/product
>
> 2. **Topic modeling:**
>    - Main themes (5-10 topics)
>    - Topic prevalence
>    - Topic sentiment
>
> 3. **Keyword extraction:**
>    - Most frequent terms
>    - TF-IDF important terms
>    - Emerging keywords
>
> 4. **Entity recognition:**
>    - Products mentioned
>    - Features discussed
>    - Competitors referenced
>
> 5. **Insight extraction:**
>    - Common complaints
>    - Praise patterns
>    - Feature requests
>    - Pain points
>
> 6. **Visualization specs:**
>    - Word cloud
>    - Sentiment timeline
>    - Topic clusters
>
> **Actionable recommendations:** Top 3 priorities from analysis

**Why it works:** Unstructured text becomes structured insights.

---

## Discover More Grok Prompts
Browse 1000+ prompts at **[GrokPrompts.app](https://grokprompts.app)** - Free AI prompt library
