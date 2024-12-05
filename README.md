# econo_assignment5

1.	C
2.	C, D
3.	C, D
4.	B, C
5.	C, D
6.	C
7.	A, B, C, D
8.	A, B
9.	C
10.	B, C
11.	
a.	No, the coefficient on time_dummy (91.31,p=0.973) is not a good estimator because it is statistically insignificant and fails to account for individual or time-invariant effects, potentially biasing results.
b.	The interaction_b coefficient (−11.12,p=0.998) is statistically insignificant, indicating no significant treatment effect. Additional controls or refinements are necessary to clarify the policy's impact.
c.	The interaction_c coefficient (11.12,p=0.998) remains statistically insignificant, showing no strong evidence of a treatment effect when considering multiple time periods.
d.	Collinearity caused post_policy_d and interaction_d to be omitted, rendering this specification ineffective. The coefficient on d (4009.09,p=0.015) is significant, but its interpretation is confounded by omitted variables.
12.	
a.	x2_collinear is omitted due to collinearity, confirming that perfect collinearity prevents OLS from estimating coefficients for all variables simultaneously.
b.	The fixed-effects model yields significant coefficients for x1 (−4.26,p<0.001) and x2 (−1.54,p<0.001), indicating that OLS is consistent and accounts for within-group variation.
c.	The coefficient on x1_missing (−639.00,p=0.592) is statistically insignificant, likely due to the reduced sample size, while x2 remains significant (1889.79,p<0.001).
d.	The coefficient on x1_trend (−167.37,p=0.554) is insignificant, reflecting a potential bias caused by correlation with time. This violates OLS assumptions.
13.	The interaction_13 coefficient (14.10, p<0.001) remains overestimated compared to the true effect (5), even with added controls and interactions. Collinearity with fixed effects likely inflates the estimate, requiring further refinement of the model.

