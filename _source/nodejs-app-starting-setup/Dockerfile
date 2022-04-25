# Start from image of node
FROM node

WORKDIR /apt

COPY . /app

# running npm install for install server
RUN npm install 

# this way in incorrect
# RUN node server.js


# For container knows that when running this -> would be run on port of 80
# Syntax: EXPOSE `port
EXPOSE 80

# correct way
# syntax: CMD ["Executed", "params", ...]
CMD ["node", "server.js"]