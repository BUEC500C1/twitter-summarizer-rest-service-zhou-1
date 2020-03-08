# Goal    
Make your HW4 "Convert Tweet contents to a video" a REST service running on AWS      

## Details   
Step 1: Use Flask as your WEB service platform     
Reference 1:  https://palletsprojects.com/p/flask/ (Github:  https://github.com/pallets/flask )   
Reference 2:  Flask-RESTFUL  (Github:  https://github.com/flask-restful/flask-restful )     
Use Python and Flask to achieve the RESTful services.    

Step 2:  Integrate your module to become a RESTFUL system   
Deploy your system to free AWS services:  https://aws.amazon.com/free/?all-free-tier.sort-by=item.additionalFields.SortRank&all-free-tier.sort-order=asc    
Develop simple WEB applications to test your system.      

## Caution  
Document your REST APIs on your Github    
Keep your server off until we request it for grading.  We dont want you to waste money.     

# Set up    
## Flask    
Command for downloading Flask using pip     
```
pip install -U Flask
```
## Flask-RESTful     
Install Flask-RESTful with pip    
```
pip install flask-restful
```

# Examples    
## Flask &Flask-RESTful     
Examples can be [viewed here](https://github.com/BUEC500C1/twitter-summarizer-rest-service-zhou-1/tree/master/FlaskProj)    

## This project   
clone this repo     
```
git clone https://github.com/BUEC500C1/twitter-summarizer-rest-service-zhou-1.git
```

Install all requirements for this program   
```
pip3 install -r requirements.txt
```

<b> Important! </b> Please go to keys file, to add in your own Tweepy API keys in below format:
```
[auth]
consumer_key = ****
consumer_secret = ****
access_token = ****
access_secret = ****
```

### Run this program    
On your shell/terminal, run this program by typing below command:   
```
python flaskWeb.py
```





