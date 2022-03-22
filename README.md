# drone

Drone Continuous Delivery Documentation.

## Usage
1. Install ngrok and forward localhost:80
   ```
   ngrok http 8081
   ```
2. add Github OAuth comsumer with ngrok url

3. Update environment variables in .env

4. Start drone
   ```
   docker-compose -f ./docker-compose.yml up
   ```
