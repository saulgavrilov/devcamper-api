# DevCamper API

## Usage

Create config.env file in config folder & update the values/settings to your own

```env
NODE_ENV=development
PORT=5000

MONGO_URI=

GEOCODER_PROVIDER=mapquest
GEOCODER_API_KEY=

FILE_UPLOAD_PATH= ./public/uploads
MAX_FILE_UPLOAD=1000000

JWT_SECRET=
JWT_EXPIRE=30d
JWT_COOKIE_EXPIRE=30

SMTP_HOST=smtp.mailtrap.io
SMTP_PORT=2525
SMTP_EMAIL=
SMTP_PASSWORD=
FROM_EMAIL=
FROM_NAME=
```

## Install Dependencies

```
npm install
```

## Run App
```
# Run in dev mode
npm run dev

# Run in prod mode
npm start
```

## Database Seeder

To seed the database with users, bootcamps, courses and reviews with data from the "_data" folder, run

```
# Destroy all data
node seeder -d

# Import all data
node seeder -i
```
