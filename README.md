<h1>Business-Intelligence</h1>

<h3>Design and Implementation</h3>


These essential steps should be followed with the goal to implement and design a business intelligence tool for General Motors Ltd. that will support advanced problem-solving and decision-making that is in line with GM's requirements:
<p>1.	Establishing Specific Tasks and Goals</p>
Utilising data on carbon emissions to identify countries with a high potential for the adoption of electric vehicles (EVs).
<p>•	Analyse Carbon Emissions Data: Evaluate the data to gain insight about the impact on the environment and market availability, such as total emissions, emissions per capita, and energy consumption.</p>
<p>•	Analyse Other Relevant Factors: Consider the EV market size, the environment for regulation, and the general availability of infrastructure for charging EVs.</p>
<p>2.	Gathering and Preparing Data</p>
<p>•	Data Sources: Collect data related to carbon emissions, considering energy consumption, per-capita emissions, and total emissions. Utilise Excel's geographic function to extract and calculate key information applicable to an analysis of EV adoption.</p>

<img alt="image" src="https://github.com/user-attachments/assets/4ea534ce-020e-4438-acb5-f519829a02d4" />

<p>•	Upload the Data: Select Excel spreadsheets to start the data upload process from the Home ribbon's Data section in Power BI tool. You can choose to load or transform the data in the Navigator to ensure accuracy by using the preview feature offered by the Navigator to confirm that Power BI is loading the proper data range before moving further.</p>

<img alt="image" src="https://github.com/user-attachments/assets/e140f56d-6159-40fb-a4a1-a9ffe412cdcf" />

<p>•	Data Transformation and Cleaning: Using Power BI's Power Query Editor to make sure the data is clear, organised, and prepared for precise analysis, this step involves deleting duplicates, fixing errors, and formatting different data types.</p>

<img alt="image" src="https://github.com/user-attachments/assets/7149dcd1-9e35-47de-b3f9-66da162ec688" />

<p>3.	Use Power BI for Designing the BI Solution</p>

<p>•	Dashboard Creation: Utilise Power BI to create a dashboard that indicates different countries with great potential for EV adoption by visualising data on carbon emissions.</p>

<img alt="image" src="https://github.com/user-attachments/assets/a8b39df7-7049-476e-8394-96c7149b534e" />
<img alt="image" src="https://github.com/user-attachments/assets/d29fd0ce-6b7b-49d8-9a1f-a8cad0630ae7" />

<p>•	Data Visualisations: Use a variety of graphs and charts to visually present emissions data. Stakeholders will find it easier to read and understand the data as a result of these visual elements.</p>

<img alt="image" src="https://github.com/user-attachments/assets/bf3c9ee1-fba0-4945-be9f-768f89bb5207" />

<p>•	Advanced Features: Make use of Power BI's drill-throughs, slicers, and dynamic filters to explore more thoroughly into the data and analyse carbon dioxide emissions trends and factors that influence the adoption of electric vehicles.</p>

<p>4.	Testing the Dashboard</p>

  <table>
        <tr>
            <th>Test No</th>
            <th>Description</th>
            <th>Test Steps</th>
            <th>Expected Output</th>
            <th>Actual Output</th>
            <th>Test Status</th>
        </tr>
        <tr>
            <td>1</td>
            <td>Check that the information provided on CO2 emissions, GDP, minimum wage, petrol prices, and sales of electric cars matches the data from the original sources.</td>
            <td>Verify that the calculations are accurate, including sums, averages, and percentages.</td>
            <td>According to the source files, every value on the dashboard should represent correct data.</td>
            <td>Displayed values are matching the source file values.</td>
            <td>PASS</td>
        </tr>
        <tr>
            <td>2</td>
            <td>Examine the readability presentation of each graph and chart.</td>
            <td>Make sure the titles, legends, and labels effectively and clearly represent the data.</td>
            <td>Visuals are supposed to be easy to understand without further explanation, effectively labelled, and clear.</td>
            <td>The readability meets the basic requirements; therefore, improvements could be considered.</td>
            <td>PASS</td>
        </tr>
        <tr>
            <td>3</td>
            <td>Examine every interactive component, including drill-down capabilities, filters, and slicers.</td>
            <td>Verify whether changing the data groups or countries properly updates the visuals.</td>
            <td>Interactive elements would need to function seamlessly, precisely updating relevant information and charts.</td>
            <td>The interactive elements function as expected.</td>
            <td>PASS</td>
        </tr>
        <tr>
            <td>4</td>
            <td>Examine how quickly the dashboard loads and how adaptable the visuals are when applying the filters or interacting with the various components.</td>
            <td>Check the dashboard's performance consistency across various browsers and devices (PC, tablet, smartphone).</td>
            <td>The dashboard should continue to load rapidly and adapt to user input on various devices with effectiveness.</td>
            <td>The dashboard is performing as expected.</td>
            <td>PASS</td>
        </tr>
        <tr>
            <td>5</td>
            <td>Analyse the navigation and usability of the entire user experience.</td>
            <td>Verify the user-friendly interface and its functionality.</td>
            <td>All intended users should be able to navigate the dashboard and have an excellent user experience.</td>
            <td>The user experience meets the basic requirements; additionally, improvements can be made to ensure a user-friendly interface.</td>
            <td>PASS</td>
        </tr>
    </table>

<p>5.	Maintenance</p>


<p>Since Power BI allows quick transitions between data, insights, and action, data refreshment is essential to generate accurate and up-to-date results. When a report or dashboard’s visualisations depend on a refreshed model, Power BI searches the underlying data sources, loads the data into the model, and makes the necessary updates (Microsoft, 2024).</p>

<p>Creating valuable knowledge from data is becoming increasingly difficult as the amounts of information continue to rise. Power BI’s dataflows encourage the reuse of data components, ensuring access to cloud-based or on-premises databases without having to setup new connections. Dataflows give management improved authority over data refresh operations and minimise the workload on the initial systems by restricting access to the underlying data. This approach indicates that data is secure and simple to access for analysis while also enhancing overall data management and performance (Microsoft, 2023).</p>


<p>Additionally, alerts can be configured on visuals generated from live databases and attached from a report to a dashboard. Users can view notifications in the Power BI service and the Power BI mobile due to the complete platform synchronisation of these data alerts, which ensures timely updates and reliable information regardless of where you are (Microsoft, 2024).</p>


<p>6. Feedback and Refinement</p>


<p>Getting feedback from stakeholders on the EV adoption dashboard is critical for improving the tool and supporting decision-making. Their observations contribute to the following enhancements that should be taken into consideration:</p>

<p>•	Key Metrics: The dashboard should include essential information on labour force participation rates, EV sales by region, and CO2 emissions. These statistics should provide an in-depth understanding of the factors that impacts the adoption of EVs.</p>
<p>•	Data Visualisations: The dashboard should present data in a user-friendly format using a variety of visualisations, including bar charts and pie charts. Improving the user experience requires that these visualisations clearly communicate important insights.</p>
<p>•	Design and Layout: Users should be able to quickly find relevant information in addition of the dashboard's user-friendly layout. A user-friendly layout assures that viewers can quickly explore and understand the data displayed.</p>
<p>•	It's critical that the dashboard's titles, legends, and data labels are clear and help users in understanding the data that has been visualised. Managers could benefit from adding more concise labels. For example, laying out the importance of each statistic and assisting in connecting the data to potential strategies for the market.</p>
<p>•	Focus on suitable metrics which reinforce strategic goals and ensure the data provided is in line with the decision-making procedures of the stakeholders. Furthermore, evaluate the usefulness of the dashboard's interactive features, such as slicers and drill-down options while making sure these improve user experience and enable more in-depth data search.</p>


<p>7. Customization and User Interface</p>


<p>The solution has been customised to suit General Motors Ltd.'s needs for efficient data visualisation, functionality, and support for decision-making. The design was constructed to be user-friendly by considering the feedback from stakeholders and provide an interface that is functional.</p>

<p>A.	Essential Enhancements</p>

<p>•	Data Overview and Visual Elements: Using a variety of visualisations, both dashboard versions addressed important metrics such as CO2 emissions, EV sales, and economic factors. The updated dashboard provides results more readily and improves the understanding of each metric by introducing more descriptive diagrams and clearer data labels.</p>
<p>•	Functionality and Interactivity: The dashboard's initial version had minimal filters for data selections and basic interactive elements. The updated version includes navigation buttons, drill-down features, and dynamic filters that considerably enhance interactivity while making it easier for users to investigate and conduct in-depth analyses of particular data groups.</p>
<p>•	User-friendly Interface Design: Users faced challenges navigating the initial created dashboard interface since it was overcrowded and hard to understand. The updated dashboard has a clear design with easily accessible filters that makes it less difficult to navigate and improves overall usability and efficient data interpretation.</p>

<img alt="image" src="https://github.com/user-attachments/assets/b9cd76b9-3e2f-4f14-bc26-55d22e444813" />
<img alt="image" src="https://github.com/user-attachments/assets/ce884410-38cb-4ceb-b978-72904deb0eb4" />
<img alt="image" src="https://github.com/user-attachments/assets/b1c5db3e-3db0-4bc6-9903-1bcae05fcd38" />

<p>B.	Data Analysis for General Motors Ltd.</p>

<p>•	The "CO2 Emissions by Country" chart identifies regions where increased adoption of electric vehicles might considerably reduce CO2 emissions. It shows the biggest emitters such as China (10M), the USA (5M), India (2M), and Japan (1M).</p>

<img alt="image" src="https://github.com/user-attachments/assets/d6898a43-d0e9-4f90-9014-ce7ca0fc458f" />

<p>•	The charts known as "Historical and Projected EV Charging Points" suggest China's leading position, with 7.6 million charging points currently in use and a projected 38 million, ahead of the United States, which has a significant opportunity to grow in terms of charging infrastructure.</p>

<img alt="image" src="https://github.com/user-attachments/assets/7aadb41a-b1f2-44ac-b3a5-0d792d8c2c06" />

<p>•	China leads in the "Electric Vehicles Sold by Country" chart with 21.8 million EVs sold, followed by the USA (4.7 million) and Germany (2.9 million), which are thriving regions with high rate of adoption.</p>

<img alt="image" src="https://github.com/user-attachments/assets/d5c5b34e-de2f-430f-a653-62e77feadb97" />

<p>•	The report identifies Australia, Brazil, and Canada as important markets for EV adoption based on their excellent infrastructure and favourable economic conditions.</p>

<img alt="image" src="https://github.com/user-attachments/assets/88ff3340-9690-4deb-910d-6bde6a5e5028" />

<img alt="image" src="https://github.com/user-attachments/assets/5b6fe5c0-f4f0-4a8b-9b4d-626893e2ec56" />

<img alt="image" src="https://github.com/user-attachments/assets/31df9dfa-d84d-45bf-8d16-71ac6af588df" />

<p>•	The charts known as "GDP by Country" and "Minimum Wage and Gasoline Price" indicate the affordability as well as economic stability of important markets such as the USA, China, Japan and Germany which can have an impact on the adoption of electric vehicles and consumer spending power.</p>

<img alt="image" src="https://github.com/user-attachments/assets/ecfeff53-13e6-4b59-9dbc-71cc88982ed9" />

<p>•	These geographical areas are attractive to future expansion of the market and EV adoption strategies since the data analysis results are indicating high labour force participation and low unemployment rates in markets such as Qatar, revealing economic optimism and strong buying potential.</p>

<img alt="image" src="https://github.com/user-attachments/assets/e7e8b132-3584-4be6-9af1-15005f800e94" />














