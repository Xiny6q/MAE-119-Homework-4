Download link :https://programming.engineering/product/mae-119-homework-4/

# MAE-119-Homework-4
MAE 119: Homework 4
You must show all work for full credit. Joint submissions can be made in groups of two. All submissions and code must be uploaded to Canvas for full credit.

Problem 1 (100 points)

The Konocti substation in the Bay Area is considering to build a microgrid in order to be more resilient to PG&E outages. Let’s consider their economic options for the month of October, when wild res usually occur. The following is the electric demand for a typical day in October1.

Hour

Demand (MW)

Hour

Demand (MW)

0

5.1

12

6.2

1

4.9

13

5.9

2

5.1

14

5.9

3

5.3

15

5.9

4

5.6

16

6.5

5

6.7

17

7.2

6

8.0

18

7.9

7

8.6

19

8.1

8

8.3

20

8.1

9

7.6

21

7.4

10

7.2

22

6.4

11

6.7

23

5.6

(20 points) We will consider 3 options for the microgrid. Determine the nominal capacity for each:

Diesel generation: Size to be equal to the peak load.

Solar: Size to produce as much as the monthly demand. To do this, size the actual generation that we could get during October at this site using TMY3 data for Ukiah, CA, and considering arrays of

5000 Canadian Solar panels (220 W nominal power each) connected to a Green Power Technologies: PV900WD inverter (1 MW nominal capacity). How many 1 MW arrays are needed to produce the monthly demand?

Battery: Size to equal the nighttime energy use (t 7 PM or t 7 AM).

(80 points) Let us consider only the operation during the power outages which are assumed occur during

20 days in October, for the three following solutions:

A diesel microgrid, where the investment costs are $550/kW, O&M yearly costs are $0.012/kW, fuel costs are $3.96/gal, and the fuel consumption is 0.10 gal/kWh.

A solar+battery microgrid, where the solar investment costs are $1800/kW, the O&M costs are $9/kW, there is a 30% tax incentive, the battery investment costs are $600/kWh, and the O&M costs are $0 for the rst 10 years (10 year warranty). The battery system is replaced at year 10 and a new 10 year warranty applies.

1https://www.pge.com/en US/for-our-business-partners/energy-supply/electric-rfo/wholesale-electric-power-procurement/system-reliability-rfo.page?WT.mc id=Vanity rfo-systemreliabilityrfo


A hybrid solar and diesel microgrid, where the solar system is sized for the daytime peak instead. To do this, model the solar generation for October 15, and assume that the rest of the demand is satis ed with diesel.

For each solution, evaluate two scenarios: the rst with a loan with 10% down payment and a 5%/year interest rate, and the second paying for the investment cash (without a loan). Consider a market discount rate of 6%, in ation of 5%, and compute the present worth and cumulative costs for years 0-20. Report the net present value (LLC for diesel and LCS for the solar+battery and solar+diesel) and LCOE for the two nancing scenarios.

Why does the analysis not capture the full value of solar? Assume that during the non-outage periods (the remaining days of the year), solar energy can be sold at 15 cents per kWh. Recalculate the life cycle savings of adding solar (without battery) to a diesel powered microgrid.

Acknowledgements: Economic parameters were provided by Zackary Pecenak from Xendee.
