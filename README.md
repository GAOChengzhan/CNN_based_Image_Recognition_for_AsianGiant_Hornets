# CNN-based-Image-Recognition-for-AsianGiant-Hornets
## 0.Outlines
1. Built an Auto-Regressive Integrated Moving Average model to predict the expansion of hornets 
2. Trained a CNN-based model to distinguish Asian Giant Hornets from other bees 
3. Implemented a multi-parameter optimization technique and finally F1-Score reached 0.992 while accuracy reached 0.987
## 1.Problem Statement
In September 2019, a colony of Vespa mandarinia (also known as the Asian giant hornet) was 
discovered on Vancouver Island in British Columbia, Canada. The nest was quickly destroyed, 
but the news of the event spread rapidly throughout the area. Since that time, several confirmed 
sightings of the pest have occurred in neighboring Washington State, as well as a multitude of 
mistaken sightings. See Figure 1 below for a map of detections, hornet watches, and public 
sightings.
Due to the potential severe impact on local honeybee populations, the presence of Vespa 
mandarinia can cause a good deal of anxiety. The State of Washington has created helplines and 
a website for people to report sightings of these hornets. Based on these reports from the public, 
the state must decide how to prioritize its limited resources to follow-up with additional 
investigation. While some reports have been determined to be Vespa mandarinia, many other 
sightings have turned out to be other types of insects. 
![image](https://user-images.githubusercontent.com/39005000/198202491-5676b4c8-0fbd-421d-be0e-550a5e9d3ab2.png)

## 2.EDA
![image](https://user-images.githubusercontent.com/39005000/198411049-d2e6f39e-5960-49ca-a750-e72614666023.png)

## 3.ARIMA Autoregressive Integrated Moving Average model
![image](https://user-images.githubusercontent.com/39005000/198411129-cf77becd-fa71-48f6-84fc-16fa375c0277.png)

## Hornets
![image](https://user-images.githubusercontent.com/39005000/198411165-b9776a72-a61a-40dc-9b6f-a5360ce14646.png)

## 4.Positive Label Data Augmentation
#### flip, blur, sharpen, change the contrast and other operations on the image
![image](https://user-images.githubusercontent.com/39005000/198411673-7ae70c9d-6e55-4036-ac41-c101d7364b88.png)

![image](https://user-images.githubusercontent.com/39005000/198411189-57aa3e37-3a7f-4064-8e7a-ef7a55d2c8cc.png)

## 5.Residual Network 
![image](https://user-images.githubusercontent.com/39005000/198411600-6641a784-f82a-4cfd-ad4f-8bdc2d1755d3.png)
![image](https://user-images.githubusercontent.com/39005000/198411639-f297c0db-f315-450a-8a24-f4a3500af51c.png)

## 6.Train Function
![image](https://user-images.githubusercontent.com/39005000/198411718-b1cb9e72-d101-4515-8127-36799d4bb5b8.png)

## 7.Results
![image](https://user-images.githubusercontent.com/39005000/198411771-68f9123c-e632-4247-be91-f3e61599e24d.png)

