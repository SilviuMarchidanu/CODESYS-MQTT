# CODESYS-MQTT
MQTT client for CODESYS

# NEW Example!
- please have a look in the GreatExampleOfAdvantages!
- it runs out of the box with test.mosquitto.org
- there look into MyProperty programm
- it shows you how to never ever again tipp any topic in you program!
- have fun!!!

# NEWS
- 64bit support, but you need to enable dynamic memory allocation
- much faster testHighReciveSplitPayload() works with nearly 600 sends, recives per second!

# subscription now works with new approach

- now is done with callbacks
- see the TestMQTTGithubInterfaceExampleTopicAndPayload examples, there you can see the benefits.
You can publish direkt to the instance and variable name, and the lib is doing the rest
have fun!

# Dependencies

all needed Libraries can be found at
  
  https://github.com/stefandreyer

# Features
- all QoS Levels for publish and subscribe
- will topic
- retain option for publish and will topic
- unlimited publish FBs(by library)
- unlimited subscribe FBs(by library)
- TLS support(without certificates)
- FBs for easy transmit of values and states
- nice collection FB for collecting subscription FBs
- usefull FBs for callbacks, for list use too

# New value FB

created an new FB for easy publishing Values to broker

# New Stats FB

created new FB for easy publishing stats(on/off, true/false) to broker

# Will topic

will topic is now build with client id

# Examples

nice example projets for Windows and RaspberryPi with and without TLS using test.mosquitto.org, so no own broker needed


