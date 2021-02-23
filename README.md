# Nexpose_Tagging_Multiple
Tagging large number of assets automatically using Nexpose API

Description: Apart from the many features offered by Nexpose/InsightVM, havent you at some point tried to perform a function that seems to take impossible amount of manual work? One of such problems is tagging your assets based on the owner. This is an enhancement of the previous code which tags assets using a tesxt file consodering each ip had 1 tag related to it. As there might be thousands of assets with a different owner for every few assets and to avoid hours of manual work, this program will help in automatic tagging

Prerequisites:
1. Active Nexpose/InsightVM console
2. Nexpose security console information such as IP address and login credentials
3. Text file with IP address and tag names 
4. Python 3+
5. Postman (optional - will help with testing the API)

Installation: Download this code and run in python after changing the required information. I have also added a sample text file with IP addresses and tag names in the required format.

I have used the API docuemntation from Rapid7 to build it and check for search criteria etc. If you want to change these, please refer to: https://help.rapid7.com/insightvm/en-us/api/index.html

I am open to all comments, changes, feedback or reccomendations, please do let me know if you have any ideas or additional use cases you would like some answers to.
