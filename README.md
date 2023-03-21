# Amazon Web Scraping Project

This project is designed to scrape data from Amazon website and extract pricing information for specific products. The project utilizes various libraries such as BeautifulSoup, Requests, and SMTPLib to accomplish this task.

# Getting Started
To get started, make sure you have Python installed on your system. You will also need to install the following libraries:

BeautifulSoup
Requests
SMTPLib
You can install these libraries using the pip package manager.

# How It Works
The project works by connecting to the Amazon website and pulling in data for specific products. It then cleans up the data and creates a timestamp for the output to track when data was collected. The project also creates a CSV file and writes headers and data into the file.

The project can be run on a set timer to check for price changes and update the CSV file accordingly. Additionally, the project includes a feature to send an email notification when a price hits below a certain level.

# Using the Code
To use the code, simply run the Python script. The script will connect to the Amazon website and extract pricing information for the specified products. The data will be saved to a CSV file.

If you want to modify the code to scrape pricing information for different products, simply change the URL in the script to point to the product you are interested in.

# Conclusion
This Amazon web scraping project is a great way to extract pricing information for specific products on the Amazon website. By utilizing various libraries and functions, the project can be customized to meet your specific needs.
