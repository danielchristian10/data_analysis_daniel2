# Descriptive Analsys of Parking Tickets

# Objective

This project was intended to perform a significant exploratory analysis of parking ticket information including ticket subtypes, parking blocks, dates of issue, times, vehicle manufacturers, and fines. The objective was to get insights within the data about the trends and patterns of parking violations that would serve as reference in enhancing parking enforcement strategies, areas with high parking violations and recommendations on parking management. Thus, knowing the characteristics of these penalties parking authorities can implement appropriate actions to decrease violations and improve the general traffic management of cities.

# Dataset

The dataset consists of detailed parking ticket penalty data from various locations. The following features were included:

-. Ticket ID: A unique identifier assigned to each parking ticket.

-. Violation Date: The exact date and time when the violation occurred.

-. Violation Code: A numerical or categorical code representing the specific parking violation (e.g., expired meter, no-parking zone).

-. Vehicle Plate: License plate number of the vehicle that received the ticket.

-. Fine Amount: The monetary penalty imposed for the parking violation.

-. Issuing Officer ID: The ID of the officer responsible for issuing the ticket.

-. Location: The location (street, neighborhood, or zone) where the violation occurred.

-. Vehicle Make: The make or brand of the vehicle (e.g., Toyota, Ford, Honda).

-. Violation Status: The current status of the ticket (e.g., paid, unpaid, contested).

-. Time of Day: Extracted from the violation date to understand when violations occurred (morning, afternoon, evening).

Example of dataset: 

![image](https://github.com/user-attachments/assets/e6d63030-d04d-4243-89bc-051571ec37d0)

# Methodology 

1. Data Collection and Preparation

-. Data Loading: The parking ticket dataset was loaded using Python libraries such as Pandas for efficient data handling and manipulation.

-. Data Cleaning:Handling Missing Values, Standardizing Data Types, and Duplicate Removal

2. Descriptive Statistics:

-. Numerical Analysis and Categorical Analysis

3. Data Visualization:

-. Histograms and Boxplots: Created histograms to illustrate the distribution of fine amounts, revealing common penalty ranges and the presence of any outliers (e.g., severe penalties for critical violations like obstructing traffic).

-. Bar Charts: Created bar charts to display the most frequent violation types (e.g., expired meters, no-parking zone infractions) and the most commonly ticketed vehicle makes, highlighting patterns among violators.

-. Heatmaps: Developed heatmaps to visualize the density of parking violations by location. This identified “hot spots” where parking violations were frequent, such as business districts or high-traffic areas.

-. Time Series Analysis: A time series plot was created to visualize the occurrence of parking violations over time, identifying peaks and troughs (e.g., higher violations during weekdays vs. weekends, or during specific hours of the day).

4. Violation Pattern and Trend

-. Location-Based Analysis: Compares the number of violation in relative to other site to determine areas with high traffic in ticket issuance. For instance, places close to malls or business and commercial buildings received high violation rates because of inadequate parking space.

-. Vehicle Make Analysis: The study looked at which vehicle brands were cited most often, and these results may have depicted relations between demographic of vehicle ownership and parking offences. This could unveil trends such as increased violations in commuter or dyna-frequently parked sh axis used frequently.-parked vehicles.

-. Fine Amount and Violation Severity: Explored moderating variables using violation type and fine amount, showing that certain violations elicit higher penalties than other violations (e. g., parking in handicapped zones compared with overstaying a parking meter).

5. Insights and Findings:

-. Most Common Violations: One of the findings of the carried out analysis was the fact that some types of infractions, including extended time at parking meter zone and parking in no-standing zones, comprised the greatest percentage of parking tickets. This highlights areas that, with increased enforcement, improved enforcement or different type of parking facilities, the violations are likely to be minimized.

-. Location Hotspots: Strong correlation of parking tickets to certain areas of the city, more specifically to the places which were commercial and having crossroads. These details are important for authorities to use in the best possible way with regard to patrols and enforcement.

-. Time-Based Violation Patterns: Most violations took place during working hours extending from mid-morning to late afternoon which would suggest possible inadequate parking space during rush hours regarding business undertakings.

-. Unpaid Tickets: Substantial number of tickets were still unpaid, which implied that there could be defects in the processes of payment or enforcement of tickets that could be worked on to increase compliance.

6. Recommendations:

-. Enhanced Parking Enforcement: Ensure that there are more enforcement officers on the streets during the times of the day that the violations are most common for example around business centres during late morning and afternoon hours.

-. Improved Signage and Education: Even to the parts of the road where there are many incidences of no-parking zone violations, it may be necessary to install better signs; or even launch an information campaign meant to go to drivers to clear misconceptions regarding the zoning of the road.

-. Dynamic Penalty System: We should consider proposing the dynamic penalty system which will include the increase of the fines for certain violations depending on their gravity, time period and geographical area. For instance one may be required to pay higher fines when you commit an offense in areas that have got a lot of traffic or when you get on the list of repeat offenders.

-. Online Payment and Notification System: Promote easier ways of paying fines by increasing the efficiency of the online platform or a specified mobile application to limit the number of unpaid tickets.

![image](https://github.com/user-attachments/assets/dca6b1c0-1b51-486b-9a74-9406e610e7c2)

# Tools and Technologies

  1. Python: For data manipulation and analysis

  2. Tableau: Used for interactive dashboard creation, enabling stakeholders to explore visual trends in parking violations.

  3. Excel: For data exploration

![image](https://github.com/user-attachments/assets/c4f15f13-0544-4af5-a890-c17a0a572d4b)

# Deliverables

1. Visualization: Using all of the available tools mentioned above

2. Presentation: Summarizing key findings and recommendations for improving parking enforcement and reducing violation frequency. The presentation includes visual elements and insights tailored to non-technical stakeholders.

3. A Comprehensive Documentation: Documenting each step of the analysis, including data cleaning, descriptive statistics, and visualizations. The notebook contains code and narrative explanations for easy replication.

# Outcome

Over the period under consideration, the project was able to point out prevalent parking violation majoring on the location, time, and type of vehicle. Based on these patterns, the analysis made several suggestions on how to improve parking enforcement, to decrease violations and to optimise parking space in certain areas thus improving their availability. The results were also provided the premise for predictive analysis to predict the parking violations depending on the location, time and the type of vehicle.
