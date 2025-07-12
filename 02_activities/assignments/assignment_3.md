# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 

    > What software did you use to create your data visualization?
    I used Python, specifically the Pandas library for data processing and Seaborn/ Matplotlib for creating the bar chart visualization.

    > Who is your intended audience? 
    The intended audience includes city planners, local community organizations, and residents of Toronto interested in understanding where new park projects are concentrated. It can also be useful for journalists or policymakers tracking urban development and green space investment.
    
    > What information or message are you trying to convey with your visualization? 
    The visualization conveys which areas in Toronto have the highest number of new park development projects. It highlights geographic trends and helps identify neighborhoods with growing recreational infrastructure investment.
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    Simplicity: The bar chart was chosen for easy interpretation of comparative counts.
    Color choice: I used a green palette (palette='summer') to symbolically associate the color with parks and nature.
    Orientation: A horizontal bar chart improves readability of area names on the y-axis.
    Title and labels: Clear, descriptive titles and axis labels guide the viewer to understand what the chart represents without additional explanation.
     Top 10 filter: To avoid clutter, only the top 10 areas are shown, focusing attention on the most significant locations.


    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
     The entire process is scripted in Python, which means the visualization can be recreated exactly by running the same code with the dataset. Using open-source libraries like Pandas and Seaborn ensures anyone with access to the code and data can reproduce the analysis.
     The reproducibility would be impacted if the dataset changes or if the script depends on external files that are not shared. To mitigate this, I documented the dataset source and saved the cleaned data version.
    
    > How did you ensure that your data visualization is accessible?  

    Used clear, high-contrast colors to support viewers with color vision deficiencies.
    The font sizes for axis labels and titles were large enough for easy reading.
    The horizontal bar layout allows easy scanning for users with cognitive difficulties.
    The chart was saved as a high-resolution PNG to ensure clarity when shared digitally.
    
    > Who are the individuals and communities who might be impacted by your visualization?  

    Toronto residents can use this information to advocate for park access in underserved neighborhoods.
    City planners and policymakers might prioritize funding and resources to areas lacking park projects.
    Local community groups and activists may leverage this data for engagement or grant proposals.
    Researchers and journalists focused on urban development and public health.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
     Focused on the project_name, address, and description fields to identify new park projects and their locations.
     Excluded columns unrelated to geography or project type, such as IDs or detailed descriptions not useful for this aggregation.
    Simplified the address to an approximate area name to group projects by location.
     Filtered specifically for “new park” keywords to isolate relevant projects.

    
    > What ‘underwater labour’ contributed to your final data visualization product?

    Data cleaning: Handling missing or inconsistent address data and filtering relevant projects.
    Text parsing: Developing logic to extract meaningful area names from messy address strings.
    Research: Understanding the dataset schema and verifying the meaning of columns.
    Design iteration: Testing different chart types and color palettes to improve clarity and accessibility.
    Code debugging: Ensuring the script ran without errors and the plot displayed correctly.
    Documentation: Writing comments and explanations to clarify each step for reproducibility.

     Note: Please follow the analysis Visualization file 'NewPark_Projects.png'.

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
* Submission Due Date: `23:59 - 13/07/2025`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_3.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
