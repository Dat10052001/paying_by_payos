# Instructions
## Requirements
* Created [payOS](https://my.payos.vn) payment channel
## Run project
Rename the file `.env.example` to a file named `.env`.

Fill in the fields `PAYOS_CLIENT_ID`, `PAYOS_API_KEY`, `PAYOS_CHECKSUM_KEY` which are in the file named `.env` with the payment channel information you created on payOS.

Run following commands:
```bash
npm i
npm start
```

After NodeJS project started, visit http://localhost:3030 to access the demo page using payOS payment method implemented in NodeJS.




