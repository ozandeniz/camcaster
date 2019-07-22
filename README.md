# camcaster

Peer to peer webcam app

- Each customer will have an unique id
  - During first page load we will create session key and store it as cookie
  - Customer will use this session key to communicate with other customers
- Customer does not need any session. This means customer does not need to sign up. 
- We will use WebRTC (See: https://developer.mozilla.org/en-US/docs/Web/API/WebRTC_API)

# setup 

npm install
npm start
