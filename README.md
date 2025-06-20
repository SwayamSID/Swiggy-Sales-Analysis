![MasterHead](https://exotel.com/uae/wp-content/uploads/sites/4/2023/04/swiggy-1-scaled.jpg)

# Swiggy-Sales-Analysis
This project narrates about the Sales Analysis done regarding the company Swiggy, which is a very big name in the quick commerce industry famous for food deliveries.

---

## 👨‍🏫 Aim of the Project 
By using data analytic tools on Swiggy's vast dataset, this project seeks to help budding food sector entrepreneurs. The project aims to offer insightful analysis and practical suggestions for anyone wishing to launch their own restaurant business by examining Swiggy's data. The goal of this project is to democratize knowledge so that business owners may make well-informed choices, maximize their tactics, and raise their chances of success in the cutthroat food industry.

---

## 📝 Project Description:
With Swiggy, one of the top platforms in the sector, we explore the world of food delivery in this project. Our solution uses a multifaceted strategy that utilizes the capabilities of Excel, capabilities Query, and Python modules to extract significant insights from Swiggy's massive dataset.

Phases of the project:

- Data Extraction with Python tools: Raw data was extracted from Swiggy's servers using Python tools like Pandas and Requests.
- In order to provide a complete dataset for analysis, online scraping techniques were used to gather real-time data on menu items, customer ratings, and restaurant listings.
- Data Transformation and Cleaning using Power Query:
  - The extracted data was imported into Excel, and the dataset was cleaned, transformed, and organized using Power Query.
  - To guarantee data correctness and consistency, missing values were filled in, formats were standardized, and duplicates were eliminated.
  - Utilized the user-friendly interface of Power Query to expedite the cleaning procedure and get the data ready for in-depth examination.
- Excel data analytics:
  - Used statistical analysis techniques and sophisticated Excel functions to extract valuable insights from the cleaned dataset.
  - Descriptive analytics were used to determine regional patterns, popular cuisines, client preferences, and peak ordering hours.
  - To help identify important industry trends and possibilities, data patterns were visualized using pivot tables and charts.


---

# _Steps involved in process:_

## 1. 🔎 Web Scrapping:
Swiggy's content is dynamic, thus a traditional iteration across pages was not feasible.  Rather, the website was continuously scrolled through by automation, which retrieved data as it loaded dynamically. The         automation script was created to simulate user activity by using webdriver and Selenium. It scrolled along the Swiggy website to record the dynamically loaded content.  This method made it possible to retrieve more    data than what was initially displayed on the screen.  The script successfully retrieved the data as it scrolled down, guaranteeing a complete dataset for additional analysis.  The code for website automation is as   follows:
![image](https://github.com/user-attachments/assets/33acecd1-fb14-4e2f-8888-872fe8b11830)

## 2. 🧼 Data Cleaning:
The extracted dataset from Swiggy was refined using Power Query throughout the data cleaning process to guarantee its accuracy and consistency for additional analysis.  A number of important cleaning procedures were used:

i. Removing Duplicate Data:
  - Using Power Query, duplicate records in the dataset were found and removed.  Eliminating duplicates made guaranteed that every entry was distinct and avoided any analysis distortions brought on by redundant data.
    
ii. Spelling Check of the Locations:
  - Power Query modifications were used to fix location data that was inconsistent or misspelled.  In addition to improving the dataset's usability, standardizing the location names allowed for precise insights into       regional trends through accurate geographical analysis.
    
iii. Removing Null Values:
  - To improve the dataset's completeness, null or missing values were found and eliminated.  Power Query made it simple to find and remove these null values, guaranteeing that the dataset was complete and trustworthy     for further examination.

---

## 3. 📊 Insights Generated:
i. A thorough analysis of the distribution of restaurants in various regions was carried out.  The survey revealed important details about the local restaurant scene by concentrating on well-known neighborhoods           including BTM Layout, Indiranagar, and Koramangala.

<img width="870" alt="image" src="https://github.com/user-attachments/assets/f90643a6-f752-44b8-8291-7983309f9f39" />

ii. The most expensive dishes were offered in Indiranagar and BTM Layout, according to the Swiggy data analysis, but the base price was the same in all other areas.

<img width="793" alt="image" src="https://github.com/user-attachments/assets/6bc03366-fea5-4d6f-ac89-2a313415631c" />
<img width="1100" alt="image" src="https://github.com/user-attachments/assets/befbe387-27e1-4150-aa75-df64695ea5ff" />

iii. Based on the quantity of restaurant ratings, an emphasis was made on assessing the popularity of various locations. In particular, eateries with over 1000 ratings were seen as important popularity indicators.          The most well-liked locations for dining experiences were identified by this investigation in a number of areas.

<img width="744" alt="image" src="https://github.com/user-attachments/assets/fd47aec6-a1ac-4149-879d-f3909c913756" />

iv. To investigate the connection between delivery timings and restaurant ratings, a correlation analysis was carried out. Unexpectedly, the results showed that these two factors had a negative connection. This            indicates that, in contrast to popular belief, restaurant evaluations tended to decline as delivery delays rose.

<img width="797" alt="image" src="https://github.com/user-attachments/assets/47b5bfb9-6c9f-47aa-86c9-9fc8f35b29db" />

v. With ratings below 3.5 regarded as a sign of low customer satisfaction, particular attention was paid to locating regions with the greatest concentration of low-rated eateries. This criterion made it possible to       thoroughly analyze the locations where patrons may have unsatisfactory dining experiences.

<img width="796" alt="image" src="https://github.com/user-attachments/assets/99410668-ce87-4bbc-a55f-372502ff15a9" />

vi. To comprehend the gastronomic landscape in various regions, a thorough analysis was carried out.  Finding the most popular cuisines and how they are distributed throughout different locations was the main goal.  Curiously, the study found that a small number of cuisines controlled the industry, with the top 5–6 cuisines accounting for almost half of the market share overall.

<img width="679" alt="image" src="https://github.com/user-attachments/assets/622f8c08-c7f3-4615-89ea-bf3a10757e20" />

vii. The Swiggy dashboard has an easy-to-use layout that delivers insights, highlights regions with low-rated eateries, and provides comprehensive pricing information for various cuisines.  By adding the area-wise slicer, user interaction is improved and an entity can make a customized, data-driven choice.

<img width="1320" alt="image" src="https://github.com/user-attachments/assets/586deae2-30ed-4f73-8e05-676f0be3f167" />

---

## ✍️ Important Insights:
The analysis of low-rated restaurants in specific areas on Swiggy's platform has revealed a compelling investment insight: targeting areas with a high concentration of low-rated cuisines presents a unique business opportunity.  There is a noticeable need for fast delivery services and high-quality cuisine in these areas.  By strategically concentrating on these areas, investors looking to enter the food industry could take advantage of the disparity in customer satisfaction.  There is a great chance to acquire market share and win over customers by starting a restaurant or food delivery business that places a high value on delicious meals and prompt deliveries.  The current discontent among patrons in these regions represents an unexplored market ready for better eating experiences.

<img width="770" alt="image" src="https://github.com/user-attachments/assets/7c648c55-0063-451c-bf4d-bb3fb48ce647" />

---

## 🎖 Conclusion:
In conclusion, the Swiggy project emerges as a pivotal tool for prospective entrepreneurs venturing into the hotel business. By harnessing the power of analytics and insights, it provides invaluable data-driven guidance essential for making informed decisions. Through detailed analysis, it not only offers a profound understanding of market trends but also aids in identifying relevant locations for establishing new businesses. Armed with comprehensive information, entrepreneurs can strategically position their ventures, ensuring they thrive in the competitive landscape. Swiggy's innovative approach not only simplifies the complexities of the business world but also paves the way for sustainable growth and success in the ever-evolving hospitality industry.

---

## 👨‍💻 Key Learnings:
The Swiggy initiative provides a number of important lessons that business owners and entrepreneurs can use to their advantage:
- Data-Driven Decision Making: Swiggy's successful application of data analytics is a key factor in its success.  Entrepreneurs can understand how crucial it is to gather, examine, and use data in order to make wise judgments.  Businesses can make strategic decisions by using data-driven insights to comprehend market trends, customer preferences, and operational efficiencies.
- Client-Centric Approach: Swiggy has raised the bar in the food delivery sector by emphasizing convenience and client pleasure.  Entrepreneurs can learn the value of putting the requirements of their customers first, making sure user experiences are flawless, and cultivating a devoted following.  Long-term success depends on getting input from customers and meeting their needs.
- Adoption of novel technology: Swiggy has embraced real-time tracking systems, smartphone apps, and novel technology.  In order to improve productivity, client interaction, and overall operations, entrepreneurs can understand how important it is to keep up with technology developments and incorporate them into their business plans.
- Successful Collaborations: Swiggy's expansion has been largely attributed to its collaborations with delivery drivers, cloud kitchens, and eateries.  Within the industry, entrepreneurs can master the skill of establishing strategic partnerships and collaborations.  These collaborations can give a competitive edge, increase market reach, and generate synergies.

---

## 📌 Future Scope:
Swiggy's study has a wide and bright future for businesspeople starting in the hotel industry.  Swiggy's data analytics can be used for strategic decision-making in the following important areas:
- Market Demand Analysis: Patterns of market demand can be examined using Swiggy's vast data set.  Entrepreneurs are able to determine which foods, meals, and cuisines are popular in a given area.  Planning a menu and comprehending regional tastes and preferences require knowledge of this information.
- Location Intelligence: Swiggy's information can reveal the best places to set up a restaurant or hotel.  Entrepreneurs may maximize visibility and profitability by making data-driven decisions regarding the best location for their business by examining delivery trends, foot traffic, and client demographics.
- Dynamic price Strategies: Using Swiggy's price data, dynamic pricing strategies can be applied in response to local events, seasonal variations, and variations in demand.  Entrepreneurs can maximize profits and maintain market competitiveness by making real-time price adjustments.
- Supply Chain Optimization: By forecasting demand for different ingredients and suppliers, Swiggy's data analytics can assist in supply chain optimization.  This keeps operations cost-effective, minimizes waste, and guarantees good inventory management.
- Consumer Behavior Analysis: Swiggy's data on consumer behavior offers important insights into popular add-ons, ordering patterns, peak ordering periods, and user reviews.  Entrepreneurs may improve customer happiness and loyalty by customizing their services, menus, and marketing initiatives based on an understanding of client preferences.
- Operational Efficiency: Internal procedures like delivery logistics and kitchen operations can be streamlined with the help of Swiggy's analytics.  By optimizing workforce levels, delivery routes, and order processing times, entrepreneurs can save operating costs and increase efficiency.
- Quality Control and Analysis of Feedback: Swiggy's rating and feedback information provides insight into the degree of client satisfaction.  In order to uphold high standards of quality, respond to client issues, and consistently improve the overall eating experience, entrepreneurs can examine this data.
- Expansion Strategies: Swiggy's data can help business owners find possible locations to grow their company.  Entrepreneurs can decide whether to open new locations or vary their product offerings to cater to particular market demands by researching demand patterns in various geographic areas.
- Prospects for Collaboration and Partnership: Swiggy's network of eateries, cloud kitchens, and suppliers can provide business owners beneficial collaboration and partnership prospects.  Entrepreneurs can find possible partners for sourcing ingredients, investigating co-branding options, or growing their menu offerings by examining successful partnerships inside the Swiggy ecosystem.

---

## Summary:
In conclusion, entrepreneurs venturing into the hotel industry can benefit from actionable information by utilizing Swiggy's strong data analytics skills.  Entrepreneurs may improve customer experiences, streamline operations, make well-informed decisions, and maintain an advantage in the cutthroat hospitality sector by utilizing this data.
