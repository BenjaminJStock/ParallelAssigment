The provided data files contain records of air temperature collected over a period of more than 80 years from five weather stations in 
Lincolnshire: Barkston Heath, Scampton, Waddington, Cranwell and Coningsby. The original file is called “temp_lincolnshire.txt” and the
short dataset is in “temp_lincolnshire_short.txt”.
Each column corresponds to the following category:
   1. weather station name
   2. year the record was collected
   3. month
   4. day
   5 time (HHMM)
   6 air temperature (degree Celsius)
   
   
   Your task is to develop a simple statistical tool for analysing historical weather records from
Lincolnshire. The provided data files include records of air temperature collected over a period of
more than 80 years from five weather stations in Lincolnshire: Barkston Heath, Scampton,
Waddington, Cranwell and Coningsby. Your tool should be able to load the provided dataset and
perform statistical summaries of temperature including the min, max and average values, and standard
deviation. The provided summaries should be performed on the entire dataset regardless their
acquisition time and location. For additional credit, you can also consider the median statistic and its
1st and 3rd quartiles (i.e. 25th and 75th percentiles).
Due to the large amount of data (i.e. 1.8 million records), all statistical calculations shall be performed
on parallel hardware and implemented by software written in OpenCL. Your tool should also report
memory transfer, kernel execution and total program execution times for performance assessment.
Further credit will be given for additional optimisation strategies which target the parallel performance
of the tool. In such a case, your program should run and display execution times for different variants
of your algorithm. Your basic implementation can assume temperature values expressed as integers
and skip all parts after a decimal point. For additional credit, you should also consider the exact
temperature values and their corresponding statistics.
You can base your code on the material provided during workshop sessions but you are not allowed to
use any existing parallel libraries. To help you with code development, a shorter dataset is also
provided which is 100 times smaller. The original file is called “weather_lincolnshire.txt” and the
short dataset is “weather_lincolnshire_short.txt”. More details about the file format are included in the
“readme.txt” file. The output results and performance measures should be reported in a console
window in a clear and readable format.
The main assessment criteria for this task are related to the correctness of the developed algorithms
and effectiveness of optimisation s
