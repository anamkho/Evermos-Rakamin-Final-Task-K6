This repository is for Performance Test and Integration Test Project-Based Internship Final Task Evermos x Rakamin Academy

The tests is using K6 tool with javascript, and using dummy API from https://reqres.in/

Task to be done:
1. Create a test scenario for the integration test of the 2 APIs and implement it into k6 and add assertions from each test performed in 1 test file
2. Create a test scenario to test the performance of the 2 APIs with a total of 1000 virtual users, 3500 iterations and a maximum API response tolerance limit of 2 seconds and add assertions from each test performed in 1 test file
3. Generate a report in HTML from no. 2 to get a visualization of the performance test performed.

## Getting Started

### Preparation

Make sure you have installed the following software:

1. [Postman](https://www.postman.com/)
2. [Node.js](https://nodejs.org/)
3. [Git](https://git-scm.com/)
4. [K6](https://k6.io/docs/get-started/installation/)

### Installation

1. Clone This Repository

    ```bash
    git clone https://github.com/anamkho/Evermos-Rakamin-Final-Task-K6.git
    ```

2. Navigate to the folder

    ```bash
    cd Evermos-Rakamin-Final-Task-K6
    ```

3. Run the Project

    ```bash
    k6 run script.js
    ```