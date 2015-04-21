# starlink.deploy
mup deployment script

#### Install mup:
    // https://github.com/arunoda/meteor-up
    npm install -g mup

#### Change app location in mup.json accordingly:
      // Location of app (local directory)
    "app": "../starlink",

#### Setup Meteor on starlink.io server
    mup setup

#### Deploy starlink application to starlink.io server
    mup deploy

#### Other mup commands
    mup reconfig
    mup logs -f
    mup start
    mup stop
    mup restart

#### SSH to starlink.io server
    chmod 400 StarLinkDev.pem
    ssh -i StarLinkDev.pem ubuntu@istartups.io

