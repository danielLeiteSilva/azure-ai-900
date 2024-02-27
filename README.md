# azure-ai-900 exercises DIO

Machine learning course

#### Exercise 1

```url
 https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html
```

#### Endereço de API

```url
 http://b04cf4e4-2281-4ca4-b347-a76c8fbdfff5.eastus2.azurecontainer.io
```

```http
  GET /score
```

## BODY
```json

 {
   "Inputs": { 
     "data": [
       {
         "day": 1,
         "mnth": 1,   
         "year": 2022,
         "season": 2,
         "holiday": 0,
         "weekday": 1,
         "workingday": 1,
         "weathersit": 2, 
         "temp": 0.3, 
         "atemp": 0.3,
         "hum": 0.3,
         "windspeed": 0.3 
       }
     ]    
   },   
   "GlobalParameters": 1.0
 }

```
## RESPONSE

```json

 {
   "Results": [
     444.27799000000000
   ]
 }

```
