# coj160-install-starter

# ติดตั้ง Node.js 
`ดาวน์โหลด >>` https://nodejs.org/en/download/

# ติดตั้ง `yarn`
```sh
# Install with npm
npm install --global yarn

# Check version
yarn --version
```

# ติดตั้ง Nest.js
```sh
# 1. ติดตั้งด้วย npm
yarn global add @nestjs/cli

# 2. ตรวจสอบว่าติดตั้งเรียบร้อยหรือไม่
nest --version
```

# ติดตั้ง Vue.js
```sh
yarn global add @vue/cli
```

# ติดตั้ง API
```sh
git clone https://[Your Github Access Token]:github.com/midnighttime-cha/coj160-migration-api.git api
cd api
yarn install
yarn start
```

# ติดตั้ง Back Office
```sh
git clone https://[Your Github Access Token]:github.com/midnighttime-cha/coj160-migration-office.git office
cd office
yarn install
yarn dev --open
```
