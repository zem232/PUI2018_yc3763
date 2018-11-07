Dear Yushi Chen,

    Good choice of a clear and testable hypothesis! Your hypothesis statement should be more of an IDEA statement which will then form your null and alternative hypotheses. But your null hypothesis is formulated correctly! You just need to further state your corresonding alternative hypothesis. In this case, it would be "The proportion of customer biking on daily basis is lower than the proportion of subscriber biking on daily basis". You may also want to add mathematical expressions for both hypotheses to make them even clearer: H0: Pc - Ps >= 0; H1: Pc - Ps < 0, where P is proportion, c is customer, and s is subscriber. Meanwhile, you clearly stated your confidence level alpha = 0.05.

    The data you chose is appropriate for your hypothesis test. You dropped the other columns and left only "usertype" and "date", which are sufficient for differentiating two user types from all the "starttime" from all stations. You also processed the "starttime" into "date" ahead, which standardized the "starttime" column and made it into values that can be recognized by "groupby" coding operation.

    Given the your idea statement and hypotheses which are about proportions of categorical data, I suggest that you use a Z-test to test your null hypothesis. Because Z statistics tells you whether there is a significant difference between proportion in 2 samples, and the sample size in this case is larger than N =30 which fulfills the requirement of Z statistics. You can try out the CitiBike data of another or more months to see if your result for hypothesis test holds!