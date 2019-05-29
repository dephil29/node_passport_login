There should also be a file in the config dir called 'keys.js' that has an object exported with the key to that object as 'MongoURI' and the value as the address of a mongodb db. Like so:

  module.exports = {
    MongoURI: 'super secret uri to your mongodb db'
  }
