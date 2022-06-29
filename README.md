#answer2
t.test(Dominos$Time,mu=173.62)

	One Sample t-test

data:  Dominos$Time
t = -4.2568, df = 29, p-value = 0.0001984
alternative hypothesis: true mean is not equal to 173.62
95 percent confidence interval:
 151.6632 165.9148
sample estimates:
mean of x 
  158.789 
  
 #answer3
  t.test(mydata$cyl, mydata$hp, alt="two.sided")

	Welch Two Sample t-test

data:  mydata$cyl and mydata$hp
t = -11.588, df = 31.042, p-value = 8.322e-13
alternative hypothesis: true difference in means is not equal to 0
95 percent confidence interval:
 -165.2266 -115.7734
sample estimates:
mean of x mean of y 
   6.1875  146.6875 
