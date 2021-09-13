# Okra-Question-2

Question 2 - Creating Logic
Consuming API's is something we do regualarly. Whether it's a banks API to give access or if it's a 3rd party tool to make our internal processes smoother. Your ability to consumer and create API routes is paramount to Okra. Below we have created a fake API to allow you to get started.

POST https://api.okra.ng/v2/mock-api/login {username, password}
POST https://api.okra.ng/v2/mock-api/refresh-wallet {wallet_id, variable: mockVariable} //pass in the mockVariable paramter as variable
GET https://api.okra.ng/v2/mock-api/logout
Requirements
- login using passed variables
- keep store of user's info and wallet
- refresh user's wallet and keep new value
- logout and keep msg sent back
- should ouptu [user's name, user's id, users wallet amount before refreshing as string, users wallet amount after refrshing as string, logout message]