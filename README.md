# API Python
- Communicating with external service API openweathermap.org

### To run API server local: 
    * export API_KEY='your_api_key' (https://openweathermap.org/)
    * docker-compose up --build

#### Python version: 3.9

#### Project dependencies: 
    * Flask 1.1.2
    * requests 2.25.1

#### How to run with docker (choose your port, by default 5000):
    * docker build -t weather-api .
    * docker run -dit --rm -p 5000:5000 --name weather weather:v1

#### ...