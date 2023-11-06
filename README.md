# Project-1
Group 3
https://docs.google.com/presentation/d/1KWbXadK3VwhmyAKGE7ip4fId99K_JiWmKiD3gNV4ajQ/edit?usp=sharing

# Statistical analysis

# ---------------------------
The reseach asks the question if it is wise to invest in beverage stocks. We achive this by tracking the overall trend of the beverage market, which group of drink is most profitable, and which company is the most profitable based off it's trends.

Stock data was found using the Polygon API, tracing two years of trends at the start of each month. The main groups were beer with Budweiser (BUD) and Coors (TAP), soda with Coke (KO) and Pepsi (PEP), and coffee with Starbucks (SBUX) and Dutch bros (BROS).

The primary variable that we are using as a point of reference is C, or closing price. This allows for a consistant way to track pricing for each point in time.

The dataset contained no outliers, which could be attributed to it being a small dataset, or that the stocks experienced no sudden spikes or loss of value in the last two years. This suggests that the stocks are allrelatively stable in their courses.

The C value correlation was very high, even close to a value of 1 in regards to the other price point variables, which was expected. However, the volume weighted variable was not expected to be as high, with a .99 coefficient. Volume weighted was discarded and not used in any other analysis, so this abnormality was disregarded.

The mean of each stock can be taken into consideration when determining its middle point, as it takes variability into consideration. BUD and TAP were the closest means, with BUD at 56.7, and TAP at 56.9. KO and PEP had the highest difference with KO at 59.6 and PEP at 173.8. SBUX and BROS had means of 96.2 and 30.2 respectively.

The lowest variation and standard deviation was KO, with a varience of 8.28 and standard deviation of 2.88, suggesting that it is the most stable of the stocks tracked. The two runner ups were BUD with a varience of 18 and standard deviation of 4.25, and DUTCH with a varience of 20 and a standard deviation of 4.48. While this does not determine the profitability, a more stable stock may be more desirable for long term investment.

# Question answers

# ---------------------------
1) The entire dataset shows a downward trend of twenty two cents per month, suggesting that the current trends of the beverage market are not worth investing in short term.

2) Beer stocks were the only group trending up, at a gain of fourteen cents per month. Soda was trending down at a loss of eight cents per month, and coffee at seventy cents per month.

3) The clear winner was TAP, with a gain of fourty five cents per month. The clear loser was BROS at a loss of a dollar sixty two per month. BUD trended down at seventeen cents per month, KO also trended down at thirty one cents per month. The other two stocks were positive, with PEP up fourteen cents, and SBUX up twenty one cents. 
