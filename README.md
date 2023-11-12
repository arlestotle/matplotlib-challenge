# matplotlib-challenge

In this challenge we were tasked to analyze the data from a new pharmaceutical company that specializs in anti-cancer medications. The dataset contained information on 249 mice, including one duplicate, for a total of 248 different mice.

We found that mice treated with Ketapril had the greatest average tumor volume of 55.23 mm3, whereas mice treated with Ramicane had the lowest average tumor volume of 40.21 mm3. Capomulin was the drug that treated the most amount of mice and Propriva was the drug that treated the least amount of mice. 51% of the treated mice were male. 

We were asked to run further analysis on mice treated with Capomulin, Ramicane, Infubinol, and Ceftamin. We found that Capomulin and Ramicane had a similar spread of final tumor volumes. Although Infubinol had a similar spread of final tumor volumes, it also contained a lower bound outlier. 

The correlation between mouse weight and the average tumor volume for Capomulin treated mice was 0.84.

Through the use of the starter code, Stack Overflow, and the help of some of my peers I was able to find the code for the pie chart percent labeling: "autopct = "%1.1f%%"", the for loop used to calculate the IQR of tumor volumes: "treatments = [] for drug in treatment_timepoint["Drug Regimen"]: if drug not in treatments: treatments.append(drug)" and the linear regression equation: ""y = " + str(round(slope,2)) + "x + " + str(round(intercept,2))".
