# Data Visualization

## Assignment 4: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
    Python: For customized visualizations with Matplotlib and Seaborn.
    Power BI: For interactive and user-friendly visualizations

    > Who is your intended audience? 
    City Officials and Planners: To support decision-making regarding park and washroom facilities.
    Community Members: To gain insights into accessibility and service alerts in parks.
    PFR Staff: For managing and monitoring park facilities more effectively.

    > What information or message are you trying to convey with your visualization? 
    Python Visualization:
    Visualization: Heatmap of washroom density by location.
    Highlights locations with varying densities of washroom facilities, aiding in resource allocation and maintenance planning.
    Bar Chart of Washroom Types and Statuses: Shows the distribution of different types of washroom facilities and their operational statuses, providing insights into the availability and condition of these facilities.
    
    Power BI Visualizations:
    Total No. Parks by Type of Accessibility: Shows the distribution of parks based on their accessibility type, helping to identify which parks are more or less accessible.
    No. of Closed/Service Alert Parks by Reason: Provides an overview of parks currently closed or under service alerts, categorized by the reasons for these statuses. This helps in understanding and addressing common issues.


    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
    Substantive:
    Accuracy: Ensured data accurately represents accessibility types and service alert reasons.
    Relevance: Focused on key aspects like accessibility and service alerts to provide actionable insights.

    Perceptual:
    Clarity: Utilized clear labels, distinct colors, and intuitive layouts in Power BI to enhance data interpretation.
    Simplicity: Designed visualizations to be straightforward, avoiding unnecessary complexity.

    Aesthetic:
    Consistency: Maintained a uniform design and color scheme to ensure visual coherence across visualizations.
    Engagement: Made the dashboards interactive to facilitate user exploration and engagement with the data.

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    Python: Used scripts that can be rerun with updated datasets, ensuring consistent and repeatable visualizations.
    Power BI: Enabled automatic data refreshes and updates, ensuring that dashboards remain current and relevant

    Impact of Non-Reproducibility: If visualizations in Power BI are not reproducible, it could lead to outdated or inaccurate insights, affecting decision-making. Reproducibility ensures ongoing accuracy and relevance.

    > How did you ensure that your data visualization is accessible?  
    Python: Applied clear annotations, accessible color schemes, and readable labels to enhance visualization accessibility.
    Power BI: Configured visualizations to support accessibility features, including screen readers and color-blind friendly palettes.

    > Who are the individuals and communities who might be impacted by your visualization?  
    Community Members: Gain insights into park accessibility and service status.
    City Planners: Use data to improve park accessibility and address service issues.
    PFR Staff: Better manage park facilities based on current accessibility and service status information.


    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    Included: Focused on accessibility types and service alert reasons to provide relevant and actionable insights.
    Excluded: Omitted less relevant details that do not directly contribute to the analysis of accessibility and service status.


    > What ‘underwater labour’ contributed to your final data visualization product?
    Data Cleaning: Ensured accuracy by addressing missing or inconsistent data.
    Feature Engineering: Developed meaningful metrics and visual summaries for clear insights.
    Customization: Tailored the visualizations to meet audience needs, ensuring they are both informative and actionabl


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
