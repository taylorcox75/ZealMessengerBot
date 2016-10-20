#Zeal [![Build Status](https://travis-ci.com/taylorcox75/Zeal.svg?token=XbqCKDp6PtzWG54UBd9w&branch=master)](https://travis-ci.com/taylorcox75/Zeal)

## [Taylor Cox](mailto:taylorcox75@gmail.com), [YuanJun Ma](mailto:yuanma@email.arizona.edu), [Siddharth Sharma](mailto:siddi.sharma@gmail.com),[ Chioke Aarhus](mailto:caarhus@email.arizona.edu)

##Project Setup

###Prerequisites

>Ruby on Rails

>`gem install rails`

>`bundle install` 

> `brew update`

> `brew install postgresql`

> `gem install pg` 

>`bundle install` 

###In Terminal at Desired Location
>`git clone https://github.com/taylorcox75/Zeal.git`

>`cd Zeal`

To Reinit Main Bot
>`curl -X POST "https://graph.facebook.com/v2.6/me/subscribed_apps?access_token=EAAEaNSbDzrwBAMHdn3oJ7cbSRwumMt9nwfFUZAIpGDuajvKM2FvuvbNklf1ZCevkroE9ZAbEDZCZAMwLQlvGTzzlpThBsHaeVSvpOULDj1eCMtzPJ2cfrYencmWtH6J0lZALEvaJnVWZCzXbQqUaorKvKo1MjILdM225rc7bmkldgZDZD"`

>`rails s`

To Reinit Development Bot
>`curl -X POST "https://graph.facebook.com/v2.6/me/subscribed_apps?access_token=EAAZAWPnkEQSsBAEUWcLGQbOX0p80br14CXyddWdKhvKe52wWSDzpHZB0q3bbKcuvNxDiYpOfwcMDN7yGks8ZCr1WPc9wZBlVRATf3FZAdb566RvLTR85AFnsOxQ7rf8CDwStaL9yZCP8uSKGEXZASLfvkiZCmpxHycoK8OoVCZCz8eQZDZD"`

>`rails s`(start server)

Must run rake jobs:work to run reminder workers in local machine databse.

> `rake jobs:work`
 
>New Terminal Tab

>`./ngrok http 3000 -subdomain=zeal2`

# One Solution.  One Bot

The main idea behind Zeal is rethinking the way we establish reminders. With a simple interface, Zeal functions as a bot whose sole goal is to assist in aiming for the completion of the user’s goals. Zeal will handle reminders in a unique way. It will offer location based reminders, as well as scanning user’s social calendars and such, with the use of various API’s. With a completely rebuilt way of using prioritized reminders, Zeal will make sure the user gets their tasks completed.


# Project Iterations
## **Viable Release**
TBD

## **Functional Release**
TBD

## **Beta Release**
TBD

