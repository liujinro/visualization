# Data Visualization

## Assignment 4: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
## Visualization 1
    > What software did you use to create your data visualization?
    For Visualization 1, I used Python (Matplotlib) to perform the Visualization.

    > Who is your intended audience? 
    For Visualization 1, the intended audience is City planners, transportation analysis and who need to analysis the trend of transportation to make strategy or decision making.
    
    > What information or message are you trying to convey with your visualization?
    The bar chart depicts the number of trips per route, where each Route ID is plotted on the x-axis and the corresponding number of trips is plotted on the y-axis. The visualization likely aims to highlight the distribution and frequency of trips across different routes.
    - The chart provides a visual representation of how the trips are distributed across various routes. 
    - The routes with the highest number of trips can be easily identified, which could be useful for transportation planning, resource allocation, or further analysis.
    - The chart shows variability in the number of trips, indicating that some routes are much more popular than others.
    
    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
    - The bar chart is chosen to clearly show the differences in the number of trips across various routes, making it easy to identify routes with higher or lower usage.
    
    Perceptual Design Principles:
    - While the chart aims to be clear, the x-axis labels are currently overlapping and hard to read. This can be improved by rotating the labels or using a subset of route IDs.
    - The bars accurately represent the number of trips, providing a truthful depiction of the data without any misleading elements.
    
    Aesthetic Design Principles:
    - The chart is kept simple with a single color for the bars, avoiding unnecessary decorations that could distract from the data.
    - The chart maintains a balanced look, with the bars distributed evenly along the x-axis, and a clear title to provide context.
    - Consistent use of bar width and spacing ensures a uniform look, making it easier for viewers to interpret the data.

    Application of Principles to Plot Elements:
    - Selected for its ability to clearly display differences in the number of trips per route, facilitating easy comparison.
    - X-Axis: Displays the route IDs, though improvements in label readability are needed.
    - Y-Axis: Clearly shows the number of trips, with appropriate scaling to accommodate the data range.
    - Color: A single color is used for all bars to maintain simplicity and focus on the data.
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?
    - I documented each step of the visualization process, including data preprocessing, tool configuration, and visualization settings. This ensures that anyone following the same steps can reproduce the visualization.
    - I added some comments in the code to explain each part of the process, making it easier for others to understand and replicate the steps.
    - I used widely-accepted data visualization tools like Python's Matplotlib, which is known for the reliability and ease of sharing configurations.
    - I used Open data to ensur that the dataset used for visualization is accessible and provided along with the visualization. If the data is confidential, provided a sample dataset with similar structure for demonstration purposes.
    - I provided scripts (e.g., Python scripts) used for data manipulation and visualization, allowing others to run the same code with the provided data.
    - I attached the dataset with a link to access it.
 
    > How did you ensure that your data visualization is accessible?  
    - Designed the visualization with a straightforward layout, avoiding clutter and unnecessary elements that can overwhelm users.
    - Used large, clear fonts for all text elements, including titles, axis labels, and data labels, ensuring they are legible.
   

    > Who are the individuals and communities who might be impacted by your visualization?  
    - Transportation planners and city authorities can use the data to allocate resources effectively, ensuring that high-demand routes are well-serviced.
    - Helps in making informed decisions regarding public transportation policies, route adjustments, and service frequency.
   
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    - The main objective was to display the number of trips per route. Hence, the features included were Route ID and Number of Trips as they directly relate to the visualization's goal.
    - Selected features that were consistently recorded and formatted correctly throughout the dataset.

    > What ‘underwater labour’ contributed to your final data visualization product?
    - Ensured the accuracy and consistency of data by checking for errors, missing values, and duplicates.
    - Merged datasets on common keys to form a comprehensive dataset for analysis.
    - Ensured that the visualization was accessible to all potential users, including those with disabilities.
    - Provided clear instructions and necessary files to allow others to reproduce the visualization.

## Visualization 2:

 > What software did you use to create your data visualization?
 For Visualization 2, I used Excel (Pivot table) to represent the data visualization.
 
 > Who is your intended audience?
 - Business Analysts: To analyze the trends and identify which routes have the highest trip and route counts.
 - Operations Managers: To make data-driven decisions regarding route management and optimization
 - Financial Analysts: To assess the financial impact and efficiency of different routes.
 - Data Analysts: To further investigate and derive insights from the data presented.

 > What information or message are you trying to convey with your visualization?
 - The sum of trip_id values for each route, indicating how many trips have been recorded for each route.
 - Total Route Counts per Route: The sum of route_id values for each route, showing the number of distinct routes or segments within each route category.
 
 > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization?
 Substantive Design Principles:
 - Ensuring that the data is represented accurately without any distortion or misrepresentation of the values.
 Perceptual Design Principles:
 - Using clear and distinct labels for each route and the corresponding trip and route sums to avoid confusion.
 - Differentiating between the sums of trip_id and route_id using different colors in the bar chart, making it easy to compare the two metrics.
 Aesthetic Design Principles:
 - Keeping the visualization simple and free of unnecessary elements, allowing the viewer to focus on the data.
 - Using consistent colors and formatting throughout the chart to maintain a professional and coherent look.
 
 > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?
 - Create the visualization using widely available tools like Excel.
- Write down each step of your process, including how you processed the data and created the visualization.
- Provide the raw data and any transformations so others can start from the same point.

> How did you ensure that your data visualization is accessible?
- Using clear, large fonts for all text elements, including axis labels and titles, to make the information readable for people with visual impairments.
- Providing descriptive and clear labels for axes, bars, and titles to give context to the data being presented.
- Keeping the design simple and uncluttered to avoid overwhelming users and to make it easier for everyone to understand the data.

> Who are the individuals and communities who might be impacted by your visualization?
- Public Transit Authorities: They might use the data to enhance service planning, improve route coverage, and increase operational efficiency.
- Policy Makers: They could leverage the data to make informed decisions regarding transportation policies and infrastructure investments.

> How did you choose which features of your chosen dataset to include or exclude from your visualization?
-Including too many features can clutter the visualization and make it hard to interpret. By focusing on the sums of trip_id and route_id, the visualization remains clear and easy to understand.

> What ‘underwater labour’ contributed to your final data visualization product?
Data Collection:
- Finding and gathering the relevant data needed for the analysis.
- Importing the data into Excel or another tool for further processing.
- Identifying and addressing any missing or incomplete data points.



- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-4`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_4.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-4`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
