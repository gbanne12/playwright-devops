# playwright-devops

Setup for playwright to run on Azure Devops pipeline. 

Example test makes use of an environment variable that is added to DevOps through the web interface. 

Playwright reporters and pipeline configured to display reporting artifacts following test run 

- Results of the test run are shown on the tests tab by using the junit reporter option in playwright config. 
- Screenshots can be viewed by looking at the specific tests
- Report artifacts and trace are published to DevOps

![Example run](https://i.postimg.cc/Hn8PQR33/image.png)
