# Benefex
The Benefex connector enables seamless data integration between Benifix and other HR or payroll systems, ensuring accurate and up-to-date benefits information across platforms.

## Publisher: Benefex

## Prerequisites
> To access our API, you will need to obtain the necessary credentials that should be delivered by connect api platform
team in individual manner.

Please contact us at: platform@benefex.co

## Supported Operations

- **`Create New User:`** Create a new user on the Benefex platform.

- **`Get Existing Users:`** Get created users at Benefex platform by employee IDs with pagination support.

- **`Update Existing User:`** Update existing user at Benefex platform.

- **`Get Existing User:`** Get created user at Benefex platform.

- **`Get summarized available and eligible-to-add benefits of user:`** Returns current and eligible to add benefits for the requested user.

- **`Get detailed available and eligible-to-add benefits of user:`** Returns details of current and eligible to add benefits for the requested user.

- **`Get user benefit information:`** Returns details of single benefit of the requested user.

More details on the supported operations can be found here "https://docs.onehub.global/bfx-playground/reference/connect_createuser"

## Obtaining Credentials
Make an Api call to the endpoint "https://hub.onehub.global/oauth2/default/v1/token" with an API testing Tool with the query parameters "client_id", "client_secret", "grant_type".

## Known Issues and Limitations
"client_id" and "client_secret" of Benefex platform are manadotory to estabalish connection with connectors.

## API Documentation
Refer to "https://docs.onehub.global/bfx-playground/" 
