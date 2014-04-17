---
title: How to import bank or card statement
description: Who likes manual entry? None of us.
layout: article
---
Who likes to record everything manually? We don't. And hopefully, neither you. So, let's import all our transactions (both income and expense) in bulk using bank or card statements from bank.

*For now, we support importing from CSV and XLS files only. In future, we will open up other methods too.*

1. Click on your company name in the top-left corner and then on **Import** to start importing.

	![import-nav]({{site.url}}/images/import/import-nav.png)

2. Click on the **New** button in the top-left corner to begin uploading a file.

	![import-new]({{site.url}}/images/import/import-new.png)

3. An modal window will open with options ***Bank Statement***, ***Card Statement***, ***Clients***, ***Vendors***. Click on the either **Bank Statement** or **Card Statement**.

	***Note:** The file you upload should be a .xls or .csv file only.*

	***Note:** Number of columns in file should be either **3** or **4**. When **3** then every row should contain **Date**, **Description** and **Amount** columns. When **4** then every row should contain **Date**, **Description**, **Debit** and **Credit** columns.*

	![import-upload]({{site.url}}/images/import/import-upload.png)

4. After uploading the file you will be redirected to **Mapping** window where you have to map the uploaded file's columns as follows: 
	1. To properly understand the format of the date, please select the date formet from the drop down menu.
	2. Select the **Money Account** to which the transactions should be added.
	3. We have tried our best to match the column headings with that of your files, but you are free to make the required changes.

	![import-map]({{site.url}}/images/import/import-map-statement.png)

5. Once done, click on the **Map** button at the bottom extreme right corner and the data will be imported in the background. It may take a couple of minutes before all the data is imported in your account. We will send you an email when the import is done.
	 