FROM apify/actor-node-playwright:22

COPY package.json ./

RUN npm --quiet set progress=false \
 && npm install --only=prod --no-optional

COPY . ./
