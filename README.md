
<html>
  <head>
    
     Crop-prediction-using-Machine-Learning
    
  </head>
  <body>
  <ol type="1">
    <li> Data Collation

<ul>
  
<li>At first the Air humidity, Air temperature, Soil moisture, Soil pH and the GPS sensor modules are integrated with the NodeMCU platform into a portable kit. This kit is installed in the farm to gather the respective data of the soil. The data gathered is transferred in real time to firebase database for storage and further processing. 
<li>The atmospheric humidity, temperature, soil moisture, soil pH are sent as it is to the database. The latitude and longitude sent by the GPS module is retrieved in the form of which state they fall under. This enables us to collect the rainfall of that place in the previous year.
  </ul>
<li>	Data Processing Using Machine Learning

<ul>
  
<li>	Crop Prediction:
<li>	Price Prediction:
  </ul>
<li>	Implementation using Android Application

<p>After the predicted data gets reflected in the firebase database, the farmers can view it in their mobile application.</p>
<p>They can know what crop to cultivate and what price at which the crops should be sold to earn reasonable profit for the farmers</p>
<p>They can also view the necessary nutrients and fertilizers that the crop would need for its healthy growth</p>
<p>Any drastic change in the environmental factors could be notified to the farmers immediately</p>
<div>
  <li> Results
    The result of the android application can be seen <a href="https://github.com/Priyabrata017/Crop-prediction-using-Machine-Learning/tree/master/Results">here</a>
    <img src="https://github.com/Priyabrata017/Crop-prediction-using-Machine-Learning/blob/master/Results/Mango/mango%20app.jpeg?raw=true" alt="Mango">
    </div>
</body>
</html>
