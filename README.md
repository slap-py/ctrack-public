# ctrack-public
# By using this service, you understand that your IP may be logged for security purposes.
## How to use callsign tracking.
Firstly, you want to start off by getting the IP, which currently is ``http://ec2-3-84-33-249.compute-1.amazonaws.com:80``. And going to /docs of that. This will give you a GUI that will allow you to put in your information to receive your data.
Click on the one you want to do, for the sake of tutorial we are using /callsigns, a description of each endpoint will be below. Click "try it out" in the top right of the new box, and put in your API Key, which will be provided to you if you are authorized to use it. Next, put in your "acid" (GeoFS User ID) or Callsign, one or the other, one is required. Then, you will say if you want "all", which in this case means if you want every person that has ever used that specific callsign. Click "Execute" and your information will be below titled in a box called "Response Body".



## Endpoints Explained

### /callsigns Endpoint
#### Use
This gets the callsigns previously used by a user.
#### Required Information
API Key (given to you by slappy01#0001 on Discord if requested and accepted, your usage is logged.)
Callsign or Acid (the latest callsign of the person, or their ID, with the exception of all=true then it can be any callsign they have ever used.)
All (returns every user that has ever used the provided callsign, and their previous and current callsigns. This is not applicable for passing in an ID and can be ignored in that case)

### /teleports Endpoint
#### Use
This gets every time the user has teleported, the locations to and from, and the time.

#### Required Information
API Key (given to you by slappy01#0001 on Discord if requested and accepted, your usage is logged.)
Callsign or Acid (the latest callsign of the person, or their ID.)

### /currentinfo Endpoint
#### Use
This gets the users current information (callsign, heading, location, speed, etc)

#### Required Information
API Key (given to you by slappy01#0001 on Discord if requested and accepted, your usage is logged.)
Callsign or Acid (the latest callsign of the person, or their ID.)

# To request access, DM slappy01#0001 on Discord.
