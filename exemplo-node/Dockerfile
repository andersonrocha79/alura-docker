FROM node:latest                
COPY . /var/www                 
ENV NODE-ENV=production         
ENV PORT=3000       
WORKDIR /var/www                
RUN npm install                 
ENTRYPOINT npm start            
EXPOSE $PORT                    

# docker build . -t andersonrocha79/node