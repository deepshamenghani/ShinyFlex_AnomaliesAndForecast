# **EverythingYouWillNeed.com Sales Anomalies and Forecast Report**

This is an interactive R Shiny app that generates a report on sales data for a selected product. It includes information about product sales over time, key performance indicators, forecasting, and anomaly detection. The data used in this report is fake and the company name is also a fabrication.

You can find the published app at this [Link](https://hzon6a-deepsha-menghani.shinyapps.io/Sales_forecast_anomalies/)

## **Getting started**

When the app is running, you will see a sidebar on the left with various input options. To get started, select the product you want to analyze and the date range you are interested in, and then click the **`Apply`** button.

## **App functionality**

This app has three main tabs: **`Product Sales`**, **`Forecast`**, and **`Anomalies`**. Each tab provides different information and visualizations to help you understand the sales data for the selected product.

### **Product Sales**

The **`Product Sales`** tab displays an overview of the product sales and key performance indicators over time. The tab includes a table of product sales filtered by the selected product and date range, and it also shows the total purchase count and average weekly purchase for the selected product.

### **Forecast**

The **`Forecast`** tab checks for seasonality and trend to forecast product sales for the upcoming month. The plot shows the forecasted sales with 95% confidence intervals. A table of the predicted sales can also be found on this tab.

### **Anomalies**

The **`Anomalies`** tab checks for anomalies in the sales data to detect any upstream data issues or red signals in sales so that the relevant business action can be taken. You can change the sensitivity level for the Inter Quartile Range (IQR) method to detect anomalies.

## **Dashboard author**

This app was created by Deepsha Menghani. You can find more of her work on her [**portfolio**](https://deepshamenghani.quarto.pub/dmenghani/), [**GitHub**](https://github.com/deepshamenghani), and [**LinkedIn**](https://www.linkedin.com/in/deepshamenghani/) profiles.

## **Packages used**

-   **flexdashboard**: An R package for creating interactive dashboards with R Markdown.

    -   [Link](https://rmarkdown.rstudio.com/flexdashboard/)

-   **shiny**: An R package for building interactive web applications with R.

    -   [Link](https://shiny.rstudio.com/)

-   **shinyWidgets**: An R package for enhancing Shiny with additional widgets.

    -   [Link](https://dreamrs.github.io/shinyWidgets/)

-   **shinyjs**: An R package for adding JavaScript functionality to Shiny apps.

    -   [Link](https://deanattali.com/shinyjs/)

-   **data.table**: An R package for working with large data sets in R.

    -   [Link](https://rdatatable.gitlab.io/data.table/)

-   **tidyverse**: An R package for data manipulation and visualization.

    -   [Link](https://www.tidyverse.org/)

-   **tidyquant**: An R package for quantitative finance and financial data management.

    -   [Link](https://business-science.github.io/tidyquant/)

-   **anomalize**: An R package for detecting anomalies in time series data.

    -   [Link](https://business-science.github.io/anomalize/)

-   **plotly**: An R package for creating interactive plots and charts.

    -   [Link](https://plotly.com/r/)

-   **modeltime**: An R package for time series modeling and forecasting.

    -   [Link](https://business-science.github.io/modeltime/)

-   **timetk**: An R package for working with time series data in R.

    -   [Link](<https://business-science.github.io/timetk/>)

-   **tidymodels**: An R package for modeling and machine learning with tidy data principles.

    -   [Link](<https://www.tidymodels.org/>)

<img src="https://user-images.githubusercontent.com/46545400/193694905-25b316b3-8f1d-47a0-a1c6-4d0c070ed9ed.png" alt="image" width="956"/>
