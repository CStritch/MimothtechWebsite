# This requires two servers to run
# - Angular server to run web page on port 4200 (docker still in construction)
# - - while in angular folder, run command inc full stop: docker build -t angular-website .

# - Data server on port 3000 to show nodes database. build and run in /data (finished docker)
# - This uses
# - - docker build -t json-database .
# - - docker run -d -p 3000:3000 --name home-data json-database
#
## objectives##
##
## - Create website
## - modify CSS to be business colours
## - modify javascript/typescript to convert CSV to nodes
## - present builds based on features of computer builds 
## - - Price
## - - availability
## - - Other
## - seek other functionality as required.
##
##
## Current tasks ##
##
## - create docker to represent web server for client
## - server setup for data (basics set up, interface for back-end update)
## - Create web application backend (hidden from public, password protected?)
## - - Web application for dev/client to update database
## - - - function: add stock
## - - - function: delete stock (Hide?)
## - - Web application for dev/client to build computer with stock parts
## - - - function: Add build
## - - - - Choose components (to match stock available)
## - - - function: delete build (Hide?)
## - - - - have exception if stock is deleted to note not available
##
## - Layout of website is to be landing page followed by functions
## - - Computer builds
## - - Stock available
## - - 
##
##
## ----- Depreciated information ----- ##
## when copying from one location to another (i.e. pull) ##
## Need to do the following commands:
## npm install
## npm install -g json-server
## ng serve (starts up application at http://localhost:4200)


## json-server --watch db.json (starts up server to read json file at http://localhose:3000)

## Good luck! This is the basic angular tutorial completed with customisations.