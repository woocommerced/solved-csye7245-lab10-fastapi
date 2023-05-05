Download Link: https://assignmentchef.com/product/solved-csye7245-lab10-fastapi
<br>
<h1></h1>

This lab leveraged the FastAPI framework for building APIs with Python 3.6+ based on standard Python type hints. In this lab we worked on 2 examples one was just Fastapi demo and other we created a fastapi that can be used to track investors buying and selling on the stock-market.

In addition to serving PUT and GET requests, the endpoint stores all data on DynamoDB.

The key features are:

<ul>

 <li>Fast: Very high performance, on par with NodeJS and Go (thanks to Starlette and Pydantic). <a href="https://fastapi.tiangolo.com/#performance">One of the fastest Python frameworks available</a>.</li>

 <li>Fast to code: Increase the speed to develop features by about 200% to 300%. *</li>

 <li>Fewer bugs: Reduce about 40% of human (developer) induced errors. *</li>

 <li>Intuitive: Great editor support. Completion everywhere. Less time debugging.</li>

 <li>Easy: Designed to be easy to use and learn. Less time reading docs.</li>

 <li>Short: Minimize code duplication. Multiple features from each parameter declaration. Fewer bugs.</li>

 <li>Robust: Get production-ready code. With automatic interactive documentation.</li>

 <li>Standards-based: Based on (and fully compatible with) the open standards for APIs: <a href="https://github.com/OAI/OpenAPI-Specification">OpenAPI</a> (previously known as Swagger) and <a href="https://json-schema.org/">JSON Schema</a>.</li>

</ul>

<h1><strong>Experiment Setup</strong></h1>

<h2><strong>Prerequisites</strong></h2>

<ol>

 <li>Installed below 3 libraries

  <ol>

   <li><strong>pip3 install fastapi</strong></li>

   <li><strong>pip3 install uvicorn</strong></li>

   <li><strong>pip3 install iexfinance</strong></li>

  </ol></li>

 <li>Created a free developer account in IEXCloud to access the current stock price using API tokens.</li>

</ol>

<ol>

 <li>Created a table ‘Customer_Trades’ in AWS DynamoDB to store the data from API.</li>

</ol>




<h1><strong>Example-1</strong></h1>

<ol>

 <li>In python file we have code for root</li>

 <li>Used the below command highlighted command to run the app</li>

 <li> App is launched in port 127.0.0.1:8000 by default</li>

</ol>

<h1><strong>Result-1</strong></h1>

We also tested the docs and executed get and put methods.

<h1><strong>Example-2</strong></h1>

<ol>

 <li>Here we are using trades.py and stock_price.py files</li>

</ol>

Stock_price.py contains the function that is fetching current stock price based on ticker.




<h1>    <strong> </strong><strong>Result-2</strong></h1>

<ol>

 <li>Executing get and post methods and checking DynamoDB records</li>

</ol>

<ul>

 <li>Getting current of stock of Apple</li>

 <li>Adding a customer entry in DynamoDB</li>

 <li>Record is successfully stored</li>

</ul>




<ul>

 <li>AWS Dynamodb Table Console</li>

</ul>




<ul>

 <li>Getting details of Customer records based on ID</li>

</ul>




<h1><strong> </strong></h1>

<h1><strong> </strong></h1>

<h1><strong> </strong></h1>

<h1><strong>Lesson Learned</strong></h1>

<ol>

 <li>Learned to create an app using  Fastapi framework</li>

 <li>Learned to store and fetch data using api from AWS DynamoDB</li>

 <li>Learned about default docs in Fastapi available to get and put data</li>

</ol>




<h1><strong>References</strong></h1>

<a href="https://iexcloud.io/console/"><strong>https://iexcloud.io/console/</strong></a>

<a href="https://github.com/holladileep/CSYE7245-Spring2021-Labs/tree/main/fast-api"><strong>https://github.com/holladileep/CSYE7245-Spring2021-Labs/tree/main/fast-api</strong></a>

<a href="https://fastapi.tiangolo.com/"><strong>https://fastapi.tiangolo.com/</strong></a>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>