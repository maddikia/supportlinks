# [supportlinks](http://www.supportlinks.tech/)

## what is supportlinks?
a fully anonymous, youth-focused support chatbot providing mental health resources and connecting users to peer support

## get linked
* express yourself anonymously & get **link**ed to mental health resources
* form support **link**s with experienced peers in our volunteer network
* get **link**ed to local hospitals in times of crisis or injury
* un**link** yourself from mental illness and **link** yourself to a healthy mind

## what we offer
the basis of our platform is **link** (they/them), a **natural language understanding chatbot**. they’ve been trained to recognize depression, suicidal tendencies, stress, anxiety, and some eating disorders. by sharing what you’re feeling with a link, they’ll provide you with student-centered resources to seek help and make strides towards a healthy mind. if you’re in crisis, in danger, or harmed, they will **connect you to hospitals** in your area. link can also introduce you to our peer network. beyond connecting you with external resources, we can link you to other students with similar experiences through our **peer support network**. 

## why it's relevant
it is estimated that 13–20% of youth living in the United States experience a mental disorder in a given year ([source](https://www.cdc.gov/childrensmentalhealth/features/kf-childrens-mental-health-report.html)). the pandemic certainly hasn't helped, and 56.2% of young adults (ages 18-24) now report symptoms of anxiety and/or depressive disorder ([source](https://www.kff.org/coronavirus-covid-19/issue-brief/the-implications-of-covid-19-for-mental-health-and-substance-use/)). youth's mental state is deteriorating, and we need resources for youth well-being now more than ever. with link, we can help users identify the root of their symptoms and compile mental health resources all in one place, providings users with everything they need in one place. there has also been research in support of peer support ([source](https://www.mhanational.org/peer-support-research-and-reports)), so we chose to add peer connection to our platform. 

## how we built it
we built link, our favorite chatbot, using Google Cloud’s **Dialogflow**, with all interactions implemented as intents. in cases of injury and crisis, we connected link with the **public [Hospital General Information dataset](https://console.cloud.google.com/marketplace/product/hhs/hospital-general-information?project=peppy-tiger-268215)** using **BigQuery API**. our website was built using **HTML/CSS/JS** and our logo was custom-designed.

## future steps
our first steps will be to compile more mental health resources and better train **link** to identify causes; we will also want to incorperate specificity within broad categories, such as subsets of anxiety. next, will will expand our peer support network and build a connection platform specific to supportlinks to better preserve anonymity and allow for instantaneous, automatic connection. (our connect network is currently not automated and run through Google Forms but, with more time, we hope to use Flask and a database to store users; in addition to an anonymous text platform, we hope to also implement a Clubhouse-esque anonymous call platform.) 

## credits & acknowledgement
the base of our website was developed with influence from [Stack Lite](https://onepagelove.com/stack-lite) and we sourced our landing page graphic from [unDraw](https://undraw.co/). thank you to the organizing team, sponsors, and mentors for this amazing weekend. we want to especially thank our mentor, Ron, so much for all of his help throughout the weekend! 
