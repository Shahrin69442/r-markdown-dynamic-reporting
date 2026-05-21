# Dynamic Reporting and Data Visualization with R Markdown

This repository showcases a foundational project focused on creating reproducible and dynamic data reports using **R Markdown** within **RStudio**. 

## 📌 Project Overview
The goal of this project was to understand the workflow of R Markdown and generate a fully compiled HTML report that integrates live R code, statistical analysis, and data plotting.

## 🛠️ Tools & Technologies Used
* **Language:** R
* **IDE:** RStudio
* **Key Packages:** `knitr`, `rmarkdown`
* **Output Format:** HTML (`html_document`)

## 📊 Features & Contents
1. **Automated Summary Statistics:** Utilized the built-in `cars` dataset to automatically generate baseline statistical metrics (`Min`, `1st Qu.`, `Median`, `Mean`, `3rd Qu.`, `Max`).
2. **Data Visualization:** Embedded a dynamic plot utilizing the `pressure` dataset to visualize temperature vs. pressure curves.
3. **Reproducible Pipeline:** Managed code chunks using `{r setup, include=FALSE}` and custom parameters like `echo=FALSE` to create a clean end-user presentation.

## 🚀 How to Run the Project
1. Clone this repository.
2. Open the `.Rmd` file in RStudio.
3. Click the **Knit** button to regenerate the `HTML` or `PDF` report dynamically.

---
*Maintained by Md Shahrin Parvez.*
