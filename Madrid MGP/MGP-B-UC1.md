---
layout: default
title: MGP-B-UC1
parent: Madrid MGP
nav_order: 2
---



### users

Possible users/purchasers of this tool:

1. Facilities managers: These are individuals responsible for the operation and maintenance of the DHCN (District Heating and Cooling Network). They would benefit from using this tool to calculate the various KPIs needed to guide their decision-making process.

2. Energy analysts: These are professionals who analyze energy consumption and performance to identify opportunities for improvement. They could use this tool to calculate the KPIs related to energy generation and efficiency in the DHCN.

3. Energy consultants: These are experts who provide advice and recommendations on energy-related projects. They could use this tool to assess the performance of the DHCN and make proposals for optimization.

4. Building owners: Owners of buildings connected to the DHCN may have an interest in monitoring the performance of the system. They could use this tool to track the KPIs relevant to their specific building and assess the efficiency of the DHCN in meeting their heating and cooling needs.

5. Energy regulators: Regulatory bodies responsible for monitoring and controlling energy systems may need to assess the performance of the DHCN. This tool could assist them in evaluating compliance with energy efficiency standards and identifying areas for improvement.

6. Energy system developers: Companies or organizations involved in the development of DHCN systems may find this tool useful for testing and optimizing the performance of their designs.

7. Energy researchers: Researchers in the field of energy systems and sustainability could utilize this tool to analyze the performance of the DHCN and contribute to the advancement of knowledge in this area.

8. Energy auditors: Professionals performing energy audits for buildings connected to the DHCN could use this tool to collect data and calculate relevant KPIs for their assessments.

9. Energy service companies (ESCOs): ESCOs offering energy management and efficiency services could incorporate this tool into their portfolio to enhance their capabilities in assessing and optimizing DHCN performance.

10. Sustainable energy advocates: Individuals or organizations advocating for sustainable energy solutions may have an interest in monitoring the performance of the DHCN in terms of renewable energy generation and carbon emissions reduction. They could use this tool to track the relevant KPIs and support their advocacy efforts.

['Facilities managers', 'Energy analysts', 'Energy consultants', 'Building owners', 'Energy regulators', 'Energy system developers', 'Energy researchers', 'Energy auditors', 'Energy service companies', 'Sustainable energy advocates']



### Pain

The pain(s) that this use case solves for the tool user include:

1. Manual calculation: Prior to the development of this tool, users would have to manually calculate each KPI value based on the formula and measurements associated with it. This could be a time-consuming and error-prone process. The tool automates this calculation, saving time and reducing the risk of errors.

2. Complex calculations: The calculation of some KPIs, such as seasonal thermal balance or geothermal power for each borehole, may involve multiple variables and complex formulas. The tool simplifies these calculations by taking the formula and relevant measurements as inputs and producing the KPI value as an output.

3. Data storage and accessibility: The values of the calculated KPIs need to be stored and made available for other use cases. Prior to the tool, users would have to manually record and organize these values, which could be a cumbersome task. The tool automates the storage of KPI values, ensuring they are readily accessible for other analyses or decision-making processes.

4. Decision-making support: The KPI values calculated by the tool provide essential information for decision-making concerning the operation and maintenance of the DHCN. Without the tool, users would have to rely on estimations or less accurate methods to guide their decisions, potentially leading to suboptimal outcomes.

Overall, the tool addresses the pain points of manual calculations, complex calculations, data storage, and decision-making support, making the process more efficient, accurate, and user-friendly.



### Gain

The gain(s) created for the tool user by this use case are as follows:

1. Improved decision-making: By providing the needed Key Performance Indicators (KPIs), the decision support system enables the user to make informed decisions regarding the operation and maintenance of the District Heating and Cooling Network (DHCN). The calculated KPI values serve as indicators of the network's performance and efficiency, allowing the user to identify areas for improvement and optimization.

2. Efficient monitoring: The use case is triggered periodically by the actor "Time", ensuring regular monitoring of the KPIs. This enables the user to have a real-time view of the network's performance without the need for manual data collection and calculations. The automated calculation of KPI values saves time and effort for the user, allowing them to focus on analyzing the results and taking appropriate actions.

3. Comprehensive insights: The calculation of various KPIs, such as ground temperature profile, seasonal thermal balance, geothermal power, energy generation percentages, coefficient of performance, and energy efficiency ratio, provides the user with a comprehensive understanding of the DHCN's performance. These insights enable the user to identify patterns, trends, and potential issues in the network's operation and make data-driven decisions to optimize its efficiency.

4. Long-term planning: By storing the calculated KPI values, the tool allows the user to track changes in the network's performance over time. This historical data helps in identifying long-term trends and patterns, facilitating strategic planning for the future of the DHCN. The user can assess the impact of various operational and maintenance decisions on the network's performance and make informed choices for its sustainable development.

5. Energy optimization: The average temperature of exchanges with the ground, average usage temperature, and PV consumption of Heat Pumps KPIs provide insights into the energy usage and efficiency of the DHCN. By analyzing these KPIs, the user can identify opportunities for energy optimization, such as adjusting temperature setpoints or increasing the use of renewable energy sources like PV. This leads to cost savings, reduced environmental impact, and improved overall system performance.

In summary, the use case of calculating the KPI values for the DHCN decision support system creates gains for the tool user in terms of improved decision-making, efficient monitoring, comprehensive insights, long-term planning, and energy optimization.



### Output

The outputs of this tool are the calculated values for the following Key Performance Indicators (KPIs):

1. Ground temperature profile [ºC] (for 1-2 boreholes): The tool will calculate the profile of ground temperature for each borehole, providing temperature values in degrees Celsius.

2. Seasonal thermal balance in the ground: The tool will calculate the seasonal thermal balance in the ground, indicating the energy exchange between the ground and the system over a specific time period.

3. Geothermal power for each borehole: The tool will calculate the geothermal power (heat) generated by each borehole, indicating the amount of heat energy produced.

4. % of energy generated by the ground for each energy thermal unit (heat) produced: The tool will calculate the percentage of heat energy generated by the ground in relation to the total heat energy produced by the system, indicating the contribution of the ground as a heat source.

5. % of energy generated by the ground for each energy thermal unit (cold) produced: The tool will calculate the percentage of cool energy generated by the ground in relation to the total cool energy produced by the system, indicating the contribution of the ground as a cool source.

6. Seasonal coefficient of performance (SCOP) (coefficient of performance averaged over the length of the heating season): The tool will calculate the SCOP, which represents the average efficiency of the system in converting input energy into heat energy over the heating season.

7. Seasonal energy efficiency ratio (SEER) (concerning cooling): The tool will calculate the SEER, which represents the efficiency of the system in providing cooling over a specific time period.

8. Average temperature of the exchanges with the ground (average among outputs and inputs) (ground source exchange average): The tool will calculate the average temperature of the exchanges between the system and the ground, providing a consolidated value for the ground source exchange temperature.

9. Average usage temperature (both for heating and cooling): The tool will calculate the average usage temperature for heating and cooling, indicating the average temperature at which the system operates.

10. Average of PV consumed by each Heat Pump (and % of the whole electricity consumed that comes from PV): The tool will calculate the average amount of electricity consumed by each Heat Pump and the percentage of electricity consumed that is generated by photovoltaic (PV) systems.

These calculated values will be stored and made available for other use cases within the decision support system for the operation and maintenance of the DHCN.



### Outcome

The outcomes of this tool are as follows:

1. Ground temperature profile [ºC]: The tool will calculate the profile of ground temperature for each borehole, providing temperature values in degrees Celsius. This information is crucial for understanding the thermal behavior of the ground and optimizing the performance of the system.

2. Seasonal thermal balance in the ground: The tool will calculate the seasonal thermal balance in the ground, indicating the energy exchange between the ground and the system over a specific time period. This helps assess the overall efficiency of the system and ensures that the energy exchange is balanced and sustainable.

3. Geothermal power for each borehole: The tool will calculate the geothermal power (heat) generated by each borehole, indicating the amount of heat energy produced. This information helps in understanding the heat production capacity of each borehole and optimizing the distribution of heat energy.

4. % of energy generated by the ground for each energy thermal unit (heat) produced: The tool will calculate the percentage of heat energy generated by the ground in relation to the total heat energy produced by the system, indicating the contribution of the ground as a heat source. This helps in evaluating the reliance on the ground as a heat source and determining the overall sustainability of the system.

5. % of energy generated by the ground for each energy thermal unit (cold) produced: The tool will calculate the percentage of cool energy generated by the ground in relation to the total cool energy produced by the system, indicating the contribution of the ground as a cool source. This helps in evaluating the reliance on the ground as a cooling source and determining the overall sustainability of the system.

6. Seasonal coefficient of performance (SCOP): The tool will calculate the SCOP, which represents the average efficiency of the system in converting input energy into heat energy over the heating season. This helps in assessing the overall efficiency of the system in providing heat.

7. Seasonal energy efficiency ratio (SEER): The tool will calculate the SEER, which represents the efficiency of the system in providing cooling over a specific time period. This helps in assessing the overall efficiency of the system in providing cooling.

8. Average temperature of the exchanges with the ground (ground source exchange average): The tool will calculate the average temperature of the exchanges between the system and the ground, providing a consolidated value for the ground source exchange temperature. This information helps in understanding the performance of the system and optimizing the energy exchange between the system and the ground.

9. Average usage temperature: The tool will calculate the average usage temperature for heating and cooling, indicating the average temperature at which the system operates. This helps in assessing the comfort level provided by the system and optimizing the temperature settings.

10. Average of PV consumed by each Heat Pump (and % of the whole electricity consumed that comes from PV): The tool will calculate the average amount of electricity consumed by each Heat Pump and the percentage of electricity consumed that is generated by photovoltaic (PV) systems. This helps in evaluating the energy efficiency of the system and the contribution of renewable energy sources.



### Social benefits

The social benefits/outcomes of this tool are as follows:

1. Improved energy efficiency: By calculating the ground temperature profile and seasonal thermal balance, the tool helps optimize the performance of the system, leading to better energy efficiency. This results in reduced energy consumption, lower greenhouse gas emissions, and a more sustainable energy usage.

2. Increased use of renewable energy sources: The tool calculates the percentage of energy generated by the ground for each energy thermal unit produced. By evaluating the reliance on the ground as a heat and cooling source, the tool helps in determining the overall sustainability of the system and encourages the use of renewable energy sources, such as geothermal power. This contributes to a more environmentally friendly energy mix.

3. Enhanced system performance and comfort: The tool calculates the average temperature of the exchanges with the ground and the average usage temperature for heating and cooling. By optimizing the energy exchange and temperature settings, the tool ensures a higher level of comfort provided by the system. This leads to improved user satisfaction and well-being.

4. Informed decision-making: The tool provides various KPIs, including geothermal power, SCOP, SEER, and average of PV consumed by each Heat Pump. These KPIs offer valuable insights into the performance and efficiency of the system. By having access to accurate and up-to-date information, facilities managers and decision-makers can make informed decisions regarding the operation and maintenance of the DHCN. This can result in cost savings, improved system reliability, and better resource allocation.

5. Contribution to sustainable development: The overall social benefit of this tool is its contribution to sustainable development. By optimizing energy usage, increasing the use of renewable energy sources, improving system performance and comfort, and enabling informed decision-making, the tool supports the transition towards a more sustainable and environmentally friendly energy system. This aligns with global efforts to mitigate climate change, reduce reliance on fossil fuels, and promote sustainable development goals.



### Environmental benefits

The environmental benefits/outcomes of this tool are as follows:

1. Ground temperature profile [ºC]: By calculating the ground temperature profile for each borehole, the tool helps optimize the performance of the system. This optimization leads to energy savings and reduces the overall environmental impact of the system.

2. Seasonal thermal balance in the ground: The tool calculates the energy exchange between the ground and the system over a specific time period. This information helps assess the overall efficiency of the system and ensures that the energy exchange is balanced and sustainable. By maintaining a balanced thermal balance in the ground, the system operates more efficiently and reduces energy waste.

3. Geothermal power for each borehole: The tool calculates the amount of heat energy generated by each borehole. This information helps in understanding the heat production capacity of each borehole and optimizing the distribution of heat energy. By optimizing the heat distribution, the system can minimize energy losses and reduce its environmental footprint.

4. % of energy generated by the ground for each energy thermal unit (heat) produced: The tool calculates the percentage of heat energy generated by the ground in relation to the total heat energy produced by the system. This information helps in evaluating the reliance on the ground as a heat source. By relying more on the ground as a heat source, the system reduces its dependence on fossil fuels and lowers greenhouse gas emissions.

5. % of energy generated by the ground for each energy thermal unit (cold) produced: Similar to heat energy, the tool calculates the percentage of cool energy generated by the ground in relation to the total cool energy produced by the system. By relying more on the ground as a cooling source, the system reduces its energy consumption from traditional cooling methods such as air conditioning, resulting in lower energy consumption and environmental impact.

6. Seasonal coefficient of performance (SCOP): The tool calculates the average efficiency of the system in converting input energy into heat energy over the heating season. This helps in assessing the overall efficiency of the system in providing heat. A higher SCOP indicates a more efficient system, resulting in lower energy consumption and reduced environmental impact.

7. Seasonal energy efficiency ratio (SEER): The tool calculates the efficiency of the system in providing cooling over a specific time period. This helps in assessing the overall efficiency of the system in providing cooling. A higher SEER indicates a more efficient system, resulting in lower energy consumption and reduced environmental impact.

8. Average temperature of the exchanges with the ground (ground source exchange average): The tool calculates the average temperature of the exchanges between the system and the ground. By optimizing the energy exchange between the system and the ground, the tool helps improve the overall performance and efficiency of the system, reducing energy waste and minimizing environmental impact.

9. Average usage temperature: The tool calculates the average temperature at which the system operates for heating and cooling purposes. By optimizing the temperature settings, the tool helps ensure that the system operates at the most energy-efficient levels, reducing energy consumption and environmental impact.

10. Average of PV consumed by each Heat Pump (and % of the whole electricity consumed that comes from PV): The tool calculates the average amount of electricity consumed by each Heat Pump and the percentage of electricity consumed that is generated by photovoltaic (PV) systems. By incorporating renewable energy sources such as PV systems, the tool helps reduce reliance on non-renewable energy sources and decrease greenhouse gas emissions.



### Economic benefits

The economic benefits/outcomes of this tool are as follows:

1. Ground temperature profile [ºC]: This information is crucial for understanding the thermal behavior of the ground and optimizing the performance of the system. By having accurate temperature profiles for each borehole, system operators can make informed decisions about heat distribution and ensure the system operates at peak efficiency. This can lead to cost savings and energy conservation by avoiding unnecessary energy consumption.

2. Seasonal thermal balance in the ground: Calculating the seasonal thermal balance helps assess the overall efficiency of the system and ensures that the energy exchange between the ground and the system is balanced and sustainable. This information allows system operators to identify any energy imbalances and make necessary adjustments for optimal performance. By optimizing the thermal balance, the system can operate with maximum efficiency, reducing energy waste and associated costs.

3. Geothermal power for each borehole: By calculating the geothermal power generated by each borehole, system operators can determine the heat production capacity of each borehole. This information is valuable for optimizing the distribution of heat energy and ensuring each borehole is utilized effectively. By maximizing heat production, the system can provide sufficient heating capacity while minimizing energy consumption, resulting in cost savings.

4. % of energy generated by the ground for each energy thermal unit (heat) produced: Calculating the percentage of heat energy generated by the ground in relation to the total heat energy produced by the system provides insights into the reliance on the ground as a heat source. This information helps evaluate the system's sustainability and energy efficiency. By increasing the percentage of heat energy generated by the ground, the system can reduce its reliance on external energy sources, leading to cost savings and environmental benefits.

5. % of energy generated by the ground for each energy thermal unit (cold) produced: Similar to the previous point, calculating the percentage of cool energy generated by the ground in relation to the total cool energy produced by the system helps evaluate the system's sustainability and energy efficiency in cooling. By increasing the percentage of cool energy generated by the ground, the system can reduce its reliance on external cooling sources, leading to cost savings and environmental benefits.

6. Seasonal coefficient of performance (SCOP): The SCOP represents the average efficiency of the system in converting input energy into heat energy over the heating season. By calculating the SCOP, system operators can assess the overall efficiency of the system in providing heat. A higher SCOP indicates better energy utilization and can result in cost savings by reducing energy consumption for heating.

7. Seasonal energy efficiency ratio (SEER): The SEER represents the efficiency of the system in providing cooling over a specific time period. By calculating the SEER, system operators can assess the overall efficiency of the system in providing cooling. A higher SEER indicates better energy utilization and can result in cost savings by reducing energy consumption for cooling.

8. Average temperature of the exchanges with the ground (ground source exchange average): Calculating the average temperature of the exchanges between the system and the ground provides a consolidated value for the ground source exchange temperature. This information helps in understanding the performance of the system and optimizing the energy exchange between the system and the ground. By optimizing the temperature exchanges, the system can operate at maximum efficiency, reducing energy waste and associated costs.

9. Average usage temperature: Calculating the average usage temperature for heating and cooling helps assess the comfort level provided by the system. By optimizing the temperature settings, the system can ensure optimal comfort for occupants while minimizing energy consumption and associated costs.

10. Average of PV consumed by each Heat Pump (and % of the whole electricity consumed that comes from PV): By calculating the average amount of electricity consumed by each Heat Pump and the percentage of electricity consumed that is generated by photovoltaic (PV) systems, system operators can evaluate the energy efficiency of the system and the contribution of renewable energy sources. This information helps assess the environmental sustainability of the system and can lead to cost savings by reducing reliance on non-renewable energy sources.



### ValueProp

The different value propositions for this tool could include:

1. Decision support: The tool provides calculated KPI values that are crucial for guiding the decision-making process regarding the operation and maintenance of the DHCN. It gives insights and information that can help optimize the performance and efficiency of the system.

2. Operational efficiency: By automatically calculating KPI values based on the measurements and formulas, the tool eliminates the need for manual calculations, saving time and effort for the facilities manager or any other personnel involved in the process. It streamlines the data analysis process and provides accurate and reliable results.

3. Monitoring and tracking: The tool stores the calculated KPI values, making them available for other use cases. This allows for continuous monitoring and tracking of the performance of the DHCN over time. It helps in identifying trends, patterns, and potential areas for improvement.

4. Performance optimization: By providing KPI values related to ground temperature profile, thermal balance, geothermal power, energy generation from the ground, coefficient of performance, energy efficiency ratio, temperature exchanges with the ground, and average usage temperature, the tool enables users to assess and optimize the system's performance. It helps in identifying areas where energy can be saved, efficiencies can be improved, and costs can be reduced.

5. Renewable energy utilization: The tool calculates the average PV consumed by each Heat Pump and the percentage of electricity consumed that comes from PV. This information helps in monitoring the utilization of renewable energy sources and highlights the contribution of renewable energy to the overall energy consumption of the system. It supports sustainability goals and provides insights into the environmental impact of the DHCN.

6. Cost optimization: By analyzing KPI values such as energy generation, usage, and efficiency, the tool helps in optimizing energy consumption and reducing operational costs. It enables users to identify energy wastages, inefficient practices, and areas where energy-saving measures can be implemented. This can lead to cost savings and increased cost-effectiveness of the DHCN system.

7. Proactive maintenance: By continuously monitoring and tracking the performance of the DHCN through calculated KPI values, the tool can detect any deviations or anomalies that may indicate potential issues or maintenance needs. It enables proactive maintenance practices, preventing costly breakdowns and ensuring the smooth operation of the system.

Overall, the tool's value propositions include decision support, operational efficiency, monitoring and tracking, performance optimization, renewable energy utilization, cost optimization, and proactive maintenance.



### GBNs

The tool being described in this use case, the DHCN decision support system, has the potential to have several positive impacts on GBNs (green building neighbourhoods) or smart and sustainable neighbourhoods. These impacts include:

1. Energy Efficiency: By providing KPIs related to the operation and maintenance of the DHCN (District Heating and Cooling Network), the tool can help optimize energy consumption and improve energy efficiency in the neighbourhood. KPIs such as the seasonal thermal balance, geothermal power, and energy generated by the ground can provide insights into the performance of the system and identify areas for improvement.

2. Cost Savings: With access to accurate KPIs, the facilities manager can identify inefficiencies in the system and take necessary actions to optimize energy usage. This can result in cost savings for both the residents and the neighbourhood as a whole. For example, by monitoring the SCOP and SEER values, the system can identify opportunities to reduce energy wastage and decrease operational costs.

3. Environmental Sustainability: The tool's ability to calculate KPIs related to the usage of renewable energy sources, such as ground heat and PV consumption, can contribute to the environmental sustainability goals of GBNs. By monitoring and optimizing these values, the neighbourhood can reduce its reliance on non-renewable energy sources and decrease its carbon footprint.

4. Improved Comfort and Well-being: The tool's KPIs related to temperature profiles, usage temperature, and ground source exchanges can be used to ensure optimal thermal comfort for the residents. By monitoring these values and taking necessary actions, such as adjusting the heating or cooling systems, the neighbourhood can provide a comfortable living environment for its residents, enhancing their well-being.

5. Data-Driven Decision Making: The availability of accurate and up-to-date KPIs in the decision support system can support data-driven decision making for the facilities manager and other stakeholders. This can help identify trends, patterns, and areas of improvement in the DHCN, leading to more informed and effective decision making.

Overall, the tool described in this use case has the potential to positively impact GBNs by improving energy efficiency, reducing costs, promoting environmental sustainability, enhancing resident comfort and well-being, and enabling data-driven decision making.



### Activities

The activities enabled by this tool include:

1. Gathering measurements: The tool collects the necessary data and measurements required to calculate the KPIs. This may include data on ground temperature, thermal balance, geothermal power, energy generation, coefficient of performance, energy efficiency ratio, temperature exchanges, and average usage.

2. Applying formulas: The tool applies predefined formulas to the gathered measurements in order to calculate the values for each KPI. These formulas may be based on industry standards and best practices.

3. Calculation of KPIs: The tool performs the calculations using the gathered measurements and applied formulas to determine the values for each KPI. This may involve complex calculations and mathematical operations.

4. Storage of KPI values: The tool stores the calculated KPI values for future reference and use in other use cases. This ensures that the values are readily available and can be accessed by other decision support systems or processes.

5. Automation of calculations: The tool automates the calculation process, allowing for periodic and consistent calculations to be performed without the need for manual intervention. This increases efficiency and reduces the likelihood of errors.

6. Integration with decision-making process: The calculated KPI values are used as inputs in the decision-making process related to the operation and maintenance of the DHCN. The tool ensures that accurate and up-to-date KPI values are available to guide decision-making.

Overall, this tool enables the efficient and consistent calculation of various KPIs related to the DHCN. It automates the calculation process and ensures that the values are readily available for decision-making purposes.



### RevenuesUser

The revenues streams enabled by this tool for the tool user can be derived from the value that it provides in guiding the decision-making process concerning the operation and maintenance of the DHCN (District Heating and Cooling Network). By calculating and providing the KPIs, the tool helps the user optimize the performance and efficiency of the DHCN system, leading to potential cost savings and increased operational effectiveness.

1. Cost optimization: The tool calculates the ground temperature profile, geothermal power, and seasonal thermal balance in the ground. By analyzing these KPIs, the user can identify the most efficient use of energy resources and make informed decisions on how to optimize the system's performance. This can result in cost savings by minimizing energy waste and reducing reliance on external energy sources.

2. Energy generation analysis: The tool calculates the percentage of energy generated by the ground for each thermal unit produced (heat and cool). By assessing these KPIs, the user can understand the system's energy generation capabilities and identify opportunities to maximize the utilization of geothermal power. This can lead to reduced energy costs and a more sustainable energy mix for the DHCN.

3. Performance evaluation: The tool calculates the seasonal coefficient of performance (SCOP) and seasonal energy efficiency ratio (SEER). These KPIs provide insights into the system's overall performance in terms of heating and cooling efficiency. By monitoring and optimizing these performance metrics, the user can ensure that the DHCN operates at its highest efficiency, reducing operational costs and increasing customer satisfaction.

4. Renewable energy integration: The tool calculates the average PV consumption by each heat pump and the percentage of electricity consumed that comes from PV (photovoltaic). These KPIs enable the user to assess the integration of renewable energy sources into the DHCN system. By leveraging renewable energy, the user can reduce reliance on traditional energy sources, lower carbon emissions, and potentially benefit from incentives or subsidies for renewable energy usage.

Overall, the tool's revenue streams are derived from the cost optimization, energy generation analysis, performance evaluation, and renewable energy integration enabled by the provided KPI calculations. By utilizing these insights, the tool user can make data-driven decisions that improve the DHCN's efficiency, reduce costs, and enhance sustainability.



### RevenuesCreator

The revenue streams that this tool enables for the tool creator can be categorized as follows:

1. Software Licensing: The tool creator can generate revenue by licensing the decision support system to organizations or individuals who manage District Heating and Cooling Networks (DHCN). The tool can be sold as a one-time purchase or as a subscription-based model where users pay a recurring fee to access the software.

2. Maintenance and Support: The tool creator can provide ongoing maintenance and support services for the decision support system. This can include bug fixes, updates, and technical assistance to ensure the smooth functioning of the software. The tool creator can charge a fee for these services, either as part of the software licensing package or as a separate agreement.

3. Customization and Integration: Organizations using the decision support system may require customization or integration with other existing systems. The tool creator can offer customization services to tailor the software to the specific needs of the organization, as well as integration services to seamlessly integrate the tool with other software or hardware systems. These services can be offered at an additional cost.

4. Training and Consultancy: The tool creator can provide training programs to users of the decision support system, helping them understand how to effectively use the tool and interpret the KPIs generated. Additionally, the tool creator can offer consultancy services to assist organizations in leveraging the KPIs to make informed decisions regarding the operation and maintenance of DHCN. These training and consultancy services can be offered as on-site or online sessions, and the tool creator can charge a fee for these services.

It is important to note that the actual pricing and revenue generation strategies would depend on various factors such as market demand, competition, customer size, and geographic location. The tool creator can consider offering different pricing tiers based on the size of the organization or the level of features and support required. Additionally, the tool creator can explore partnerships with industry associations or energy efficiency initiatives to promote the use of the decision support system and potentially generate additional revenue through collaborations or sponsorships.

