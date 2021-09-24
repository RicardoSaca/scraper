# Linkedin Scraper using Selenium
by: Ricardo Saca

## What infromation it collects?
* Name
* Current Job Title
* Current Company
* Last College
* Education section
* Current Location
* Skill Set section
* Linkedin URL

## How it works?
### Setup
Clone the respository and install the required libraries to your virtual environment. <br>
Edit the parameters.py with your linkedin email and password, as well as the local path to chromedriver ([more information](https://chromedriver.chromium.org/getting-started))

### Running the Scraper
Run the scraper on the command line by using: py scraper.py <br>
The scraper will then ask how many users you are looking for, give number with a multiple of 10 <br>
Then it will ask what is the search query you want, use format "POSITION" AND "LOCATION" <br>
Then it will ask if you want to search for another position return Y or N <br>
Repeat until you have all the positions you are looking for <br>
The scraper will then run and create a file called results.csv where the information you are looking for will be found

## Demo 
[linkedin-scraper-demo](https://github.com/RicardoSaca/scraper/edit/main/demo.gif)
The scrapping is seen at 2x the speed to lower the file size. 

### Disclamer
Scrapping linkedin can lead to your profile being banned or suspnded. It is recommended to use an account that is not your main one.
It is [legal](https://www.forbes.com/sites/emmawoollacott/2019/09/10/linkedin-data-scraping-ruled-legal/#:~:text=A%20court%20has%20ruled%20that,that%20this%20violates%20user%20privacy.) but the company views it as [a violation of terms of service](https://news.linkedin.com/2021/april/an-update-from-linkedin)

### Tutorials used
https://www.linkedin.com/pulse/how-easy-scraping-data-from-linkedin-profiles-david-craven/
https://stackoverflow.com/questions/62009351/linkedin-scraper-to-extract-skills

