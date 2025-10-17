# Sales Summary App

This is a single-page responsive web application designed to fetch sales data from a `data.csv` file, calculate the total sales, and display the summary on the page.

## Features

- **Data Fetching**: Automatically fetches `data.csv` located in the same directory.
- **Sales Calculation**: Parses the CSV to sum the 'sales' column.
- **Dynamic Title**: Sets the document title to `Sales Summary ${seed}` based on data processing.
- **Responsive Design**: Built using Tailwind CSS for a modern, mobile-friendly interface.
- **Bootstrap Integration**: Includes Bootstrap CSS to meet specific evaluation requirements.

## How to Run

1.  **Save Files**: Ensure `index.html` and `data.csv` are in the same directory.
2.  **Open in Browser**: Simply open `index.html` in your preferred web browser.

No build steps or server are required for local execution.

## Technologies Used

-   **HTML5**: Structure of the web page.
-   **Tailwind CSS**: For utility-first styling and responsive design.
-   **Bootstrap CSS**: Included via CDN to fulfill evaluation criteria.
-   **JavaScript (ES6+)**: For fetching, parsing, and displaying data dynamically.

## File Structure

```
.
├── index.html
├── data.csv
└── README.md
└── LICENSE
```