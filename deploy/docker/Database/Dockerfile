# FROM mongo

# # MAINTAINER juliens@microsoft.com

# COPY drop/* /tmp/

# CMD ["mongod", "--smallfiles", "--rest"]
FROM mongo:3.4 
COPY drop/* usr/local/data/db/ 
CMD ["mongod", "--smallfiles", "--rest"]