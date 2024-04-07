# 🌾CropForEst--Location-based-Crop-Prediction-and-Estimation
## Mail to : [suriyaa2002@gmail.com](mailto:suriyaa2002@gmail.com) for access to Full Project Report and Full Project Code.

### Kindly Star this Repository ⚡
This project focuses on addressing the challenges in the agriculture industry, particularly in the areas of crop prediction and price estimation. Accurately predicting crop yield production and crop demand is crucial for efficient resource allocation and profitability. Traditional methods of prediction are often time-consuming and prone to errors, leading to inefficient resource utilization and revenue loss. To overcome these challenges, an intelligent platform leveraging machine learning algorithms has been developed.

The project consists of two main modules: Crop Prediction and Crop Price Estimation.


# Features
## Crop Prediction: 
This feature utilizes machine learning algorithms to predict the most suitable crop for cultivation based on climatic and soil conditions. It takes into account parameters such as temperature, humidity, rainfall, and nutrient ratios to make accurate predictions.

- Input:
Location: The place where the crop is to be grown
Temperature: The temperature in degrees Celsius taken from API.
Humidity: The humidity level in percentage taken from API
Rainfall: The amount of annual rainfall in millimeters.
Nutrient Ratios (N, P, K): The ratios of nitrogen, phosphorus, and potassium nutrients in the soil.

- Output:
Most Suitable Crop: The output is a single string, which represents the name of the most suitable crop for the given climatic and soil conditions. This prediction is based on the input parameters and the trained machine learning model.

## Crop Price Estimation: 
This feature employs machine learning techniques to forecast crop prices for the next 12 months in a specific district. It uses the predicted crop name obtained from the Crop Prediction module, along with other relevant details, to estimate prices. This information assists stakeholders in making informed decisions and optimizing profitability.

- Input:
Crop Name: The predicted crop name obtained from the Crop Prediction module.
Other Details: Additional information such as the month, and year which is obtained in real time.

- Output:
List of Dictionaries: The output is a list of dictionaries, where each dictionary contains the following information:
Month Name: The name of the month.
Crop Prices: The prices of the predicted crop for that particular month in the given district.

### Screenshots
Input Form 
:-------------------:
![Input - screenshot](https://github.com/SuriyaaVijay/CropForEst--Location-based-Crop-Prediction-and-Estimation/assets/92075531/7067569b-7a05-4c4d-9b72-489817398093)
Price for 12 months in a district for a crop
![Price - screenshot](https://github.com/SuriyaaVijay/CropForEst--Location-based-Crop-Prediction-and-Estimation/assets/92075531/ed77d42f-e7e3-4ab9-976f-e3d7f261cecb)
Result Graph 
![Graph - screenshot](https://github.com/SuriyaaVijay/CropForEst--Location-based-Crop-Prediction-and-Estimation/assets/92075531/f34840e5-c725-4e66-a990-7f192db546b0) 


### Installation
- Clone the repository: git clone https://github.com/SuriyaaVijay/CropForEst--Location-based-Crop-Prediction-and-Estimation
- Open the project in a Code Editor like VS Code
- Install dependancies using requirements.txt
- Create API token from OpenWeatherMap and replace it 

### Contributing
We welcome contributions to enhance the functionality and usability of W-Safe. To contribute, follow these steps:

0. Star <a href="https://github.com/SuriyaaVijay/CropForEst--Location-based-Crop-Prediction-and-Estimation" title="this">this</a> repository.

1. Fork <a href="https://github.com/SuriyaaVijay/CropForEst--Location-based-Crop-Prediction-and-Estimation" title="this">this</a> repository.

2. Clone the forked repository.
```css
git clone https://github.com/<your-github-username>/CropForEst--Location-based-Crop-Prediction-and-Estimation
```
  
3. Navigate to the project directory.
```py
cd CropForEst--Location-based-Crop-Prediction-and-Estimation
```

4. Create a new branch.
```css
git checkout -b <your_branch_name>
```

5. Make changes.

6. Stage your changes and commit
```css
git add -A

git commit -m "<your_commit_message>"
```

7. Push your local commits to the remote repo.
```css
git push -u origin <your_branch_name>
```

8. Create a <a href="https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request" title="Pull Request">Pull-Request</a> to `develop` !

9. Congratulations! 🎉 Sit and relax, you've made your contribution. ✌️ ❤️ 💥


### Fork the repository.
1. Create a new branch: git checkout -b feature/your-feature-name
2. Make your changes and commit them: git commit -m 'Add some feature'
3. Push the changes to your branch: git push origin feature/your-feature-name
4. Submit a pull request.

#### Prerequisites :
- Code Editor (VSCode)
- Python, Jupyter Notebook
- OpenWeather Map API
- HTML, CSS, JavaScript

## Build and Run Application

###### 🌾CropForEst--Location-based-Crop-Prediction-and-Estimation 
