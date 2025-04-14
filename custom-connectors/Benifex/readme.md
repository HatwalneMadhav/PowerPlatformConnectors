# Benifex
The Benifex connector enables seamless data integration between Benifix and other HR or payroll systems, ensuring accurate and up-to-date benefits information across platforms.

## Publisher: HR Copilot

## Prerequisites
> To access the Benifex connector you need client_id and client_secret.

## Supported Operations

- **`GetExistingUsers`**
- *Inputs:* `Body` `employeeIds` `page` `size`
- *HTTP Verb:* `GET`
- *Description:* Get created users at Benifex platform by employee IDs with pagination support.

- **`CreateUser`**
- *Inputs:* `Body` 
- *HTTP Verb:* `POST`
- *Description:* Create a new user on the Benifex platform.

- **`GetExistingUser`**
- *Inputs:* `user-id` 
- *HTTP Verb:* `GET`
- *Description:* Get created user at Benifex platform.

- **`UpdateExistingUser`**
- *Inputs:* `user-id` `Body`
- *HTTP Verb:* `PATCH`
- *Description:* Update existing user at Benifex platform.

- **`GetDetailedAvailableAndEligible-to-addBenefitsOfUser`**
- *Inputs:* `user-id` 
- *HTTP Verb:* `GET`
- *Description:* Returns details of current and eligible to add benefits for the requested user.

- **`GetSummarizedAvailableAndEligible-to-addBenefitsOfUser`**
- *Inputs:* `user-id` 
- *HTTP Verb:* `GET`
- *Description:* Returns current and eligible to add benefits for the requested user.

- **`GetUserBenefitInformation`**
- *Inputs:* `user-id` `benefit-key`
- *HTTP Verb:* `GET`
- *Description:* Returns details of single benefit of the requested user.

## Obtaining Credentials
Make an Api call to the endpoint "https://hub.onehub.global/oauth2/default/v1/token" with an API testing Tool with the query parameters "client_id", "client_secret", "grant_type".

## Known Issues and Limitations
"client_id" and "client_secret" of benifex platform are manadotory to estabalish connection with connectors.

## API Documentation
Refer to "https://docs.onehub.global/bfx-playground/" 

