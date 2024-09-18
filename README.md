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

-. Location-Based Analysis: Compared the frequency of violations across different locations to identify areas with high ticket volumes. For example, areas near shopping centers or downtown business districts showed disproportionately high violation rates due to parking shortages.

-. Vehicle Make Analysis: The analysis explored which vehicle brands were most frequently ticketed, showing potential correlations between vehicle ownership demographics and parking violations. This could reveal trends such as more violations among vehicles used by commuters or those frequently parked in high-traffic areas.

-. Fine Amount and Violation Severity: Analyzed the relationship between violation type and fine amount, revealing that some violations (e.g., parking in handicapped spots) consistently resulted in higher penalties compared to others (e.g., overstaying parking meters).

5. Insights and Findings:

-. Most Common Violations: The analysis showed that certain types of violations—such as overstaying at parking meters and parking in no-parking zones—accounted for the majority of parking tickets. This points to areas where better enforcement or alternative parking options could reduce violations.

-. Location Hotspots: Identified areas, especially around commercial zones and busy intersections, where parking tickets were most frequent. This information is useful for authorities to optimize patrols and enforcement strategies.

-. Time-Based Violation Patterns: Violations were concentrated during business hours (particularly mid-morning and late afternoon), indicating potential issues with parking availability during peak times.

-. Unpaid Tickets: A notable portion of tickets remained unpaid, suggesting inefficiencies in the payment or enforcement process that could be addressed to improve compliance.

6. Recommendations:

-. Enhanced Parking Enforcement: Increase the presence of enforcement officers in high-violation areas during peak hours (e.g., around business districts during late mornings and afternoons) to deter violations.

-. Improved Signage and Education: In areas with frequent no-parking zone violations, consider adding clearer signage or running public awareness campaigns to reduce confusion about parking rules.

-. Dynamic Penalty System: Explore introducing a dynamic penalty system that adjusts fines based on the severity of the violation, the time of day, and location. For example, higher fines could be imposed in high-traffic zones or for repeat offenders.

-. Online Payment and Notification System: Streamline the process for paying fines through a more accessible online portal or mobile app, reducing the number of unpaid tickets.

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

The project successfully identified critical parking violation trends across locations, times, and vehicle types. By understanding these patterns, the analysis provided actionable recommendations to enhance parking enforcement strategies, reduce violations, and improve parking availability in key areas. The results also laid the foundation for further predictive analysis to forecast parking violations based on factors such as location, time, and vehicle type.

