# VBA Challenge

## Overview of Project

This project focuses on refactoring the original script to make it more efficient and streamlined. The script automates the calculation of one year returns, Volume of stocks traded and also formats the output sheet. The algorithm written in this project is high performing as it is almost 5 times faster than the original macro.
 
## Results

In this section we will discuss two aspects of the project, The performance of the stocks and improvements implemented on the original macro.

### Performance of Stocks

The year 2017 was largely a good year for stocks that were under consideration. The percentage return was showing a positive direction and some stocks like DQ and ENPH more than doubled in their value. The image below shows a summary of how 2017 rolled out for the stocks.  

<img width="246" alt="2017" src="https://user-images.githubusercontent.com/73799417/103441052-28f57380-4c19-11eb-8704-6a11609dbc91.png">

2018 was generally a bad year for the portfolio. Most of the stocks lost a chunck of their value , where only ENPH and RUN were able to finish the year with positive gains. It is also interseting to see how the volume of shares traded in 2018 is less than 2017.

<img width="242" alt="2018" src="https://user-images.githubusercontent.com/73799417/103442003-38c48600-4c20-11eb-9be0-70ba9a1f1f46.png">

### Refactoring the VBA script

The previously created macro was over-all slower to run. This maybe because of the nested loops it had which made the process take more time. The code was refactored by creating an incremental variable which performed as an index for output arrays. This optimized my code and allowed the execution to occur in minimum amount of time. The image on the left belongs to the original code and the image to the right belongs to the optimized code.

<img width="259" alt="Original_2017" src="https://user-images.githubusercontent.com/73799417/103442149-9c02e800-4c21-11eb-880f-c5bd8eaf51e3.png">    <img width="263" alt="VBA_CHALLENGE2017" src="https://user-images.githubusercontent.com/73799417/103442153-a1603280-4c21-11eb-984b-486629093b09.png">


<img width="260" alt="Original_2018" src="https://user-images.githubusercontent.com/73799417/103442202-264b4c00-4c22-11eb-8184-4f9836b26a63.png">    <img width="262" alt="VBA_CHALLENGE_2018" src="https://user-images.githubusercontent.com/73799417/103442205-29463c80-4c22-11eb-94ad-7eb93b643f00.png">


## Summary

### Advantages of refactoring the code

1) The code becomes more easier to read.
2) It is less complex
3) Editing it is easier

### Disadvantages of refactoring the code

1) The amount of time required to carry out this process is hard to project
2) Can lead to scenarios where one can be completely lost

### Pros and Cons of refactoring this particular script

The readability of the VBA script improved drastically. Since the complex nested loop was removed, the ease of understanding the logic of the script was much better. Since the script is a little more user friendly, in the future if required the script can be comfortably edited according to the needs. Simplifying the script also allowed to significantly reduce the execution time too.

Initially it is quite difficult to come up with a solution that is needed to reach our goals. Therefore, a lot of time had to be allocated to understand the logic and come up with a working script. The code had to be thoroughly checked because while refactoring some formulas/functions might get accidently changed which may lead to erroneous results.

