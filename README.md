# Facial-Recognition-Lock
When participating in the Global AI Hackathon, my team decided to build a door lock based on facial recognition.
The system was based on an Arduino, a servo lock, the Twilio API, and the Clarifai API.

Our project was heavily inspired by this: https://www.twilio.com/blog/2014/03/build-your-own-lockitron-with-twilio-arduino-and-node-js.html

The goal was to train a facial recognition system using the Clarifai API. A user could then have their face scanned by the system, and if it matched the training set to a certain degree of precision the system would use Twilio to send a message to the Arduino and open the door. If the user failed the facial recognition test, the system would send a message to a phone number with a warning that an unauthorized user was attempting to gain access.

A large portion of the middleware was completed before the end of our 24 hour countdown. Most of this relates to the communication between Twilio and the Arduino.
