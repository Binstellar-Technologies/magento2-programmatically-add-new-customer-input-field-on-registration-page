## Magento2 Programmatically Add New Customer Input Field on Registration Page

> Magento2 an open-source e-commerce platform written in PHP.

&nbsp;
&nbsp;

> Here in this extension we are going to learn how to add new customer input field on Registration page.

&nbsp;
&nbsp;

> In this extension we have added an input field named "Custom Field" on the registration page & displayed its value in the admin customer grid.

&nbsp;
&nbsp;

## Installation Steps

##### Step 1 : Download the Zip file from Github & Unzip it
##### Step 2 : Create a directory under app/code/Binstellar/CustomFieldOnRegistration
##### Step 3 : Upload the files & folders from extracted package to app/code/Binstellar/CustomFieldOnRegistration
##### Step 4 : Go to the Magento2 Root directory & run following commands

php bin/magento setup:upgrade

php bin/magento setup:di:compile

php bin/magento setup:static-content:deploy -f

php bin/magento cache:flush

&nbsp;
&nbsp;

<h5>Frontend - Customer Registration Page</h5>
<kbd>

![image1](https://user-images.githubusercontent.com/123800304/218378188-905c851e-abf9-46fd-9c34-6d151e80bf03.png)


</kbd>

&nbsp;
&nbsp;

<h5>Admin - Customer Admin Page</h5>
<kbd>


![image2](https://user-images.githubusercontent.com/123800304/218378310-878b8aae-03cb-4406-b61a-252d87b74200.png)


</kbd>

&nbsp;
&nbsp;
## Note : We have tested this option in Magento ver. 2.4.5-p1
