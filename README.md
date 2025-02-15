# Solar Power Production Calculator

This program can calculate the power production of your system for a year. It will show you a graph that represents the months with power production that your system will probably produce. 

**Why probably?** Nature does what nature does. Sometimes the sun shines more or less. But this gives an indication of how much power can be produced.

---

## What do I need to make this calculation?

You need to know the maximum power production of your system. So, for example, if you have 20 solar panels of 410Wp (watt peak), you have a system with 20 * 410Wp = 8200 Wp. 

Start the program and change the number to match your system's power (Wp). 

The power production can be determined from this number. Here in the Netherlands, we have an annual power production factor of 0.85 times the Wp. So, an 8200Wp system over here can produce:
8200 * 0.85 = 6970 kWh annually.

---

## How do you know what the power production is each month?

That's actually simple. If you have a graph of your system’s production over a full year, you can see the power generated each month. We need to determine the production percentage for each month. 

How do we do that? It's simple:
- Add all the power produced in a full year. 
- The production factor for January is calculated as:  
PJanuary / PYear.
You do this for each month, so the sum of all monthly production factors will be 1 (100%).

---

## Customizing the Calculation for Your System

Each system has its own particular power production characteristics, so I will make it possible for you to have an external file with 12 lines of the power production for each month. This way, the program will calculate the power production factor for each month based on your data and give a more accurate estimate.

---

## How to Use the Program

1. Start the program and enter your system's Wp value to match your total system power.
2. Do **NOT** change the efficiency just yet—perform a calculation first.
3. You will see the program calculate an estimated yearly production.
4. If the numbers don’t match your system's actual monthly production, double-click on a month in the graph.  
   **Please try to pick an average month, avoiding extreme weather conditions.**
5. A pop-up will appear—enter the correct kWh value for that month and click **OK**.
6. The program will automatically adjust the efficiency to reflect the updated data, and your results will become more accurate.

---

## Conclusion

This program will give you a better understanding of your system’s expected power production. The flexibility to adjust monthly data makes it more accurate and representative of your actual system performance. 
