
# Credit Score Evaluator

This folder is our submission to EY techathon 4.0 final round for which we won 2nd prize. The project uploaded here mainly deals with the financial aspect of our end to end credit score evaluator application.


## Ideation Process

The problem statement proposed to us was to create a end to end credit score evaluator application using genAI.

Approach to this problem was:

i. To create a dummy dataset to train our model.

ii. Create a form in which BFSI employees will fill the data of farmer.

iii. XgBoost takes in the data and gives out a credit score.

iv. For making sure of investment done is right two more features were added into it.
First one is a lstm model to to calculate future 3 years worth of credit history and second one is lstm autoencoder to check for any frauds committed. 


## Demo

You can access the demo video of the application from here:
https://drive.google.com/file/d/1lhSchIp-Oy6G3uLKLDDEvkE7RNJmj1df/view?usp=drive_link



## Deployment

To deploy this project run

```bash
  cd client
  npm start
```

```bash
  cd api
  nodemon index.js
```
Also to turn on the ml model

```bash
  uvicorn app:app --host 0.0.0.0 --port 8001
```

