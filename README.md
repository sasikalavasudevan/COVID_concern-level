# 1. Extracting US states from address string:
The address string retreived from twitter may contain many complex data. For example:
a. non-ASCII keys
b. spell mistakes in state name
c. may have only city names and not include state name
Therefore, the address line is cleaned and appropriate states are recovered using the python code provided in "Extracting states from address string" file.

# 2. concern level of people from each state is found:
After extracting states, a consolidated monthly data is analysed and concern level of people for each state is calculated using code from "computing concern-level" file.
This helps us analyze how covid impacted a certain state during certain time period.
 
# 3. US map showing the concern level of each state, number of positive tweets, negative tweets are displayed:
The output file of "#2" is used as input and US map using choropleth is created. The code can be found in "Creating US map" file.

# 4. A webpage is created with an interactive US map that shows concern level of each state during various time period using html. 

# The result of the above mentioned jobs can be found in http://cis.csi.cuny.edu/~soon/dgo/2020/index.html under the topic "Citizen Concern Map"
