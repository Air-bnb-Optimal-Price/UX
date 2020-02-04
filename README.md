# UX

AirBnB Optimal Price

NAME
AirBnB Optimal Price

PITCH
Use historical booking data to predict the optimal price for an AirBnB in Berlin. 

MVP

DS:
- Train a predictive model on AirBnB prices using historical data. 
- Make predictions accessible to the rest of the team. E.g. deploy via a Flask API (or equivalent) to receive inputs (location, size, etc), and output predicted optimal price in JSON format.

Web:
- User register/login flow
- User can add their AirBnB listings to their profile
- User can edit properties about each listing (ie room type, minimum number of nights, location, etc) . Make cure to collaborate with the DS students on the best data to send to them.  When properties are saved, the data is sent to the DS API and the returned optimal price is dynamically saved for the current home/property.
- User can edit properties for their listings and get an updated optimal price
- User can delete listings

STRETCH

DS:
- Use feature importances to create visual recommendations to user (e.g. you're in the green zone in terms of location, but your availability is in the red zone). 

Web:
- User can add pictures to their listings using an API like Cloudinary
- User can set their database to check the optimal price at certain intervals (weekly, monthly, etc) and they are alerted when there is a change via email or text.

INTERNATIONAL POTENTIAL
AVAILABLE COMPONENTS
DS Component, Web Component
FIGMA DESIGN LINK
https://www.figma.com/file/40k60nIT7U6dG9oj9boh5Y/Airbnb-Design-Exploration-v.-1?node-id=17%3A580
DATA LINKS
https://www.kaggle.com/brittabettendorf/berlin-airbnb-data/downloads/berlin-airbnb-data.zip/2

http://insideairbnb.com/get-the-data.html
EXAMPLE ARCHITECTURE
https://www.notion.so/AirBnB-Optimal-Price-bc281b0b14f944528e3bd091c3996e24