# Python-Task
#### For Completion of this task i used BS4 from which BeautifulSoup was imported, requests module for permoing HTTP requests and also various other module reuired for this project.<br/>
![image](https://user-images.githubusercontent.com/54362906/181418082-2f7dc360-53f4-4210-9163-e3f137d59f9c.png)<br/>
#### I created a dataframe df for storing Asin and Country value from Amazon Scraping - Sheet1.csv file. Now i created a Asin list for storing Asin value and Country list for storing Country value fron dataframe df.<r/>
![image](https://user-images.githubusercontent.com/54362906/181418865-a0cbab6f-e4ba-4d0d-aef3-ad70c9f033bd.png)<br/>
#### Now I created Product_Title, Product_Image_URL, Price_Of_The_Product, Product_Details as a list of dictionary and also created Data list for storing all these lists.
![image](https://user-images.githubusercontent.com/54362906/181419478-a1f52e36-79f0-4fa4-a068-91c9d06c5705.png)<br/>
#### Now I defined a headers for bypassing 503 error and run a loop for 100 times in each iteration a url is generated and using requests module a get request command is performed on this url if response status is 404 then i simply print url is not available anf if this url is workinf then i created soup object parsed the html content.</br>
![image](https://user-images.githubusercontent.com/54362906/181420488-47636d72-162d-402a-9874-bc3038b5aa48.png)<br/>
#### For finding Product title i executed below code. </br>
![image](https://user-images.githubusercontent.com/54362906/181420721-fe87b13f-7313-4a30-8091-51300516e376.png)<br/>
#### For finding Image of Product i executed below code.<br/>
![image](https://user-images.githubusercontent.com/54362906/181420874-bfc1af51-9be6-4d96-a8de-73ec75dd7cea.png)<br/>
#### For finding Price of the product, the below code was executed.<br/>
![image](https://user-images.githubusercontent.com/54362906/181421016-68183e8e-74f9-4544-aa44-201ff96d9901.png)<br/>
#### For storing product details i created a list key for storing product details of each page.<br/>
![image](https://user-images.githubusercontent.com/54362906/181421244-aa20370b-4a75-4694-87c5-7b138c85191b.png)<br/>
#### Now i appended all required list of dictionary in Data list.<br/>
![image](https://user-images.githubusercontent.com/54362906/181421390-2a92a9f6-58b7-4b8f-b0e4-302b148b5092.png)<br/>
#### And last i stored this Data list in mydata.json file.<br/>
![image](https://user-images.githubusercontent.com/54362906/181421686-a04c8a0b-f82e-4c95-9751-9dd8dcae6016.png)

## [Click this link for full code](https://colab.research.google.com/drive/1_awio8jvMQEMAWE4LUw0R3F0okDoE_or?usp=sharing)






