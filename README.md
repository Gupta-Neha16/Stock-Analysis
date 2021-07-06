
# Stock-Analysis

The purpose of this project is to use data from yahoo finance and leverage the yahoo finance library to showcase the market trends at the start of the Covid crisis.

![Screen Shot 2021-06-15 at 8 50 46 PM](https://user-images.githubusercontent.com/29782408/122145707-5dea3100-ce1b-11eb-84d3-7c9bb8e58b7d.png)


Obtained historical data for Microsoft with duration as maximum.

The image below shows stock splits, dividends, volumne, close, low, high and open values plotted on a chart since 1988.

![Screen Shot 2021-06-15 at 8 18 48 PM](https://user-images.githubusercontent.com/29782408/122143482-2bd6d000-ce17-11eb-86aa-4e6960a7a4fb.png)

Obtained world indices from "https://finance.yahoo.com/world-indices" by grabbing the first table.
The data required cleaning as there was a "^" symbol with the indices. The data was converted to a list.

![Screen Shot 2021-06-15 at 8 26 27 PM](https://user-images.githubusercontent.com/29782408/122143880-f7afdf00-ce17-11eb-820d-635a649b6d92.png)

Data for the indices were then downloaded from 2020-01-15 to 2020-04-15.
There were many values with "NaN". Dropped the columns (indices) that had more than 10 values as NaN.

<img width="720" alt="Screen Shot 2021-07-06 at 1 55 42 PM" src="https://user-images.githubusercontent.com/29782408/124652563-df087700-de61-11eb-826a-cc03f2ddaefd.png">

After that we were left with 7 world markets data. The data was plotted for these world markets.

The plots below show the dip in the market due to the Covid crisis. 

![Screen Shot 2021-06-15 at 8 32 27 PM](https://user-images.githubusercontent.com/29782408/122144289-cdaaec80-ce18-11eb-9b88-86bf6188fd90.png)

Dropping XAX from the graphs as there is large amount of data missing.

![Screen Shot 2021-06-15 at 8 37 29 PM](https://user-images.githubusercontent.com/29782408/122144650-82450e00-ce19-11eb-96da-7885c1238547.png)




Let's look at Dow Jones Industrial index.
Daily Percent Change shows the market instability as the Covid lockdowns were announced.


![Screen Shot 2021-06-15 at 8 37 51 PM](https://user-images.githubusercontent.com/29782408/122144681-8ffa9380-ce19-11eb-94d9-bb1f9d6a6f53.png)

Daily Returns = (Daily Price/(Daily Price -1))-1


![Screen Shot 2021-06-15 at 8 38 04 PM](https://user-images.githubusercontent.com/29782408/122144704-97ba3800-ce19-11eb-94b5-44b4f4accf33.png)


