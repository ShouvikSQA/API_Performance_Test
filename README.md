# API_Performance_Test

## Project Summery -
  - HereI have performed Load Test and Stress Test on the below Website APIs -
  https://restful-booker.herokuapp.com
  - Then Did some API Chaining on the below website APIs -
  http://dmoney.roadtocareer.net
  - Here I Have Taken data from CSV files and Run Multiple APIs at a time using Four Threads in Jmeter.
  

## Testcase scenarios for Load and Stress Test -
1. Create a Collectio of API of Login API, Create Booking API and Search API Http requests.
2. Perform Load Test and Stress Test. Find the Bottleneck point and Capacity Point.

## Testcase scenarios for API Chaining in Jmeter Test -
1. 5 agents perform deposits for 10 customers.
2. 5 customers send money to another 10 customers.
3. 5 customers make payments to 2 merchants.
4. Withdraw Money applying Boundary Value Analysis (BVA) for the withdrawal amount.
- Set the ramp-up time to 120 seconds in all the above thread configuration.


## How to run?
### Execute the following steps using JMeter:
- ``` git clone <repo_url> ```
- ``` Open ApacheJMeter ```
- ``` From ApacheJMeter open the JMX File ```
- ``` Finally Run ```

### Execute the following steps using CLI:
- ``` git clone <repo_url> ```
- ``` jmeter -n -t Dmoney.jmx -l DMoney.csv ```


## Documantation for the API Collection -
 - [Click Here To Open The API Documantation](https://documenter.getpostman.com/view/28923318/2sAXjPzpTm)

## Test Cases For my Project -
 - [Click Here To Open Test Cases on DMoney APIs](https://docs.google.com/spreadsheets/d/1cGM0UKiFCwRpFosZIlTMw2fyO6W5wkxe9fyeQ3fpKGc/edit?usp=sharing)

## Bug Report For My Project -
 -  [Click Here To Open Bug Report on DMoney APIs](https://docs.google.com/spreadsheets/d/1BEXQOKZuqPUv1CBNdCexjiaCzT8x1fdp_vZvv9qI-18/edit?usp=sharing)
## Output -
![image](https://github.com/user-attachments/assets/946b8a4c-0ece-4b71-85fd-6bf1097ceffb)

