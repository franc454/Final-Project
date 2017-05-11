# Final-Project

plot_LWC takes a .txt file with GPS data and returns a plot of liquid water content of
a snowpack through time based on that GPS data.  A PDF of the plot is also saved.
The liquid water content (LWC) values are averaged over a certain timestep.

plot_LWC.py calls liquid_water_content.py to convert signal strength above and below the 
snowpack, snow depth, and elevation angle to a liquid water content value. Run plot_LWC.py.

Adjustable interval of time for averaging LWC values ('time_step') is on line 38.
To change files, change the 'name' variable to your desired file's name.  The 'name'
variable is on line 32.

The PDF of the plot will be saved under the same name as the text file being read
but with '_SWEplotted.pdf' added.  For example, reading a file 'hour_test_1.txt' 
will save a PDF titled 'hour_test_1_SWEplotted.pdf.'

Author: Keenen Francois-King
