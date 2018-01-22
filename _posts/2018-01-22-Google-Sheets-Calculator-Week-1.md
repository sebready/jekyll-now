---
title: Google Sheets Calculator Week 1
layout: post
author: seb.read
permalink: /google-sheets-calculator-week-1/
source-id: 1FGWgigDU1na5Is_TLVfdSdxzQXCq1_dG5_RpwKAh6Ew
published: true
---
**Google Sheets Calculator Week 1**

This week started working on our google sheets calculator project.

We started off at the beginning and made a list of items in the "shop". And then gave each of the items a price.

![image alt text]({{ site.url }}/public/uaaH3RQD6okWk2RyETpfg_img_0.png)

Then to make the shopkeepers life easier we added a column so they can select the items the customer wants in the boxes provided.

![image alt text]({{ site.url }}/public/uaaH3RQD6okWk2RyETpfg_img_1.png)

After that the calculator works out how much each of those items cost with this code =iferror(vlookup(E2,$A$2:$B$6,2,false), ). And then it works out the total cost of that =SUM(G2:G6)

![image alt text]({{ site.url }}/public/uaaH3RQD6okWk2RyETpfg_img_2.png)

After the shopkeeper has to assign all of the different items the quantity of each item that the customer has bought. Plus it also sums up the amount of items the customer has bought altogether. =SUM(I2:I6)

![image alt text]({{ site.url }}/public/uaaH3RQD6okWk2RyETpfg_img_3.png)

Then the calculator works out the amount of money for that one item times the quantity of that item the customer has. =G3*I3. Then displays the amount of money altogether owed by the customer. 

![image alt text]({{ site.url }}/public/uaaH3RQD6okWk2RyETpfg_img_4.png)

After the shopkeeper has a chance to add discounts to the final price and then displays the final price at the bottom of that column.

![image alt text]({{ site.url }}/public/uaaH3RQD6okWk2RyETpfg_img_5.png)

So the final Table after the lesson looked like this. 

![image alt text]({{ site.url }}/public/uaaH3RQD6okWk2RyETpfg_img_6.png)       

