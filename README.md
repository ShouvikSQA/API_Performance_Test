# API_Performance_Test

## Project Summery -
  - Here I have performed Load Test and Stress Test on Booking APIs.
  - Then Did some API Chaining (JMeter Collection) on the DMoney website Transaction APIs .
  -  Here I Have Taken data from CSV files and Run Multiple APIs at a time using Four Threads in Jmeter, For Transaction APIs .
  

## Testcase scenarios for Load and Stress Test -
1. Create a Collectio of APIs (JMeter Collection) of Login API, Create Booking API and Search API Http requests.
2. Perform Load Test and Stress Test. Find the Bottleneck point and Capacity Point.
- Website for APIs - https://restful-booker.herokuapp.com

## Testcase scenarios for API Chaining in Jmeter Test -
1. 5 agents perform deposits for 10 customers.
2. 5 customers send money to another 10 customers.
3. 5 customers make payments to 2 merchants.
4. Withdraw Money applying Boundary Value Analysis (BVA) for the withdrawal amount.
- Set the ramp-up time to 120 seconds in all the above thread configuration.
- Website for APIs - http://dmoney.roadtocareer.net


## How to run?
### Execute the following steps using JMeter:
- ``` git clone <repo_url> ```
- ``` Open ApacheJMeter ```
- ``` From ApacheJMeter open the JMX File ```
- ``` Finally Run ```

### Execute the following steps using CLI:
- ``` git clone <repo_url> ```
- ``` jmeter -n -t .\Booking.jmx -l .\Booking.jtl -e -o Reports ``` [For Booking APIs JMeter Collection]
- ``` jmeter -n -t .\Dmoney.jmx -l .\Dmoney.jtl -e -o Reports ``` [For DMoney Trabsaction APIs JMeter Collection ]

## Load and Stress Test Excel Repoet -
 - [Click Here To Open The Report](https://docs.google.com/spreadsheets/d/19GYjbZhdUXBxYSQHAeiZ1zXB1yhEJTzp/edit?usp=sharing&ouid=108139447743460312613&rtpof=true&sd=true)

### Generated HTML report for Load Test -
![image](https://github.com/user-attachments/assets/dca4e63d-46c4-4b01-a72c-159308b073c2)

### Generated HTML report for Stress Test -
![image](https://github.com/user-attachments/assets/ccc8e73f-a8a8-4f11-bf46-0e9f794c28dc)

### Generated HTML report for DMoney Jmeter Collection Test -
![image](https://github.com/user-attachments/assets/3cda7f79-7225-454e-b0bf-6a93f8a116bb)








