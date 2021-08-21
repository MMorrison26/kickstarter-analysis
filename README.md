# Kickstarting with Excel
## *Overview* 
We will be using a dataset of more than 4,000 campaigns conducted over the last decade to analyze their success rate (and sometimes lack thereof) to compare against Launch Dates and Funding Goals.
### *Purpose* 
Client Louise has started conducting a fundraising campaign for a play (Fever), and she would like to know how different campaigns fared in relation to their launch dates and funding goals.
### *Analysis and Challenges*
We were able to hone in on data specifically relating to theater and even more specifically, relating to plays (as opposed to musicals or theater spaces). The data presented a challenge given the original "Category," but we were able to break out a Subcategory that allowed for more pertinent data to be studied. From here, we could analyze "successful" campaigns based on the month (regardless of year) (See Figure A below) as well as the percentage of successful campaigns between certain dollar goals (See Figure B below). 
#### Figure A:
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/87578449/130326279-03216b30-241c-4293-8bf9-93c22e2621a0.png)
#### Figure B:
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/87578449/130159558-ae5a4b01-53e2-4498-b6da-96b682b12b81.png)
### *Analysis of Outcomes Based on Launch Date*
In general, you'll notice that the most theater campaigns, regardless of outcome, were launched in May, June, and July. December had the fewest campaigns launched by far. The trend lines for both successful and failed outcomes follow similar trajectories with the exception of those 3 popular months (May, Jun, Ju) during which the success rate further outweights failed outcomes in comparison to other months. There's also a larger spike in failed campaigns in October than the corresponding spike of successful campaigns in October. (Interestingly October was also the only month that didn't have any canceled campaigns.)
### *Analysis of Outcomes Based on Goals*
Because this graph is based on percent of a whole, you'll notice that Percentage Successful and Percentage Failed are a mirror image of each other on the line graph (since no campaigns for plays were canceled). In general, the success goes down as the fundraising goal increases if we focus on 98% of the data. The uptick in success rate for goals of $35,000+ accounts for just 2% of the overall data since the number of plays in this data with goals that large was negligible. 
### *Challenges and Difficulties Encountered*
I was struggling with the Outcomes Based on Goals table/chart. The numbers just weren't adding up. I finally scrutinized the formulas only to realize 1) I hadn't narrowed down the COUNTIFS to include "plays" and 2) I hadn't included the "=" sign in order to include "greater than *or equal to*" in the formulas. This small correction really altered the corresponding line graph and where everything intersected. Because goals are often round numbers, it very much makes sense why this had such an effect on the results.
## *Results*
As seen from Figure A, May is the most successful month during which to launch a campaign. The rest of the summer months are also fairly successful in relation to other times of year. The other months of the year see a fairly consistent trend between successful and failed campaigns, meaning they spike and decline at a comparable rate. As seen from Figure B, campaigns are generally more successful if their goals are smaller. You can see three quarters of the campaigns under $1,000 were sucessful, steadly declining as you increase the goal to $30,000. Interestingly, there's an uptick in success from $30,000 to $45,000 before a large decline in success above a goal of $45,000 (although there were very few plays in the data with funding goals between $40,000 to $50,000 so those outcomes doesn't hold as much clout.) 

We could use some additional data with those higher goals to determine if that downward trend would continue. This data also dates 2009 - 2017; it wouldn't hurt to get some updated data to see how the economy (perhaps COVID) might effect campaigns like this. 

Some other information Louise might have found interesting was if we looked at average donations made specifically for campaigns regarding plays. Then she could have a target of how many people she needed to get pledges from in order to hit whatever goal she decides on. We could have also evaluated the length of campaigns that were successful vs. failed. Then she could identify that "sweet spot" of how long she should target to keep her campaign open and be able to sustain momentum. 

In all, Louise should have some great takeaways on how to continue her campaign. We wish her the best on making "Fever" happen!
