# EVS-Project

## Installation

To get started with the project, follow these steps:

1. Clone this repository.

```json
git clone https://github.com/NancyPatel11/EVS-Project.git
```

2. Install the necessary dependencies.
   Run the following command in your terminal. Make sure you are at the correct path (home) of the cloned repository.

```json
pip install numpy pandas matplotlib seaborn tensorflow keras tqdm scikit-learn fastapi uvicorn glob math os warnings io pillow
```

3. Run the project.
   In the api.py file, run the code.

You will be directed to the following page:
![alt text](/api_trial/1.png)

Next, type `/docs` at the end of the url as shown below:
![alt text](/api_trial/2.png)

You will get directed to the FASTAPI homepage. Here, you can see the `uploadfile` post request. Click on it to expand it. You will see the option `try it`.
![alt text](/api_trial/3.png)

Now click on the `try it` button, you will see an image upload section where you can choose any garbage image from your computer:
![alt text](/api_trial/4.png)

Once you upload a garbage image, click on execute. Our model will then be called in the backend and you will the classification result along with the model confidence as shown below:
![alt text](/api_trial/5.png)
