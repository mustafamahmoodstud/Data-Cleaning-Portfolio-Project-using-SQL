# Data-Cleaning-Portfolio-Project-using-SQL

Overview:

This project involved cleaning and standardizing data within the NashvilleHousing table of the PortfolioProject database. The dataset, sourced from Kaggle, contained information about housing properties in Nashville and required various cleaning tasks to enhance its quality and usability.

Data Cleaning Process:

The data cleaning process encompassed several steps:

Standardizing Date Format: The SaleDate column was converted to a standardized date format to ensure consistency and facilitate future analysis. This involved updating the SaleDate column and addressing any issues with the conversion process.

Populating Property Address Data: Null values in the PropertyAddress column were handled by filling them with available data from records sharing the same ParcelID. This involved joining the table with itself based on ParcelID and updating null values accordingly.

Breaking out Address into Individual Columns: The PropertyAddress and OwnerAddress columns were split into separate columns for Address, City, and State to improve data organization and accessibility. String manipulation functions such as SUBSTRING and PARSENAME were used for this purpose.

Standardizing Yes/No Values: Values in the SoldAsVacant column were standardized to 'Yes' or 'No' to improve clarity and consistency. This involved updating 'Y' and 'N' values accordingly.

Removing Duplicates: Duplicate records were identified based on specific columns (ParcelID, PropertyAddress, SalePrice, SaleDate, LegalReference) and removed to ensure data integrity.

Deleting Unused Columns: Columns deemed unnecessary for further analysis were dropped from the dataset to reduce redundancy and streamline data storage.

Future Steps:

Further Analysis: After cleaning the data, it can undergo in-depth analysis to extract insights and inform decision-making processes.
Visualization: Visualizations such as charts, graphs, and maps can be created to present findings in a more intuitive and understandable manner.
Machine Learning: Advanced techniques like predictive modeling or clustering can be applied to uncover hidden patterns or trends within the dataset.
Conclusion:
Data cleaning is a crucial step in the data analysis process, ensuring that the data is accurate, consistent, and reliable. By performing these cleaning tasks, the quality of the NashvilleHousing dataset sourced from Kaggle has been significantly improved, laying a solid foundation for further analysis and exploration.

Note: The dataset used in this project was obtained from Kaggle, a platform for sharing datasets and data analysis resources. This information underscores the transparency and credibility of the data source, providing assurance regarding the dataset's origins and reliability.



