# IBM-Data-Analyst-Capstone-Project-Dashboards
In this module, I will create a dashboard using IBM Cognos Analytics or Google Looker Studio. This platform allows me to design various charts and assemble a visually appealing, easy-to-understand dashboard. My dashboard will present data analysis clearly, with options for intuitive data drill-down.


# IBM Cognos Analytics Dashboard Project

This project involves creating interactive dashboards using the IBM Cognos Analytics tool. The dashboards are designed to visualize and analyze data from the 2019 Stack Overflow Developer Survey. The assignment focuses on exploring current technology usage, future technology trends, and demographic data of the survey respondents.

## Software Used

- **IBM Cognos Analytics Tool:** The project is implemented using the free trial version of IBM Cognos Analytics.

## Prerequisites

- **Access to Cognos Analytics:** You'll need access to IBM Cognos Analytics to complete this assignment. A Cognos lab will guide you through the process of gaining access and provide an introduction to the tool's features for analyzing data.

## Dataset Used

- **Source:** The dataset used in this assignment comes from the [2019 Stack Overflow Developer Survey Results](https://stackoverflow.blog/2019/04/09/the-2019-stack-overflow-developer-survey-results-are-in/) and is provided under an ODbL: Open Database License.
- **Modified Subset:** A modified subset of the original dataset is used for this assignment. Please use the provided dataset files rather than downloading the data from the original source.

## Project Structure

### Datasets

- `m5_survey_data_demographics.csv`
- `m5_survey_data_technologies_normalised.csv`

Upload these files as data assets in your Cognos Analytics project.

### Dashboards

#### 1. **Current Technology Usage**
   - **Template:** 2 x 2 rectangle areas tabbed template.
   - **Rename:** This dashboard tab to `Current Technology Usage`.
   - **Visualizations:**
     - **Panel 1:** Bar chart of the Top 10 `LanguageWorkedWith`.
     - **Panel 2:** Column chart of the Top 10 `DatabaseWorkedWith`.
     - **Panel 3:** Word cloud of `PlatformWorkedWith`.
     - **Panel 4:** Hierarchy bubble chart of the Top 10 `WebFrameWorkedWith`.

#### 2. **Future Technology Trend**
   - **Template:** 2 x 2 rectangle areas tabbed template.
   - **Rename:** This dashboard tab to `Future Technology Trend`.
   - **Visualizations:**
     - **Panel 1:** Bar chart of the Top 10 `LanguageDesireNextYear`.
     - **Panel 2:** Column chart of the Top 10 `DatabaseDesireNextYear`.
     - **Panel 3:** Tree map chart of `PlatformDesireNextYear`.
     - **Panel 4:** Hierarchy bubble chart of the Top 10 `WebFrameDesireNextYear`.

#### 3. **Demographics**
   - **Template:** 2 x 2 rectangle areas tabbed template.
   - **Rename:** This dashboard tab to `Demographics`.
   - **Filters:** Apply a filter to display only entries for "Man" and "Woman" in the `Gender` field.
   - **Visualizations:**
     - **Panel 1:** Pie chart of `Respondent` classified by `Gender`.
     - **Panel 2:** Map chart of `Respondent` count for `Countries`.
     - **Panel 3:** Line chart of `Respondent` count by `Age`.
     - **Panel 4:** Stacked bar chart of `Respondent` count by `Gender`, classified by `Formal Education Level`.

## Guidelines for Submission

1. **Upload the Datasets:** Upload the two provided CSV files as data assets in your Cognos Analytics project.
2. **Create the Dashboards:** Follow the instructions to create three dashboards with four panels each, visualizing the specified metrics.
3. **Apply Filters:** Use the filtering feature to refine the data in the Demographics dashboard tab as instructed.


