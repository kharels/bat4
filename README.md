# Are you ready for another DevOps anecdote?

-  This eCommerce platform has 4.4 million sellers and 81.9 million buyers
-  This gaint enables eCommerce on enormous scale for varoius arts and crafts communities accross globe
-  It saw massive growth and had to piviot several times during pandemic.

# Who could it be?
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

![Etsy Logo](Etsy_logo.svg)


# History
- Changes pushed twice a week
- Spend weeks writing code before deploying it
- painful merges
- Devs handed off the code to deployers 
- Lots of outages followed deployment
- Teams were siloed, and things moved at very slow pace
- Oh, there is rollback..
- Nevermind, the change never made it to production. 
- Used home grown deployment tool called 'Sprouter', which eventually became SPOF and almost every deployment cuased outage

# Change is inevitable
- In 2009, Etsy adopted DevOps, and since has been great example of methodology since
- It took them 2 years to reach steady state and derive value from investment
- Now they deploy more than 50 times a day (unrelated fun fact, on busy day amazon deploys about 1100 times in an hour)
- How did they get there
    - Started with monitoring, and stablizing sites
    - automated DB upgrades
    - implemented continuous deployment
    - Developed 'Try'(Open Source) for testing their changes in Jenkins
    - Developed 'Deployinator'(Open Source) for deployment orchestration
    - investment in prod like staging environment, where all test happened
    - Config flags were integral part of deployment
    - Continuous monitoring

# Lessons to learn
- It's not about doing it all at once, or doing it right the first time.
- Invest in open source
- Enable your people, break silos, cross train.
- And don't forget DevOps is Journey NOT destination
