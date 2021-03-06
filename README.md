# Node Typescript Template

Basic node template using rollup to output ts -> js.   
Project is setup for a basic express server with passport and mongo. 
Delete packages as needed. 

#### Current Dependencies

**package.json**

```json
{
  "name": "node-typescript-template",
  "version": "1.0.0",
  "description": "",
  "main": "./output/bundle.js",
  "scripts": {
    "bundle": "npm install && npx rollup -c rollup.config.js",
    "start": "cd output && node bundle.js"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "devDependencies": {
    "@rollup/plugin-typescript": "^8.2.1",
    "@types/bcrypt": "^5.0.0",
    "@types/cors": "^2.8.10",
    "@types/dotenv": "^8.2.0",
    "@types/express": "^4.17.12",
    "@types/express-session": "^1.17.3",
    "@types/node": "^15.6.1",
    "@types/passport-local": "^1.0.33",
    "ts-loader": "^9.2.2",
    "tslib": "^2.2.0",
    "typescript": "^4.3.2"
  },
  "dependencies": {
    "axios": "^0.21.1",
    "bcrypt": "^5.0.1",
    "connect-mongo": "^4.4.1",
    "cors": "^2.8.5",
    "dotenv": "^10.0.0",
    "express": "^4.17.1",
    "express-session": "^1.17.2",
    "mongodb": "^3.6.9",
    "mongoose": "^5.13.0",
    "passport": "^0.4.1",
    "passport-local": "^1.0.0",
    "passport-local-mongoose": "^6.1.0",
    "passport-oauth": "^1.0.0"
  }
}
```
