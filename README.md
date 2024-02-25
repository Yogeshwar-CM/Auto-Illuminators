# AutoIlluminators - Drive Smart, Drive Safe

AutoIlluminators is an advanced indicator and headlight monitoring system designed to enhance safety by utilizing the advantages of machine learning and the Google Maps Platform. Our solution comprises two key components: firstly, the efficient management of turn indicators, and secondly, the regulation of beam lights in accordance with driving regulations to prevent accidents with approaching vehicles.


https://github.com/Yogeshwar-CM/Auto-Illuminators/assets/82727820/2e7cb194-2423-4670-a69e-214b0b730ec2

![Screenshot (291)](https://github.com/Yogeshwar-CM/Auto-Illuminators/assets/117517206/b16a9c0b-a06e-4863-86b5-6064b4f977d9)

## 1) Managing Indicators

According to the Motor Vehicles Act, it's imperative to use proper indicators for every turn while driving. Failure to do so can result in collisions between vehicles and potentially cause accidents. However, consistently signaling turns can be challenging for drivers, especially when experiencing mental fatigue. Our platform offers a solution by allowing users to input their starting point and destination. By retrieving travel details and routes from the Google Maps platform using directions APIs, our system intelligently activates indicators at specific waypoints along the journey, alleviating the burden on drivers.

## 2) Managing beam lights - Dipping the beam lights from high to low

Various rules and regulations govern the use of beam lights, including the requirement to maintain low beams when encountering approaching vehicles or navigating through crowded traffic areas. High beam lights have the potential to blind individuals approaching from the opposite direction, presenting a safety hazard. To address this issue, we utilize machine learning and object recognition technology to detect vehicles and intelligently adjust the beam to low settings, thereby mitigating the risk of accidents.

# Tech Stack:
1) Google Maps API
2) Google Cloud
3) React Js
4) Google Flutter
5) Tensorflow/PyTorch

## Command to execute

Clone the repository to your local machine 
`git clone https://github.com/Yogeshwar-CM/Auto-Illuminators `

Install dependencies 
`npm install`

Start script 
`npm start`

Navigate to 
`http://localhost:3000/`
