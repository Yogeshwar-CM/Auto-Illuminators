# AutoIlluminator - Drive Smart, Drive Safe

AutoIlluminator, is a smart indicator and headlight monitoring platform to avoid accidents by levaraging the benefits of ML and Google Maps Platform. Our solution consists of two part firstly, managing the turn indicators and Secondly, management of Beam lights as per the driving regulations for an approaching vehicles.

https://github.com/Yogeshwar-CM/Auto-Illuminators/assets/82727820/2e7cb194-2423-4670-a69e-214b0b730ec2

## 1.) Managing Indicators.

As per Motor Vehicles act it is necessary to give appropriate indicators during each and every turn while driving. Improper use of indicators can lead to a dash between vehicles and may also cause accidents. giving indicators during turns at time can be difficult for a driver due to mental fatigue. Thus our platform provides a solution where a person has to enter the starting point and destination and by fetching the details of travel/route from GoogleMaps platform using directions APIs and smartly triggering the indicators on the particular waypoints.

## 2.) Managing beam lights - Dipping the beam lights from high to low

There are different rules and regulations innvolved with the usage of beam lights such as keeping a low beam for an approaching vehicle and in a crowded and a traffic area. High beam light can blind the person approaching from the other end, thus we solve this problem by employing ML and performing object recognition to detect the vehicle and smartly dip to low beam to avoid accidents.

# Tech Stack:
1) Google Maps API
2) Google Cloud
3) React Js
4) Google Flutter
5) Tensorflow/PyTorch

## Command to execute

Clone the repository to your local machine `git clone https://github.com/Yogeshwar-CM/Auto-Illuminators `

Install dependencies `npm install`

Start script `npm start`

Navigate to `http://localhost:3000/`
