## Inspiration
After seeing steps in electric charging and electric vehicles, we designed an app to optimize and simplify the charging stations. Since the demand for charging stations is increasing, we wanted to create an app that allows users to find charging stations near them and the available locations they can charge at. Users can also reserve and pay for the charge through the mobile device.

## What it does
Full Charge is an android app that uses Google Cloud and MATLAB to find and reserve charging locations. The user signs up using their DESO identity and links their app to their car device. The app uses the user's location and finds charging stations near them along with the available spots that can be reserved. The device is installed inside the user charging port cap and connects to the phone during the one-time setup. When a user finds a charging station, they can reserve a spot. The charging lot then detects the user's car device when it passes through the entrance and notifies you that you have made it to the lot and directs you to your spot. The user can pay for the charge through the mobile app too.

## How we built it
Using Andriod Native, we designed and developed this mobile app and launched it on the DESO blockchain. Users link their DESO identity to the car device which is designed using an ATmega328P and Embedded C to link the car device to the mobile app. We use Google Cloud to find charging stations near you and store the information regarding the available spots. We use MATLAB to model the vehicle entering the EV charging stations and determine the optimal path for the location of the empty space or reserved space. 

## Challenges we ran into
We had issues with connecting the car device to the mobile app. Launching the app on the DESO blockchain was very hard to launch since the documents of the blockchain were blocked on our school network. The MATLAB program to simulate and optimize the reserved spots was an interesting challenge but we learned a lot from it.

## Accomplishments that we're proud of
We are proud of creating a DESO blockchain application that uses the DESO identity to store the information of users. 

## What we learned
Learning how to connect the embedded system to our mobile device was so much fun and satisfying to get working. Learning the DESO blockchain technology and using it in our project was hard but we learned a lot about Web3 applications.

## What's next for Full Charge
We hope to continue the integration with this project including automation to detect the charging port and use a robotic arm to plug your car in without the user needing to plug it in.
