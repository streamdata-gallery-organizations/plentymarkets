---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Get all posting accounts by locationId and type
  description: Get all posting accounts by locationid and type.
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /export/{exportKey}:
    get:
      summary: Get Export Keys
      description: Get export keys.
      operationId: getExportExportkey
      x-api-path-slug: exportexportkey-get
      parameters:
      - in: path
        name: exportKey
      responses:
        200:
          description: OK
      tags:
      - Keys
  /export/{exportKey}/{token}:
    get:
      summary: Get Export Key
      description: Get export keys..
      operationId: getExportExportkeyToken
      x-api-path-slug: exportexportkeytoken-get
      parameters:
      - in: path
        name: exportKey
      - in: path
        name: token
      responses:
        200:
          description: OK
      tags:
      - Keys
  /rest/account/login:
    post:
      summary: Login
      description: Logs in to the online store with front end user credentials. The
        login call returns a JSON object that contains information, such as the access
        token and the refresh token.
      operationId: postRestAccountLogin
      x-api-path-slug: restaccountlogin-post
      parameters:
      - in: body
        name: /rest/account/login
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Login
  /rest/account/login/refresh:
    post:
      summary: Refresh
      description: Refreshes the access token using the refresh token. The refresh
        token is part of the login call response.
      operationId: postRestAccountLoginRefresh
      x-api-path-slug: restaccountloginrefresh-post
      responses:
        200:
          description: OK
      tags:
      - Refresh
  /rest/account/logout:
    post:
      summary: Logout
      description: Logs out the front end user from the online store. The access token
        expires.
      operationId: postRestAccountLogout
      x-api-path-slug: restaccountlogout-post
      responses:
        200:
          description: OK
      tags:
      - Logout
  /rest/accounting/locations:
    post:
      summary: Create an accounting location
      description: Creates an accounting location for a client. The plenty ID of the
        client must be specified.
      operationId: postRestAccountingLocations
      x-api-path-slug: restaccountinglocations-post
      parameters:
      - in: body
        name: /rest/accounting/locations
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Accounting
      - Location
  /rest/accounting/locations/existing_accounts:
    get:
      summary: Get all unique posting accounts
      description: Get all unique posting accounts.
      operationId: getRestAccountingLocationsExistingAccounts
      x-api-path-slug: restaccountinglocationsexisting-accounts-get
      responses:
        200:
          description: OK
      tags:
      - Unique
      - Posting
      - Accounts
  /rest/accounting/locations/posting_accounts:
    get:
      summary: Get all posting accounts
      description: Get all posting accounts.
      operationId: getRestAccountingLocationsAddingAccounts
      x-api-path-slug: restaccountinglocationsposting-accounts-get
      responses:
        200:
          description: OK
      tags:
      - Posting
      - Accounts
    post:
      summary: Save posting accounts
      description: Save posting accounts.
      operationId: postRestAccountingLocationsAddingAccounts
      x-api-path-slug: restaccountinglocationsposting-accounts-post
      responses:
        200:
          description: OK
      tags:
      - Save
      - Posting
      - Accounts
  /rest/accounting/locations/posting_accounts/{id}:
    delete:
      summary: Delete an posting account
      description: Delete an posting account.
      operationId: deleteRestAccountingLocationsAddingAccounts
      x-api-path-slug: restaccountinglocationsposting-accountsid-delete
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Posting
      - Account
    get:
      summary: Gets posting account by the unique id
      description: Gets posting account by the unique id.
      operationId: getRestAccountingLocationsAddingAccounts
      x-api-path-slug: restaccountinglocationsposting-accountsid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - S
      - Posting
      - Account
      - By
      - Unique
      - Id
  /rest/accounting/locations/revenue_account_configurations:
    get:
      summary: List revenue account configurations
      description: Lists revenue account configurations of a system. The revenue accounts
        are returned as paginated result. By default 50 revenue accounts are on one
        page.
      operationId: getRestAccountingLocationsRevenueAccountConfigurations
      x-api-path-slug: restaccountinglocationsrevenue-account-configurations-get
      parameters:
      - in: query
        name: itemsPerPage
        description: The number of revenue accounts to be displayed per page
      - in: query
        name: page
        description: The page to get
      responses:
        200:
          description: OK
      tags:
      - List
      - Revenue
      - Account
      - Configurations
  /rest/accounting/locations/{locationId}:
    delete:
      summary: Delete an accounting location
      description: Deletes an accounting location. The ID of the accounting location
        must be specified. Standard accounting locations can not be deleted.
      operationId: deleteRestAccountingLocationsLocation
      x-api-path-slug: restaccountinglocationslocationid-delete
      parameters:
      - in: path
        name: locationId
      responses:
        200:
          description: OK
      tags:
      - Accounting
      - Location
    get:
      summary: Get an accounting location
      description: Gets an accounting location. The ID of the accounting location
        must be specified.
      operationId: getRestAccountingLocationsLocation
      x-api-path-slug: restaccountinglocationslocationid-get
      parameters:
      - in: path
        name: locationId
      responses:
        200:
          description: OK
      tags:
      - Accounting
      - Location
    put:
      summary: Update an accounting location
      description: Updates an accounting location. The ID of the accounting location
        must be specified.
      operationId: putRestAccountingLocationsLocation
      x-api-path-slug: restaccountinglocationslocationid-put
      parameters:
      - in: body
        name: /rest/accounting/locations/{locationId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: locationId
      responses:
        200:
          description: OK
      tags:
      - Accounting
      - Location
  /rest/accounting/locations/{locationId}/countries/{countryId}/revenue_accounts:
    get:
      summary: Get the revenue account configuration of a country
      description: Get the revenue account configuration of a country. The ID of the
        accounting location that the country is associated with as well as the ID
        of the country must be specified.
      operationId: getRestAccountingLocationsLocationCountriesCountryRevenueAccounts
      x-api-path-slug: restaccountinglocationslocationidcountriescountryidrevenue-accounts-get
      parameters:
      - in: path
        name: countryId
      - in: path
        name: locationId
      responses:
        200:
          description: OK
      tags:
      - Revenue
      - Account
      - Configuration
      - Of
      - Country
  /rest/accounting/locations/{locationId}/debtor_account_configurations:
    get:
      summary: Get debtor account configuration of an accounting location
      description: Gets the debtor account configuration of an accounting location.
        The ID of the accounting location has to be specified. The debtor account
        configuration can contain one standard debtor account only or e.g. several
        accounts for each country of delivery.
      operationId: getRestAccountingLocationsLocationDebtorAccountConfigurations
      x-api-path-slug: restaccountinglocationslocationiddebtor-account-configurations-get
      parameters:
      - in: path
        name: locationId
      responses:
        200:
          description: OK
      tags:
      - Debtor
      - Account
      - Configuration
      - Of
      - Accounting
      - Location
  /rest/accounting/locations/{locationId}/debtor_accounts/{mode}:
    get:
      summary: Lists the debtor accounts by mode.
      description: Lists the debtor accounts of an accounting location by mode. The
        ID of the accounting location and the mode have to be specified.
      operationId: getRestAccountingLocationsLocationDebtorAccountsMode
      x-api-path-slug: restaccountinglocationslocationiddebtor-accountsmode-get
      parameters:
      - in: path
        name: locationId
      - in: path
        name: mode
      responses:
        200:
          description: OK
      tags:
      - Lists
      - Debtor
      - Accounts
      - By
      - Mode
  /rest/accounting/locations/{locationId}/posting_accounts:
    get:
      summary: Get all posting accounts by locationId
      description: Get all posting accounts by locationid.
      operationId: getRestAccountingLocationsLocationAddingAccounts
      x-api-path-slug: restaccountinglocationslocationidposting-accounts-get
      parameters:
      - in: path
        name: locationId
      responses:
        200:
          description: OK
      tags:
      - Posting
      - Accounts
      - By
      - LocationId
  /rest/accounting/locations/{locationId}/posting_key_configurations:
    get:
      summary: Get a posting key configuration of an accounting location
      description: Gets a posting key configuration of an accounting location. The
        ID of the accounting location has to be specified. The posting key configuration
        can contain up to 4 posting keys.
      operationId: getRestAccountingLocationsLocationAddingKeyConfigurations
      x-api-path-slug: restaccountinglocationslocationidposting-key-configurations-get
      parameters:
      - in: path
        name: locationId
      responses:
        200:
          description: OK
      tags:
      - Posting
      - Key
      - Configuration
      - Of
      - Accounting
      - Location
  /rest/accounting/locations/{locationId}/revenue_account_configurations:
    get:
      summary: Get the revenue account configuration of an accounting location
      description: Gets the revenue account configuration of an accounting location.
        A revenue account location configuration contains several revenue accounts.
        The ID of the accounting location has to be specified.
      operationId: getRestAccountingLocationsLocationRevenueAccountConfigurations
      x-api-path-slug: restaccountinglocationslocationidrevenue-account-configurations-get
      parameters:
      - in: path
        name: locationId
      responses:
        200:
          description: OK
      tags:
      - Revenue
      - Account
      - Configuration
      - Of
      - Accounting
      - Location
  /rest/accounting/locations/{locationId}/{type}/posting_accounts:
    get:
      summary: Get all posting accounts by locationId and type
      description: Get all posting accounts by locationid and type.
      operationId: getRestAccountingLocationsLocationTypeAddingAccounts
      x-api-path-slug: restaccountinglocationslocationidtypeposting-accounts-get
      parameters:
      - in: path
        name: locationId
      - in: path
        name: type
      responses:
        200:
          description: OK
      tags:
      - Posting
      - Accounts
      - By
      - LocationId
      - Type
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---