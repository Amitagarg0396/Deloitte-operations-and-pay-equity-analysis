**Forensic Gender Pay Equality Analysis (Excel)
**

**1. Business Context**

Daikibo received internal complaints regarding gender pay inequality. An Equality Score (-100 to +100) was generated for job roles across factories, where 0 represents ideal balance.

 -The objective was to classify roles based on severity.

**2. Methodology**

Created a new column Equality Class using nested logical conditions:

  =IF(C2>=-10,
    IF(C2<=10,"Fair",
       IF(C2<=20,"Unfair","Highly Discriminative")),
    IF(C2>=-20,"Unfair","Highly Discriminative"))

-Classification logic:

  Fair → Score between -10 and +10

  Unfair → Moderate deviation

  Highly Discriminative → Severe deviation (> ±20)

**3. Key Insights**

 -Several roles fall under Highly Discriminative category.

 -Moderate inequality exists across multiple job roles.

 -Classification enables structured risk prioritization.

**4. Business Recommendations**

 -Conduct salary audits for Highly Discriminative roles.

 -Review HR compensation policies.

 -Implement regular pay equality monitoring framework.

**5. Skills Demonstrated**

 -Advanced Excel (IF, AND, OR)

 -Logical Rule-Based Modeling

 -Risk Categorization

 -Forensic Data Analysis
