---
name: Plentymarkets
x-slug: plentymarkets
description: plentymarkets is an all-in-one e-commerce ERP solution, which combines
  a comprehensive stock management system with a versatile shop system and effortless
  multichannel sales. Thanks to comprehensive functions and interfaces that include
  all steps of the e-commerce value chain, you can use the cloud based software to
  completely automate all of your e-business processes as well as your companys own
  individual processes.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
x-kinRank: "7"
x-alexaRank: ""
tags: Plentymarkets
created: "2018-08-30"
modified: "2018-08-30"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/apis.md
specificationVersion: "0.14"
apis:
- name: plentymarkets REST-API - Get Export Keys
  x-api-slug: exportexportkey-get
  description: Get export keys.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/exportexportkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/exportexportkey-get-openapi.md
- name: plentymarkets REST-API - Get Export Key
  x-api-slug: exportexportkeytoken-get
  description: Get export keys..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/exportexportkeytoken-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/exportexportkeytoken-get-openapi.md
- name: plentymarkets REST-API - Login
  x-api-slug: restaccountlogin-post
  description: Logs in to the online store with front end user credentials. The login
    call returns a JSON object that contains information, such as the access token
    and the refresh token.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountlogin-post-openapi.md
- name: plentymarkets REST-API - Refresh
  x-api-slug: restaccountloginrefresh-post
  description: Refreshes the access token using the refresh token. The refresh token
    is part of the login call response.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountloginrefresh-post-openapi.md
- name: plentymarkets REST-API - Logout
  x-api-slug: restaccountlogout-post
  description: Logs out the front end user from the online store. The access token
    expires.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountlogout-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountlogout-post-openapi.md
- name: plentymarkets REST-API - Create an accounting location
  x-api-slug: restaccountinglocations-post
  description: Creates an accounting location for a client. The plenty ID of the client
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountinglocations-post-openapi.md
- name: plentymarkets REST-API - Get all unique posting accounts
  x-api-slug: restaccountinglocationsexisting-accounts-get
  description: Get all unique posting accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountinglocationsexisting-accounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountinglocationsexisting-accounts-get-openapi.md
- name: plentymarkets REST-API - Get all posting accounts
  x-api-slug: restaccountinglocationsposting-accounts-get
  description: Get all posting accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountinglocationsposting-accounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountinglocationsposting-accounts-get-openapi.md
- name: plentymarkets REST-API - Save posting accounts
  x-api-slug: restaccountinglocationsposting-accounts-post
  description: Save posting accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountinglocationsposting-accounts-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountinglocationsposting-accounts-post-openapi.md
- name: plentymarkets REST-API - Delete an posting account
  x-api-slug: restaccountinglocationsposting-accountsid-delete
  description: Delete an posting account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountinglocationsposting-accountsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountinglocationsposting-accountsid-delete-openapi.md
- name: plentymarkets REST-API - Gets posting account by the unique id
  x-api-slug: restaccountinglocationsposting-accountsid-get
  description: Gets posting account by the unique id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountinglocationsposting-accountsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountinglocationsposting-accountsid-get-openapi.md
- name: plentymarkets REST-API - List revenue account configurations
  x-api-slug: restaccountinglocationsrevenue-account-configurations-get
  description: Lists revenue account configurations of a system. The revenue accounts
    are returned as paginated result. By default 50 revenue accounts are on one page.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountinglocationsrevenue-account-configurations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountinglocationsrevenue-account-configurations-get-openapi.md
- name: plentymarkets REST-API - Delete an accounting location
  x-api-slug: restaccountinglocationslocationid-delete
  description: Deletes an accounting location. The ID of the accounting location must
    be specified. Standard accounting locations can not be deleted.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountinglocationslocationid-delete-openapi.md
- name: plentymarkets REST-API - Get an accounting location
  x-api-slug: restaccountinglocationslocationid-get
  description: Gets an accounting location. The ID of the accounting location must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountinglocationslocationid-get-openapi.md
- name: plentymarkets REST-API - Update an accounting location
  x-api-slug: restaccountinglocationslocationid-put
  description: Updates an accounting location. The ID of the accounting location must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountinglocationslocationid-put-openapi.md
- name: plentymarkets REST-API - Get the revenue account configuration of a country
  x-api-slug: restaccountinglocationslocationidcountriescountryidrevenue-accounts-get
  description: Get the revenue account configuration of a country. The ID of the accounting
    location that the country is associated with as well as the ID of the country
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountinglocationslocationidcountriescountryidrevenue-accounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountinglocationslocationidcountriescountryidrevenue-accounts-get-openapi.md
- name: plentymarkets REST-API - Get debtor account configuration of an accounting
    location
  x-api-slug: restaccountinglocationslocationiddebtor-account-configurations-get
  description: Gets the debtor account configuration of an accounting location. The
    ID of the accounting location has to be specified. The debtor account configuration
    can contain one standard debtor account only or e.g. several accounts for each
    country of delivery.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountinglocationslocationiddebtor-account-configurations-get-openapi.md
- name: plentymarkets REST-API - Lists the debtor accounts by mode.
  x-api-slug: restaccountinglocationslocationiddebtor-accountsmode-get
  description: Lists the debtor accounts of an accounting location by mode. The ID
    of the accounting location and the mode have to be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountinglocationslocationiddebtor-accountsmode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountinglocationslocationiddebtor-accountsmode-get-openapi.md
- name: plentymarkets REST-API - Get all posting accounts by locationId
  x-api-slug: restaccountinglocationslocationidposting-accounts-get
  description: Get all posting accounts by locationid.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountinglocationslocationidposting-accounts-get-openapi.md
- name: plentymarkets REST-API - Get a posting key configuration of an accounting
    location
  x-api-slug: restaccountinglocationslocationidposting-key-configurations-get
  description: Gets a posting key configuration of an accounting location. The ID
    of the accounting location has to be specified. The posting key configuration
    can contain up to 4 posting keys.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountinglocationslocationidposting-key-configurations-get-openapi.md
- name: plentymarkets REST-API - Get the revenue account configuration of an accounting
    location
  x-api-slug: restaccountinglocationslocationidrevenue-account-configurations-get
  description: Gets the revenue account configuration of an accounting location. A
    revenue account location configuration contains several revenue accounts. The
    ID of the accounting location has to be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountinglocationslocationidrevenue-account-configurations-get-openapi.md
- name: plentymarkets REST-API - Get all posting accounts by locationId and type
  x-api-slug: restaccountinglocationslocationidtypeposting-accounts-get
  description: Get all posting accounts by locationid and type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountinglocationslocationidtypeposting-accounts-get-openapi.md
- name: plentymarkets REST-API - Get all posting accounts for a country of a webstore
  x-api-slug: restaccountinglocationswebstoreidcountryidposting-accounts-get
  description: Get all posting accounts for a country of a webstore.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountinglocationswebstoreidcountryidposting-accounts-get-openapi.md
- name: plentymarkets REST-API - List all accounting locations
  x-api-slug: restaccountingstoreslocations-get
  description: List all accounting locations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountingstoreslocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountingstoreslocations-get-openapi.md
- name: plentymarkets REST-API - List accounting locations of a client
  x-api-slug: restaccountingstoresplentyidlocations-get
  description: Lists accounting locations of a client. The plenty ID of the client
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountingstoresplentyidlocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountingstoresplentyidlocations-get-openapi.md
- name: plentymarkets REST-API - List accounts
  x-api-slug: restaccounts-get
  description: List accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccounts-get-openapi.md
- name: plentymarkets REST-API - Create an account
  x-api-slug: restaccounts-post
  description: Create an account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccounts-post-openapi.md
- name: plentymarkets REST-API - Create an address
  x-api-slug: restaccountsaddresses-post
  description: Create an address.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaddresses-post-openapi.md
- name: plentymarkets REST-API - List address contact relations
  x-api-slug: restaccountsaddressescontact-relations-get
  description: List address contact relations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaddressescontact-relations-get-openapi.md
- name: plentymarkets REST-API - Create address contact relations
  x-api-slug: restaccountsaddressescontact-relations-post
  description: Create address contact relations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaddressescontact-relations-post-openapi.md
- name: plentymarkets REST-API - Update address contact relations
  x-api-slug: restaccountsaddressescontact-relations-put
  description: Update address contact relations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaddressescontact-relations-put-openapi.md
- name: plentymarkets REST-API - Delete an address contact relation
  x-api-slug: restaccountsaddressescontact-relationsaddresscontactrelationid-delete
  description: Deletes an address contact relation. The ID of the relation must be
    specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaddressescontact-relationsaddresscontactrelationid-delete-openapi.md
- name: plentymarkets REST-API - Get an address contact relation
  x-api-slug: restaccountsaddressescontact-relationsaddresscontactrelationid-get
  description: Gets an address contact relation. The ID of the address contact relation
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaddressescontact-relationsaddresscontactrelationid-get-openapi.md
- name: plentymarkets REST-API - List address option types
  x-api-slug: restaccountsaddressesoption-types-get
  description: List address option types.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaddressesoption-types-get-openapi.md
- name: plentymarkets REST-API - Create an address option type
  x-api-slug: restaccountsaddressesoption-types-post
  description: Create an address option type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaddressesoption-types-post-openapi.md
- name: plentymarkets REST-API - Delete an address option type
  x-api-slug: restaccountsaddressesoption-typesoptiontypeid-delete
  description: Deletes an address option type. The ID of the option type must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaddressesoption-typesoptiontypeid-delete-openapi.md
- name: plentymarkets REST-API - Get an address option type
  x-api-slug: restaccountsaddressesoption-typesoptiontypeid-get
  description: Gets an address option type. The ID of the option type must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaddressesoption-typesoptiontypeid-get-openapi.md
- name: plentymarkets REST-API - Update an address option type
  x-api-slug: restaccountsaddressesoption-typesoptiontypeid-put
  description: Updates an address option type. The ID of the option type must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaddressesoption-typesoptiontypeid-put-openapi.md
- name: plentymarkets REST-API - Delete an address option by the option ID
  x-api-slug: restaccountsaddressesoptionsoptionid-delete
  description: Deletes an address option. The ID of the option must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaddressesoptionsoptionid-delete-openapi.md
- name: plentymarkets REST-API - Get an address option
  x-api-slug: restaccountsaddressesoptionsoptionid-get
  description: Gets an address option. The ID of the option must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaddressesoptionsoptionid-get-openapi.md
- name: plentymarkets REST-API - Update an address option
  x-api-slug: restaccountsaddressesoptionsoptionid-put
  description: Updates an address option. The ID of the option must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaddressesoptionsoptionid-put-openapi.md
- name: plentymarkets REST-API - List address POS relations
  x-api-slug: restaccountsaddressespos-relations-get
  description: List address pos relations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaddressespos-relations-get-openapi.md
- name: plentymarkets REST-API - Create an address POS relation
  x-api-slug: restaccountsaddressespos-relations-post
  description: Create an address pos relation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaddressespos-relations-post-openapi.md
- name: plentymarkets REST-API - Delete an address POS relation
  x-api-slug: restaccountsaddressespos-relationsaddressposrelationid-delete
  description: Deletes an address POS relation. The ID of the address POS relation
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaddressespos-relationsaddressposrelationid-delete-openapi.md
- name: plentymarkets REST-API - Get an address POS relation
  x-api-slug: restaccountsaddressespos-relationsaddressposrelationid-get
  description: Gets an address POS relation. The ID of the address POS relation must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaddressespos-relationsaddressposrelationid-get-openapi.md
- name: plentymarkets REST-API - Update an address POS relation
  x-api-slug: restaccountsaddressespos-relationsaddressposrelationid-put
  description: Updates an address POS relation. The ID of the address POS relation
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaddressespos-relationsaddressposrelationid-put-openapi.md
- name: plentymarkets REST-API - List address relation types
  x-api-slug: restaccountsaddressesrelation-types-get
  description: List address relation types.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaddressesrelation-types-get-openapi.md
- name: plentymarkets REST-API - List address relation types
  x-api-slug: restaccountsaddressesrelationstypesapplicationsapplicationlang-get
  description: |-
    Lists address relation types. The application and the language must be specified.
    <br>Possible applications:
    <ul>
    <li>contact</li>
    <li>order</li>
    <li>warehouse</li>
    <li>pos</li>
    </ul>
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaddressesrelationstypesapplicationsapplicationlang-get-openapi.md
- name: plentymarkets REST-API - Create an address warehouse relation
  x-api-slug: restaccountsaddresseswarehouse-relations-post
  description: Create an address warehouse relation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaddresseswarehouse-relations-post-openapi.md
- name: plentymarkets REST-API - Delete an address warehouse relation
  x-api-slug: restaccountsaddresseswarehouse-relationsrelationid-delete
  description: Deletes an address warehouse relation. The ID of the relation must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaddresseswarehouse-relationsrelationid-delete-openapi.md
- name: plentymarkets REST-API - Update an address warehouse relation
  x-api-slug: restaccountsaddresseswarehouse-relationsrelationid-put
  description: Updates an address warehouse relation. The ID of the relation must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaddresseswarehouse-relationsrelationid-put-openapi.md
- name: plentymarkets REST-API - Delete an address
  x-api-slug: restaccountsaddressesaddressid-delete
  description: Deletes an address. The ID of the address must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaddressesaddressid-delete-openapi.md
- name: plentymarkets REST-API - Get an address
  x-api-slug: restaccountsaddressesaddressid-get
  description: Gets an address. The ID of the address must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaddressesaddressid-get-openapi.md
- name: plentymarkets REST-API - Update an address
  x-api-slug: restaccountsaddressesaddressid-put
  description: Updates an address. The ID of the address must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaddressesaddressid-put-openapi.md
- name: plentymarkets REST-API - Delete an address option by the address ID
  x-api-slug: restaccountsaddressesaddressidoptions-delete
  description: Deletes an address option. The ID of the address must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaddressesaddressidoptions-delete-openapi.md
- name: plentymarkets REST-API - List address options
  x-api-slug: restaccountsaddressesaddressidoptions-get
  description: Lists address options. The ID of the address must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaddressesaddressidoptions-get-openapi.md
- name: plentymarkets REST-API - Create an address option
  x-api-slug: restaccountsaddressesaddressidoptions-post
  description: Creates an address option. The ID of the address must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaddressesaddressidoptions-post-openapi.md
- name: plentymarkets REST-API - Update the address options for an address
  x-api-slug: restaccountsaddressesaddressidoptions-put
  description: Update the address options for an address.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaddressesaddressidoptions-put-openapi.md
- name: plentymarkets REST-API - Find address data by address id
  x-api-slug: restaccountsaddressesaddressidrelated-data-get
  description: Find address data by address id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaddressesaddressidrelated-data-get-openapi.md
- name: plentymarkets REST-API - Deletes an account contact relation. The ID of the
    account contact relation must be specified.
  x-api-slug: restaccountscontact-relationsaccountcontactrelationid-delete
  description: Deletes an account contact relation. the id of the account contact
    relation must be specified..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontact-relationsaccountcontactrelationid-delete-openapi.md
- name: plentymarkets REST-API - Gets an account contact releation. The ID of the
    account contact relation must be specified.
  x-api-slug: restaccountscontact-relationsaccountcontactrelationid-get
  description: Gets an account contact releation. the id of the account contact relation
    must be specified..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontact-relationsaccountcontactrelationid-get-openapi.md
- name: plentymarkets REST-API - List contacts
  x-api-slug: restaccountscontacts-get
  description: List contacts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontacts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontacts-get-openapi.md
- name: plentymarkets REST-API - Create a contact
  x-api-slug: restaccountscontacts-post
  description: Create a contact.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontacts-post-openapi.md
- name: plentymarkets REST-API - Create a bank account
  x-api-slug: restaccountscontactsbanks-post
  description: Create a bank account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactsbanks-post-openapi.md
- name: plentymarkets REST-API - Delete a bank account
  x-api-slug: restaccountscontactsbankscontactbankid-delete
  description: Deletes a bank account. The ID of the bank account must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactsbankscontactbankid-delete-openapi.md
- name: plentymarkets REST-API - Get a bank account
  x-api-slug: restaccountscontactsbankscontactbankid-get
  description: Gets a bank account of the contact. The ID of the bank account must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactsbankscontactbankid-get-openapi.md
- name: plentymarkets REST-API - Update a bank account
  x-api-slug: restaccountscontactsbankscontactbankid-put
  description: Updates a bank account. The ID of the bank account must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactsbankscontactbankid-put-openapi.md
- name: plentymarkets REST-API - List contact classes
  x-api-slug: restaccountscontactsclasses-get
  description: List contact classes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactsclasses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactsclasses-get-openapi.md
- name: plentymarkets REST-API - Get a contact class
  x-api-slug: restaccountscontactsclassescontactclassid-get
  description: Gets a contact class. The ID of the contact class must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactsclassescontactclassid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactsclassescontactclassid-get-openapi.md
- name: plentymarkets REST-API - List contact events
  x-api-slug: restaccountscontactscontact-events-get
  description: Lists contact events.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontact-events-get-openapi.md
- name: plentymarkets REST-API - Create a contact event
  x-api-slug: restaccountscontactscontact-events-post
  description: Creates a contact event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontact-events-post-openapi.md
- name: plentymarkets REST-API - Delete a contact event
  x-api-slug: restaccountscontactscontact-eventscontacteventid-delete
  description: Deletes a contact event. The ID of the contact event must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontact-eventscontacteventid-delete-openapi.md
- name: plentymarkets REST-API - Update a contact event
  x-api-slug: restaccountscontactscontact-eventscontacteventid-put
  description: Updates a contact event. The ID of the contact event must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontact-eventscontacteventid-put-openapi.md
- name: plentymarkets REST-API - List contact departments
  x-api-slug: restaccountscontactsdepartments-get
  description: List contact departments.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactsdepartments-get-openapi.md
- name: plentymarkets REST-API - Create a contact department
  x-api-slug: restaccountscontactsdepartments-post
  description: Create a contact department.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactsdepartments-post-openapi.md
- name: plentymarkets REST-API - Delete a contact department
  x-api-slug: restaccountscontactsdepartmentsdepartmentid-delete
  description: Deletes a contact department. The ID of the department must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactsdepartmentsdepartmentid-delete-openapi.md
- name: plentymarkets REST-API - Get a contact department
  x-api-slug: restaccountscontactsdepartmentsdepartmentid-get
  description: Gets a contact department. The ID of the department must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactsdepartmentsdepartmentid-get-openapi.md
- name: plentymarkets REST-API - Update a contact department
  x-api-slug: restaccountscontactsdepartmentsdepartmentid-put
  description: Updates a contact department. The ID of the department must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactsdepartmentsdepartmentid-put-openapi.md
- name: plentymarkets REST-API - List all group function related data
  x-api-slug: restaccountscontactsgroup-functions-get
  description: Lists all data that is related to the contact group function contents.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactsgroup-functions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactsgroup-functions-get-openapi.md
- name: plentymarkets REST-API - Apply selected group function options for given contact
    IDs
  x-api-slug: restaccountscontactsgroup-functions-post
  description: Applies selected group function options for given contact IDs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactsgroup-functions-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactsgroup-functions-post-openapi.md
- name: plentymarkets REST-API - List contact option sub-types
  x-api-slug: restaccountscontactsoption-sub-types-get
  description: List contact option sub-types.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactsoption-sub-types-get-openapi.md
- name: plentymarkets REST-API - Create a contact option sub-type
  x-api-slug: restaccountscontactsoption-sub-types-post
  description: Create a contact option sub-type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactsoption-sub-types-post-openapi.md
- name: plentymarkets REST-API - Delete a contact option sub-type
  x-api-slug: restaccountscontactsoption-sub-typesoptionsubtypeid-delete
  description: Deletes a contact option sub-type. The ID of the option sub-type must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactsoption-sub-typesoptionsubtypeid-delete-openapi.md
- name: plentymarkets REST-API - Get a contact option sub-type
  x-api-slug: restaccountscontactsoption-sub-typesoptionsubtypeid-get
  description: Gets a contact option sub-type. The ID of the option sub-type must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactsoption-sub-typesoptionsubtypeid-get-openapi.md
- name: plentymarkets REST-API - Update a contact option sub-type
  x-api-slug: restaccountscontactsoption-sub-typesoptionsubtypeid-put
  description: Updates a contact option sub-type. The ID of the option sub-type must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactsoption-sub-typesoptionsubtypeid-put-openapi.md
- name: plentymarkets REST-API - List contact option types
  x-api-slug: restaccountscontactsoption-types-get
  description: List contact option types.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactsoption-types-get-openapi.md
- name: plentymarkets REST-API - Create a contact option type
  x-api-slug: restaccountscontactsoption-types-post
  description: Create a contact option type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactsoption-types-post-openapi.md
- name: plentymarkets REST-API - Delete a contact option type
  x-api-slug: restaccountscontactsoption-typesoptiontypeid-delete
  description: Deletes a contact option type. The ID of the option type must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactsoption-typesoptiontypeid-delete-openapi.md
- name: plentymarkets REST-API - Get a contact option type
  x-api-slug: restaccountscontactsoption-typesoptiontypeid-get
  description: Gets a contact option type. The ID of the option type must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactsoption-typesoptiontypeid-get-openapi.md
- name: plentymarkets REST-API - Update a contact option type
  x-api-slug: restaccountscontactsoption-typesoptiontypeid-put
  description: Updates a contact option type. The ID of the option type must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactsoption-typesoptiontypeid-put-openapi.md
- name: plentymarkets REST-API - Delete a contact option by the option ID
  x-api-slug: restaccountscontactsoptionsoptionid-delete
  description: Deletes a contact option. The ID of the option must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactsoptionsoptionid-delete-openapi.md
- name: plentymarkets REST-API - Get a contact option by the option ID
  x-api-slug: restaccountscontactsoptionsoptionid-get
  description: Gets a contact option. The ID of the option must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactsoptionsoptionid-get-openapi.md
- name: plentymarkets REST-API - Update a contact option by the option ID
  x-api-slug: restaccountscontactsoptionsoptionid-put
  description: Updates a contact option. The ID of the option must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactsoptionsoptionid-put-openapi.md
- name: plentymarkets REST-API - List contact positions
  x-api-slug: restaccountscontactspositions-get
  description: List contact positions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactspositions-get-openapi.md
- name: plentymarkets REST-API - Create a contact position
  x-api-slug: restaccountscontactspositions-post
  description: Create a contact position.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactspositions-post-openapi.md
- name: plentymarkets REST-API - Delete a contact position
  x-api-slug: restaccountscontactspositionspositionid-delete
  description: Deletes a contact position. The ID of the position must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactspositionspositionid-delete-openapi.md
- name: plentymarkets REST-API - Get a contact position
  x-api-slug: restaccountscontactspositionspositionid-get
  description: Gets a contact position. The ID of the position must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactspositionspositionid-get-openapi.md
- name: plentymarkets REST-API - Update a contact position
  x-api-slug: restaccountscontactspositionspositionid-put
  description: Updates a contact position. The ID of the position must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactspositionspositionid-put-openapi.md
- name: plentymarkets REST-API - List contact types
  x-api-slug: restaccountscontactstypes-get
  description: List contact types.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactstypes-get-openapi.md
- name: plentymarkets REST-API - Create a contact type
  x-api-slug: restaccountscontactstypes-post
  description: Create a contact type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactstypes-post-openapi.md
- name: plentymarkets REST-API - Delete a contact type
  x-api-slug: restaccountscontactstypestypeid-delete
  description: Deletes a contact type. The ID of the contact type must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactstypestypeid-delete-openapi.md
- name: plentymarkets REST-API - Get a contact type
  x-api-slug: restaccountscontactstypestypeid-get
  description: Gets a contact type. The ID of the contact type must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactstypestypeid-get-openapi.md
- name: plentymarkets REST-API - Update a contact type
  x-api-slug: restaccountscontactstypestypeid-put
  description: Updates a contact type. The ID of the contact type must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactstypestypeid-put-openapi.md
- name: plentymarkets REST-API - Delete a contact
  x-api-slug: restaccountscontactscontactid-delete
  description: Deletes a contact. The ID of the contact must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactid-delete-openapi.md
- name: plentymarkets REST-API - Get a contact
  x-api-slug: restaccountscontactscontactid-get
  description: Gets a contact. The ID of the contact must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactid-get-openapi.md
- name: plentymarkets REST-API - Update a contact
  x-api-slug: restaccountscontactscontactid-put
  description: Updates a contact. The ID of the contact must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactid-put-openapi.md
- name: plentymarkets REST-API - Get the login URL
  x-api-slug: restaccountscontactscontactidaccess-datalogin-url-get
  description: Gets the URL to login as the given contact. The ID of the contact must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactidaccess-datalogin-url-get-openapi.md
- name: plentymarkets REST-API - Send password link for a contact
  x-api-slug: restaccountscontactscontactidaccess-datanew-password-put
  description: Sends an email to a contact with a link to change the password. The
    ID of the contact must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactidaccess-datanew-password-put-openapi.md
- name: plentymarkets REST-API - Update the password for a contact
  x-api-slug: restaccountscontactscontactidaccess-dataset-password-put
  description: Updates the password for a contact. The ID of the contact must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactidaccess-dataset-password-put-openapi.md
- name: plentymarkets REST-API - Unblock a contact
  x-api-slug: restaccountscontactscontactidaccess-dataunblock-user-put
  description: Unblocks a contact to allow this contact to log in again. The ID of
    the contact must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactidaccess-dataunblock-user-put-openapi.md
- name: plentymarkets REST-API - Create an account for existing contact
  x-api-slug: restaccountscontactscontactidaccounts-post
  description: Creates an account for an existing contact. The ID of the contact must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactidaccounts-post-openapi.md
- name: plentymarkets REST-API - Delete an account of the contact
  x-api-slug: restaccountscontactscontactidaccountsaccountid-delete
  description: Deletes an account of the contact. The ID of the contact and the ID
    of the account must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactidaccountsaccountid-delete-openapi.md
- name: plentymarkets REST-API - Get an account of the contact
  x-api-slug: restaccountscontactscontactidaccountsaccountid-get
  description: Gets an account of the contact. The ID of the contact and the ID of
    the account must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactidaccountsaccountid-get-openapi.md
- name: plentymarkets REST-API - Update an account
  x-api-slug: restaccountscontactscontactidaccountsaccountid-put
  description: Updates an account. The ID of the contact and the ID of the account
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactidaccountsaccountid-put-openapi.md
- name: plentymarkets REST-API - Create an address for existing contact and type
  x-api-slug: restaccountscontactscontactidaddresses-post
  description: Creates an address. The ID of the contact must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactidaddresses-post-openapi.md
- name: plentymarkets REST-API - Delete an address of the contact
  x-api-slug: restaccountscontactscontactidaddressesaddressid-delete
  description: Deletes an address of the contact. The ID of the contact and the ID
    of the address must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactidaddressesaddressid-delete-openapi.md
- name: plentymarkets REST-API - Update an address of the contact
  x-api-slug: restaccountscontactscontactidaddressesaddressid-put
  description: Updates an address of the contact. The ID of the contact and the ID
    of the address must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactidaddressesaddressid-put-openapi.md
- name: plentymarkets REST-API - Set a contact address per address type as the primary
    address
  x-api-slug: restaccountscontactscontactidaddressesaddressidtypesaddresstypeidprimary-put
  description: Sets a contact address per address type as the primary address. The
    ID of the contact, the ID of the address and the ID of the address type must be
    specified. A primary address is also definable if you create or update a contact
    address.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactidaddressesaddressidtypesaddresstypeidprimary-put-openapi.md
- name: plentymarkets REST-API - Resets a contact primary address
  x-api-slug: restaccountscontactscontactidaddressesaddressidtypesaddresstypeidreset-primary-put
  description: Resets a contact primary address. The ID of the contact, the ID of
    the address and the ID of the address type must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactidaddressesaddressidtypesaddresstypeidreset-primary-put-openapi.md
- name: plentymarkets REST-API - List addresses that are linked with contacts
  x-api-slug: restaccountscontactscontactidaddressesaddresstypeid-get
  description: Lists addresses of the contact. The ID of the contact must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactidaddressesaddresstypeid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactidaddressesaddresstypeid-get-openapi.md
- name: plentymarkets REST-API - anonymize Contact
  x-api-slug: restaccountscontactscontactidanonymize-put
  description: anonymizes the given contact.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactidanonymize-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactidanonymize-put-openapi.md
- name: plentymarkets REST-API - List bank accounts
  x-api-slug: restaccountscontactscontactidbanks-get
  description: Lists bank accounts of the contact. The ID of the contact must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactidbanks-get-openapi.md
- name: plentymarkets REST-API - List contact events by contact ID
  x-api-slug: restaccountscontactscontactidcontact-events-get
  description: Lists contact events by contact ID. The ID of the contact must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactidcontact-events-get-openapi.md
- name: plentymarkets REST-API - Get a single storage object from contact documents
  x-api-slug: restaccountscontactscontactiddocument-get
  description: Get a single storage object from contact documents.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactiddocument-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactiddocument-get-openapi.md
- name: plentymarkets REST-API - Upload a document to contact directory
  x-api-slug: restaccountscontactscontactiddocument-post
  description: Upload a document to contact directory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactiddocument-post-openapi.md
- name: plentymarkets REST-API - Get a temporary url for a single document
  x-api-slug: restaccountscontactscontactiddocumenturl-get
  description: Get a temporary url for a single document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactiddocumenturl-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactiddocumenturl-get-openapi.md
- name: plentymarkets REST-API - Delete files from contact documents
  x-api-slug: restaccountscontactscontactiddocuments-delete
  description: Delete files from contact documents.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactiddocuments-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactiddocuments-delete-openapi.md
- name: plentymarkets REST-API - List documents for a single contact
  x-api-slug: restaccountscontactscontactiddocuments-get
  description: List documents for a single contact.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactiddocuments-get-openapi.md
- name: plentymarkets REST-API - Delete a contact option by the contact ID
  x-api-slug: restaccountscontactscontactidoptions-delete
  description: Deletes a contact option for an existing contact. The ID of the contact
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactidoptions-delete-openapi.md
- name: plentymarkets REST-API - List contact options by the contact ID
  x-api-slug: restaccountscontactscontactidoptions-get
  description: Lists contact options. The ID of the contact must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactidoptions-get-openapi.md
- name: plentymarkets REST-API - Create a contact option by the contact ID
  x-api-slug: restaccountscontactscontactidoptions-post
  description: Creates a contact option for an existing contact. The ID of the contact
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactidoptions-post-openapi.md
- name: plentymarkets REST-API - Update a contact option by the contact ID
  x-api-slug: restaccountscontactscontactidoptions-put
  description: Updates a contact option for an existing contact. The ID of the contact
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactidoptions-put-openapi.md
- name: plentymarkets REST-API - Validate a contact option by a given value
  x-api-slug: restaccountscontactscontactidoptionsvalidate-get
  description: validates a contact option by a given value
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactidoptionsvalidate-get-openapi.md
- name: plentymarkets REST-API - Return all contact related data
  x-api-slug: restaccountscontactscontactidrelated-data-get
  description: Returns all contact related data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactidrelated-data-get-openapi.md
- name: plentymarkets REST-API - get a filestream of vcard from customer
  x-api-slug: restaccountscontactscontactidvcard-get
  description: Get a filestream of vcard from customer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactidvcard-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountscontactscontactidvcard-get-openapi.md
- name: plentymarkets REST-API - List order summaries
  x-api-slug: restaccountsorder-summaries-get
  description: List order summaries.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsorder-summaries-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsorder-summaries-get-openapi.md
- name: plentymarkets REST-API - Create an order summary
  x-api-slug: restaccountsorder-summaries-post
  description: Create an order summary.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsorder-summaries-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsorder-summaries-post-openapi.md
- name: plentymarkets REST-API - Get an order summary by the contact ID
  x-api-slug: restaccountsorder-summariescontactscontactid-get
  description: Gets an order summary. The ID of the contact must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsorder-summariescontactscontactid-get-openapi.md
- name: plentymarkets REST-API - Get an order summary by the address ID
  x-api-slug: restaccountsorder-summariesordersaddressid-get
  description: Gets an order summary. The ID of the address must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsorder-summariesordersaddressid-get-openapi.md
- name: plentymarkets REST-API - Delete an order summary
  x-api-slug: restaccountsorder-summariesordersummaryid-delete
  description: Deletes an order summary. The ID of the order summary must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsorder-summariesordersummaryid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsorder-summariesordersummaryid-delete-openapi.md
- name: plentymarkets REST-API - Get an order summary by the order summary ID
  x-api-slug: restaccountsorder-summariesordersummaryid-get
  description: Gets an order summary. The ID of the order summary must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsorder-summariesordersummaryid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsorder-summariesordersummaryid-get-openapi.md
- name: plentymarkets REST-API - Update an order summary
  x-api-slug: restaccountsorder-summariesordersummaryid-put
  description: Updates an order summary. The ID of the order summary must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsorder-summariesordersummaryid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsorder-summariesordersummaryid-put-openapi.md
- name: plentymarkets REST-API - Delete an account
  x-api-slug: restaccountsaccountid-delete
  description: Deletes an account. The ID of the account must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaccountid-delete-openapi.md
- name: plentymarkets REST-API - Get an account
  x-api-slug: restaccountsaccountid-get
  description: Gets an account. The ID of the account must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaccountid-get-openapi.md
- name: plentymarkets REST-API - Update an account
  x-api-slug: restaccountsaccountid-put
  description: Updates an account. The ID of the account must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaccountid-put-openapi.md
- name: plentymarkets REST-API - List contacts
  x-api-slug: restaccountsaccountidcontacts-get
  description: Lists contacts of the account. The ID of the account must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaccountidcontacts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restaccountsaccountidcontacts-get-openapi.md
- name: plentymarkets REST-API - Get authorized user
  x-api-slug: restauthorized-user-get
  description: Gets an authorized user. This call returns a JSON object with information
    about the user after login. This information is used for correctly displaying
    the plentymarkets back end.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restauthorized-user-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restauthorized-user-get-openapi.md
- name: plentymarkets REST-API - List item availabilities
  x-api-slug: restavailabilities-get
  description: Lists all item availabilities.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restavailabilities-get-openapi.md
- name: plentymarkets REST-API - Get an item availability
  x-api-slug: restavailabilitiesid-get
  description: Gets an item availability. The ID of the availability must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restavailabilitiesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restavailabilitiesid-get-openapi.md
- name: plentymarkets REST-API - Update an item availability
  x-api-slug: restavailabilitiesid-put
  description: Updates an item availability.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restavailabilitiesid-put-openapi.md
- name: 'plentymarkets REST-API - '
  x-api-slug: restbackenduseruserid-get
  description: .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restbackenduseruserid-get-openapi.md
- name: 'plentymarkets REST-API - '
  x-api-slug: restbackendusers-get
  description: .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restbackendusers-get-openapi.md
- name: plentymarkets REST-API - Find all users having a name or username like the
    given one.
  x-api-slug: restbackenduserssearch-namename-get
  description: Find all users having a name or username like the given one..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restbackenduserssearch-namename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restbackenduserssearch-namename-get-openapi.md
- name: plentymarkets REST-API - Get basket
  x-api-slug: restbasket-get
  description: Gets the shopping cart for the current customer session.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restbasket-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restbasket-get-openapi.md
- name: plentymarkets REST-API - List basket items
  x-api-slug: restbasketitems-get
  description: Lists all items in the shopping cart for the current customer session.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restbasketitems-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restbasketitems-get-openapi.md
- name: plentymarkets REST-API - Add item to basket
  x-api-slug: restbasketitems-post
  description: Adds a new item to the shopping cart using the request parameters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restbasketitems-post-openapi.md
- name: plentymarkets REST-API - Find a basket item by it's ID
  x-api-slug: restbasketitemsid-get
  description: Find a basket item by it's id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restbasketitemsid-get-openapi.md
- name: plentymarkets REST-API - Make batch requests
  x-api-slug: restbatch-get
  description: Pass several operations into a single HTTP request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restbatch-get-openapi.md
- name: plentymarkets REST-API - Lists all boards.
  x-api-slug: restboards-get
  description: Lists all boards..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restboards-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restboards-get-openapi.md
- name: plentymarkets REST-API - Creates a new board.
  x-api-slug: restboards-post
  description: Creates a new board..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restboards-post-openapi.md
- name: plentymarkets REST-API - Deletes a specific board.
  x-api-slug: restboardsboardid-delete
  description: Deletes a specific board..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restboardsboardid-delete-openapi.md
- name: plentymarkets REST-API - Gets a single board by its ID
  x-api-slug: restboardsboardid-get
  description: Gets a single board by its id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restboardsboardid-get-openapi.md
- name: plentymarkets REST-API - Copies a specific board.
  x-api-slug: restboardsboardid-post
  description: Copies a specific board..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restboardsboardid-post-openapi.md
- name: plentymarkets REST-API - Updates a specific board.
  x-api-slug: restboardsboardid-put
  description: Updates a specific board..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restboardsboardid-put-openapi.md
- name: plentymarkets REST-API - Lists all columns for a given board
  x-api-slug: restboardsboardidcolumns-get
  description: Lists all columns for a given board.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restboardsboardidcolumns-get-openapi.md
- name: plentymarkets REST-API - Creates a new column and assigns it to a given board
  x-api-slug: restboardsboardidcolumns-post
  description: Creates a new column and assigns it to a given board.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restboardsboardidcolumns-post-openapi.md
- name: plentymarkets REST-API - Deletes a specific column.
  x-api-slug: restboardsboardidcolumnscolumnid-delete
  description: Deletes a specific column..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restboardsboardidcolumnscolumnid-delete-openapi.md
- name: plentymarkets REST-API - Copies a specific column.
  x-api-slug: restboardsboardidcolumnscolumnid-post
  description: Copies a specific column..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restboardsboardidcolumnscolumnid-post-openapi.md
- name: plentymarkets REST-API - Updates a specific column.
  x-api-slug: restboardsboardidcolumnscolumnid-put
  description: Updates a specific column..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restboardsboardidcolumnscolumnid-put-openapi.md
- name: plentymarkets REST-API - Updates the position of a specific column. Also updates
    the positions of all following columns on the same board.
  x-api-slug: restboardsboardidcolumnscolumnidposition-put
  description: Updates the position of a specific column. also updates the positions
    of all following columns on the same board..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restboardsboardidcolumnscolumnidposition-put-openapi.md
- name: plentymarkets REST-API - Lists all tasks for a given column.
  x-api-slug: restboardsboardidcolumnscolumnidtasks-get
  description: Lists all tasks for a given column..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restboardsboardidcolumnscolumnidtasks-get-openapi.md
- name: plentymarkets REST-API - Creates a new tasks on a specified column.
  x-api-slug: restboardsboardidcolumnscolumnidtasks-post
  description: Creates a new tasks on a specified column..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restboardsboardidcolumnscolumnidtasks-post-openapi.md
- name: plentymarkets REST-API - Deletes a task.
  x-api-slug: restboardsboardidcolumnscolumnidtaskstaskid-delete
  description: Deletes a task..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restboardsboardidcolumnscolumnidtaskstaskid-delete-openapi.md
- name: plentymarkets REST-API - Gets a task by its ID.
  x-api-slug: restboardsboardidcolumnscolumnidtaskstaskid-get
  description: Gets a task by its id..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restboardsboardidcolumnscolumnidtaskstaskid-get-openapi.md
- name: plentymarkets REST-API - Copies a specific task.
  x-api-slug: restboardsboardidcolumnscolumnidtaskstaskid-post
  description: Copies a specific task..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restboardsboardidcolumnscolumnidtaskstaskid-post-openapi.md
- name: plentymarkets REST-API - Updates a task.
  x-api-slug: restboardsboardidcolumnscolumnidtaskstaskid-put
  description: Updates a task..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restboardsboardidcolumnscolumnidtaskstaskid-put-openapi.md
- name: plentymarkets REST-API - Updates the position of a task.
  x-api-slug: restboardsboardidcolumnscolumnidtaskstaskidposition-put
  description: Updates the position of a task..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restboardsboardidcolumnscolumnidtaskstaskidposition-put-openapi.md
- name: plentymarkets REST-API - Creates a new reference from a given task to a contact
    or a ticket.
  x-api-slug: restboardsboardidcolumnscolumnidtaskstaskidreferences-post
  description: Creates a new reference from a given task to a contact or a ticket..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restboardsboardidcolumnscolumnidtaskstaskidreferences-post-openapi.md
- name: plentymarkets REST-API - Deletes a reference from a given task.
  x-api-slug: restboardsboardidcolumnscolumnidtaskstaskidreferencesreferenceid-delete
  description: Deletes a reference from a given task..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restboardsboardidcolumnscolumnidtaskstaskidreferencesreferenceid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restboardsboardidcolumnscolumnidtaskstaskidreferencesreferenceid-delete-openapi.md
- name: 'plentymarkets REST-API - '
  x-api-slug: restboardsboardidcolumnscolumnidtaskstaskidreferencesreferencetypereferencekey-get
  description: .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restboardsboardidcolumnscolumnidtaskstaskidreferencesreferencetypereferencekey-get-openapi.md
- name: plentymarkets REST-API - List categories
  x-api-slug: restcategories-get
  description: List categories.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcategories-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcategories-get-openapi.md
- name: plentymarkets REST-API - Creates new categories
  x-api-slug: restcategories-post
  description: Creates new categories.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcategories-post-openapi.md
- name: plentymarkets REST-API - Updates categories
  x-api-slug: restcategories-put
  description: Updates categories.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcategories-put-openapi.md
- name: plentymarkets REST-API - List documents of a category
  x-api-slug: restcategoriescategoryiddocuments-get
  description: Lists the documents of a category. The ID of the category must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcategoriescategoryiddocuments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcategoriescategoryiddocuments-get-openapi.md
- name: plentymarkets REST-API - Upload category documents
  x-api-slug: restcategoriescategoryiddocuments-post
  description: Uploads documents to a category. The ID of the category must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcategoriescategoryiddocuments-post-openapi.md
- name: plentymarkets REST-API - Download category documents
  x-api-slug: restcategoriescategoryiddocumentsdownloads-get
  description: Downloads the documents of a category as a zip file. The ID of the
    category must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcategoriescategoryiddocumentsdownloads-get-openapi.md
- name: plentymarkets REST-API - Deletes a category document. The ID of the document
    must be specified.
  x-api-slug: restcategoriescategoryiddocumentsdocumentid-delete
  description: Deletes a category document. the id of the document must be specified..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcategoriescategoryiddocumentsdocumentid-delete-openapi.md
- name: plentymarkets REST-API - Deletes a category
  x-api-slug: restcategoriesid-delete
  description: Deletes a category. The ID of the category must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcategoriesid-delete-openapi.md
- name: plentymarkets REST-API - List categories
  x-api-slug: restcategoriesid-get
  description: List categories.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcategoriesid-get-openapi.md
- name: plentymarkets REST-API - Updates one category
  x-api-slug: restcategoriesid-put
  description: Updates an existing category. The ID of the category must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcategoriesid-put-openapi.md
- name: plentymarkets REST-API - Deactivate availability for clients
  x-api-slug: restcategoriesidclients-delete
  description: Deactivate availability for clients.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcategoriesidclients-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcategoriesidclients-delete-openapi.md
- name: plentymarkets REST-API - Delete category details for the specified languages
  x-api-slug: restcategoriesiddetails-delete
  description: Delete category details for the specified languages.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcategoriesiddetails-delete-openapi.md
- name: plentymarkets REST-API - Delete a category template
  x-api-slug: restcategoriesidtemplates-delete
  description: Deletes a category template. The ID of the category, the plenty ID
    of the client (store) and the language must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcategoriesidtemplates-delete-openapi.md
- name: plentymarkets REST-API - Get a category template
  x-api-slug: restcategoriesidtemplates-get
  description: Gets a category template. The ID of the category, the plenty ID of
    the client (store) and the language must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcategoriesidtemplates-get-openapi.md
- name: plentymarkets REST-API - Update a category template
  x-api-slug: restcategoriesidtemplates-put
  description: Updates a category template. The ID of the category, the plenty ID
    of the client (store) and the language must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcategoriesidtemplates-put-openapi.md
- name: plentymarkets REST-API - Get category trees
  x-api-slug: restcategory-branches-get
  description: Get category trees.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcategory-branches-get-openapi.md
- name: plentymarkets REST-API - Get category tree
  x-api-slug: restcategory-branchesid-get
  description: Gets the category tree of a category. The ID of the category must be
    specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcategory-branchesid-get-openapi.md
- name: plentymarkets REST-API - Create a comment
  x-api-slug: restcomments-post
  description: Creates a comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcomments-post-openapi.md
- name: plentymarkets REST-API - Delete a comment
  x-api-slug: restcommentscommentid-delete
  description: Deletes a comment. The ID of the comment must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcommentscommentid-delete-openapi.md
- name: plentymarkets REST-API - Get a comment
  x-api-slug: restcommentscommentid-get
  description: Gets a comment. The ID of the comment must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcommentscommentid-get-openapi.md
- name: 'plentymarkets REST-API - '
  x-api-slug: restcommentscommentid-put
  description: .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcommentscommentid-put-openapi.md
- name: plentymarkets REST-API - List comments
  x-api-slug: restcommentsreferencetypereferencevalue-get
  description: Lists comments. The reference type and the reference value must be
    specified (e.g. the reference type is 'order' and the reference value is the ID
    of the order).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcommentsreferencetypereferencevalue-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcommentsreferencetypereferencevalue-get-openapi.md
- name: plentymarkets REST-API - List contracts
  x-api-slug: restcustomer-contracts-get
  description: List contracts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcustomer-contracts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcustomer-contracts-get-openapi.md
- name: plentymarkets REST-API - Creates a new contract
  x-api-slug: restcustomer-contracts-post
  description: Creates a new contract.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcustomer-contracts-post-openapi.md
- name: plentymarkets REST-API - Returns a single contract
  x-api-slug: restcustomer-contractscontractid-get
  description: Returns a single contract.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcustomer-contractscontractid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcustomer-contractscontractid-get-openapi.md
- name: plentymarkets REST-API - Starts download of contract document
  x-api-slug: restcustomer-contractscontractiddocument-get
  description: Starts download of contract document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcustomer-contractscontractiddocument-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcustomer-contractscontractiddocument-get-openapi.md
- name: plentymarkets REST-API - Returns signing of a contract
  x-api-slug: restcustomer-contractscontractidsign-get
  description: Returns signing of a contract.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcustomer-contractscontractidsign-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcustomer-contractscontractidsign-get-openapi.md
- name: plentymarkets REST-API - Sign a contract
  x-api-slug: restcustomer-contractscontractidsign-post
  description: Sign a contract.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcustomer-contractscontractidsign-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcustomer-contractscontractidsign-post-openapi.md
- name: plentymarkets REST-API - Starts download of signed contract document
  x-api-slug: restcustomer-contractscontractidsigndocument-get
  description: Starts download of signed contract document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcustomer-contractscontractidsigndocument-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restcustomer-contractscontractidsigndocument-get-openapi.md
- name: plentymarkets REST-API - Search the delete log
  x-api-slug: restdelete-log-get
  description: Searches the delete log.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restdelete-log-get-openapi.md
- name: plentymarkets REST-API - Download the content of a document
  x-api-slug: restdocumentsdocumentid-get
  description: Downloads the content of a document. The ID of the document must be
    specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restdocumentsdocumentid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restdocumentsdocumentid-get-openapi.md
- name: plentymarkets REST-API - List elastic exports
  x-api-slug: restexports-get
  description: Lists elastic exports.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restexports-get-openapi.md
- name: plentymarkets REST-API - Create an export
  x-api-slug: restexports-post
  description: Creates an export.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restexports-post-openapi.md
- name: plentymarkets REST-API - Get format keys
  x-api-slug: restexportsformat-keys-get
  description: Shows all format keys registered by plugins in production state
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restexportsformat-keys-get-openapi.md
- name: plentymarkets REST-API - Get format keys
  x-api-slug: restexportsformat-keystype-get
  description: Shows all format keys registered by plugins in production state
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restexportsformat-keystype-get-openapi.md
- name: plentymarkets REST-API - Generate a token
  x-api-slug: restexportsgenerate-token-get
  description: Creates a new token which can be used as <code>OutputParam</code> entry.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restexportsgenerate-token-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restexportsgenerate-token-get-openapi.md
- name: plentymarkets REST-API - Delete export
  x-api-slug: restexportsexportid-delete
  description: Deletes an export. The ID of the export must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restexportsexportid-delete-openapi.md
- name: plentymarkets REST-API - Get export
  x-api-slug: restexportsexportid-get
  description: Gets detailed information about an export. The ID of the export must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restexportsexportid-get-openapi.md
- name: plentymarkets REST-API - Update an export
  x-api-slug: restexportsexportid-put
  description: Updates an export. The ID of the export must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restexportsexportid-put-openapi.md
- name: 'plentymarkets REST-API - '
  x-api-slug: restexportsexportidfiltersfilterid-delete
  description: .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restexportsexportidfiltersfilterid-delete-openapi.md
- name: 'plentymarkets REST-API - '
  x-api-slug: restexportsexportidfilterskey-delete
  description: .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restexportsexportidfilterskey-delete-openapi.md
- name: plentymarkets REST-API - Create a feedback comment
  x-api-slug: restfeedbackscomment-post
  description: Creates a feedback comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restfeedbackscomment-post-openapi.md
- name: plentymarkets REST-API - Delete a feedback comment
  x-api-slug: restfeedbackscommentcommentid-delete
  description: Deletes a feedback comment. The ID of the feedback comment must be
    specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restfeedbackscommentcommentid-delete-openapi.md
- name: plentymarkets REST-API - Get a feedback comment
  x-api-slug: restfeedbackscommentcommentid-get
  description: Gets a feedback comment. The ID of the feedback comment must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restfeedbackscommentcommentid-get-openapi.md
- name: 'plentymarkets REST-API - '
  x-api-slug: restfeedbackscommentcommentid-put
  description: .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restfeedbackscommentcommentid-put-openapi.md
- name: plentymarkets REST-API - List feedback comments
  x-api-slug: restfeedbackscomments-get
  description: Lists feedback comments.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restfeedbackscomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restfeedbackscomments-get-openapi.md
- name: plentymarkets REST-API - Delete multiple feedbacks
  x-api-slug: restfeedbacksdelete-feedbacksfeedbackids-delete
  description: Deletes multiple feedbacks. A list with IDs of feedbacks must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restfeedbacksdelete-feedbacksfeedbackids-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restfeedbacksdelete-feedbacksfeedbackids-delete-openapi.md
- name: plentymarkets REST-API - Create a feedback
  x-api-slug: restfeedbacksfeedback-post
  description: Creates a feedback.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restfeedbacksfeedback-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restfeedbacksfeedback-post-openapi.md
- name: plentymarkets REST-API - List feedback replies
  x-api-slug: restfeedbacksfeedbackrepliesfeedbackid-get
  description: Lists feedback replies. The ID of the feedback must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restfeedbacksfeedbackrepliesfeedbackid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restfeedbacksfeedbackrepliesfeedbackid-get-openapi.md
- name: plentymarkets REST-API - Delete a feedback
  x-api-slug: restfeedbacksfeedbackfeedbackid-delete
  description: Deletes a feedback. The ID of the feedback must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restfeedbacksfeedbackfeedbackid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restfeedbacksfeedbackfeedbackid-delete-openapi.md
- name: plentymarkets REST-API - Get a feedback
  x-api-slug: restfeedbacksfeedbackfeedbackid-get
  description: Gets a feedback. The ID of the feedback must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restfeedbacksfeedbackfeedbackid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restfeedbacksfeedbackfeedbackid-get-openapi.md
- name: plentymarkets REST-API - Update a feedback
  x-api-slug: restfeedbacksfeedbackfeedbackid-put
  description: Updates a feedback. The ID of the feedback must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restfeedbacksfeedbackfeedbackid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restfeedbacksfeedbackfeedbackid-put-openapi.md
- name: plentymarkets REST-API - List feedbacks
  x-api-slug: restfeedbacksfeedbacks-get
  description: Lists feedbacks. The reference type and the reference value must be
    specified (e.g. the reference type is 'order' and the reference value is the ID
    of the order).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restfeedbacksfeedbacks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restfeedbacksfeedbacks-get-openapi.md
- name: plentymarkets REST-API - Update the visibility of multiple feedbacks
  x-api-slug: restfeedbacksfeedbacks-visibility-put
  description: Updates the visibility of multiple feedbacks. A list with IDs of feedbacks
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restfeedbacksfeedbacks-visibility-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restfeedbacksfeedbacks-visibility-put-openapi.md
- name: plentymarkets REST-API - Migrate legacy feedbacks
  x-api-slug: restfeedbacksmigrate-post
  description: Migrate legacy feedbacks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restfeedbacksmigrate-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restfeedbacksmigrate-post-openapi.md
- name: plentymarkets REST-API - Create a feedback rating
  x-api-slug: restfeedbacksrating-post
  description: Creates a feedback rating.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restfeedbacksrating-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restfeedbacksrating-post-openapi.md
- name: plentymarkets REST-API - Delete a feedback rating
  x-api-slug: restfeedbacksratingratingid-delete
  description: Deletes a feedback rating. The ID of the feedback rating must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restfeedbacksratingratingid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restfeedbacksratingratingid-delete-openapi.md
- name: plentymarkets REST-API - Get a feedback rating
  x-api-slug: restfeedbacksratingratingid-get
  description: Gets a feedback rating. The ID of the feedback rating must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restfeedbacksratingratingid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restfeedbacksratingratingid-get-openapi.md
- name: 'plentymarkets REST-API - '
  x-api-slug: restfeedbacksratingratingid-put
  description: .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restfeedbacksratingratingid-put-openapi.md
- name: plentymarkets REST-API - List feedback ratings
  x-api-slug: restfeedbacksratings-get
  description: Lists feedback ratings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restfeedbacksratings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restfeedbacksratings-get-openapi.md
- name: plentymarkets REST-API - Delete item sets
  x-api-slug: restitem-sets-delete
  description: Delete item sets.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitem-sets-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitem-sets-delete-openapi.md
- name: plentymarkets REST-API - List item sets
  x-api-slug: restitem-sets-get
  description: Lists all item sets.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitem-sets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitem-sets-get-openapi.md
- name: plentymarkets REST-API - Create item sets
  x-api-slug: restitem-sets-post
  description: Create item sets.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitem-sets-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitem-sets-post-openapi.md
- name: plentymarkets REST-API - Update item sets
  x-api-slug: restitem-sets-put
  description: Update item sets.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitem-sets-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitem-sets-put-openapi.md
- name: plentymarkets REST-API - Delete an item set
  x-api-slug: restitem-setsid-delete
  description: Deletes an item set. The item ID of the item set must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitem-setsid-delete-openapi.md
- name: plentymarkets REST-API - Get an item set
  x-api-slug: restitem-setsid-get
  description: Gets the configuration of an item set. The item ID of the item set
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitem-setsid-get-openapi.md
- name: plentymarkets REST-API - Update an item set
  x-api-slug: restitem-setsid-put
  description: Updates an item set. The item ID of the item set must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitem-setsid-put-openapi.md
- name: plentymarkets REST-API - Delete item set components
  x-api-slug: restitem-setssetidcomponents-delete
  description: Delete item set components.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitem-setssetidcomponents-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitem-setssetidcomponents-delete-openapi.md
- name: plentymarkets REST-API - List item set components of an item set
  x-api-slug: restitem-setssetidcomponents-get
  description: Lists the item set components of an item set. The ID of the item set
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitem-setssetidcomponents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitem-setssetidcomponents-get-openapi.md
- name: plentymarkets REST-API - Create item set components
  x-api-slug: restitem-setssetidcomponents-post
  description: Create item set components.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitem-setssetidcomponents-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitem-setssetidcomponents-post-openapi.md
- name: plentymarkets REST-API - Update item set components
  x-api-slug: restitem-setssetidcomponents-put
  description: Update item set components.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitem-setssetidcomponents-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitem-setssetidcomponents-put-openapi.md
- name: plentymarkets REST-API - Delete an item set component
  x-api-slug: restitem-setssetidcomponentsid-delete
  description: Deletes an item set component. The item set component ID of the item
    set component must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitem-setssetidcomponentsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitem-setssetidcomponentsid-delete-openapi.md
- name: plentymarkets REST-API - Get an item set component
  x-api-slug: restitem-setssetidcomponentsid-get
  description: Get an item set component.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitem-setssetidcomponentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitem-setssetidcomponentsid-get-openapi.md
- name: plentymarkets REST-API - Update an item set component
  x-api-slug: restitem-setssetidcomponentsid-put
  description: Update an item set component.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitem-setssetidcomponentsid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitem-setssetidcomponentsid-put-openapi.md
- name: plentymarkets REST-API - Get the item set configuration of an item set
  x-api-slug: restitem-setssetidconfig-get
  description: Get the item set configuration of an item set.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitem-setssetidconfig-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitem-setssetidconfig-get-openapi.md
- name: plentymarkets REST-API - Update an item set configuration
  x-api-slug: restitem-setssetidconfig-put
  description: Update an item set configuration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitem-setssetidconfig-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitem-setssetidconfig-put-openapi.md
- name: plentymarkets REST-API - Search item
  x-api-slug: restitems-get
  description: Search item.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitems-get-openapi.md
- name: plentymarkets REST-API - Create new item
  x-api-slug: restitems-post
  description: Create new item.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitems-post-openapi.md
- name: plentymarkets REST-API - Get name and language for an attribute value ID
  x-api-slug: restitemsattribute-valuesvalueidnames-get
  description: Gets name and language for an attribute value ID. The attribute value
    ID must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattribute-valuesvalueidnames-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattribute-valuesvalueidnames-get-openapi.md
- name: plentymarkets REST-API - Create an attribute value name
  x-api-slug: restitemsattribute-valuesvalueidnames-post
  description: Creates an attribute value name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattribute-valuesvalueidnames-post-openapi.md
- name: plentymarkets REST-API - Delete an attribute value name
  x-api-slug: restitemsattribute-valuesvalueidnameslang-delete
  description: Deletes an attribute value name. The attribute value ID and language
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattribute-valuesvalueidnameslang-delete-openapi.md
- name: plentymarkets REST-API - Get an attribute value name
  x-api-slug: restitemsattribute-valuesvalueidnameslang-get
  description: Gets the attribute value name. The attribute value ID and language
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattribute-valuesvalueidnameslang-get-openapi.md
- name: plentymarkets REST-API - Update an attribute value name
  x-api-slug: restitemsattribute-valuesvalueidnameslang-put
  description: Updates an attribute value name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattribute-valuesvalueidnameslang-put-openapi.md
- name: plentymarkets REST-API - List attributes
  x-api-slug: restitemsattributes-get
  description: Lists all attributes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattributes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattributes-get-openapi.md
- name: plentymarkets REST-API - Create an attribute
  x-api-slug: restitemsattributes-post
  description: Creates an attribute.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattributes-post-openapi.md
- name: plentymarkets REST-API - Lists all attribute maps.
  x-api-slug: restitemsattributesmaps-get
  description: Lists all attribute maps..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattributesmaps-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattributesmaps-get-openapi.md
- name: plentymarkets REST-API - Creates a new attribute map.
  x-api-slug: restitemsattributesmarketsmaps-post
  description: Creates a new attribute map..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattributesmarketsmaps-post-openapi.md
- name: plentymarkets REST-API - Lists all attribute value maps.
  x-api-slug: restitemsattributesvaluesmaps-get
  description: Lists all attribute value maps..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattributesvaluesmaps-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattributesvaluesmaps-get-openapi.md
- name: plentymarkets REST-API - Creates a new attribute value map.
  x-api-slug: restitemsattributesvaluesmarketsmaps-post
  description: Creates a new attribute value map..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattributesvaluesmarketsmaps-post-openapi.md
- name: plentymarkets REST-API - Deletes an attribute map.
  x-api-slug: restitemsattributesattributeidmarketsmarketidmaps-delete
  description: Deletes an attribute map. The ID of the attribute and the ID of the
    market must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattributesattributeidmarketsmarketidmaps-delete-openapi.md
- name: plentymarkets REST-API - Gets an attribute map.
  x-api-slug: restitemsattributesattributeidmarketsmarketidmaps-get
  description: Gets an attribute map. The ID of the attribute and the ID of the market
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattributesattributeidmarketsmarketidmaps-get-openapi.md
- name: plentymarkets REST-API - Updates an attribute map.
  x-api-slug: restitemsattributesattributeidmarketsmarketidmaps-put
  description: Updates an attribute map. The ID of the attribute and the ID of the
    market must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattributesattributeidmarketsmarketidmaps-put-openapi.md
- name: plentymarkets REST-API - Get an attribute name
  x-api-slug: restitemsattributesattributeidnames-get
  description: Gets the attribute name in the specified language. The language code
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattributesattributeidnames-get-openapi.md
- name: plentymarkets REST-API - Create an attribute name
  x-api-slug: restitemsattributesattributeidnames-post
  description: Creates an attribute name in the specified language. The language code
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattributesattributeidnames-post-openapi.md
- name: plentymarkets REST-API - Delete an attribute name
  x-api-slug: restitemsattributesattributeidnameslang-delete
  description: Deletes the attribute name in the specified language. The language
    code and attribute name must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattributesattributeidnameslang-delete-openapi.md
- name: plentymarkets REST-API - List attribute names
  x-api-slug: restitemsattributesattributeidnameslang-get
  description: Lists the attribute names of an attribute.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattributesattributeidnameslang-get-openapi.md
- name: plentymarkets REST-API - Update an attribute name
  x-api-slug: restitemsattributesattributeidnameslang-put
  description: Updates the attribute name in the specified language. The language
    code and attribute name must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattributesattributeidnameslang-put-openapi.md
- name: plentymarkets REST-API - Search attribute value market names
  x-api-slug: restitemsattributesattributeidvalue-market-names-get
  description: Search attribute value market names.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattributesattributeidvalue-market-names-get-openapi.md
- name: plentymarkets REST-API - Create an attribute value market name
  x-api-slug: restitemsattributesattributeidvalue-market-names-post
  description: Creates an attribute value market name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattributesattributeidvalue-market-names-post-openapi.md
- name: plentymarkets REST-API - Delete an attribute value market name
  x-api-slug: restitemsattributesattributeidvalue-market-namesvalueidlangreferencetype-delete
  description: Deletes an attribute value market name. The attribute value ID and
    language must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattributesattributeidvalue-market-namesvalueidlangreferencetype-delete-openapi.md
- name: plentymarkets REST-API - Update an attribute value market name
  x-api-slug: restitemsattributesattributeidvalue-market-namesvalueidlangreferencetype-put
  description: Updates an attribute value market name. The attribute value ID and
    language must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattributesattributeidvalue-market-namesvalueidlangreferencetype-put-openapi.md
- name: plentymarkets REST-API - List attribute values
  x-api-slug: restitemsattributesattributeidvalues-get
  description: Lists the attribute values for an attribute. The attribute ID must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattributesattributeidvalues-get-openapi.md
- name: plentymarkets REST-API - Create an attribute value
  x-api-slug: restitemsattributesattributeidvalues-post
  description: Creates an attribute value.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattributesattributeidvalues-post-openapi.md
- name: plentymarkets REST-API - Deletes an attribute value map.
  x-api-slug: restitemsattributesattributeidvaluesattributevalueidmarketsmarketidmaps-delete
  description: Deletes an attribute value map. The ID of the attribute, the ID of
    the attribute value and the ID of the market must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattributesattributeidvaluesattributevalueidmarketsmarketidmaps-delete-openapi.md
- name: plentymarkets REST-API - Gets an attribute value map.
  x-api-slug: restitemsattributesattributeidvaluesattributevalueidmarketsmarketidmaps-get
  description: Gets an attribute value map. The ID of the attribute, the ID of the
    attribute value and the ID of the market must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattributesattributeidvaluesattributevalueidmarketsmarketidmaps-get-openapi.md
- name: plentymarkets REST-API - Updates an attribute value map.
  x-api-slug: restitemsattributesattributeidvaluesattributevalueidmarketsmarketidmaps-put
  description: Updates an attribute value map. The ID of the attribute, the ID of
    the attribute value and the ID of the market must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattributesattributeidvaluesattributevalueidmarketsmarketidmaps-put-openapi.md
- name: plentymarkets REST-API - Delete an attribute value
  x-api-slug: restitemsattributesattributeidvaluesid-delete
  description: Deletes an attribute value. The attribute ID must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattributesattributeidvaluesid-delete-openapi.md
- name: plentymarkets REST-API - Get an attribute value
  x-api-slug: restitemsattributesattributeidvaluesid-get
  description: Get an attribute value. The ID of the attribute value must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattributesattributeidvaluesid-get-openapi.md
- name: plentymarkets REST-API - Update an attribute value
  x-api-slug: restitemsattributesattributeidvaluesid-put
  description: Updates an attribute value. The attribute value must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattributesattributeidvaluesid-put-openapi.md
- name: plentymarkets REST-API - Delete an attribute
  x-api-slug: restitemsattributesid-delete
  description: Deletes an attribute. The ID of the attribute must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattributesid-delete-openapi.md
- name: plentymarkets REST-API - Get an attribute
  x-api-slug: restitemsattributesid-get
  description: Gets an attribute. The ID of the attribute must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattributesid-get-openapi.md
- name: plentymarkets REST-API - Update an attribute
  x-api-slug: restitemsattributesid-put
  description: Updates an attribute. The ID of the attribute must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsattributesid-put-openapi.md
- name: plentymarkets REST-API - List barcodes
  x-api-slug: restitemsbarcodes-get
  description: Lists all barcodes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsbarcodes-get-openapi.md
- name: plentymarkets REST-API - Create a barcode
  x-api-slug: restitemsbarcodes-post
  description: Creates a barcode.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsbarcodes-post-openapi.md
- name: plentymarkets REST-API - List barcodes by referrer
  x-api-slug: restitemsbarcodesreferrerreferrerid-get
  description: Lists barcodes linked to the specified referrer. The ID of the referrer
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsbarcodesreferrerreferrerid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsbarcodesreferrerreferrerid-get-openapi.md
- name: plentymarkets REST-API - List barcodes by type
  x-api-slug: restitemsbarcodestypetype-get
  description: Lists all barcodes of a specific type. The type must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsbarcodestypetype-get-openapi.md
- name: plentymarkets REST-API - Delete a barcode
  x-api-slug: restitemsbarcodesbarcodeid-delete
  description: Deletes a barcode. The ID of the barcode must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsbarcodesbarcodeid-delete-openapi.md
- name: plentymarkets REST-API - Get a barcode
  x-api-slug: restitemsbarcodesbarcodeid-get
  description: Gets a barcode. The ID of the barcode must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsbarcodesbarcodeid-get-openapi.md
- name: plentymarkets REST-API - Update a barcode
  x-api-slug: restitemsbarcodesbarcodeid-put
  description: Updates a barcode. The ID of the barcode must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsbarcodesbarcodeid-put-openapi.md
- name: plentymarkets REST-API - Activate a referrer
  x-api-slug: restitemsbarcodesbarcodeidreferrer-post
  description: Activate a referrer for a barcode.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsbarcodesbarcodeidreferrer-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsbarcodesbarcodeidreferrer-post-openapi.md
- name: plentymarkets REST-API - Deactivate a referrer
  x-api-slug: restitemsbarcodesbarcodeidreferrerreferrerid-delete
  description: Deactivate a referrer for a barcode. The ID of the barcode and the
    ID of the referrer must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsbarcodesbarcodeidreferrerreferrerid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsbarcodesbarcodeidreferrerreferrerid-delete-openapi.md
- name: plentymarkets REST-API - List all shipping profiles of all items
  x-api-slug: restitemsitem-shipping-profiles-get
  description: |-
    Lists all shipping profiles of all items. Results can be filtered by the timestamp of the link between items and shipping profiles (eq, lt, lte, gt, gte, between).
    <ul>
    <li>eq = Equal to</li>
    <li>gte = Greater than or equal to</li>
    <li>gt = Greater than</li>
    <li>lte = Less than or equal to</li>
    <li>lt = Less than</li>
    <li>between = Date range</li>
    </ul>
    Example: updated=gt:2018-04-16 16:00:00 returns all items with shipping profiles that were activated after 4pm on the 16th of April 2018.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsitem-shipping-profiles-get-openapi.md
- name: plentymarkets REST-API - Bulk activate shipping profiles
  x-api-slug: restitemsitem-shipping-profiles-post
  description: Activates up to 50 shipping profiles for items
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsitem-shipping-profiles-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsitem-shipping-profiles-post-openapi.md
- name: plentymarkets REST-API - List item label templates
  x-api-slug: restitemslabels-get
  description: Lists the ID and name of all item label templates saved in the system.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemslabels-get-openapi.md
- name: plentymarkets REST-API - List manufacturers
  x-api-slug: restitemsmanufacturers-get
  description: |-
    Lists all manufacturers in the system.

    Display a listing of the resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsmanufacturers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsmanufacturers-get-openapi.md
- name: plentymarkets REST-API - Create a manufacturer
  x-api-slug: restitemsmanufacturers-post
  description: Creates a manufacturer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsmanufacturers-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsmanufacturers-post-openapi.md
- name: plentymarkets REST-API - Delete a manufacturer
  x-api-slug: restitemsmanufacturersid-delete
  description: Deletes a manufacturer. The ID of the manufacturer must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsmanufacturersid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsmanufacturersid-delete-openapi.md
- name: plentymarkets REST-API - Get a manufacturer
  x-api-slug: restitemsmanufacturersid-get
  description: Gets a manufacturer. The ID of the manufacturer must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsmanufacturersid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsmanufacturersid-get-openapi.md
- name: plentymarkets REST-API - Update a manufacturer
  x-api-slug: restitemsmanufacturersid-put
  description: Updates a manufacturer. The ID of the manufacturer must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsmanufacturersid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsmanufacturersid-put-openapi.md
- name: plentymarkets REST-API - List commissions
  x-api-slug: restitemsmanufacturersidcommissions-get
  description: Lists all commissions associated with a manufacturer. The ID of the
    manufacturer must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsmanufacturersidcommissions-get-openapi.md
- name: plentymarkets REST-API - Create a commission
  x-api-slug: restitemsmanufacturersidcommissions-post
  description: Creates a commission for a manufacturer. The ID of the manufacturer
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsmanufacturersidcommissions-post-openapi.md
- name: plentymarkets REST-API - Delete a commission
  x-api-slug: restitemsmanufacturersidcommissionsmanufacturerid-delete
  description: Delete a commission. The ID of the commission must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsmanufacturersidcommissionsmanufacturerid-delete-openapi.md
- name: plentymarkets REST-API - Get a commission
  x-api-slug: restitemsmanufacturersidcommissionsmanufacturerid-get
  description: Gets a commission for a manufacturer. The ID of the commission must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsmanufacturersidcommissionsmanufacturerid-get-openapi.md
- name: plentymarkets REST-API - Update a commission
  x-api-slug: restitemsmanufacturersidcommissionsmanufacturerid-put
  description: Updates a commission. The ID of the commission must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsmanufacturersidcommissionsmanufacturerid-put-openapi.md
- name: plentymarkets REST-API - List properties
  x-api-slug: restitemsproperties-get
  description: Lists all properties.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsproperties-get-openapi.md
- name: plentymarkets REST-API - Create a property
  x-api-slug: restitemsproperties-post
  description: Creates a property.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsproperties-post-openapi.md
- name: plentymarkets REST-API - Delete a property
  x-api-slug: restitemspropertiesid-delete
  description: Deletes a property. The ID of the property must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemspropertiesid-delete-openapi.md
- name: plentymarkets REST-API - Get a property
  x-api-slug: restitemspropertiesid-get
  description: Gets a property. The ID of the property must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemspropertiesid-get-openapi.md
- name: plentymarkets REST-API - Update a property
  x-api-slug: restitemspropertiesid-put
  description: Updates a property. The ID of the property must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemspropertiesid-put-openapi.md
- name: plentymarkets REST-API - List property market references
  x-api-slug: restitemspropertiesidmarket-references-get
  description: Lists the property market references of a property. The ID of the property
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemspropertiesidmarket-references-get-openapi.md
- name: plentymarkets REST-API - Create a property market reference
  x-api-slug: restitemspropertiesidmarket-references-post
  description: Creates a property market reference.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemspropertiesidmarket-references-post-openapi.md
- name: plentymarkets REST-API - Delete a property market reference
  x-api-slug: restitemspropertiesidmarket-referencesmarketid-delete
  description: Deletes a property market reference. The ID of the property and the
    ID of the market must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemspropertiesidmarket-referencesmarketid-delete-openapi.md
- name: plentymarkets REST-API - Get a property market reference
  x-api-slug: restitemspropertiesidmarket-referencesmarketid-get
  description: Gets a property market reference. The market ID and the property ID
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemspropertiesidmarket-referencesmarketid-get-openapi.md
- name: plentymarkets REST-API - Update a property market reference
  x-api-slug: restitemspropertiesidmarket-referencesmarketid-put
  description: Updates a property market reference.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemspropertiesidmarket-referencesmarketid-put-openapi.md
- name: plentymarkets REST-API - List the property names
  x-api-slug: restitemspropertiesidnames-get
  description: Lists the names of a property in all languages. The ID of the property
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemspropertiesidnames-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemspropertiesidnames-get-openapi.md
- name: plentymarkets REST-API - Create a property name
  x-api-slug: restitemspropertiesidnames-post
  description: Creates a property name. The ID of the property must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemspropertiesidnames-post-openapi.md
- name: plentymarkets REST-API - Delete a property name
  x-api-slug: restitemspropertiesidnameslang-delete
  description: Deletes a property name. The ID of the property must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemspropertiesidnameslang-delete-openapi.md
- name: plentymarkets REST-API - Get a property name
  x-api-slug: restitemspropertiesidnameslang-get
  description: Gets a property name in a specified language. The ID of the property
    and the language code must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemspropertiesidnameslang-get-openapi.md
- name: plentymarkets REST-API - Update a property name
  x-api-slug: restitemspropertiesidnameslang-put
  description: Updates a property name. The ID of the property and the language code
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemspropertiesidnameslang-put-openapi.md
- name: plentymarkets REST-API - List property selections
  x-api-slug: restitemspropertiespropertyidselections-get
  description: Lists the property selections of a property. The ID of the property
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemspropertiespropertyidselections-get-openapi.md
- name: plentymarkets REST-API - Create a property selection
  x-api-slug: restitemspropertiespropertyidselections-post
  description: Creates a property selection.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemspropertiespropertyidselections-post-openapi.md
- name: plentymarkets REST-API - Delete a property selection
  x-api-slug: restitemspropertiespropertyidselectionsid-delete
  description: Deletes a property selection. The ID of the property must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemspropertiespropertyidselectionsid-delete-openapi.md
- name: plentymarkets REST-API - Get a property selection
  x-api-slug: restitemspropertiespropertyidselectionsid-get
  description: Gets a property selection of a property.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemspropertiespropertyidselectionsid-get-openapi.md
- name: plentymarkets REST-API - Creates a property selection lang
  x-api-slug: restitemspropertiespropertyidselectionsid-post
  description: Creates a property selection lang.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemspropertiespropertyidselectionsid-post-openapi.md
- name: plentymarkets REST-API - Delete a property selection language
  x-api-slug: restitemspropertiespropertyidselectionsidlang-delete
  description: Deletes a property selection language. The ID of the selection and
    the language must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemspropertiespropertyidselectionsidlang-delete-openapi.md
- name: plentymarkets REST-API - List property selections by language
  x-api-slug: restitemspropertiespropertyidselectionsidlang-get
  description: Lists the property selections of a property for a specific language.
    The ID and language of the property must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemspropertiespropertyidselectionsidlang-get-openapi.md
- name: plentymarkets REST-API - Update a property selection
  x-api-slug: restitemspropertiespropertyidselectionsidlang-put
  description: Updates a property selection.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemspropertiespropertyidselectionsidlang-put-openapi.md
- name: plentymarkets REST-API - List property selections
  x-api-slug: restitemspropertiespropertyidselectionslang-get
  description: Lists the property selections of a property. The ID of the property
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemspropertiespropertyidselectionslang-get-openapi.md
- name: plentymarkets REST-API - List property groups
  x-api-slug: restitemsproperty-groups-get
  description: Lists the property groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsproperty-groups-get-openapi.md
- name: plentymarkets REST-API - Create a property group
  x-api-slug: restitemsproperty-groups-post
  description: Creates a property group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsproperty-groups-post-openapi.md
- name: plentymarkets REST-API - Delete a property group
  x-api-slug: restitemsproperty-groupsid-delete
  description: Deletes a property group. The ID of the property group must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsproperty-groupsid-delete-openapi.md
- name: plentymarkets REST-API - Get a property group
  x-api-slug: restitemsproperty-groupsid-get
  description: Gets a property group. The ID of the property group must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsproperty-groupsid-get-openapi.md
- name: plentymarkets REST-API - Update a property group
  x-api-slug: restitemsproperty-groupsid-put
  description: Updates an existing property group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsproperty-groupsid-put-openapi.md
- name: plentymarkets REST-API - List the property group names of a property group
  x-api-slug: restitemsproperty-groupsidnames-get
  description: Lists the property group names of a property group in all languages.
    The ID of the property group must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsproperty-groupsidnames-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsproperty-groupsidnames-get-openapi.md
- name: plentymarkets REST-API - Create a property group name
  x-api-slug: restitemsproperty-groupsidnames-post
  description: Creates a property group name. The ID of the property group must be
    specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsproperty-groupsidnames-post-openapi.md
- name: plentymarkets REST-API - Delete a property group name
  x-api-slug: restitemsproperty-groupsidnameslang-delete
  description: Deletes a property group name. The ID of the property group must be
    specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsproperty-groupsidnameslang-delete-openapi.md
- name: plentymarkets REST-API - Get a property group name in a language
  x-api-slug: restitemsproperty-groupsidnameslang-get
  description: Gets a property group name in the specified language. The ID of the
    property group name and the language code must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsproperty-groupsidnameslang-get-openapi.md
- name: plentymarkets REST-API - Update a property group name
  x-api-slug: restitemsproperty-groupsidnameslang-put
  description: Updates a property group name. The ID of the property group and the
    language must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsproperty-groupsidnameslang-put-openapi.md
- name: plentymarkets REST-API - List sales prices
  x-api-slug: restitemssales-prices-get
  description: Lists all sales prices.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemssales-prices-get-openapi.md
- name: plentymarkets REST-API - Create a sales price
  x-api-slug: restitemssales-prices-post
  description: Creates a sales price.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemssales-prices-post-openapi.md
- name: plentymarkets REST-API - Delete a sales price
  x-api-slug: restitemssales-pricesid-delete
  description: |-
    Deletes a sales price. The ID of the sales price must be specified.

    Delete salesPrice
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemssales-pricesid-delete-openapi.md
- name: plentymarkets REST-API - Get a sales price
  x-api-slug: restitemssales-pricesid-get
  description: Gets the data for a specific sales price. The ID of the sales price
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemssales-pricesid-get-openapi.md
- name: plentymarkets REST-API - Update a sales price
  x-api-slug: restitemssales-pricesid-put
  description: Updates a sales price.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemssales-pricesid-put-openapi.md
- name: plentymarkets REST-API - List referrer accounts
  x-api-slug: restitemssales-pricesidaccounts-get
  description: Lists all activated referrer accounts of a sales price.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemssales-pricesidaccounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemssales-pricesidaccounts-get-openapi.md
- name: plentymarkets REST-API - Activate a referrer account
  x-api-slug: restitemssales-pricesidaccounts-post
  description: Activates a referrer account for a sales price.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemssales-pricesidaccounts-post-openapi.md
- name: plentymarkets REST-API - Deactivate a referrer account
  x-api-slug: restitemssales-pricesidaccountsaccounttypeaccountid-delete
  description: Deactivates a referrer account for a sales price.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemssales-pricesidaccountsaccounttypeaccountid-delete-openapi.md
- name: plentymarkets REST-API - List countries by sales price
  x-api-slug: restitemssales-pricesidcountries-get
  description: Lists active countries for a sales price. The ID of the sales price
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemssales-pricesidcountries-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemssales-pricesidcountries-get-openapi.md
- name: plentymarkets REST-API - Activate a country
  x-api-slug: restitemssales-pricesidcountries-post
  description: Activates a country for a sales price.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemssales-pricesidcountries-post-openapi.md
- name: plentymarkets REST-API - Deactivate a country
  x-api-slug: restitemssales-pricesidcountriescountryid-delete
  description: Deactivates a country for a sales price.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemssales-pricesidcountriescountryid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemssales-pricesidcountriescountryid-delete-openapi.md
- name: plentymarkets REST-API - List activated currencies
  x-api-slug: restitemssales-pricesidcurrencies-get
  description: List all currencies activated for a sales price. The ID of the sales
    price must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemssales-pricesidcurrencies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemssales-pricesidcurrencies-get-openapi.md
- name: plentymarkets REST-API - Activate a currency
  x-api-slug: restitemssales-pricesidcurrencies-post
  description: Activates a currency for a sales price. The ID of the sales price must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemssales-pricesidcurrencies-post-openapi.md
- name: plentymarkets REST-API - Deactivate a currency
  x-api-slug: restitemssales-pricesidcurrenciescurrency-delete
  description: Deactivate a currency for a sales price. The ID of the sales price
    and the ISO code of the currency must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemssales-pricesidcurrenciescurrency-delete-openapi.md
- name: plentymarkets REST-API - List activated customer classes
  x-api-slug: restitemssales-pricesidcustomer-classes-get
  description: Lists the activated customer classes for a sales price. The ID of the
    sales price must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemssales-pricesidcustomer-classes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemssales-pricesidcustomer-classes-get-openapi.md
- name: plentymarkets REST-API - Activate a customer class
  x-api-slug: restitemssales-pricesidcustomer-classes-post
  description: Activates a customer class for a sales price. The ID of the sales price
    and the ID of the customer class must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemssales-pricesidcustomer-classes-post-openapi.md
- name: plentymarkets REST-API - Activate a customer class
  x-api-slug: restitemssales-pricesidcustomer-classescustomerclassid-delete
  description: Activates a customer class for a sales price. The ID of the sales price
    and the ID of the customer class must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemssales-pricesidcustomer-classescustomerclassid-delete-openapi.md
- name: plentymarkets REST-API - List names of a sales price
  x-api-slug: restitemssales-pricesidnames-get
  description: Lists the names of a sales price in all languages. The ID of the sales
    price must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemssales-pricesidnames-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemssales-pricesidnames-get-openapi.md
- name: plentymarkets REST-API - Create a sales price name
  x-api-slug: restitemssales-pricesidnames-post
  description: Creates a name for a sales price in the specified language. The ID
    of the sales price must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemssales-pricesidnames-post-openapi.md
- name: plentymarkets REST-API - Delete a sales price name
  x-api-slug: restitemssales-pricesidnameslang-delete
  description: Deletes the name of a sales price in the specified language. The ID
    of the sales price and the language code must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemssales-pricesidnameslang-delete-openapi.md
- name: plentymarkets REST-API - Gets a sales price name
  x-api-slug: restitemssales-pricesidnameslang-get
  description: Gets the sales price name of a sales price in the specified langauge.
    The ID of the sales price and the language code must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemssales-pricesidnameslang-get-openapi.md
- name: plentymarkets REST-API - Update a sales price name
  x-api-slug: restitemssales-pricesidnameslang-put
  description: Updates a sales price name in the specified language. The ID of the
    sales price and the language code must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemssales-pricesidnameslang-put-openapi.md
- name: plentymarkets REST-API - List activated clients (stores)
  x-api-slug: restitemssales-pricesidonline-stores-get
  description: Lists all activated clients (stores) for a sales price. The ID of the
    sales price must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemssales-pricesidonline-stores-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemssales-pricesidonline-stores-get-openapi.md
- name: plentymarkets REST-API - Activate a client (store)
  x-api-slug: restitemssales-pricesidonline-stores-post
  description: Activates a client (store) for a sales price. The ID of the sales price
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemssales-pricesidonline-stores-post-openapi.md
- name: plentymarkets REST-API - Deactivate a client (store)
  x-api-slug: restitemssales-pricesidonline-storeswebstoreid-delete
  description: Deactivates a client (store) for a sales price. The ID of the sales
    price and the ID of the client (store) must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemssales-pricesidonline-storeswebstoreid-delete-openapi.md
- name: plentymarkets REST-API - List activated referrers
  x-api-slug: restitemssales-pricesidreferrers-get
  description: Lists all activated referrers for a sales price. The ID of the sales
    price must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemssales-pricesidreferrers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemssales-pricesidreferrers-get-openapi.md
- name: plentymarkets REST-API - Activate a referrer
  x-api-slug: restitemssales-pricesidreferrers-post
  description: Activates a referrer for a sales price. The ID of the sales price must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemssales-pricesidreferrers-post-openapi.md
- name: plentymarkets REST-API - Deactivates a referrer
  x-api-slug: restitemssales-pricesidreferrersreferrerid-delete
  description: Deactivates a referrer for a sales price. The ID of the sales price
    and the ID of the referrer must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemssales-pricesidreferrersreferrerid-delete-openapi.md
- name: plentymarkets REST-API - List units
  x-api-slug: restitemsunits-get
  description: Lists all units.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsunits-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsunits-get-openapi.md
- name: plentymarkets REST-API - Create a unit
  x-api-slug: restitemsunits-post
  description: Creates a unit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsunits-post-openapi.md
- name: plentymarkets REST-API - Delete a unit
  x-api-slug: restitemsunitsid-delete
  description: Deletes a unit. The ID of the unit must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsunitsid-delete-openapi.md
- name: plentymarkets REST-API - Get a unit
  x-api-slug: restitemsunitsid-get
  description: Gets a unit. The ID of the unit must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsunitsid-get-openapi.md
- name: plentymarkets REST-API - Update a unit
  x-api-slug: restitemsunitsid-put
  description: Updates a unit. The ID of the unit must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsunitsid-put-openapi.md
- name: plentymarkets REST-API - List unit names
  x-api-slug: restitemsunitsidnames-get
  description: Lists the unit names of a unit. The ID of the unit must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsunitsidnames-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsunitsidnames-get-openapi.md
- name: plentymarkets REST-API - Create a unit name
  x-api-slug: restitemsunitsidnames-post
  description: Creates a unit name. The ID of the unit and the language must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsunitsidnames-post-openapi.md
- name: plentymarkets REST-API - Delete a unit name
  x-api-slug: restitemsunitsidnameslang-delete
  description: Deletes a unit name. The ID of the unit and the language must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsunitsidnameslang-delete-openapi.md
- name: plentymarkets REST-API - Get a unit name
  x-api-slug: restitemsunitsidnameslang-get
  description: Gets a unit name. The ID of the unit and the language must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsunitsidnameslang-get-openapi.md
- name: plentymarkets REST-API - Update a unit name
  x-api-slug: restitemsunitsidnameslang-put
  description: Updates a unit name. The ID of the unit and the language must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsunitsidnameslang-put-openapi.md
- name: plentymarkets REST-API - Search variations
  x-api-slug: restitemsvariations-get
  description: Search variations by different filters
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsvariations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsvariations-get-openapi.md
- name: plentymarkets REST-API - Bulk create category links
  x-api-slug: restitemsvariationsvariation-categories-post
  description: Creates up to 50 links between variations and categories. The ID of
    the variations and the ID of the categories must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsvariationsvariation-categories-post-openapi.md
- name: plentymarkets REST-API - Bulk update category links
  x-api-slug: restitemsvariationsvariation-categories-put
  description: Updates up to 50 links between variations and categories. The ID of
    the variations and the ID of the categories must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsvariationsvariation-categories-put-openapi.md
- name: plentymarkets REST-API - List all links between variations and markets
  x-api-slug: restitemsvariationsvariation-markets-get
  description: |-
    Lists all links between variations and markets.
    Results can be filtered by the ID of the variation and by the ID of the market, e.g. "variationId=1030"
    lists all links of the variation with the ID 1030.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsvariationsvariation-markets-get-openapi.md
- name: plentymarkets REST-API - Create up to 50 links between variations and markets
  x-api-slug: restitemsvariationsvariation-markets-post
  description: Creates up to 50 links between variations and markets. The ID of the
    variation and the ID of the market must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsvariationsvariation-markets-post-openapi.md
- name: plentymarkets REST-API - Bulk update properties
  x-api-slug: restitemsvariationsvariation-properties-post
  description: Creates up to 50 properties of variations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsvariationsvariation-properties-post-openapi.md
- name: plentymarkets REST-API - Bulk update properties
  x-api-slug: restitemsvariationsvariation-properties-put
  description: Updates up to 50 properties of variations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsvariationsvariation-properties-put-openapi.md
- name: plentymarkets REST-API - Get all sales price relations
  x-api-slug: restitemsvariationsvariation-sales-prices-get
  description: Gets all links between variations and sales prices including sales
    price data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsvariationsvariation-sales-prices-get-openapi.md
- name: plentymarkets REST-API - Bulk create prices
  x-api-slug: restitemsvariationsvariation-sales-prices-post
  description: Creates up to 50 prices of variations. The ID of the variation, the
    ID of the sales price and a price must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsvariationsvariation-sales-prices-post-openapi.md
- name: plentymarkets REST-API - Bulk update prices
  x-api-slug: restitemsvariationsvariation-sales-prices-put
  description: Updates up to 50 prices of variations. The ID of the variation, the
    ID of the sales price and a price must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsvariationsvariation-sales-prices-put-openapi.md
- name: plentymarkets REST-API - List images of an item
  x-api-slug: restitemsidimages-get
  description: Lists all images of an item. The item ID must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidimages-get-openapi.md
- name: plentymarkets REST-API - List attribute value image link
  x-api-slug: restitemsidimagesattribute-value-markets-get
  description: Lists the images linked to an attribute value.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidimagesattribute-value-markets-get-openapi.md
- name: plentymarkets REST-API - Upload a new image
  x-api-slug: restitemsidimagesupload-post
  description: Uploads an image. The item ID must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidimagesupload-post-openapi.md
- name: plentymarkets REST-API - Delete an image
  x-api-slug: restitemsidimagesimageid-delete
  description: Delete an image. The ID of the image must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidimagesimageid-delete-openapi.md
- name: plentymarkets REST-API - Get an image
  x-api-slug: restitemsidimagesimageid-get
  description: Gets an image. The ID of the image must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidimagesimageid-get-openapi.md
- name: plentymarkets REST-API - Update an image
  x-api-slug: restitemsidimagesimageid-put
  description: Updates an image. The ID of the image must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidimagesimageid-put-openapi.md
- name: plentymarkets REST-API - Create an attribute value image link
  x-api-slug: restitemsidimagesimageidattribute-value-markets-post
  description: Creates a link between an image and an attribute value.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidimagesimageidattribute-value-markets-post-openapi.md
- name: plentymarkets REST-API - Delete an attribute value image link
  x-api-slug: restitemsidimagesimageidattribute-value-marketsvalueid-delete
  description: Deletes the link between an image and an attribute value. The attribute
    ID must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidimagesimageidattribute-value-marketsvalueid-delete-openapi.md
- name: plentymarkets REST-API - Get an attribute value image link
  x-api-slug: restitemsidimagesimageidattribute-value-marketsvalueid-get
  description: 'Gets an attribute value image link. The following IDs must be specified:
    image ID, item ID and value ID.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidimagesimageidattribute-value-marketsvalueid-get-openapi.md
- name: plentymarkets REST-API - Update an attribute value image link
  x-api-slug: restitemsidimagesimageidattribute-value-marketsvalueid-put
  description: 'Updates the link between an image and an attribute value. The following
    IDs must be specified: image ID, item ID and value ID.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidimagesimageidattribute-value-marketsvalueid-put-openapi.md
- name: plentymarkets REST-API - Delete an availability
  x-api-slug: restitemsidimagesimageidavailabilities-delete
  description: Delete an availability for a specified value.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidimagesimageidavailabilities-delete-openapi.md
- name: plentymarkets REST-API - List availabilities
  x-api-slug: restitemsidimagesimageidavailabilities-get
  description: List all availabilities of an image. The image ID must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidimagesimageidavailabilities-get-openapi.md
- name: plentymarkets REST-API - Create an availability
  x-api-slug: restitemsidimagesimageidavailabilities-post
  description: Create an availability. The image ID must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidimagesimageidavailabilities-post-openapi.md
- name: plentymarkets REST-API - List names of an image
  x-api-slug: restitemsidimagesimageidnames-get
  description: Lists all names of an image. The image ID must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidimagesimageidnames-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidimagesimageidnames-get-openapi.md
- name: plentymarkets REST-API - Create an image name
  x-api-slug: restitemsidimagesimageidnames-post
  description: Create an image name. The ID, language and name of the image must be
    specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidimagesimageidnames-post-openapi.md
- name: plentymarkets REST-API - Delete an image name
  x-api-slug: restitemsidimagesimageidnameslang-delete
  description: Delete an image name. The ID and language of the image must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidimagesimageidnameslang-delete-openapi.md
- name: plentymarkets REST-API - Get an image name
  x-api-slug: restitemsidimagesimageidnameslang-get
  description: Gets an image name. The image ID and language must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidimagesimageidnameslang-get-openapi.md
- name: plentymarkets REST-API - Update an image name
  x-api-slug: restitemsidimagesimageidnameslang-put
  description: Update an image name. The ID, language and name of the image must be
    specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidimagesimageidnameslang-put-openapi.md
- name: plentymarkets REST-API - List image links of an image
  x-api-slug: restitemsidimagesimageidvariation-images-get
  description: Lists all variations linked to an image. The image ID must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidimagesimageidvariation-images-get-openapi.md
- name: plentymarkets REST-API - List cross-selling links
  x-api-slug: restitemsiditem-cross-selling-get
  description: Lists all cross-selling items linked to an item. The ID of the item
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsiditem-cross-selling-get-openapi.md
- name: plentymarkets REST-API - Create a cross-selling link
  x-api-slug: restitemsiditem-cross-selling-post
  description: Creates a cross-selling link.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsiditem-cross-selling-post-openapi.md
- name: plentymarkets REST-API - Delete a cross-selling link
  x-api-slug: restitemsiditem-cross-sellingcrossitemid-delete
  description: Deletes a cross-selling link. The ID of the item and the ID of the
    cross-selling item must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsiditem-cross-sellingcrossitemid-delete-openapi.md
- name: plentymarkets REST-API - List image links of an item
  x-api-slug: restitemsidvariation-images-get
  description: Lists all images linked to an item. The item ID must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariation-images-get-openapi.md
- name: plentymarkets REST-API - List texts
  x-api-slug: restitemsidvariationsvariationiddescriptions-get
  description: Lists the texts for an item in all available languages. The ID of the
    variation must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationiddescriptions-get-openapi.md
- name: plentymarkets REST-API - Create texts
  x-api-slug: restitemsidvariationsvariationiddescriptions-post
  description: Creates texts for an item. The ID of the variation and the language
    code must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationiddescriptions-post-openapi.md
- name: plentymarkets REST-API - Delete texts
  x-api-slug: restitemsidvariationsvariationiddescriptionslang-delete
  description: Deletes texts for an item in the specified language. The ID of the
    variation and the language code must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationiddescriptionslang-delete-openapi.md
- name: plentymarkets REST-API - Get texts
  x-api-slug: restitemsidvariationsvariationiddescriptionslang-get
  description: Gets the texts for an item in the specified language. The ID of the
    variation and the language code must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationiddescriptionslang-get-openapi.md
- name: plentymarkets REST-API - Update texts
  x-api-slug: restitemsidvariationsvariationiddescriptionslang-put
  description: Updates texts for an item in the specified language. The ID of the
    variation and the language code must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationiddescriptionslang-put-openapi.md
- name: plentymarkets REST-API - List images of a variation
  x-api-slug: restitemsidvariationsvariationidimages-get
  description: Lists all images of a variation. The variation ID must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidimages-get-openapi.md
- name: plentymarkets REST-API - Get a variation label
  x-api-slug: restitemsidvariationsvariationidlabels-post
  description: Gets a base64 encoded label for the specified variation ID. The labelId
    of the label template must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidlabels-post-openapi.md
- name: plentymarkets REST-API - List ident number of a variation
  x-api-slug: restitemsidvariationsvariationidmarket-ident-numbers-get
  description: Lists the ident number (ASIN/ePID) of a variation. The ID of the item
    and the ID of the variation must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidmarket-ident-numbers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidmarket-ident-numbers-get-openapi.md
- name: plentymarkets REST-API - Create a market ident number
  x-api-slug: restitemsidvariationsvariationidmarket-ident-numbers-post
  description: Creates a market ident number (ASIN/ePID) for a variation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidmarket-ident-numbers-post-openapi.md
- name: plentymarkets REST-API - Deletes a market ident number
  x-api-slug: restitemsidvariationsvariationidmarket-ident-numbersmarketidentnumberid-delete
  description: Deletes a market ident number (ASIN/ePID) of a variation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidmarket-ident-numbersmarketidentnumberid-delete-openapi.md
- name: plentymarkets REST-API - Get a market ident number
  x-api-slug: restitemsidvariationsvariationidmarket-ident-numbersmarketidentnumberid-get
  description: Gets a market ident number (ASIN/ePID) of a variation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidmarket-ident-numbersmarketidentnumberid-get-openapi.md
- name: plentymarkets REST-API - Updates a market ident number
  x-api-slug: restitemsidvariationsvariationidmarket-ident-numbersmarketidentnumberid-put
  description: Updates a market ident number (ASIN/ePID) of a variation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidmarket-ident-numbersmarketidentnumberid-put-openapi.md
- name: plentymarkets REST-API - List stock of a variation per warehouse
  x-api-slug: restitemsidvariationsvariationidstock-get
  description: Lists stock of a variation per warehouse. The ID of the item and the
    ID of the variation must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidstock-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidstock-get-openapi.md
- name: plentymarkets REST-API - Book incoming stock
  x-api-slug: restitemsidvariationsvariationidstockbookincomingitems-put
  description: Books incoming stock for a variation. The incoming stock will be added
    to the existing stock. The ID of the item and the ID of the variation must be
    specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidstockbookincomingitems-put-openapi.md
- name: plentymarkets REST-API - Correct stock
  x-api-slug: restitemsidvariationsvariationidstockcorrection-put
  description: Corrects stock. The item ID and the variation ID must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidstockcorrection-put-openapi.md
- name: plentymarkets REST-API - List stock movements
  x-api-slug: restitemsidvariationsvariationidstockmovements-get
  description: |-
    Lists stock movements for a variation. The ID of the item and the ID of the variation must be specified. To get movements older than 3 months, set the 'year' parameter.
    NOTE: You can either get archive entries or non-archive entries. You can not get entries for the current year that are younger and older than 3 months with one request. You need separate requests to get entries older and younger than 3 months. To get all entries younger than 3 month you do not need to specify a year or any createdAt parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidstockmovements-get-openapi.md
- name: plentymarkets REST-API - Redistribute stock
  x-api-slug: restitemsidvariationsvariationidstockredistribute-put
  description: Redistributes the stock of one storage location among one or more storage
    locations. The item ID and the variation ID need to be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidstockredistribute-put-openapi.md
- name: plentymarkets REST-API - List stock of a variation per storage locations
  x-api-slug: restitemsidvariationsvariationidstockstoragelocations-get
  description: Lists stock of a variation per storage location. The ID of the item
    and the ID of the variation must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidstockstoragelocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidstockstoragelocations-get-openapi.md
- name: plentymarkets REST-API - List additional SKUs
  x-api-slug: restitemsidvariationsvariationidvariation-additional-skus-get
  description: Lists the additional SKUs of a variation. Filters must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-additional-skus-get-openapi.md
- name: plentymarkets REST-API - Create an additional SKU
  x-api-slug: restitemsidvariationsvariationidvariation-additional-skus-post
  description: Creates an additional SKU. The ID of the variation must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-additional-skus-post-openapi.md
- name: plentymarkets REST-API - Delete an additional SKU
  x-api-slug: restitemsidvariationsvariationidvariation-additional-skusadditionalskuid-delete
  description: Deletes an additional SKU. The ID of the additional SKU must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-additional-skusadditionalskuid-delete-openapi.md
- name: plentymarkets REST-API - Gets an additional SKU
  x-api-slug: restitemsidvariationsvariationidvariation-additional-skusadditionalskuid-get
  description: Gets an additional SKU. The ID of the additional SKU must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-additional-skusadditionalskuid-get-openapi.md
- name: plentymarkets REST-API - Update an additional SKU
  x-api-slug: restitemsidvariationsvariationidvariation-additional-skusadditionalskuid-put
  description: Updates an additional SKU. The ID of the additional SKU must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-additional-skusadditionalskuid-put-openapi.md
- name: plentymarkets REST-API - List variation barcodes
  x-api-slug: restitemsidvariationsvariationidvariation-barcodes-get
  description: Lists all barcodes of a variation. The ID of the item and the ID of
    the variation must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-barcodes-get-openapi.md
- name: plentymarkets REST-API - Create a variation barcode
  x-api-slug: restitemsidvariationsvariationidvariation-barcodes-post
  description: Creates a variation barcode. The ID of the item, the ID of the variation,
    the ID of the barcode and the code must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-barcodes-post-openapi.md
- name: plentymarkets REST-API - Delete a variation barcode
  x-api-slug: restitemsidvariationsvariationidvariation-barcodesbarcodeid-delete
  description: Deletes a variation barcode. Unlinks the barcode from the variation
    and deletes the code saved for the variation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-barcodesbarcodeid-delete-openapi.md
- name: plentymarkets REST-API - Get a variation barcode
  x-api-slug: restitemsidvariationsvariationidvariation-barcodesbarcodeid-get
  description: Get a specific variation barcode. The ID of the item, the ID of the
    variation and the ID of the barcode must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-barcodesbarcodeid-get-openapi.md
- name: plentymarkets REST-API - Update a variation barcode
  x-api-slug: restitemsidvariationsvariationidvariation-barcodesbarcodeid-put
  description: Updates a variation barcode. The ID of the item, the ID of the variation,
    the ID of the barcode and the code must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-barcodesbarcodeid-put-openapi.md
- name: plentymarkets REST-API - List bundle components
  x-api-slug: restitemsidvariationsvariationidvariation-bundles-get
  description: List all components of a bundle. The ID of the item and the ID of the
    variation to which bundle components were added must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-bundles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-bundles-get-openapi.md
- name: plentymarkets REST-API - Add a variation to a bundle
  x-api-slug: restitemsidvariationsvariationidvariation-bundles-post
  description: Adds a variation to a bundle variation as a bundle component.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-bundles-post-openapi.md
- name: plentymarkets REST-API - Remove a bundle component
  x-api-slug: restitemsidvariationsvariationidvariation-bundlesbundleid-delete
  description: Removes a component from a bundle. The bundle ID must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-bundlesbundleid-delete-openapi.md
- name: plentymarkets REST-API - Get a variation bundle
  x-api-slug: restitemsidvariationsvariationidvariation-bundlesbundleid-get
  description: Gets the bundle information for a specific bundle component.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-bundlesbundleid-get-openapi.md
- name: plentymarkets REST-API - Update a variation bundle
  x-api-slug: restitemsidvariationsvariationidvariation-bundlesbundleid-put
  description: Updates a variation bundle component.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-bundlesbundleid-put-openapi.md
- name: plentymarkets REST-API - List categories linked to a variation
  x-api-slug: restitemsidvariationsvariationidvariation-categories-get
  description: Lists all categories linked to a variation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-categories-get-openapi.md
- name: plentymarkets REST-API - Link a category to a variation
  x-api-slug: restitemsidvariationsvariationidvariation-categories-post
  description: Creates a link between a category and a variation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-categories-post-openapi.md
- name: plentymarkets REST-API - Remove a category from a variation
  x-api-slug: restitemsidvariationsvariationidvariation-categoriescatid-delete
  description: Deletes the link between a category and a variation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-categoriescatid-delete-openapi.md
- name: plentymarkets REST-API - Get link between category and variation
  x-api-slug: restitemsidvariationsvariationidvariation-categoriescatid-get
  description: Gets the link between a category and a variation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-categoriescatid-get-openapi.md
- name: plentymarkets REST-API - Update variation category link
  x-api-slug: restitemsidvariationsvariationidvariation-categoriescatid-put
  description: Updates the link between a category and a variation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-categoriescatid-put-openapi.md
- name: plentymarkets REST-API - List clients linked to a variation
  x-api-slug: restitemsidvariationsvariationidvariation-clients-get
  description: Lists all clients (stores) linked to a variation. The ID of the variation
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-clients-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-clients-get-openapi.md
- name: plentymarkets REST-API - Link a client to a variation
  x-api-slug: restitemsidvariationsvariationidvariation-clients-post
  description: Creates a link between a client (store) and a variation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-clients-post-openapi.md
- name: plentymarkets REST-API - Unlink a client from a variation
  x-api-slug: restitemsidvariationsvariationidvariation-clientsplentyid-delete
  description: Deletes the link between a client (store) and a variation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-clientsplentyid-delete-openapi.md
- name: plentymarkets REST-API - List default category links
  x-api-slug: restitemsidvariationsvariationidvariation-default-categories-get
  description: Lists the default category of a variation for all clients (stores).
    The ID of the item and the ID of the variation must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-default-categories-get-openapi.md
- name: plentymarkets REST-API - Create a default category link
  x-api-slug: restitemsidvariationsvariationidvariation-default-categories-post
  description: Creates a link between a variation and a category that designates the
    category as the default category.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-default-categories-post-openapi.md
- name: plentymarkets REST-API - Delete a default category link
  x-api-slug: restitemsidvariationsvariationidvariation-default-categoriesplentyid-delete
  description: Deletes a link between a variation and a category that designates this
    category as the default category.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-default-categoriesplentyid-delete-openapi.md
- name: plentymarkets REST-API - Gets a default category link
  x-api-slug: restitemsidvariationsvariationidvariation-default-categoriesplentyid-get
  description: Gets the default category linked to a variation for the specified client
    (store). The ID of the item, the ID of the variation and the ID of the client
    (store) must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-default-categoriesplentyid-get-openapi.md
- name: plentymarkets REST-API - List image links of a variation
  x-api-slug: restitemsidvariationsvariationidvariation-images-get
  description: Lists all images linked to a variation. The variation ID must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-images-get-openapi.md
- name: plentymarkets REST-API - Create an image link
  x-api-slug: restitemsidvariationsvariationidvariation-images-post
  description: Creates a link between an image and a variation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-images-post-openapi.md
- name: plentymarkets REST-API - Delete an image link
  x-api-slug: restitemsidvariationsvariationidvariation-imagesimageid-delete
  description: Deletes a link between an image and a variation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-imagesimageid-delete-openapi.md
- name: plentymarkets REST-API - Delete all market links of one variation
  x-api-slug: restitemsidvariationsvariationidvariation-markets-delete
  description: Deletes all links of one variation. The ID of the variation must be
    specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-markets-delete-openapi.md
- name: plentymarkets REST-API - List markets linked to a variation
  x-api-slug: restitemsidvariationsvariationidvariation-markets-get
  description: Lists all markets linked to a variation. The ID of the item and the
    ID of the variation must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-markets-get-openapi.md
- name: plentymarkets REST-API - Create link between variation and market
  x-api-slug: restitemsidvariationsvariationidvariation-markets-post
  description: Creates a link between a variation and a market. The ID of the item,
    the ID of the variation and the ID of the market must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-markets-post-openapi.md
- name: plentymarkets REST-API - Delete link between variation and market
  x-api-slug: restitemsidvariationsvariationidvariation-marketsmarketplaceid-delete
  description: Deletes a link between a variation and a market. The ID of the item,
    the ID of the variation and the ID of the market must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-marketsmarketplaceid-delete-openapi.md
- name: plentymarkets REST-API - Deletes all links between a variation and its property
    values
  x-api-slug: restitemsidvariationsvariationidvariation-properties-delete
  description: Deletes all links between a variation and its property values. The
    ID of the variation must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-properties-delete-openapi.md
- name: plentymarkets REST-API - List property values linked to a variation
  x-api-slug: restitemsidvariationsvariationidvariation-properties-get
  description: Lists the property values linked to a variation. The ID of the item
    and the ID of the variation must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-properties-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-properties-get-openapi.md
- name: plentymarkets REST-API - Create link between variation and property value
  x-api-slug: restitemsidvariationsvariationidvariation-properties-post
  description: Creates a link between a variation and a property value.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-properties-post-openapi.md
- name: plentymarkets REST-API - Delete link between variation and property value
  x-api-slug: restitemsidvariationsvariationidvariation-propertiespropertyid-delete
  description: Delete a link between a variation and a property value. The ID of the
    item, the ID of the variation and the ID of the property must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-propertiespropertyid-delete-openapi.md
- name: plentymarkets REST-API - Get a property value
  x-api-slug: restitemsidvariationsvariationidvariation-propertiespropertyid-get
  description: Gets a property value linked to a variation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-propertiespropertyid-get-openapi.md
- name: plentymarkets REST-API - Update a property value
  x-api-slug: restitemsidvariationsvariationidvariation-propertiespropertyid-put
  description: Update the data of a property value linked to a variation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-propertiespropertyid-put-openapi.md
- name: plentymarkets REST-API - Delete all links between a variation and its sales
    prices
  x-api-slug: restitemsidvariationsvariationidvariation-sales-prices-delete
  description: Deletes all links between a variation and its sales prices and deletes
    the sales price data. The ID of the variation must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-sales-prices-delete-openapi.md
- name: plentymarkets REST-API - List sales prices of a variation
  x-api-slug: restitemsidvariationsvariationidvariation-sales-prices-get
  description: Lists the sales prices of a variation. The ID of the variation must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-sales-prices-get-openapi.md
- name: plentymarkets REST-API - Create link between variation and sales price
  x-api-slug: restitemsidvariationsvariationidvariation-sales-prices-post
  description: Creates a link between a variation and a sales price and adds sales
    price data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-sales-prices-post-openapi.md
- name: plentymarkets REST-API - Delete link between variation and sales price
  x-api-slug: restitemsidvariationsvariationidvariation-sales-pricespriceid-delete
  description: Deletes a link between a variation and a sales price and deletes the
    sales price data. The ID of the sales price and the ID of the variation must be
    specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-sales-pricespriceid-delete-openapi.md
- name: plentymarkets REST-API - Get sales price data for a variation
  x-api-slug: restitemsidvariationsvariationidvariation-sales-pricespriceid-get
  description: Gets sales price data linked to a variation. The ID of the sales price
    and the ID of the variation must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-sales-pricespriceid-get-openapi.md
- name: plentymarkets REST-API - Update sales price data
  x-api-slug: restitemsidvariationsvariationidvariation-sales-pricespriceid-put
  description: Updates sales price data linked to a variation. The ID of the sales
    price and the ID of the variation must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-sales-pricespriceid-put-openapi.md
- name: plentymarkets REST-API - List SKUs
  x-api-slug: restitemsidvariationsvariationidvariation-skus-get
  description: Lists the SKUs of a variation. Filters must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-skus-get-openapi.md
- name: plentymarkets REST-API - Create an SKU
  x-api-slug: restitemsidvariationsvariationidvariation-skus-post
  description: Creates an SKU. The ID of the variation must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-skus-post-openapi.md
- name: plentymarkets REST-API - Delete an SKU
  x-api-slug: restitemsidvariationsvariationidvariation-skusskuid-delete
  description: Deletes an SKU. The ID of the SKU must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-skusskuid-delete-openapi.md
- name: plentymarkets REST-API - Get an SKU
  x-api-slug: restitemsidvariationsvariationidvariation-skusskuid-get
  description: Gets an SKU. The ID of the SKU must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-skusskuid-get-openapi.md
- name: plentymarkets REST-API - Update an SKU
  x-api-slug: restitemsidvariationsvariationidvariation-skusskuid-put
  description: Updates an SKU. The ID of the SKU must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-skusskuid-put-openapi.md
- name: plentymarkets REST-API - Lists suppliers for a variation
  x-api-slug: restitemsidvariationsvariationidvariation-suppliers-get
  description: Lists all supplier data linked to a variation. The ID of the variation
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-suppliers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-suppliers-get-openapi.md
- name: plentymarkets REST-API - Create a link between variation and supplier
  x-api-slug: restitemsidvariationsvariationidvariation-suppliers-post
  description: Creates a link between a variation and a supplier and adds supplier
    data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-suppliers-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-suppliers-post-openapi.md
- name: plentymarkets REST-API - Delete link between variation and supplier
  x-api-slug: restitemsidvariationsvariationidvariation-suppliersvariationsupplierid-delete
  description: Deletes a link between a variation and a supplier. The ID of the variation
    and the ID of the link between the variation and the supplier must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-suppliersvariationsupplierid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-suppliersvariationsupplierid-delete-openapi.md
- name: plentymarkets REST-API - Get supplier data for a variation
  x-api-slug: restitemsidvariationsvariationidvariation-suppliersvariationsupplierid-get
  description: Gets the data for a supplier linked to a variation. The ID of the variation
    and the ID of the link between the variation and the supplier must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-suppliersvariationsupplierid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-suppliersvariationsupplierid-get-openapi.md
- name: plentymarkets REST-API - Updates supplier data for a variation
  x-api-slug: restitemsidvariationsvariationidvariation-suppliersvariationsupplierid-put
  description: Updates the data of a supplier linked to a variation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-suppliersvariationsupplierid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-suppliersvariationsupplierid-put-openapi.md
- name: plentymarkets REST-API - List the warehouses linked to a variation
  x-api-slug: restitemsidvariationsvariationidvariation-warehouses-get
  description: Lists the warehouses linked to a variation. The ID of the item and
    the ID of the variation must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-warehouses-get-openapi.md
- name: plentymarkets REST-API - Create link between a variation and a warehouse
  x-api-slug: restitemsidvariationsvariationidvariation-warehouses-post
  description: Creates a link between a variation and a warehouse and adds warehouse
    data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-warehouses-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-warehouses-post-openapi.md
- name: plentymarkets REST-API - Delete link between a warehouse and a variation
  x-api-slug: restitemsidvariationsvariationidvariation-warehouseswarehouseid-delete
  description: Deletes the link between a warehouse and a variation. The ID of the
    variation and the ID of the warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-warehouseswarehouseid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-warehouseswarehouseid-delete-openapi.md
- name: plentymarkets REST-API - Get warehouse data for a variation
  x-api-slug: restitemsidvariationsvariationidvariation-warehouseswarehouseid-get
  description: Gets the data of a warehouse linked to a variation. The ID of the variation
    and the ID of the warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-warehouseswarehouseid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-warehouseswarehouseid-get-openapi.md
- name: plentymarkets REST-API - Update warehouse data of a variation
  x-api-slug: restitemsidvariationsvariationidvariation-warehouseswarehouseid-put
  description: Updates the data of a warehouse linked to a variation. The ID of the
    variation and the ID of the warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-warehouseswarehouseid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-warehouseswarehouseid-put-openapi.md
- name: plentymarkets REST-API - Delete an item
  x-api-slug: restitemsitemid-delete
  description: Deletes an item. The ID of the item must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsitemid-delete-openapi.md
- name: plentymarkets REST-API - Show an item
  x-api-slug: restitemsitemid-get
  description: Show an item by itemId
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsitemid-get-openapi.md
- name: plentymarkets REST-API - Update a item
  x-api-slug: restitemsitemid-put
  description: Updates a item. The ID of the item must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsitemid-put-openapi.md
- name: plentymarkets REST-API - Deactivate shipping profiles of an item
  x-api-slug: restitemsitemiditem-shipping-profiles-delete
  description: Deactivates all shipping profiles of an item. The ID of the item must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsitemiditem-shipping-profiles-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsitemiditem-shipping-profiles-delete-openapi.md
- name: plentymarkets REST-API - List shipping profiles of an item
  x-api-slug: restitemsitemiditem-shipping-profiles-get
  description: Lists the shipping profiles linked to an item. The ID of the item must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsitemiditem-shipping-profiles-get-openapi.md
- name: plentymarkets REST-API - Activate a shipping profile
  x-api-slug: restitemsitemiditem-shipping-profiles-post
  description: Links a shipping profile to the item. The ID of the item and the ID
    of the shipping profile must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsitemiditem-shipping-profiles-post-openapi.md
- name: plentymarkets REST-API - Deactivate a shipping profile
  x-api-slug: restitemsitemiditem-shipping-profilesid-delete
  description: Unlinks a shipping profile from the item. The ID of the item must be
    specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsitemiditem-shipping-profilesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsitemiditem-shipping-profilesid-delete-openapi.md
- name: plentymarkets REST-API - List variations of an item
  x-api-slug: restitemsitemidvariations-get
  description: Lists all variations of an item. The ID of the item must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsitemidvariations-get-openapi.md
- name: plentymarkets REST-API - Create a variation
  x-api-slug: restitemsitemidvariations-post
  description: Create a variation. The ID of the item must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsitemidvariations-post-openapi.md
- name: plentymarkets REST-API - Delete a variation
  x-api-slug: restitemsitemidvariationsvariationid-delete
  description: Delete a variation. The ID of the item and the ID of the variation
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsitemidvariationsvariationid-delete-openapi.md
- name: plentymarkets REST-API - Get a variation
  x-api-slug: restitemsitemidvariationsvariationid-get
  description: Get a variation. The ID of the item and the ID of the variation must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsitemidvariationsvariationid-get-openapi.md
- name: plentymarkets REST-API - Update a variation
  x-api-slug: restitemsitemidvariationsvariationid-put
  description: Updates a variation. The ID of the variation must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsitemidvariationsvariationid-put-openapi.md
- name: plentymarkets REST-API - Get property value texts
  x-api-slug: restitemsitemidvariationsvariationidvariation-propertiespropertyidtexts-get
  description: Gets the texts saved for a specific property of the type Text in all
    available languages. The ID of the property must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsitemidvariationsvariationidvariation-propertiespropertyidtexts-get-openapi.md
- name: plentymarkets REST-API - Create property value text by language
  x-api-slug: restitemsitemidvariationsvariationidvariation-propertiespropertyidtexts-post
  description: Saves text for a specific property of the type Text in the specified
    language. The ID of the property and the language must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsitemidvariationsvariationidvariation-propertiespropertyidtexts-post-openapi.md
- name: plentymarkets REST-API - Delete property value text by language
  x-api-slug: restitemsitemidvariationsvariationidvariation-propertiespropertyidtextslang-delete
  description: Deletes the text saved for a specific property of the type Text in
    the specified language. The ID of the property  and the language must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsitemidvariationsvariationidvariation-propertiespropertyidtextslang-delete-openapi.md
- name: plentymarkets REST-API - Get property value text by language
  x-api-slug: restitemsitemidvariationsvariationidvariation-propertiespropertyidtextslang-get
  description: Gets the value text saved for a specific property of the type Text
    in the specified language. The ID of the property  and the language must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsitemidvariationsvariationidvariation-propertiespropertyidtextslang-get-openapi.md
- name: plentymarkets REST-API - Update property value text by language
  x-api-slug: restitemsitemidvariationsvariationidvariation-propertiespropertyidtextslang-put
  description: Updates the text saved for a specific property of the type Text in
    the specified language. The ID of the property and the language must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restitemsitemidvariationsvariationidvariation-propertiespropertyidtextslang-put-openapi.md
- name: plentymarkets REST-API - Create a new translation
  x-api-slug: restlanguagestranslations-post
  description: Creates a new translation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlanguagestranslations-post-openapi.md
- name: plentymarkets REST-API - Delete a translation
  x-api-slug: restlanguagestranslationstranslationid-delete
  description: Deletes a translation. The ID of the translation must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlanguagestranslationstranslationid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlanguagestranslationstranslationid-delete-openapi.md
- name: plentymarkets REST-API - Get a translation
  x-api-slug: restlanguagestranslationstranslationid-get
  description: Gets a translation. The ID of the translation must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlanguagestranslationstranslationid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlanguagestranslationstranslationid-get-openapi.md
- name: plentymarkets REST-API - Update a translation
  x-api-slug: restlanguagestranslationstranslationid-put
  description: Updates a translation. The ID of the translation must be specified
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlanguagestranslationstranslationid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlanguagestranslationstranslationid-put-openapi.md
- name: plentymarkets REST-API - Get legal information of an online store
  x-api-slug: restlegalinformationplentyidlangtype-get
  description: Gets legal information of an online store. The plenty ID of the store
    , the language and the type of legal information must be specified. The language
    must be specified as ISO 639-1 code.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlegalinformationplentyidlangtype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlegalinformationplentyidlangtype-get-openapi.md
- name: plentymarkets REST-API - Save legal information for an online store
  x-api-slug: restlegalinformationplentyidlangtype-put
  description: |-
    Saves a legal information for an online store. The plenty ID of the online store, the language of the legal information and the type of the legal information must be specified. The language must be specified as ISO 639-1 code.
    Existing legal information will be overwritten.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlegalinformationplentyidlangtype-put-openapi.md
- name: plentymarkets REST-API - List listing
  x-api-slug: restlistings-get
  description: Lists listings by filter options.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistings-get-openapi.md
- name: plentymarkets REST-API - Create new listing
  x-api-slug: restlistings-post
  description: Creates a new listing.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistings-post-openapi.md
- name: plentymarkets REST-API - Create new layout template
  x-api-slug: restlistingslayout-templates-post
  description: Creates a new layout template.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingslayout-templates-post-openapi.md
- name: plentymarkets REST-API - Delete a layout template
  x-api-slug: restlistingslayout-templatesid-delete
  description: Deletes a layout template by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingslayout-templatesid-delete-openapi.md
- name: plentymarkets REST-API - Get a layout template
  x-api-slug: restlistingslayout-templatesid-get
  description: Gets a layout template by providing its ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingslayout-templatesid-get-openapi.md
- name: plentymarkets REST-API - List listing markets
  x-api-slug: restlistingsmarkets-get
  description: Lists listing market by filter options.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsmarkets-get-openapi.md
- name: plentymarkets REST-API - Create new listing market
  x-api-slug: restlistingsmarkets-post
  description: |-
    Creates a new listing market. Based on the given options this call can create multiple listing markets. If the
    'optionTemplateId' parameter is provided and the listing option template includes options for different markets
    than one listing market will be created for each market.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsmarkets-post-openapi.md
- name: plentymarkets REST-API - Get all listing market directories
  x-api-slug: restlistingsmarketsdirectories-get
  description: Gets all listing market directories.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsmarketsdirectories-get-openapi.md
- name: plentymarkets REST-API - Create listing market directory
  x-api-slug: restlistingsmarketsdirectories-post
  description: Creates a listing market directory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsmarketsdirectories-post-openapi.md
- name: plentymarkets REST-API - Delete listing market directory
  x-api-slug: restlistingsmarketsdirectoriesid-delete
  description: Deletes a listing market directory by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsmarketsdirectoriesid-delete-openapi.md
- name: plentymarkets REST-API - Get a listing market directory
  x-api-slug: restlistingsmarketsdirectoriesid-get
  description: Gets a listing market directory by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsmarketsdirectoriesid-get-openapi.md
- name: plentymarkets REST-API - Update listing market directory
  x-api-slug: restlistingsmarketsdirectoriesid-put
  description: Updates a listing market directory by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsmarketsdirectoriesid-put-openapi.md
- name: plentymarkets REST-API - Find listing markets
  x-api-slug: restlistingsmarketsfind-get
  description: Lists listing market by filter options.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsmarketsfind-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsmarketsfind-get-openapi.md
- name: plentymarkets REST-API - List listing market history
  x-api-slug: restlistingsmarketshistories-get
  description: Lists listing market history by filter options.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsmarketshistories-get-openapi.md
- name: plentymarkets REST-API - End the listing
  x-api-slug: restlistingsmarketshistoriesendid-delete
  description: Ends the listing on the designated market.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsmarketshistoriesendid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsmarketshistoriesendid-delete-openapi.md
- name: plentymarkets REST-API - Relist the listing
  x-api-slug: restlistingsmarketshistoriesrelistid-post
  description: Relists the listing on the designated market.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsmarketshistoriesrelistid-post-openapi.md
- name: plentymarkets REST-API - Update listing market histories
  x-api-slug: restlistingsmarketshistoriesupdateid-put
  description: |-
    Updates listing market histories by given update options. The listing market histories are not directly revised,
    they are added to the batch processing lists, waiting to be revised by automated background processes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsmarketshistoriesupdateid-put-openapi.md
- name: plentymarkets REST-API - Get a listing market history
  x-api-slug: restlistingsmarketshistoriesid-get
  description: Gets a listing market history by given ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsmarketshistoriesid-get-openapi.md
- name: plentymarkets REST-API - Search listing market info
  x-api-slug: restlistingsmarketsinfos-get
  description: Search listing market info by filter options.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsmarketsinfos-get-openapi.md
- name: plentymarkets REST-API - Gets all ListingMarketItemSpecifics.
  x-api-slug: restlistingsmarketsitem-specifics-get
  description: Can be filtered by ID, listingMarketId, name and value.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsmarketsitem-specifics-get-openapi.md
- name: plentymarkets REST-API - Deletes a ListingMarketItemSpecific.
  x-api-slug: restlistingsmarketsitem-specificsid-delete
  description: Deletes a listingmarketitemspecific..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsmarketsitem-specificsid-delete-openapi.md
- name: plentymarkets REST-API - Gets a ListingMarketItemSpecific.
  x-api-slug: restlistingsmarketsitem-specificsid-get
  description: Gets a listingmarketitemspecific..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsmarketsitem-specificsid-get-openapi.md
- name: plentymarkets REST-API - Updates a ListingMarketItemSpecific.
  x-api-slug: restlistingsmarketsitem-specificsid-put
  description: Updates a listingmarketitemspecific..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsmarketsitem-specificsid-put-openapi.md
- name: plentymarkets REST-API - Start the market listing on the designated market.
  x-api-slug: restlistingsmarketsstartid-post
  description: Starts the market listing on the designated markets.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsmarketsstartid-post-openapi.md
- name: plentymarkets REST-API - List listing market texts
  x-api-slug: restlistingsmarketstexts-get
  description: Lists listing market texts by filter options.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsmarketstexts-get-openapi.md
- name: plentymarkets REST-API - Create a listing market text
  x-api-slug: restlistingsmarketstexts-post
  description: Creates a listing market text for a given listing market ID. If an
    entry with same data already exists the request will be ignored and the old entry
    will be returned.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsmarketstexts-post-openapi.md
- name: plentymarkets REST-API - Delete a listing market text
  x-api-slug: restlistingsmarketstextsid-delete
  description: Deletes a listing market text for a given listing market text ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsmarketstextsid-delete-openapi.md
- name: plentymarkets REST-API - Get a listing market text
  x-api-slug: restlistingsmarketstextsid-get
  description: Gets a listing market text by providing its ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsmarketstextsid-get-openapi.md
- name: plentymarkets REST-API - Update a listing market text
  x-api-slug: restlistingsmarketstextslistingmarketidlang-put
  description: Updates a listing market text for a given listing market ID and language.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsmarketstextslistingmarketidlang-put-openapi.md
- name: plentymarkets REST-API - Verify listing markets
  x-api-slug: restlistingsmarketsverifyid-post
  description: Verifies the listing markets.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsmarketsverifyid-post-openapi.md
- name: plentymarkets REST-API - Delete listing market
  x-api-slug: restlistingsmarketsid-delete
  description: Deletes a listing market by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsmarketsid-delete-openapi.md
- name: plentymarkets REST-API - Get a listing market
  x-api-slug: restlistingsmarketsid-get
  description: Gets a listing market by given ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsmarketsid-get-openapi.md
- name: plentymarkets REST-API - Update a listing market
  x-api-slug: restlistingsmarketsid-put
  description: Updates a listing market by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsmarketsid-put-openapi.md
- name: plentymarkets REST-API - Create option template
  x-api-slug: restlistingsoption-templates-post
  description: Creates an option template.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsoption-templates-post-openapi.md
- name: plentymarkets REST-API - Get a preview list of option templates
  x-api-slug: restlistingsoption-templatespreview-get
  description: Gets a preview list of all available listing option templates.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsoption-templatespreview-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsoption-templatespreview-get-openapi.md
- name: plentymarkets REST-API - Delete option template
  x-api-slug: restlistingsoption-templatesid-delete
  description: Deletes an option template by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsoption-templatesid-delete-openapi.md
- name: plentymarkets REST-API - Get option template
  x-api-slug: restlistingsoption-templatesid-get
  description: Gets an option template by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsoption-templatesid-get-openapi.md
- name: plentymarkets REST-API - Update option template
  x-api-slug: restlistingsoption-templatesid-put
  description: Updates an option template by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsoption-templatesid-put-openapi.md
- name: plentymarkets REST-API - List listing shipping profiles
  x-api-slug: restlistingsshipping-profiles-get
  description: Lists listing shipping profiles.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsshipping-profiles-get-openapi.md
- name: plentymarkets REST-API - Get a shipping profile
  x-api-slug: restlistingsshipping-profilesid-get
  description: Gets a shipping profile by providing its ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsshipping-profilesid-get-openapi.md
- name: plentymarkets REST-API - List listing stock dependence types
  x-api-slug: restlistingsstock-dependence-types-get
  description: Lists listing stock dependence types.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsstock-dependence-types-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsstock-dependence-types-get-openapi.md
- name: plentymarkets REST-API - Get a listing stock dependence type
  x-api-slug: restlistingsstock-dependence-typesid-get
  description: Gets a listing stock dependence type by given ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsstock-dependence-typesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsstock-dependence-typesid-get-openapi.md
- name: plentymarkets REST-API - List listing types
  x-api-slug: restlistingstypes-get
  description: Lists all listing types.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingstypes-get-openapi.md
- name: plentymarkets REST-API - Get a listing type
  x-api-slug: restlistingstypesid-get
  description: Gets a listing type by given ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingstypesid-get-openapi.md
- name: plentymarkets REST-API - Delete a listing
  x-api-slug: restlistingsid-delete
  description: Deletes a listing by given ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsid-delete-openapi.md
- name: plentymarkets REST-API - Get a listing
  x-api-slug: restlistingsid-get
  description: Gets a listing by given ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsid-get-openapi.md
- name: plentymarkets REST-API - Update a listing
  x-api-slug: restlistingsid-put
  description: Updates a listing by given ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlistingsid-put-openapi.md
- name: plentymarkets REST-API - Login
  x-api-slug: restlogin-post
  description: Logs in to plentymarkets with your back end user credentials. The login
    call returns a JSON object that contains information, such as the access token
    and the refresh token.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlogin-post-openapi.md
- name: plentymarkets REST-API - Refresh
  x-api-slug: restloginrefresh-post
  description: Refreshes the access token using the refresh token. The refresh token
    is part of the login call response.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restloginrefresh-post-openapi.md
- name: plentymarkets REST-API - Logout
  x-api-slug: restlogout-post
  description: Logs out the back end user from plentymarkets. The access token expires.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlogout-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlogout-post-openapi.md
- name: plentymarkets REST-API - Perform a search operation.
  x-api-slug: restlogs-get
  description: Perform a search operation..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlogs-get-openapi.md
- name: plentymarkets REST-API - Create a log entry.
  x-api-slug: restlogs-post
  description: Create a log entry..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlogs-post-openapi.md
- name: 'plentymarkets REST-API - '
  x-api-slug: restlogsintegration-keys-get
  description: .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlogsintegration-keys-get-openapi.md
- name: plentymarkets REST-API - Get all registered reference types.
  x-api-slug: restlogsreference-types-get
  description: Get all registered reference types..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlogsreference-types-get-openapi.md
- name: plentymarkets REST-API - Show config.
  x-api-slug: restlogssettings-get
  description: Show config..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlogssettings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlogssettings-get-openapi.md
- name: plentymarkets REST-API - Save config.
  x-api-slug: restlogssettings-post
  description: Save config..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlogssettings-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlogssettings-post-openapi.md
- name: plentymarkets REST-API - Get Log entry by ID.
  x-api-slug: restlogsid-get
  description: Get log entry by id..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restlogsid-get-openapi.md
- name: plentymarkets REST-API - List credentials
  x-api-slug: restmarketscredentials-get
  description: List credentials.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restmarketscredentials-get-openapi.md
- name: plentymarkets REST-API - Create a credential
  x-api-slug: restmarketscredentials-post
  description: Create a new credential with the given data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restmarketscredentials-post-openapi.md
- name: plentymarkets REST-API - Delete a credential
  x-api-slug: restmarketscredentialscredentialsid-delete
  description: Deletes a credential by given ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restmarketscredentialscredentialsid-delete-openapi.md
- name: plentymarkets REST-API - Get a credential
  x-api-slug: restmarketscredentialscredentialsid-get
  description: Get a credential.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restmarketscredentialscredentialsid-get-openapi.md
- name: plentymarkets REST-API - Update a credential
  x-api-slug: restmarketscredentialscredentialsid-put
  description: Update a credential with the given data and ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restmarketscredentialscredentialsid-put-openapi.md
- name: plentymarkets REST-API - Get the login url.
  x-api-slug: restmarketsebayauthlogin-get
  description: Get the login url..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restmarketsebayauthlogin-get-openapi.md
- name: plentymarkets REST-API - Refresh an expired access token.
  x-api-slug: restmarketsebayauthrefreshtoken-put
  description: Refresh an expired access token..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restmarketsebayauthrefreshtoken-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restmarketsebayauthrefreshtoken-put-openapi.md
- name: plentymarkets REST-API - List categories
  x-api-slug: restmarketsebaycategories-get
  description: Lists categories. By passing category ID as filter, only subcategories
    of that category will be returned. The marketplace ID filter is required.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restmarketsebaycategories-get-openapi.md
- name: plentymarkets REST-API - Get category
  x-api-slug: restmarketsebaycategoriesid-get
  description: Get category for given ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restmarketsebaycategoriesid-get-openapi.md
- name: plentymarkets REST-API - Get fulfillment policy
  x-api-slug: restmarketsebayfulfillment-policiesid-get
  description: Get fulfillment policy for given ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restmarketsebayfulfillment-policiesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restmarketsebayfulfillment-policiesid-get-openapi.md
- name: plentymarkets REST-API - List item specifics
  x-api-slug: restmarketsebayitem-specifics-get
  description: List item specifics for a given category Id and referrerId.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restmarketsebayitem-specifics-get-openapi.md
- name: plentymarkets REST-API - Get all eBay marketplaces.
  x-api-slug: restmarketsebaymarketplaces-get
  description: List eBay marketplaces. Use filters to find specific ones.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restmarketsebaymarketplaces-get-openapi.md
- name: plentymarkets REST-API - List fitments
  x-api-slug: restmarketsebaypartsfitments-get
  description: Lists fitments.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restmarketsebaypartsfitments-get-openapi.md
- name: plentymarkets REST-API - Create a fitment
  x-api-slug: restmarketsebaypartsfitments-post
  description: Create a new fitment for the given data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restmarketsebaypartsfitments-post-openapi.md
- name: plentymarkets REST-API - Search fitments
  x-api-slug: restmarketsebaypartsfitmentssearch-get
  description: Search fitments by filter options.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restmarketsebaypartsfitmentssearch-get-openapi.md
- name: plentymarkets REST-API - Delete a fitment.
  x-api-slug: restmarketsebaypartsfitmentsfitmentid-delete
  description: Deletes a fitment. The ID of the fitment must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restmarketsebaypartsfitmentsfitmentid-delete-openapi.md
- name: plentymarkets REST-API - Get a fitment
  x-api-slug: restmarketsebaypartsfitmentsfitmentid-get
  description: Gets a fitment. The id of the fitment must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restmarketsebaypartsfitmentsfitmentid-get-openapi.md
- name: plentymarkets REST-API - Update fitment.
  x-api-slug: restmarketsebaypartsfitmentsfitmentid-put
  description: Updates a fitment. Items that do not occur anymore will be replaced.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restmarketsebaypartsfitmentsfitmentid-put-openapi.md
- name: plentymarkets REST-API - Get payment policy
  x-api-slug: restmarketsebaypayment-policiesid-get
  description: Get payment policy for given ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restmarketsebaypayment-policiesid-get-openapi.md
- name: plentymarkets REST-API - Get return policy
  x-api-slug: restmarketsebayreturn-policiesid-get
  description: Get return policy for given ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restmarketsebayreturn-policiesid-get-openapi.md
- name: plentymarkets REST-API - List all eBay shop categories
  x-api-slug: restmarketsebayshop-categories-get
  description: Lists all eBay shop categories.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restmarketsebayshop-categories-get-openapi.md
- name: plentymarkets REST-API - List market settings
  x-api-slug: restmarketssettings-get
  description: Lists market settings. The marketplace ID and the type must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restmarketssettings-get-openapi.md
- name: plentymarkets REST-API - Create market settings
  x-api-slug: restmarketssettings-post
  description: Creates new market settings by given data. The marketplace ID and the
    type must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restmarketssettings-post-openapi.md
- name: plentymarkets REST-API - Create market settings
  x-api-slug: restmarketssettingsbulk-post
  description: Creates new market settings by given data. The marketplace ID and the
    type must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restmarketssettingsbulk-post-openapi.md
- name: plentymarkets REST-API - Update market settings
  x-api-slug: restmarketssettingsbulk-put
  description: Updates market settings. The market settings ID must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restmarketssettingsbulk-put-openapi.md
- name: plentymarkets REST-API - List correlation
  x-api-slug: restmarketssettingscorrelations-get
  description: Lists correlations. The type, the market settings ID and the correlation
    ID must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restmarketssettingscorrelations-get-openapi.md
- name: plentymarkets REST-API - Create a correlation
  x-api-slug: restmarketssettingscorrelations-post
  description: Creates a correlation. The type, the market settings ID and the correlation
    ID must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restmarketssettingscorrelations-post-openapi.md
- name: plentymarkets REST-API - Create multiple correlations
  x-api-slug: restmarketssettingscorrelationsbulk-post
  description: Creates multiple correlations. The type, market settings ID and the
    correlation ID for each param combination must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restmarketssettingscorrelationsbulk-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restmarketssettingscorrelationsbulk-post-openapi.md
- name: plentymarkets REST-API - Delete market settings
  x-api-slug: restmarketssettingssettingid-delete
  description: Deletes market settings. The market settings ID must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restmarketssettingssettingid-delete-openapi.md
- name: plentymarkets REST-API - Get market settings
  x-api-slug: restmarketssettingssettingid-get
  description: Gets market settings. The market settings ID must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restmarketssettingssettingid-get-openapi.md
- name: plentymarkets REST-API - Update market settings
  x-api-slug: restmarketssettingssettingid-put
  description: Updates market settings. The market settings ID must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restmarketssettingssettingid-put-openapi.md
- name: plentymarkets REST-API - Delete entries
  x-api-slug: restnewsletters-delete
  description: Delete entries.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restnewsletters-delete-openapi.md
- name: plentymarkets REST-API - List newsletter entries
  x-api-slug: restnewsletters-get
  description: List newsletter entries.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restnewsletters-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restnewsletters-get-openapi.md
- name: plentymarkets REST-API - Create an entry
  x-api-slug: restnewsletters-post
  description: Create an entry.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restnewsletters-post-openapi.md
- name: plentymarkets REST-API - Delete folders
  x-api-slug: restnewslettersfolders-delete
  description: Delete folders.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restnewslettersfolders-delete-openapi.md
- name: plentymarkets REST-API - List newsletter folders
  x-api-slug: restnewslettersfolders-get
  description: List newsletter folders.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restnewslettersfolders-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restnewslettersfolders-get-openapi.md
- name: plentymarkets REST-API - Create a folder
  x-api-slug: restnewslettersfolders-post
  description: Create a folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restnewslettersfolders-post-openapi.md
- name: plentymarkets REST-API - Delete a folder
  x-api-slug: restnewslettersfoldersfolderid-delete
  description: Deletes a folder. The ID of the folder must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restnewslettersfoldersfolderid-delete-openapi.md
- name: plentymarkets REST-API - List details of a folder
  x-api-slug: restnewslettersfoldersfolderid-get
  description: Lists details of a folder. The ID of the folder must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restnewslettersfoldersfolderid-get-openapi.md
- name: plentymarkets REST-API - Update a folder
  x-api-slug: restnewslettersfoldersfolderid-put
  description: Updates a folder. The ID of the folder must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restnewslettersfoldersfolderid-put-openapi.md
- name: plentymarkets REST-API - List all recipients of a folder
  x-api-slug: restnewslettersfoldersfolderidrecipients-get
  description: Lists all recipients of a folder. The ID of the folder must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restnewslettersfoldersfolderidrecipients-get-openapi.md
- name: plentymarkets REST-API - List recipients
  x-api-slug: restnewsletterslist-recipients-get
  description: List recipients.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restnewsletterslist-recipients-get-openapi.md
- name: plentymarkets REST-API - Delete recipients
  x-api-slug: restnewslettersrecipients-delete
  description: Delete recipients.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restnewslettersrecipients-delete-openapi.md
- name: plentymarkets REST-API - List recipients of a folder
  x-api-slug: restnewslettersrecipients-get
  description: List recipients of a folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restnewslettersrecipients-get-openapi.md
- name: plentymarkets REST-API - Create a recipient
  x-api-slug: restnewslettersrecipients-post
  description: Create a recipient.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restnewslettersrecipients-post-openapi.md
- name: plentymarkets REST-API - Delete a recipient
  x-api-slug: restnewslettersrecipientsrecipientid-delete
  description: Deletes a recipient. The ID of the recipient must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restnewslettersrecipientsrecipientid-delete-openapi.md
- name: plentymarkets REST-API - List a recipient
  x-api-slug: restnewslettersrecipientsrecipientid-get
  description: Lists a recipient. The ID of the recipient must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restnewslettersrecipientsrecipientid-get-openapi.md
- name: plentymarkets REST-API - Update a recipient
  x-api-slug: restnewslettersrecipientsrecipientid-put
  description: Updates a recipient that is assigned to a folder. The ID of the recipient
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restnewslettersrecipientsrecipientid-put-openapi.md
- name: plentymarkets REST-API - Delete an entry
  x-api-slug: restnewslettersentryid-delete
  description: Deletes an entry. The ID of the entry must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restnewslettersentryid-delete-openapi.md
- name: plentymarkets REST-API - List details of an entry
  x-api-slug: restnewslettersentryid-get
  description: Lists details of an entry. The ID of the entry must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restnewslettersentryid-get-openapi.md
- name: plentymarkets REST-API - Update an entry
  x-api-slug: restnewslettersentryid-put
  description: Updates an entry. The ID of the entry must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restnewslettersentryid-put-openapi.md
- name: plentymarkets REST-API - List orders by filter options
  x-api-slug: restorders-get
  description: List orders by filter options.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restorders-get-openapi.md
- name: plentymarkets REST-API - Create an order
  x-api-slug: restorders-post
  description: Create an order.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restorders-post-openapi.md
- name: plentymarkets REST-API - Create an address for existing order
  x-api-slug: restordersaddresses-post
  description: Creates an address for an existing order.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersaddresses-post-openapi.md
- name: plentymarkets REST-API - List orders of a contact
  x-api-slug: restorderscontactscontactid-get
  description: Lists all orders of a contact. The ID of the contact must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restorderscontactscontactid-get-openapi.md
- name: plentymarkets REST-API - Create a multi-order
  x-api-slug: restorderscontactscontactidmulti-order-post
  description: "Creates a multi-order for a contact. The ID of the contact must be
    specified. Options chosen in the System \xBB Orders \xBB Order types \xBB Multi-order
    menu are relevant for this call."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restorderscontactscontactidmulti-order-post-openapi.md
- name: plentymarkets REST-API - Delete a coupon
  x-api-slug: restorderscouponscampaignscodescode-delete
  description: Deletes a coupon by the coupon code.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restorderscouponscampaignscodescode-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restorderscouponscampaignscodescode-delete-openapi.md
- name: plentymarkets REST-API - Get coupon code information
  x-api-slug: restorderscouponscampaignscodescode-get
  description: Gets coupon code information. The code must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restorderscouponscampaignscodescode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restorderscouponscampaignscodescode-get-openapi.md
- name: plentymarkets REST-API - Disable or enable coupon
  x-api-slug: restorderscouponscampaignscodescodedisabledisdisabled-put
  description: Sets the coupon disable field.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restorderscouponscampaignscodescodedisabledisdisabled-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restorderscouponscampaignscodescodedisabledisdisabled-put-openapi.md
- name: plentymarkets REST-API - Create a coupon code
  x-api-slug: restorderscouponscampaignscampaignidcodes-post
  description: Creates a coupon code. The ID of the campaign must be specified. A
    code can optionally be specified. A random code will be generated if the code
    is not specified. A coupon value can also be optionally specified. The value of
    the campaign will be used if no individual value is specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restorderscouponscampaignscampaignidcodes-post-openapi.md
- name: plentymarkets REST-API - List redeemed coupon codes of a contact
  x-api-slug: restorderscouponscodescontactscontactid-get
  description: Lists the redeemed coupon codes of contact. The ID of the contact must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restorderscouponscodescontactscontactid-get-openapi.md
- name: plentymarkets REST-API - Validate a coupon
  x-api-slug: restorderscouponscodescoupon-post
  description: Validates if a coupon code can be used for the specified items, contact
    ID, etc. The code must be specified. If the coupon code is invalid, a ValidationException
    will be thrown. If the coupon code is valid, a CouponCodeValidation object will
    be returned.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restorderscouponscodescoupon-post-openapi.md
- name: plentymarkets REST-API - List currencies
  x-api-slug: restorderscurrencies-get
  description: List currencies.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restorderscurrencies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restorderscurrencies-get-openapi.md
- name: plentymarkets REST-API - Get a currency for a country
  x-api-slug: restorderscurrenciescountriescountryid-get
  description: Get a currency for a country. The ID of the country must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restorderscurrenciescountriescountryid-get-openapi.md
- name: plentymarkets REST-API - Get a currency
  x-api-slug: restorderscurrenciescurrencyiso-get
  description: Get a currency. The ISO 4217 code of the currency must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restorderscurrenciescurrencyiso-get-openapi.md
- name: plentymarkets REST-API - List countries for a currency
  x-api-slug: restorderscurrenciescurrencyisocountries-get
  description: List countries for a currency. The ISO 4271 code of the currency must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restorderscurrenciescurrencyisocountries-get-openapi.md
- name: plentymarkets REST-API - List order date types
  x-api-slug: restordersdatestypes-get
  description: List order date types.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersdatestypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersdatestypes-get-openapi.md
- name: plentymarkets REST-API - Find an order date type by it's ID
  x-api-slug: restordersdatestypestypeid-get
  description: Find an order date type by it's id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersdatestypestypeid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersdatestypestypeid-get-openapi.md
- name: plentymarkets REST-API - List names of an order date type
  x-api-slug: restordersdatestypestypeidnames-get
  description: Lists names in all languages available of an order date type. The ID
    of the date type must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersdatestypestypeidnames-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersdatestypestypeidnames-get-openapi.md
- name: plentymarkets REST-API - Get a name of an order date type
  x-api-slug: restordersdatestypestypeidnameslang-get
  description: Gets a name of an order date type. The ID of the date type and the
    language of the name must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersdatestypestypeidnameslang-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersdatestypestypeidnameslang-get-openapi.md
- name: plentymarkets REST-API - List document accounting summaries
  x-api-slug: restordersdocumentsaccounting-summary-get
  description: Lists document accounting summaries. A document accounting summary
    is saved along with each reversal document (for invoice and credit note). It contains
    accounting information about the order for this point in time. The summary is
    saved because an order can be updated after a reversal_document is generated.
    The information about the order before the update is needed for accounting.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersdocumentsaccounting-summary-get-openapi.md
- name: plentymarkets REST-API - Download documents of a document type
  x-api-slug: restordersdocumentsdownloadstype-get
  description: Downloads documents of the same document type as a zip file. The type
    of the documents must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersdocumentsdownloadstype-get-openapi.md
- name: plentymarkets REST-API - List documents of a type
  x-api-slug: restordersdocumentstype-get
  description: Lists documents of a type. The type must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersdocumentstype-get-openapi.md
- name: plentymarkets REST-API - Create a date for an order item
  x-api-slug: restordersitemsdates-post
  description: Creates a date for an order item. The ID of the order item must be
    specified
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersitemsdates-post-openapi.md
- name: plentymarkets REST-API - Delete a date from an order item
  x-api-slug: restordersitemsdatesid-delete
  description: Deletes the date from an order item. The ID of the date must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersitemsdatesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersitemsdatesid-delete-openapi.md
- name: plentymarkets REST-API - Get a date of an order item
  x-api-slug: restordersitemsdatesid-get
  description: Gets a date of an order item. The ID of the date must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersitemsdatesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersitemsdatesid-get-openapi.md
- name: plentymarkets REST-API - Update a date of an order item
  x-api-slug: restordersitemsdatesid-put
  description: Updates a date of an order item. The ID of the date must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersitemsdatesid-put-openapi.md
- name: plentymarkets REST-API - Create an order item property.
  x-api-slug: restordersitemsproperties-post
  description: Create an order item property..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersitemsproperties-post-openapi.md
- name: plentymarkets REST-API - Delete an order item property by ID.
  x-api-slug: restordersitemspropertiesid-delete
  description: Delete an order item property by id..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersitemspropertiesid-delete-openapi.md
- name: plentymarkets REST-API - Get an order item property by ID.
  x-api-slug: restordersitemspropertiesid-get
  description: Get an order item property by id..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersitemspropertiesid-get-openapi.md
- name: plentymarkets REST-API - Update an order item property by ID.
  x-api-slug: restordersitemspropertiesid-put
  description: Update an order item property by id..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersitemspropertiesid-put-openapi.md
- name: plentymarkets REST-API - List dates of an order item
  x-api-slug: restordersitemsorderitemiddates-get
  description: Lists the dates of an order item. The ID of the order item must be
    specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersitemsorderitemiddates-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersitemsorderitemiddates-get-openapi.md
- name: plentymarkets REST-API - Delete a date from an order item by order item and
    date type
  x-api-slug: restordersitemsorderitemiddatestypeid-delete
  description: Deletest a date from an order item. The ID of the order item and the
    ID of the date type must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersitemsorderitemiddatestypeid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersitemsorderitemiddatestypeid-delete-openapi.md
- name: plentymarkets REST-API - Get a date of an order item by order item and date
    type
  x-api-slug: restordersitemsorderitemiddatestypeid-get
  description: Gets a date of an order item. The ID of the order item and the ID of
    the date type must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersitemsorderitemiddatestypeid-get-openapi.md
- name: plentymarkets REST-API - Create a date for an order item by order item and
    date type
  x-api-slug: restordersitemsorderitemiddatestypeid-post
  description: Creates a date for an order item. The ID of the order item and the
    ID of the date type must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersitemsorderitemiddatestypeid-post-openapi.md
- name: plentymarkets REST-API - Update a date of an order item by order item and
    date type
  x-api-slug: restordersitemsorderitemiddatestypeid-put
  description: Updates the date of an order item. The ID of the order item and the
    ID of the date type must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersitemsorderitemiddatestypeid-put-openapi.md
- name: plentymarkets REST-API - Get all order item propertys for one order item by
    its order item id.
  x-api-slug: restordersitemsorderitemidproperties-get
  description: Get all order item propertys for one order item by its order item id..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersitemsorderitemidproperties-get-openapi.md
- name: plentymarkets REST-API - Delete an order item property by order item ID and
    order property type ID.
  x-api-slug: restordersitemsorderitemidpropertiestypeid-delete
  description: Delete an order item property by order item id and order property type
    id..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersitemsorderitemidpropertiestypeid-delete-openapi.md
- name: plentymarkets REST-API - Get an order item property by order item ID and order
    property type ID.
  x-api-slug: restordersitemsorderitemidpropertiestypeid-get
  description: Get an order item property by order item id and order property type
    id..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersitemsorderitemidpropertiestypeid-get-openapi.md
- name: plentymarkets REST-API - Create an order item property by order item ID and
    order property type ID.
  x-api-slug: restordersitemsorderitemidpropertiestypeid-post
  description: Create an order item property by order item id and order property type
    id..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersitemsorderitemidpropertiestypeid-post-openapi.md
- name: plentymarkets REST-API - Update an order item property by order item ID and
    order property type ID.
  x-api-slug: restordersitemsorderitemidpropertiestypeid-put
  description: Update an order item property by order item id and order property type
    id..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersitemsorderitemidpropertiestypeid-put-openapi.md
- name: plentymarkets REST-API - List transactions
  x-api-slug: restordersitemsorderitemidtransactions-get
  description: Lists transactions for an order item. The ID of the order item must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersitemsorderitemidtransactions-get-openapi.md
- name: plentymarkets REST-API - Create a transaction
  x-api-slug: restordersitemsorderitemidtransactions-post
  description: Create a transaction.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersitemsorderitemidtransactions-post-openapi.md
- name: plentymarkets REST-API - List order property types
  x-api-slug: restorderspropertiestypes-get
  description: Lists property types and their names in all languages. Optionally one
    or more languages can be specified to get a limited response.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restorderspropertiestypes-get-openapi.md
- name: plentymarkets REST-API - Create an order property type
  x-api-slug: restorderspropertiestypes-post
  description: Create an order property type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restorderspropertiestypes-post-openapi.md
- name: plentymarkets REST-API - Delete a property type.
  x-api-slug: restorderspropertiestypestypeid-delete
  description: Deletes a property type and all names for it from the database. The
    ID of the type must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restorderspropertiestypestypeid-delete-openapi.md
- name: plentymarkets REST-API - Get a property type
  x-api-slug: restorderspropertiestypestypeid-get
  description: Gets a property type and its names in all languages. Optionally one
    or more languages can be specified to get a limited response.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restorderspropertiestypestypeid-get-openapi.md
- name: plentymarkets REST-API - Update a property type.
  x-api-slug: restorderspropertiestypestypeid-put
  description: Updates a property type and its names. The ID of the type must be specified.
    You can also create new names, if you provide data which does not yet exist.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restorderspropertiestypestypeid-put-openapi.md
- name: plentymarkets REST-API - Delete a property of an order by property ID
  x-api-slug: restorderspropertiesid-delete
  description: Deletes a property of an order. The ID of the property must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restorderspropertiesid-delete-openapi.md
- name: plentymarkets REST-API - Update a property of an order by property ID
  x-api-slug: restorderspropertiesid-put
  description: Updates the value of a property. The ID of the property must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restorderspropertiesid-put-openapi.md
- name: plentymarkets REST-API - List referrers
  x-api-slug: restordersreferrers-get
  description: Lists referrers with the desired columns/attributes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersreferrers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersreferrers-get-openapi.md
- name: plentymarkets REST-API - Create an order referrer
  x-api-slug: restordersreferrersparentreferrerid-post
  description: |-
    Create an order referrer. The ID can be specified, a parent ID can be specified to create a sub referrer or if no ID is specified, a referrer ID will be assigned automatically.
    If an ID is specified, the ID may not be used already. If the ID is used already, the referrer will only be created.
    If the ID is automatically assigned, the first ID that has not been used before will be set.
    If the ID is not specified, but a parent referrer ID is given, then the new referrer ID will be a sub referrer of the given parent.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersreferrersparentreferrerid-post-openapi.md
- name: plentymarkets REST-API - List shipping countries
  x-api-slug: restordersshippingcountries-get
  description: List shipping countries.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersshippingcountries-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersshippingcountries-get-openapi.md
- name: plentymarkets REST-API - List export documents by order ID
  x-api-slug: restordersshippingexport-documentsorderid-get
  description: List export documents by order id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersshippingexport-documentsorderid-get-openapi.md
- name: plentymarkets REST-API - List shipping package types
  x-api-slug: restordersshippingpackage-types-get
  description: List shipping package types.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersshippingpackage-types-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersshippingpackage-types-get-openapi.md
- name: plentymarkets REST-API - Get a shipping package type
  x-api-slug: restordersshippingpackage-typesshippingpackagetypeid-get
  description: Gets a shipping package type. The ID of the shipping package type must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersshippingpackage-typesshippingpackagetypeid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersshippingpackage-typesshippingpackagetypeid-get-openapi.md
- name: plentymarkets REST-API - Get an  order parcel service region
  x-api-slug: restordersshippingparcel-service-regionsparcelserviceregionid-get
  description: Gets an parcel service region. The ID of the parcel service region
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersshippingparcel-service-regionsparcelserviceregionid-get-openapi.md
- name: plentymarkets REST-API - Get a preview list for parcel services.
  x-api-slug: restordersshippingparcelspreviewlanguage-get
  description: Get a preview list for parcel services..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersshippingparcelspreviewlanguage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersshippingparcelspreviewlanguage-get-openapi.md
- name: plentymarkets REST-API - List shipping profiles
  x-api-slug: restordersshippingpresets-get
  description: List shipping profiles.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersshippingpresets-get-openapi.md
- name: plentymarkets REST-API - Get a preview list for parcel service presets.
  x-api-slug: restordersshippingpresetspreviewlanguage-get
  description: Get a preview list for parcel service presets..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersshippingpresetspreviewlanguage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersshippingpresetspreviewlanguage-get-openapi.md
- name: plentymarkets REST-API - Get a shipping profile
  x-api-slug: restordersshippingpresetspresetid-get
  description: Gets a shipping profile. The ID of the shipping profile must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersshippingpresetspresetid-get-openapi.md
- name: plentymarkets REST-API - Lists parcel service regions by parcel service preset
    id.
  x-api-slug: restordersshippingpresetspresetidparcel-service-regions-get
  description: Lists parcel service regions. The ID of the parcel service preset must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersshippingpresetspresetidparcel-service-regions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersshippingpresetspresetidparcel-service-regions-get-openapi.md
- name: 'plentymarkets REST-API - '
  x-api-slug: restordersshippingreturnsreturns-service-providers-get
  description: .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersshippingreturnsreturns-service-providers-get-openapi.md
- name: plentymarkets REST-API - List shipping service provider plugins
  x-api-slug: restordersshippingreturnsreturns-service-providersplugins-get
  description: List shipping service provider plugins.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersshippingreturnsreturns-service-providersplugins-get-openapi.md
- name: 'plentymarkets REST-API - '
  x-api-slug: restordersshippingreturnsreturns-service-providersproviderid-get
  description: .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersshippingreturnsreturns-service-providersproviderid-get-openapi.md
- name: 'plentymarkets REST-API - '
  x-api-slug: restordersshippingreturnsreturnsid-get
  description: .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersshippingreturnsreturnsid-get-openapi.md
- name: plentymarkets REST-API - Create shipping information
  x-api-slug: restordersshippingshipping-information-post
  description: Create shipping information.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersshippingshipping-information-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersshippingshipping-information-post-openapi.md
- name: plentymarkets REST-API - List shipping service providers
  x-api-slug: restordersshippingshipping-service-providers-get
  description: List shipping service providers.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersshippingshipping-service-providers-get-openapi.md
- name: plentymarkets REST-API - Save a shipping service provider
  x-api-slug: restordersshippingshipping-service-providers-post
  description: Saves a shipping service provider. The name of the shipping service
    provider must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersshippingshipping-service-providers-post-openapi.md
- name: plentymarkets REST-API - List shipping service provider plugins
  x-api-slug: restordersshippingshipping-service-providersplugins-get
  description: List shipping service provider plugins.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersshippingshipping-service-providersplugins-get-openapi.md
- name: plentymarkets REST-API - Get a shipping service provider
  x-api-slug: restordersshippingshipping-service-providersshipping-service-provider-id-get
  description: Gets a shipping service provider. The ID of the shipping service provider
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersshippingshipping-service-providersshipping-service-provider-id-get-openapi.md
- name: plentymarkets REST-API - List status histories of orders
  x-api-slug: restordersstatushistory-get
  description: Lists the status histories of all orders. The result can be limited
    to an order, a status type, a period of time or a user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersstatushistory-get-openapi.md
- name: plentymarkets REST-API - Searches order statuses.
  x-api-slug: restordersstatuses-get
  description: Searches for a list of order statuses, specified by the given filter
    parameters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersstatuses-get-openapi.md
- name: plentymarkets REST-API - Creates an order status.
  x-api-slug: restordersstatuses-post
  description: Creates an order status, which is specified by the given ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersstatuses-post-openapi.md
- name: 'plentymarkets REST-API - '
  x-api-slug: restordersstatusesall-get
  description: .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersstatusesall-get-openapi.md
- name: plentymarkets REST-API - Delete an order status.
  x-api-slug: restordersstatusesstatusid-delete
  description: Deletes an order status, which is specified by the given ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersstatusesstatusid-delete-openapi.md
- name: plentymarkets REST-API - Get an order status.
  x-api-slug: restordersstatusesstatusid-get
  description: Gets an order status, which is specified by the given ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersstatusesstatusid-get-openapi.md
- name: plentymarkets REST-API - Update an order status.
  x-api-slug: restordersstatusesstatusid-put
  description: Updates an order status, which is specified by the given ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersstatusesstatusid-put-openapi.md
- name: plentymarkets REST-API - Delete an order
  x-api-slug: restordersorderid-delete
  description: Deletes an order. The ID of the order must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderid-delete-openapi.md
- name: plentymarkets REST-API - Get an order
  x-api-slug: restordersorderid-get
  description: Gets an order. The ID of the order must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderid-get-openapi.md
- name: plentymarkets REST-API - Update an order
  x-api-slug: restordersorderid-put
  description: Updates an order. The ID of the order must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderid-put-openapi.md
- name: plentymarkets REST-API - List order addresses
  x-api-slug: restordersorderidaddressesrelationtypeid-get
  description: Lists order addresses. The ID of the order must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderidaddressesrelationtypeid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderidaddressesrelationtypeid-get-openapi.md
- name: plentymarkets REST-API - Cancel an order
  x-api-slug: restordersorderidcancel-put
  description: Cancels an order. The ID of the order must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderidcancel-put-openapi.md
- name: plentymarkets REST-API - Get a contact wish
  x-api-slug: restordersorderidcontactwish-get
  description: Gets the contact wish for an order. The ID of the order must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderidcontactwish-get-openapi.md
- name: plentymarkets REST-API - Redeem a coupon code
  x-api-slug: restordersorderidcouponscoupon-post
  description: Redeems a coupon code and applies it to an order. The ID of the order
    must be specified. If the coupon was successfully redeemed, the coupon data will
    be returned. If the coupon can not be redeemed, a validation exception will be
    thrown.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderidcouponscoupon-post-openapi.md
- name: plentymarkets REST-API - List dates of an order
  x-api-slug: restordersorderiddates-get
  description: Lists dates of an order. The ID of the order must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderiddates-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderiddates-get-openapi.md
- name: plentymarkets REST-API - Get a date
  x-api-slug: restordersorderiddatestypeid-get
  description: Gets a date. The ID of the order and the ID of the date type must be
    specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderiddatestypeid-get-openapi.md
- name: plentymarkets REST-API - Download documents of an order
  x-api-slug: restordersorderiddocumentsdownloadstype-get
  description: Downloads documents of an order as a zip file. The ID of the order
    must be specified. In addition a type can be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderiddocumentsdownloadstype-get-openapi.md
- name: plentymarkets REST-API - List documents of an order
  x-api-slug: restordersorderiddocumentstype-get
  description: Lists documents of an order. The ID of the order must be specified.
    In addition a type can be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderiddocumentstype-get-openapi.md
- name: plentymarkets REST-API - Upload order documents
  x-api-slug: restordersorderiddocumentstype-post
  description: Uploads order documents. The ID of the order and the document type
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderiddocumentstype-post-openapi.md
- name: plentymarkets REST-API - List serial numbers of an order
  x-api-slug: restordersorderiditemsserialnumbers-get
  description: Lists all serial numbers of an order. The ID of the order must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderiditemsserialnumbers-get-openapi.md
- name: plentymarkets REST-API - Delete an order item
  x-api-slug: restordersorderiditemsorderitemid-delete
  description: Deletes an order item. The ID of the order and the ID of the order
    item must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderiditemsorderitemid-delete-openapi.md
- name: plentymarkets REST-API - List serial numbers of an order item
  x-api-slug: restordersorderiditemsorderitemidserialnumbers-get
  description: Lists all serial numbers of an order item. The ID of the order and
    the ID of the order item must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderiditemsorderitemidserialnumbers-get-openapi.md
- name: plentymarkets REST-API - Revert outgoing stock
  x-api-slug: restordersorderidoutgoing-stocks-delete
  description: Reverts the booking of order items of an order. The ID of the order
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderidoutgoing-stocks-delete-openapi.md
- name: plentymarkets REST-API - Book out order items
  x-api-slug: restordersorderidoutgoing-stocks-post
  description: Books out the order items of an order. The ID of the order must be
    specified and a booking date can be specified. The current date and time will
    be used if no date is specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderidoutgoing-stocks-post-openapi.md
- name: plentymarkets REST-API - List package numbers of an order
  x-api-slug: restordersorderidpackagenumbers-get
  description: Lists the package numbers of an order. The ID of the order must be
    specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderidpackagenumbers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderidpackagenumbers-get-openapi.md
- name: plentymarkets REST-API - Create a property for an order
  x-api-slug: restordersorderidproperties-post
  description: Creates a property and attaches it to an order. The ID of the order
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderidproperties-post-openapi.md
- name: plentymarkets REST-API - List properties of an order
  x-api-slug: restordersorderidpropertiestypeid-get
  description: Lists properties of an order. The ID of the order must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderidpropertiestypeid-get-openapi.md
- name: plentymarkets REST-API - Delete a property of an order by order ID and type
    ID
  x-api-slug: restordersorderidpropertiestypeid-delete
  description: Deletes a property of an order. The composite key of the property must
    be specified. The composite key is composed of the ID of the order and the ID
    of the order property type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderidpropertiestypeid-delete-openapi.md
- name: plentymarkets REST-API - Update a property of an order by order ID and property
    ID
  x-api-slug: restordersorderidpropertiestypeid-put
  description: Updates the value of a property. The composite key of the property
    must be specified. The composite key is composed of the ID of the order and the
    ID of the order property type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderidpropertiestypeid-put-openapi.md
- name: plentymarkets REST-API - Delete all order shipping packages for an order
  x-api-slug: restordersorderidshippingpackages-delete
  description: Deletes all order shipping packages for an order. The ID of the order
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderidshippingpackages-delete-openapi.md
- name: plentymarkets REST-API - List order shipping packages
  x-api-slug: restordersorderidshippingpackages-get
  description: Lists order shipping packages. The ID of the order must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderidshippingpackages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderidshippingpackages-get-openapi.md
- name: plentymarkets REST-API - Create an order shipping package
  x-api-slug: restordersorderidshippingpackages-post
  description: Creates an order shipping package. The ID of the order must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderidshippingpackages-post-openapi.md
- name: plentymarkets REST-API - Delete an order shipping package
  x-api-slug: restordersorderidshippingpackagesordershippingpackageid-delete
  description: Deletes an order shipping package. The ID of the order and the ID of
    the order shipping package must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderidshippingpackagesordershippingpackageid-delete-openapi.md
- name: plentymarkets REST-API - Get an order shipping package
  x-api-slug: restordersorderidshippingpackagesordershippingpackageid-get
  description: Gets an order shipping package. The ID of the order and the ID of the
    order shipping package must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderidshippingpackagesordershippingpackageid-get-openapi.md
- name: plentymarkets REST-API - Update an order shipping package
  x-api-slug: restordersorderidshippingpackagesordershippingpackageid-put
  description: Updates an order shipping package. The ID of the order and the ID of
    the order shipping package must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderidshippingpackagesordershippingpackageid-put-openapi.md
- name: 'plentymarkets REST-API - '
  x-api-slug: restordersorderidshippingreturns-get
  description: .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderidshippingreturns-get-openapi.md
- name: 'plentymarkets REST-API - '
  x-api-slug: restordersorderidshippingreturnsassign-labelreturnsid-put
  description: .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderidshippingreturnsassign-labelreturnsid-put-openapi.md
- name: plentymarkets REST-API - Delete shipping information
  x-api-slug: restordersorderidshippingshipping-information-delete
  description: Deletes the shipping information. The ID of the order must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderidshippingshipping-information-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderidshippingshipping-information-delete-openapi.md
- name: plentymarkets REST-API - Get shipping information
  x-api-slug: restordersorderidshippingshipping-information-get
  description: Gets the shipping information. The ID of the order must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderidshippingshipping-information-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderidshippingshipping-information-get-openapi.md
- name: plentymarkets REST-API - Update additional data of the shipping information
  x-api-slug: restordersorderidshippingshipping-informationadditional-data-put
  description: Updates additional data of the shipping information. The ID of the
    order must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderidshippingshipping-informationadditional-data-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderidshippingshipping-informationadditional-data-put-openapi.md
- name: plentymarkets REST-API - Update the shipping status of the shipping information
  x-api-slug: restordersorderidshippingshipping-informationstatus-put
  description: Updates the shipping status of the shipping information. The ID of
    the order must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderidshippingshipping-informationstatus-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderidshippingshipping-informationstatus-put-openapi.md
- name: plentymarkets REST-API - Get the status history of an order
  x-api-slug: restordersorderidstatushistory-get
  description: Gets the status of an order. The ID of the order must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restordersorderidstatushistory-get-openapi.md
- name: plentymarkets REST-API - Create a name of a property type
  x-api-slug: restpaymentpropertiestypesnames-post
  description: Create a name of a property type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentpropertiestypesnames-post-openapi.md
- name: plentymarkets REST-API - Update a name of a property type
  x-api-slug: restpaymentpropertiestypesnames-put
  description: Update a name of a property type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentpropertiestypesnames-put-openapi.md
- name: plentymarkets REST-API - List names of property types
  x-api-slug: restpaymentpropertiestypesnameslang-get
  description: List names of property types.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentpropertiestypesnameslang-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentpropertiestypesnameslang-get-openapi.md
- name: plentymarkets REST-API - Get a name of a property type
  x-api-slug: restpaymentpropertiestypesnamesnameid-get
  description: Gets a name of a property type. The ID of the name must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentpropertiestypesnamesnameid-get-openapi.md
- name: plentymarkets REST-API - Delete Payment-Contact-Relation
  x-api-slug: restpaymentpaymentidcontact-delete
  description: Delete payment-contact-relation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentpaymentidcontact-delete-openapi.md
- name: plentymarkets REST-API - Create Payment-Contact-Relation
  x-api-slug: restpaymentpaymentidcontactcontactid-post
  description: Create payment-contact-relation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentpaymentidcontactcontactid-post-openapi.md
- name: plentymarkets REST-API - Delete Payment-Order-Relation
  x-api-slug: restpaymentpaymentidorder-delete
  description: Delete payment-order-relation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentpaymentidorder-delete-openapi.md
- name: plentymarkets REST-API - Create Payment-Order-Relation
  x-api-slug: restpaymentpaymentidorderorderid-post
  description: Create payment-order-relation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentpaymentidorderorderid-post-openapi.md
- name: plentymarkets REST-API - List payments
  x-api-slug: restpayments-get
  description: List payments.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpayments-get-openapi.md
- name: plentymarkets REST-API - Create a payment
  x-api-slug: restpayments-post
  description: Create a payment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpayments-post-openapi.md
- name: plentymarkets REST-API - Update a payment
  x-api-slug: restpayments-put
  description: Update a payment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpayments-put-openapi.md
- name: plentymarkets REST-API - List payments by entry date
  x-api-slug: restpaymentsentrydate-get
  description: Lists all payments by entry date within a certain date range. The start
    and the end of the date range must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentsentrydate-get-openapi.md
- name: plentymarkets REST-API - List payments by import date
  x-api-slug: restpaymentsimportdate-get
  description: Lists all payments by import date within a certain date range. The
    start and the end of the date range must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentsimportdate-get-openapi.md
- name: plentymarkets REST-API - List payment methods names
  x-api-slug: restpaymentsmethodnames-get
  description: Lists all payment method names.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentsmethodnames-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentsmethodnames-get-openapi.md
- name: plentymarkets REST-API - List all payment method names for a payment method
    id
  x-api-slug: restpaymentsmethodnamespaymentmethodid-get
  description: List all payment method names for a payment method id. The payment
    method id must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentsmethodnamespaymentmethodid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentsmethodnamespaymentmethodid-get-openapi.md
- name: plentymarkets REST-API - Gets a payment method name by id and lang
  x-api-slug: restpaymentsmethodnamespaymentmethodidlang-get
  description: Gets a payment method name by id and lang. The ID and the requested
    lang of the payment method must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentsmethodnamespaymentmethodidlang-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentsmethodnamespaymentmethodidlang-get-openapi.md
- name: plentymarkets REST-API - List payment methods
  x-api-slug: restpaymentsmethods-get
  description: Lists all payment method plugins.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentsmethods-get-openapi.md
- name: plentymarkets REST-API - Create a payment method
  x-api-slug: restpaymentsmethods-post
  description: Creates a payment method. The plugin key, the payment key and the name
    of the payment method must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentsmethods-post-openapi.md
- name: plentymarkets REST-API - Update a payment method
  x-api-slug: restpaymentsmethods-put
  description: Updates the name of the payment method. The name of the payment method
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentsmethods-put-openapi.md
- name: plentymarkets REST-API - Get EBICS Accounts
  x-api-slug: restpaymentsmethodsebics-get
  description: Get ebics accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentsmethodsebics-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentsmethodsebics-get-openapi.md
- name: plentymarkets REST-API - Create an EBICS Account
  x-api-slug: restpaymentsmethodsebics-post
  description: Create an ebics account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentsmethodsebics-post-openapi.md
- name: plentymarkets REST-API - Returns the HBCI-Account count
  x-api-slug: restpaymentsmethodshbci-get
  description: Returns the hbci-account count.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentsmethodshbci-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentsmethodshbci-get-openapi.md
- name: plentymarkets REST-API - Get a payment method
  x-api-slug: restpaymentsmethodspluginspluginkey-get
  description: Gets a payment method plugin. The plugin key must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentsmethodspluginspluginkey-get-openapi.md
- name: plentymarkets REST-API - Get a preview list for parcel services.
  x-api-slug: restpaymentsmethodspreviewlanguage-get
  description: Get a preview list for parcel services..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentsmethodspreviewlanguage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentsmethodspreviewlanguage-get-openapi.md
- name: plentymarkets REST-API - List payments of a payment method
  x-api-slug: restpaymentsmethodsmethodid-get
  description: Lists all payments of the a payment method. The ID of the payment method
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentsmethodsmethodid-get-openapi.md
- name: plentymarkets REST-API - List payments of an order
  x-api-slug: restpaymentsordersorderid-get
  description: Lists all payments of an order. The ID of the order must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentsordersorderid-get-openapi.md
- name: plentymarkets REST-API - List properties
  x-api-slug: restpaymentsproperties-get
  description: List properties.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentsproperties-get-openapi.md
- name: plentymarkets REST-API - Create a payment property
  x-api-slug: restpaymentsproperties-post
  description: Create a payment property.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentsproperties-post-openapi.md
- name: plentymarkets REST-API - Update a payment property
  x-api-slug: restpaymentsproperties-put
  description: Update a payment property.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentsproperties-put-openapi.md
- name: plentymarkets REST-API - List properties by creation date
  x-api-slug: restpaymentspropertiesdate-get
  description: Lists all properties by creation date. The start and the end of the
    date range must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentspropertiesdate-get-openapi.md
- name: plentymarkets REST-API - List property types
  x-api-slug: restpaymentspropertiestypes-get
  description: Lists all property types. The language must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentspropertiestypes-get-openapi.md
- name: plentymarkets REST-API - Create a property type
  x-api-slug: restpaymentspropertiestypes-post
  description: Create a property type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentspropertiestypes-post-openapi.md
- name: plentymarkets REST-API - Update a property type
  x-api-slug: restpaymentspropertiestypes-put
  description: Update a property type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentspropertiestypes-put-openapi.md
- name: plentymarkets REST-API - Get a property type
  x-api-slug: restpaymentspropertiestypestypeid-get
  description: Gets a property type. The ID of the type must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentspropertiestypestypeid-get-openapi.md
- name: plentymarkets REST-API - Get a property
  x-api-slug: restpaymentspropertiespropertyid-get
  description: Gets a property. The ID of the property must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentspropertiespropertyid-get-openapi.md
- name: plentymarkets REST-API - List payments by property type ID and value
  x-api-slug: restpaymentspropertypropertytypeidpropertyvalue-get
  description: Lists all payments by the given property type ID and the value.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentspropertypropertytypeidpropertyvalue-get-openapi.md
- name: plentymarkets REST-API - List payments of a payment status
  x-api-slug: restpaymentsstatusstatusid-get
  description: Lists all payments of a payment status. The ID of the <a href='https://developers.plentymarkets.com/rest-doc/introduction#payment-statuses'  target='_blank'>payment
    status</a> must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentsstatusstatusid-get-openapi.md
- name: plentymarkets REST-API - List payments of a transaction type
  x-api-slug: restpaymentstransactionstransactiontypeid-get
  description: Lists all payments of a transaction type. The ID of the transaction
    type must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentstransactionstransactiontypeid-get-openapi.md
- name: plentymarkets REST-API - Get a payment
  x-api-slug: restpaymentspaymentid-get
  description: Gets a payment. The ID of the payment must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentspaymentid-get-openapi.md
- name: plentymarkets REST-API - List properties for a payment
  x-api-slug: restpaymentspaymentidproperties-get
  description: Lists all properties for a payment. The ID of the payment must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpaymentspaymentidproperties-get-openapi.md
- name: plentymarkets REST-API - List all Sets
  x-api-slug: restplugin-sets-get
  description: Lists all available sets.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restplugin-sets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restplugin-sets-get-openapi.md
- name: plentymarkets REST-API - Create a Set
  x-api-slug: restplugin-sets-post
  description: Creates a new plugin set with the given name. If a 'copyPluginSetId'
    is given, all set entries from that set will be copied into the new set
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restplugin-sets-post-openapi.md
- name: plentymarkets REST-API - Get the preview hash for a set
  x-api-slug: restplugin-setspreview-hash-get
  description: Get the hash required to preview a plugin set. Response content will
    be in the form ['previewHash' => 'adf245o9nwu90sdfjw409u4'].
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restplugin-setspreview-hash-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restplugin-setspreview-hash-get-openapi.md
- name: plentymarkets REST-API - List all the plugins translations for a plugin set
  x-api-slug: restplugin-setspluginsetidlanguages-get
  description: Lists all the plugins translations for a plugin set
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restplugin-setspluginsetidlanguages-get-openapi.md
- name: 'plentymarkets REST-API - '
  x-api-slug: restplugin-setspluginsetidlanguagescsvlanguagecode-get
  description: .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restplugin-setspluginsetidlanguagescsvlanguagecode-get-openapi.md
- name: plentymarkets REST-API - Delete multiple translation
  x-api-slug: restplugin-setspluginsetidlanguageslanguagecode-delete
  description: Deletes multiple translation. The pluginSetId and languageCode must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restplugin-setspluginsetidlanguageslanguagecode-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restplugin-setspluginsetidlanguageslanguagecode-delete-openapi.md
- name: 'plentymarkets REST-API - '
  x-api-slug: restplugin-setspluginsetidlanguagestargetlanguage-get
  description: .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restplugin-setspluginsetidlanguagestargetlanguage-get-openapi.md
- name: 'plentymarkets REST-API - '
  x-api-slug: restplugin-setspluginsetidlanguagestargetlanguage-post
  description: .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restplugin-setspluginsetidlanguagestargetlanguage-post-openapi.md
- name: plentymarkets REST-API - Delete a set
  x-api-slug: restplugin-setssetid-delete
  description: Deletes a plugin set. Response content will be the number of sets deleted
    (i. e. '1' or '0').
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restplugin-setssetid-delete-openapi.md
- name: plentymarkets REST-API - Get a set
  x-api-slug: restplugin-setssetid-get
  description: Get a set.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restplugin-setssetid-get-openapi.md
- name: plentymarkets REST-API - Update a set
  x-api-slug: restplugin-setssetid-put
  description: Updates a set. Response content will be 'true' if the update was successful,
    'false' if not.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restplugin-setssetid-put-openapi.md
- name: plentymarkets REST-API - List all Plugins of Set
  x-api-slug: restplugin-setssetidplugins-get
  description: Lists all active Plugins of given Set.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restplugin-setssetidplugins-get-openapi.md
- name: plentymarkets REST-API - Search plugins
  x-api-slug: restplugin-setssetidpluginssearch-get
  description: Searches for plugins. The search can be refined with numerous parameters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restplugin-setssetidpluginssearch-get-openapi.md
- name: plentymarkets REST-API - Remove a plugin from a set
  x-api-slug: restplugin-setssetidpluginspluginid-delete
  description: |-
    Removes a plugin from a set and deletes all plugin files. Response content will be 'true' if the deletion was successful,
    'false' if not. If no plugin set with the given id can be found or the plugin is not associated to the set, a 404 will be returned.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restplugin-setssetidpluginspluginid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restplugin-setssetidpluginspluginid-delete-openapi.md
- name: plentymarkets REST-API - Add a plugin to a set
  x-api-slug: restplugin-setssetidpluginspluginid-post
  description: Add a plugin to a set.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restplugin-setssetidpluginspluginid-post-openapi.md
- name: plentymarkets REST-API - Change a plugin's 'active' status for a set.
  x-api-slug: restplugin-setssetidpluginspluginid-put
  description: Change a plugin's 'active' status for a set..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restplugin-setssetidpluginspluginid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restplugin-setssetidpluginspluginid-put-openapi.md
- name: plentymarkets REST-API - Install a git plugin into a set
  x-api-slug: restplugin-setssetidpluginspluginidinstall-git-plugin-post
  description: Installs a git plugin into a set. Response content will be in the form
    ['gitPluginInstalled' => 'true' / 'false'].
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restplugin-setssetidpluginspluginidinstall-git-plugin-post-openapi.md
- name: plentymarkets REST-API - Set a plugin's position in a set
  x-api-slug: restplugin-setssetidpluginspluginidsetposition-post
  description: Set a plugin's position in a set.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restplugin-setssetidpluginspluginidsetposition-post-openapi.md
- name: plentymarkets REST-API - List all SetEntries of Set
  x-api-slug: restplugin-setssetidset-entries-get
  description: List all setentries of set.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restplugin-setssetidset-entries-get-openapi.md
- name: plentymarkets REST-API - List plugins
  x-api-slug: restplugins-get
  description: |-
    Lists all plugins saved in the inbox folder. Plugins that have not been provisioned to Stage or Productive will
    also be shown.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restplugins-get-openapi.md
- name: plentymarkets REST-API - Create a plugin
  x-api-slug: restplugins-post
  description: Creates a plugin with empty plugin folders and a plugin.json file.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restplugins-post-openapi.md
- name: plentymarkets REST-API - List all Plugins of Set
  x-api-slug: restpluginsplugin-setspluginsetidplugins-get
  description: Lists all active Plugins of given Set.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpluginsplugin-setspluginsetidplugins-get-openapi.md
- name: plentymarkets REST-API - List plugins
  x-api-slug: restpluginssearch-get
  description: |-
    Lists all plugins saved in the inbox folder. Plugins that have not been provisioned to Stage or Productive will
    also be shown.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpluginssearch-get-openapi.md
- name: plentymarkets REST-API - Load sitemap patterns
  x-api-slug: restpluginsseositemap-get
  description: Loads all given sitemap patterns from booted plugins.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpluginsseositemap-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpluginsseositemap-get-openapi.md
- name: plentymarkets REST-API - List plugins for backend UI
  x-api-slug: restpluginsui-get
  description: Lists all plugins provisioned in Stage or Productive that contain a
    plugin.js file.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpluginsui-get-openapi.md
- name: plentymarkets REST-API - Delete a plugin
  x-api-slug: restpluginspluginid-delete
  description: |-
    Deletes a plugin. This call also deletes all plugin files in the inbox folder! To commit the deletion, the
    plugin must be provisioned in Stage or Productive. The ID of the plugin must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpluginspluginid-delete-openapi.md
- name: plentymarkets REST-API - Get a plugin
  x-api-slug: restpluginspluginid-get
  description: Gets a plugin. The ID of the plugin must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpluginspluginid-get-openapi.md
- name: plentymarkets REST-API - Update a plugin
  x-api-slug: restpluginspluginid-put
  description: |-
    Updates a plugin. The plugin position can be changed. The plugin can be activated or deactivated for Stage or
    Productive. The plugin can be activated or deactivated for online stores. The ID of the plugin must be
    specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpluginspluginid-put-openapi.md
- name: plentymarkets REST-API - Delete a plugin
  x-api-slug: restpluginspluginidplugin-setspluginsetid-delete
  description: |-
    Deletes a plugin. This call also deletes all plugin files in the inbox folder! To commit the deletion, the
    plugin must be provisioned in Stage or Productive. The ID of the plugin must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpluginspluginidplugin-setspluginsetid-delete-openapi.md
- name: 'plentymarkets REST-API - '
  x-api-slug: restpluginspluginidplugin-setspluginsetidconfiguration-layout-get
  description: .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpluginspluginidplugin-setspluginsetidconfiguration-layout-get-openapi.md
- name: 'plentymarkets REST-API - '
  x-api-slug: restpluginspluginidplugin-setspluginsetidconfigurations-get
  description: .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpluginspluginidplugin-setspluginsetidconfigurations-get-openapi.md
- name: 'plentymarkets REST-API - '
  x-api-slug: restpluginspluginidplugin-setspluginsetidconfigurations-put
  description: .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpluginspluginidplugin-setspluginsetidconfigurations-put-openapi.md
- name: plentymarkets REST-API - Send mail
  x-api-slug: restplugins-mail-post
  description: Send mail from booted plugins.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restplugins-mail-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restplugins-mail-post-openapi.md
- name: plentymarkets REST-API - List properties
  x-api-slug: restproperties-get
  description: Lists properties.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restproperties-get-openapi.md
- name: plentymarkets REST-API - Create a property
  x-api-slug: restproperties-post
  description: Creates a property
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restproperties-post-openapi.md
- name: plentymarkets REST-API - List availabilities
  x-api-slug: restpropertiesavailabilities-get
  description: Lists availabilities.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesavailabilities-get-openapi.md
- name: plentymarkets REST-API - Create an availability
  x-api-slug: restpropertiesavailabilities-post
  description: Creates an availability.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesavailabilities-post-openapi.md
- name: plentymarkets REST-API - Delete an availability
  x-api-slug: restpropertiesavailabilitiesavailabilityid-delete
  description: Deletes an availability. The ID ot the availability must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesavailabilitiesavailabilityid-delete-openapi.md
- name: plentymarkets REST-API - Get an availability
  x-api-slug: restpropertiesavailabilitiesavailabilityid-get
  description: Gets an availability. The ID of the availability must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesavailabilitiesavailabilityid-get-openapi.md
- name: plentymarkets REST-API - Update an availability
  x-api-slug: restpropertiesavailabilitiesavailabilityid-put
  description: Updates an availability. The ID of the availabilty must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesavailabilitiesavailabilityid-put-openapi.md
- name: plentymarkets REST-API - Get property destinations
  x-api-slug: restpropertiesdestinations-get
  description: 'Returns a json with the destinations processed: data from providers
    and translations.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesdestinations-get-openapi.md
- name: plentymarkets REST-API - List property groups
  x-api-slug: restpropertiesgroups-get
  description: Lists property groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesgroups-get-openapi.md
- name: plentymarkets REST-API - Create a property group
  x-api-slug: restpropertiesgroups-post
  description: Creates a property group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesgroups-post-openapi.md
- name: plentymarkets REST-API - List group names
  x-api-slug: restpropertiesgroupsnames-get
  description: Lists group names.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesgroupsnames-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesgroupsnames-get-openapi.md
- name: plentymarkets REST-API - Create an group name
  x-api-slug: restpropertiesgroupsnames-post
  description: Create an group name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesgroupsnames-post-openapi.md
- name: plentymarkets REST-API - Delete a group name
  x-api-slug: restpropertiesgroupsnamesgroupnameid-delete
  description: Deletes a group name. The ID of the group name must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesgroupsnamesgroupnameid-delete-openapi.md
- name: plentymarkets REST-API - Get a group name
  x-api-slug: restpropertiesgroupsnamesgroupnameid-get
  description: Gets a group name. The ID of the group name must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesgroupsnamesgroupnameid-get-openapi.md
- name: plentymarkets REST-API - Update a group name
  x-api-slug: restpropertiesgroupsnamesgroupnameid-put
  description: Updates a group name. The ID of the group name must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesgroupsnamesgroupnameid-put-openapi.md
- name: plentymarkets REST-API - List group options
  x-api-slug: restpropertiesgroupsoptions-get
  description: Lists group options.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesgroupsoptions-get-openapi.md
- name: plentymarkets REST-API - Create a group option
  x-api-slug: restpropertiesgroupsoptions-post
  description: Creates a group option
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesgroupsoptions-post-openapi.md
- name: plentymarkets REST-API - Delete a group option
  x-api-slug: restpropertiesgroupsoptionsgroupoptionid-delete
  description: Deletes a group option. The ID of the group option must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesgroupsoptionsgroupoptionid-delete-openapi.md
- name: plentymarkets REST-API - Get a group option
  x-api-slug: restpropertiesgroupsoptionsgroupoptionid-get
  description: Gets a group option. The ID of the group option must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesgroupsoptionsgroupoptionid-get-openapi.md
- name: plentymarkets REST-API - Update a group option
  x-api-slug: restpropertiesgroupsoptionsgroupoptionid-put
  description: Updates a group option. The ID of the group option must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesgroupsoptionsgroupoptionid-put-openapi.md
- name: plentymarkets REST-API - Get surcharge types from module configuration
  x-api-slug: restpropertiesgroupssurchargetypes-get
  description: Get surcharge types from module configuration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesgroupssurchargetypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesgroupssurchargetypes-get-openapi.md
- name: plentymarkets REST-API - Get group types from module configuration
  x-api-slug: restpropertiesgroupstypes-get
  description: Get group types from module configuration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesgroupstypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesgroupstypes-get-openapi.md
- name: plentymarkets REST-API - Get a property group
  x-api-slug: restpropertiesgroupsgroupid-get
  description: Gets a property group. The ID of the property group must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesgroupsgroupid-get-openapi.md
- name: plentymarkets REST-API - Update a property group
  x-api-slug: restpropertiesgroupsgroupid-put
  description: Updates a property group. The ID of the property group must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesgroupsgroupid-put-openapi.md
- name: plentymarkets REST-API - Mass attach propertyId and groupId collection into
    the pivot table.
  x-api-slug: restpropertiesgroupsgroupidproperties-post
  description: Mass attach propertyid and groupid collection into the pivot table..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesgroupsgroupidproperties-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesgroupsgroupidproperties-post-openapi.md
- name: plentymarkets REST-API - Detach a property from a property group.
  x-api-slug: restpropertiesgroupsgroupidpropertiespropertyid-delete
  description: Detaches a property from a property group. The ID of the property and
    the ID of the property group must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesgroupsgroupidpropertiespropertyid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesgroupsgroupidpropertiespropertyid-delete-openapi.md
- name: plentymarkets REST-API - Attach a property to a property group
  x-api-slug: restpropertiesgroupsgroupidpropertiespropertyid-post
  description: Attaches a property to a property group. The ID of the property and
    the ID of the property group must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesgroupsgroupidpropertiespropertyid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesgroupsgroupidpropertiespropertyid-post-openapi.md
- name: plentymarkets REST-API - Delete a property group
  x-api-slug: restpropertiesgroupspropertyid-delete
  description: Deletes a property group. The ID of the property group must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesgroupspropertyid-delete-openapi.md
- name: plentymarkets REST-API - List property markets
  x-api-slug: restpropertiesmarkets-get
  description: Lists property markets
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesmarkets-get-openapi.md
- name: plentymarkets REST-API - Create a property market
  x-api-slug: restpropertiesmarkets-post
  description: Creates a property market.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesmarkets-post-openapi.md
- name: plentymarkets REST-API - Delete a property market
  x-api-slug: restpropertiesmarketspropertiesmarketid-delete
  description: Deletes a property market. The ID of the property market must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesmarketspropertiesmarketid-delete-openapi.md
- name: plentymarkets REST-API - Get a property market
  x-api-slug: restpropertiesmarketspropertiesmarketid-get
  description: Gets a property market. The ID of the property market must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesmarketspropertiesmarketid-get-openapi.md
- name: plentymarkets REST-API - Update a property market
  x-api-slug: restpropertiesmarketspropertiesmarketid-put
  description: Updates a property market. The ID of the property market must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesmarketspropertiesmarketid-put-openapi.md
- name: plentymarkets REST-API - List names
  x-api-slug: restpropertiesnames-get
  description: Lists names.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesnames-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesnames-get-openapi.md
- name: plentymarkets REST-API - Create a name
  x-api-slug: restpropertiesnames-post
  description: Creates a name
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesnames-post-openapi.md
- name: plentymarkets REST-API - Delete a property name
  x-api-slug: restpropertiesnamesnameid-delete
  description: Deletes a property name. The ID of the property name must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesnamesnameid-delete-openapi.md
- name: plentymarkets REST-API - Get a property name
  x-api-slug: restpropertiesnamesnameid-get
  description: Gets a proeprty name. The ID of the property name must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesnamesnameid-get-openapi.md
- name: plentymarkets REST-API - Update a property name
  x-api-slug: restpropertiesnamesnameid-put
  description: Updates a property name. The ID of the property name must be specified
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesnamesnameid-put-openapi.md
- name: plentymarkets REST-API - List property options
  x-api-slug: restpropertiesoptions-get
  description: Lists property options.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesoptions-get-openapi.md
- name: plentymarkets REST-API - Create a property option
  x-api-slug: restpropertiesoptions-post
  description: Creates a property option.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesoptions-post-openapi.md
- name: plentymarkets REST-API - Delete a property option
  x-api-slug: restpropertiesoptionspropertyoptionid-delete
  description: Deletes a property option. The ID of the proeprty option must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesoptionspropertyoptionid-delete-openapi.md
- name: plentymarkets REST-API - Get a property option
  x-api-slug: restpropertiesoptionspropertyoptionid-get
  description: Gets a property option. The ID of the property option must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesoptionspropertyoptionid-get-openapi.md
- name: plentymarkets REST-API - Update a property option
  x-api-slug: restpropertiesoptionspropertyoptionid-put
  description: Updates a property option. The ID of the property option must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesoptionspropertyoptionid-put-openapi.md
- name: plentymarkets REST-API - Delete property relations
  x-api-slug: restpropertiesrelations-delete
  description: Deletes property relations. The ID of the property relations must be
    specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesrelations-delete-openapi.md
- name: plentymarkets REST-API - List property relations
  x-api-slug: restpropertiesrelations-get
  description: Lists property relations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesrelations-get-openapi.md
- name: plentymarkets REST-API - Create a property relation
  x-api-slug: restpropertiesrelations-post
  description: Creates a property relation
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesrelations-post-openapi.md
- name: plentymarkets REST-API - Update relations
  x-api-slug: restpropertiesrelations-put
  description: Updates relations
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesrelations-put-openapi.md
- name: plentymarkets REST-API - List relation markups
  x-api-slug: restpropertiesrelationsmarkups-get
  description: Lists relation markups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesrelationsmarkups-get-openapi.md
- name: plentymarkets REST-API - Create a property relation markup
  x-api-slug: restpropertiesrelationsmarkups-post
  description: Creates a property relation markup
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesrelationsmarkups-post-openapi.md
- name: plentymarkets REST-API - Delete a property relation markup
  x-api-slug: restpropertiesrelationsmarkupsrelationmarkupid-delete
  description: Deletes a property relation markup
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesrelationsmarkupsrelationmarkupid-delete-openapi.md
- name: plentymarkets REST-API - Get a property relation markup
  x-api-slug: restpropertiesrelationsmarkupsrelationmarkupid-get
  description: Gets a property relation markup. The ID of the property relation markup
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesrelationsmarkupsrelationmarkupid-get-openapi.md
- name: plentymarkets REST-API - Update a property relation markup
  x-api-slug: restpropertiesrelationsmarkupsrelationmarkupid-put
  description: Updates a property relation markup
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesrelationsmarkupsrelationmarkupid-put-openapi.md
- name: plentymarkets REST-API - List property relation values
  x-api-slug: restpropertiesrelationsvalues-get
  description: Lists property relation values.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesrelationsvalues-get-openapi.md
- name: plentymarkets REST-API - Create a property relation value
  x-api-slug: restpropertiesrelationsvalues-post
  description: Creates a property relation value.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesrelationsvalues-post-openapi.md
- name: plentymarkets REST-API - Update multiple property relation value
  x-api-slug: restpropertiesrelationsvalues-put
  description: Updates multiple property relation value
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesrelationsvalues-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesrelationsvalues-put-openapi.md
- name: plentymarkets REST-API - Delete a property relation value
  x-api-slug: restpropertiesrelationsvaluespropertiesrelationvalueid-delete
  description: Deletes a property relation value. The ID of the property relation
    value must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesrelationsvaluespropertiesrelationvalueid-delete-openapi.md
- name: plentymarkets REST-API - Update a property relation value
  x-api-slug: restpropertiesrelationsvaluespropertiesrelationvalueid-put
  description: Updates a property relation value. The ID of the property relation
    value must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesrelationsvaluespropertiesrelationvalueid-put-openapi.md
- name: plentymarkets REST-API - Get a property relation value
  x-api-slug: restpropertiesrelationsvaluesrelationmarkupid-get
  description: Gets a property relation value. The ID of the property relation value
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesrelationsvaluesrelationmarkupid-get-openapi.md
- name: plentymarkets REST-API - Delete a property relation
  x-api-slug: restpropertiesrelationsrelationid-delete
  description: Deletes a property relation. The ID of the property relation must be
    specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesrelationsrelationid-delete-openapi.md
- name: plentymarkets REST-API - Get a property relation
  x-api-slug: restpropertiesrelationsrelationid-get
  description: Gets a property relation. The ID of the property relation must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesrelationsrelationid-get-openapi.md
- name: plentymarkets REST-API - Update a property relation
  x-api-slug: restpropertiesrelationsrelationid-put
  description: Updates a property relation. The ID of the property relation must be
    specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesrelationsrelationid-put-openapi.md
- name: plentymarkets REST-API - List property selections
  x-api-slug: restpropertiesselections-get
  description: Lists property selections
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesselections-get-openapi.md
- name: plentymarkets REST-API - Create a property selection
  x-api-slug: restpropertiesselections-post
  description: Creates a property selection.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesselections-post-openapi.md
- name: plentymarkets REST-API - Delete a property selection
  x-api-slug: restpropertiesselectionspropertyselectionid-delete
  description: Deletes a property selection
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesselectionspropertyselectionid-delete-openapi.md
- name: plentymarkets REST-API - Get a property selection
  x-api-slug: restpropertiesselectionspropertyselectionid-get
  description: Gets a property selection. The ID of property selection must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesselectionspropertyselectionid-get-openapi.md
- name: plentymarkets REST-API - Update a property selection
  x-api-slug: restpropertiesselectionspropertyselectionid-put
  description: Updates a property selection. The ID of the property selection must
    be specifed.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiesselectionspropertyselectionid-put-openapi.md
- name: plentymarkets REST-API - Get system language
  x-api-slug: restpropertiessystemlang-get
  description: Gets the system language.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiessystemlang-get-openapi.md
- name: plentymarkets REST-API - Delete a property
  x-api-slug: restpropertiespropertyid-delete
  description: Deletes a property. The ID of the property must be specified
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiespropertyid-delete-openapi.md
- name: plentymarkets REST-API - Get a property.
  x-api-slug: restpropertiespropertyid-get
  description: Gets a property. The ID of the property must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiespropertyid-get-openapi.md
- name: plentymarkets REST-API - Update a property
  x-api-slug: restpropertiespropertyid-put
  description: Updates a property. The ID of the property must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restpropertiespropertyid-put-openapi.md
- name: plentymarkets REST-API - List all content links for a given plugin set
  x-api-slug: restshop-buildercontent-links-get
  description: List all content links for a given plugin set.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restshop-buildercontent-links-get-openapi.md
- name: plentymarkets REST-API - Link a content to a a layout container of a frontend
    plugin.
  x-api-slug: restshop-buildercontent-links-post
  description: Link a content to a a layout container of a frontend plugin..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restshop-buildercontent-links-post-openapi.md
- name: plentymarkets REST-API - Delete a content link.
  x-api-slug: restshop-buildercontent-linkscontentlinkid-delete
  description: Delete a content link..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restshop-buildercontent-linkscontentlinkid-delete-openapi.md
- name: plentymarkets REST-API - Find a content link by id.
  x-api-slug: restshop-buildercontent-linkscontentlinkid-get
  description: Find a content link by id..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restshop-buildercontent-linkscontentlinkid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restshop-buildercontent-linkscontentlinkid-get-openapi.md
- name: plentymarkets REST-API - Update a content link.
  x-api-slug: restshop-buildercontent-linkscontentlinkid-put
  description: Update a content link..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restshop-buildercontent-linkscontentlinkid-put-openapi.md
- name: plentymarkets REST-API - List all contents.
  x-api-slug: restshop-buildercontents-get
  description: List all contents..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restshop-buildercontents-get-openapi.md
- name: plentymarkets REST-API - Create a new content.
  x-api-slug: restshop-buildercontents-post
  description: Create a new content..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restshop-buildercontents-post-openapi.md
- name: plentymarkets REST-API - Delete a content
  x-api-slug: restshop-buildercontentscontentid-delete
  description: Delete a content.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restshop-buildercontentscontentid-delete-openapi.md
- name: plentymarkets REST-API - Find a content by id.
  x-api-slug: restshop-buildercontentscontentid-get
  description: Find a content by id..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restshop-buildercontentscontentid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restshop-buildercontentscontentid-get-openapi.md
- name: plentymarkets REST-API - Update a content.
  x-api-slug: restshop-buildercontentscontentid-put
  description: Update a content..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restshop-buildercontentscontentid-put-openapi.md
- name: plentymarkets REST-API - List content pages from all plugins in a given plugin
    set.
  x-api-slug: restshop-builderpages-get
  description: List content pages from all plugins in a given plugin set..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restshop-builderpages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restshop-builderpages-get-openapi.md
- name: plentymarkets REST-API - List all widgets provided by all frontend plugins
    of a given plugin set.
  x-api-slug: restshop-builderwidgets-get
  description: List all widgets provided by all frontend plugins of a given plugin
    set..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restshop-builderwidgets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restshop-builderwidgets-get-openapi.md
- name: plentymarkets REST-API - Render the preview for widgets.
  x-api-slug: restshop-builderwidgets-post
  description: Render the preview for widgets..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restshop-builderwidgets-post-openapi.md
- name: plentymarkets REST-API - List stock
  x-api-slug: reststockmanagementstock-get
  description: Lists stock of all warehouses.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststockmanagementstock-get-openapi.md
- name: plentymarkets REST-API - Redistribute stock
  x-api-slug: reststockmanagementstockredistribute-put
  description: Redistributes stock of one storage location among one or more storage
    locations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststockmanagementstockredistribute-put-openapi.md
- name: plentymarkets REST-API - List stock by warehouse type
  x-api-slug: reststockmanagementstocktypestype-get
  description: Lists stock for all warehouses of the same warehouse type. The name
    of the type must be specified. Currently the only type available is 'sales'.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststockmanagementstocktypestype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststockmanagementstocktypestype-get-openapi.md
- name: plentymarkets REST-API - List warehouses
  x-api-slug: reststockmanagementwarehouses-get
  description: Lists warehouses without applying any filters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststockmanagementwarehouses-get-openapi.md
- name: plentymarkets REST-API - Create a warehouse
  x-api-slug: reststockmanagementwarehouses-post
  description: Create a warehouse.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststockmanagementwarehouses-post-openapi.md
- name: plentymarkets REST-API - Create an address for existing warehouse
  x-api-slug: reststockmanagementwarehousesaddresses-post
  description: Create an address for existing warehouse.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststockmanagementwarehousesaddresses-post-openapi.md
- name: plentymarkets REST-API - Get a warehouse
  x-api-slug: reststockmanagementwarehouseswarehouseid-get
  description: Gets a warehouse. The id of the warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseid-get-openapi.md
- name: plentymarkets REST-API - List warehouse addresses
  x-api-slug: reststockmanagementwarehouseswarehouseidaddressesrelationtypeid-get
  description: List warehouse addresses. The ID of the warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidaddressesrelationtypeid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidaddressesrelationtypeid-get-openapi.md
- name: plentymarkets REST-API - List racks
  x-api-slug: reststockmanagementwarehouseswarehouseidmanagementracks-get
  description: Lists racks for a warehouse. The id of the warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementracks-get-openapi.md
- name: plentymarkets REST-API - Create a rack
  x-api-slug: reststockmanagementwarehouseswarehouseidmanagementracks-post
  description: Creates a rack. The id of the warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementracks-post-openapi.md
- name: plentymarkets REST-API - Get a rack
  x-api-slug: reststockmanagementwarehouseswarehouseidmanagementracksrackid-get
  description: Gets a rack. The id of the rack and the id of the warehouse must be
    specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementracksrackid-get-openapi.md
- name: plentymarkets REST-API - List shelves
  x-api-slug: reststockmanagementwarehouseswarehouseidmanagementracksrackidshelves-get
  description: Lists shelves for a warehouse. The id of the rack and the id of the
    warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementracksrackidshelves-get-openapi.md
- name: plentymarkets REST-API - Create a shelf
  x-api-slug: reststockmanagementwarehouseswarehouseidmanagementracksrackidshelves-post
  description: Creates a shelf. The id of the warehouse and the id of the rack must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementracksrackidshelves-post-openapi.md
- name: plentymarkets REST-API - Get a shelf
  x-api-slug: reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfid-get
  description: Gets a shelf. The id of the shelf, the id of the rack and the id of
    the warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfid-get-openapi.md
- name: plentymarkets REST-API - List storage locations
  x-api-slug: reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocations-get
  description: Lists storage locations. The id of the warehouse, the id of the rack
    and the id of the shelf must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocations-get-openapi.md
- name: plentymarkets REST-API - Create a storage location
  x-api-slug: reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocations-post
  description: Creates a storage location. The id of the warehouse, the id of the
    rack and the id of the shelf must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocations-post-openapi.md
- name: plentymarkets REST-API - Get a storage location
  x-api-slug: reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocationsstoragelocationid-get
  description: Gets a storage location. The id of the warehouse, the id of the rack,
    the id of the shelf and the id of the storage location must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocationsstoragelocationid-get-openapi.md
- name: plentymarkets REST-API - List storage locations
  x-api-slug: reststockmanagementwarehouseswarehouseidmanagementstoragelocations-get
  description: Lists storage locations that belong to a warehouse. The id of the warehouse
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementstoragelocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementstoragelocations-get-openapi.md
- name: plentymarkets REST-API - Get a storage location
  x-api-slug: reststockmanagementwarehouseswarehouseidmanagementstoragelocationsstoragelocationid-get
  description: Gets a storage location. The id of the storage location and the id
    of the warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementstoragelocationsstoragelocationid-get-openapi.md
- name: plentymarkets REST-API - List stock by warehouse
  x-api-slug: reststockmanagementwarehouseswarehouseidstock-get
  description: Lists stock for a warehouse. The ID of the warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidstock-get-openapi.md
- name: plentymarkets REST-API - Book incoming stock
  x-api-slug: reststockmanagementwarehouseswarehouseidstockbookincomingitems-put
  description: Books incoming stock for multiple variations. The incoming stock will
    be added to the existing stock. The ID of the warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidstockbookincomingitems-put-openapi.md
- name: plentymarkets REST-API - Correct stock
  x-api-slug: reststockmanagementwarehouseswarehouseidstockcorrection-put
  description: Corrects stock. The ID of the warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidstockcorrection-put-openapi.md
- name: plentymarkets REST-API - List stock movements
  x-api-slug: reststockmanagementwarehouseswarehouseidstockmovements-get
  description: |-
    Lists stock movements for a warehouse. The ID of the warehouse must be specified. To get movements older than 3 months, set the 'year' parameter.
    NOTE: You can either get archive entries or non-archive entries. You can not get entries for the current year that are younger and older than 3 months with one request. You need separate requests to get entries older and younger than 3 months. To get all entries younger than 3 month you do not need to specify a year or any createdAt parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidstockmovements-get-openapi.md
- name: plentymarkets REST-API - List stock of a warehouse per storage location
  x-api-slug: reststockmanagementwarehouseswarehouseidstockstoragelocations-get
  description: Lists stock of a warehouse for each variation and storage location.
    The stock will only be listed if the stock is positive. Negative stock will not
    be listed. The ID of the warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidstockstoragelocations-get-openapi.md
- name: plentymarkets REST-API - Remove a single object from frontend storage.
  x-api-slug: reststoragefrontendfile-delete
  description: Remove a single object from frontend storage..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststoragefrontendfile-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststoragefrontendfile-delete-openapi.md
- name: plentymarkets REST-API - Get file information for a single object in frontend
    storage. Append public cloudfront url to retrieved object.
  x-api-slug: reststoragefrontendfile-get
  description: Get file information for a single object in frontend storage. append
    public cloudfront url to retrieved object..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststoragefrontendfile-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststoragefrontendfile-get-openapi.md
- name: plentymarkets REST-API - Upload a single file to frontend storage.
  x-api-slug: reststoragefrontendfile-post
  description: If file is an image, generate a thumbnail and store dimensions in metadata.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststoragefrontendfile-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststoragefrontendfile-post-openapi.md
- name: plentymarkets REST-API - Get assigend metadata for a single storage object
  x-api-slug: reststoragefrontendfilemetadata-get
  description: Get assigend metadata for a single storage object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststoragefrontendfilemetadata-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststoragefrontendfilemetadata-get-openapi.md
- name: plentymarkets REST-API - Update metadata of an storage object
  x-api-slug: reststoragefrontendfilemetadata-post
  description: Update metadata of an storage object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststoragefrontendfilemetadata-post-openapi.md
- name: plentymarkets REST-API - Delete files from frontend storage.
  x-api-slug: reststoragefrontendfiles-delete
  description: Deletes a list of files from frontend storage. A list of storage keys
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststoragefrontendfiles-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststoragefrontendfiles-delete-openapi.md
- name: plentymarkets REST-API - List files from frontend storage. Append public cloudfront
    url to each retrieved object.
  x-api-slug: reststoragefrontendfiles-get
  description: List files from frontend storage. append public cloudfront url to each
    retrieved object..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststoragefrontendfiles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststoragefrontendfiles-get-openapi.md
- name: plentymarkets REST-API - Get the URL for a layout document
  x-api-slug: reststoragefrontendobjecturl-get
  description: Gets the URL of a layout document. The storage key must be specified.
    The returned URL expires after 10 minutes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststoragefrontendobjecturl-get-openapi.md
- name: plentymarkets REST-API - Delete layout documents
  x-api-slug: reststoragelayout-delete
  description: Deletes a list of layout documents from storage. A list of storage
    keys must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststoragelayout-delete-openapi.md
- name: plentymarkets REST-API - Upload a layout document
  x-api-slug: reststoragelayout-post
  description: Uploads a layout document to storage. The storage key (i.e. file path)
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststoragelayout-post-openapi.md
- name: plentymarkets REST-API - List layout documents
  x-api-slug: reststoragelayoutlist-get
  description: |-
    Lists up to 1000 layout documents per request. If more than 1000 layout documents are available,
    a <code>nextContinuationToken</code> is returned. Use this token to get the next (up to) 1000 layout documents.
    Use the same request and include a field with the key <code>continuationToken</code> as well as the returned
    token from the previous call as the value.

    Check the <code>isTruncated</code> field in the response to see if more results are available. If <code>isTruncated</code> is true,
    repeat the request using the token from the <code>nextContinuationToken</code> field of the previous response to get all
    results.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststoragelayoutlist-get-openapi.md
- name: plentymarkets REST-API - Get the URL for a layout document
  x-api-slug: reststoragelayoutobjecturl-get
  description: Gets the URL of a layout document. The storage key must be specified.
    The returned URL expires after 10 minutes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststoragelayoutobjecturl-get-openapi.md
- name: plentymarkets REST-API - Get the URL for a order property file
  x-api-slug: reststorageorderpropertiesobjecturl-get
  description: |-
    Gets the URL of a order property file. The storage key must be specified. The returned URL expires after 10
    minutes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststorageorderpropertiesobjecturl-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststorageorderpropertiesobjecturl-get-openapi.md
- name: plentymarkets REST-API - Delete files from the inbox
  x-api-slug: reststoragepluginsinbox-delete
  description: Deletes a list of files from the inbox. A list of storage keys must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststoragepluginsinbox-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststoragepluginsinbox-delete-openapi.md
- name: plentymarkets REST-API - Upload a file to the inbox
  x-api-slug: reststoragepluginsinbox-post
  description: Uploads a file to the inbox. The storage key (i.e. file path) must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststoragepluginsinbox-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststoragepluginsinbox-post-openapi.md
- name: 'plentymarkets REST-API - '
  x-api-slug: reststoragepluginsinboxcommit-post
  description: .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststoragepluginsinboxcommit-post-openapi.md
- name: plentymarkets REST-API - List files from the inbox
  x-api-slug: reststoragepluginsinboxlist-get
  description: |-
    Lists all files of all plugins stored in the inbox. A prefix can be specified to list all files of a specific
    plugin folder only.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststoragepluginsinboxlist-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststoragepluginsinboxlist-get-openapi.md
- name: plentymarkets REST-API - Get the content of a file from the inbox
  x-api-slug: reststoragepluginsinboxobjecturl-get
  description: Gets the content of a file stored in the inbox. The storage key (i.e.
    file path) must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststoragepluginsinboxobjecturl-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststoragepluginsinboxobjecturl-get-openapi.md
- name: plentymarkets REST-API - Get the ID of an accounting location of a country
  x-api-slug: reststoresplentyidlocations-get
  description: Gets the ID of an accounting location of a country. The plenty ID of
    the client and the ID of the country must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/reststoresplentyidlocations-get-openapi.md
- name: plentymarkets REST-API - Get the cloud metrics for this system
  x-api-slug: restsystemcloudmetrics-get
  description: Get the cloud metrics for this system.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restsystemcloudmetrics-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restsystemcloudmetrics-get-openapi.md
- name: plentymarkets REST-API - Supply usage data for given plentymarkets system
  x-api-slug: restsystemmetricsplentyiddate-get
  description: Supply usage data for given plentymarkets system.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restsystemmetricsplentyiddate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restsystemmetricsplentyiddate-get-openapi.md
- name: plentymarkets REST-API - List tickets by filters
  x-api-slug: resttickets-get
  description: List tickets by filters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/resttickets-get-openapi.md
- name: plentymarkets REST-API - Create a ticket
  x-api-slug: resttickets-post
  description: Create a ticket.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/resttickets-post-openapi.md
- name: 'plentymarkets REST-API - '
  x-api-slug: restticketsstatusnames-get
  description: .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restticketsstatusnames-get-openapi.md
- name: 'plentymarkets REST-API - '
  x-api-slug: restticketsstatustypenames-get
  description: .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restticketsstatustypenames-get-openapi.md
- name: 'plentymarkets REST-API - '
  x-api-slug: restticketstypesnames-get
  description: .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restticketstypesnames-get-openapi.md
- name: plentymarkets REST-API - Create a message
  x-api-slug: restticketsticketid-post
  description: Creates a message for the ticket. The ID of the ticket must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restticketsticketid-post-openapi.md
- name: plentymarkets REST-API - Update a ticket
  x-api-slug: restticketsticketid-put
  description: Updates a ticket. The ID of the ticket must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restticketsticketid-put-openapi.md
- name: 'plentymarkets REST-API - '
  x-api-slug: restuser-get
  description: .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restuser-get-openapi.md
- name: plentymarkets REST-API - Get authorized user with UiConfig
  x-api-slug: restuserauthorized-user-with-ui-config-get
  description: Gets an authorized user with UiConfig. This call returns a JSON object
    with information about the user after login. This information is used for correctly
    displaying the plentymarkets back end.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restuserauthorized-user-with-ui-config-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restuserauthorized-user-with-ui-config-get-openapi.md
- name: plentymarkets REST-API - get the backend plugin set for user
  x-api-slug: restuserbackend-pluginset-get
  description: Get the backend plugin set for user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restuserbackend-pluginset-get-openapi.md
- name: plentymarkets REST-API - set the backend plugin set for user
  x-api-slug: restuserbackend-pluginset-post
  description: Set the backend plugin set for user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restuserbackend-pluginset-post-openapi.md
- name: plentymarkets REST-API - List VAT configurations.
  x-api-slug: restvat-get
  description: Lists the VAT configurations for the given filter. Possible filters
    are <code>locationId</code>, <code>countryId</code>, <code>taxIdNumber</code>
    and <code>startedAt</code>.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restvat-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restvat-get-openapi.md
- name: plentymarkets REST-API - Create a VAT configuration
  x-api-slug: restvat-post
  description: Create a vat configuration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restvat-post-openapi.md
- name: plentymarkets REST-API - List VAT configurations of an accounting location
  x-api-slug: restvatlocationslocationid-get
  description: Lists the VAT configurations for all countries of one accounting location
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restvatlocationslocationid-get-openapi.md
- name: plentymarkets REST-API - List VAT configurations for one country of delivery
  x-api-slug: restvatlocationslocationidcountriescountryid-get
  description: Lists the VAT configurations for a country of delivery of one accounting
    location. The ID of the accounting location and the ID of the country of delivery
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restvatlocationslocationidcountriescountryid-get-openapi.md
- name: plentymarkets REST-API - Get a VAT configuration for a country in a location.
  x-api-slug: restvatlocationslocationidcountriescountryiddatedate-get
  description: Gets the VAT configuration found by matching the given location, delivery
    country and date of validity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restvatlocationslocationidcountriescountryiddatedate-get-openapi.md
- name: plentymarkets REST-API - Get a VAT configuration for the standard accounting
    location of a client
  x-api-slug: restvatstandard-get
  description: Gets the VAT configuration currently used for the country of the standard
    accounting location of a client (store). The ID of the client (store) must be
    specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restvatstandard-get-openapi.md
- name: plentymarkets REST-API - Get a VAT configuration by id
  x-api-slug: restvatvatid-get
  description: Get a vat configuration by id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restvatvatid-get-openapi.md
- name: plentymarkets REST-API - Update a VAT configuration
  x-api-slug: restvatvatid-put
  description: Update a vat configuration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restvatvatid-put-openapi.md
- name: plentymarkets REST-API - Create a warehouse location layout
  x-api-slug: restwarehouseslayouts-post
  description: Creates a warehouse location layout
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restwarehouseslayouts-post-openapi.md
- name: plentymarkets REST-API - Delete multiple warehouse locations
  x-api-slug: restwarehouseslocations-delete
  description: Deletes multiple warehouse locations
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restwarehouseslocations-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restwarehouseslocations-delete-openapi.md
- name: plentymarkets REST-API - Create a warehouse location
  x-api-slug: restwarehouseslocations-post
  description: Creates a warehouse location.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restwarehouseslocations-post-openapi.md
- name: plentymarkets REST-API - Get warehouse location details
  x-api-slug: restwarehouseslocationsdetails-get
  description: Gets warehouse location details
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restwarehouseslocationsdetails-get-openapi.md
- name: plentymarkets REST-API - Create a warehouse location dimension
  x-api-slug: restwarehouseslocationsdimensions-post
  description: Creates a warehouse location dimension.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restwarehouseslocationsdimensions-post-openapi.md
- name: plentymarkets REST-API - Delete a warehouse location dimension
  x-api-slug: restwarehouseslocationsdimensionswarehouselocationdimensionid-delete
  description: Deletes a warehouse location dimension
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restwarehouseslocationsdimensionswarehouselocationdimensionid-delete-openapi.md
- name: plentymarkets REST-API - Get a warehouse location dimension
  x-api-slug: restwarehouseslocationsdimensionswarehouselocationdimensionid-get
  description: Gets a warehouse location dimension by ID. The warehouse location ID
    is required.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restwarehouseslocationsdimensionswarehouselocationdimensionid-get-openapi.md
- name: plentymarkets REST-API - Update a warehouse location dimension
  x-api-slug: restwarehouseslocationsdimensionswarehouselocationdimensionid-put
  description: Updates a warehouse location dimension
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restwarehouseslocationsdimensionswarehouselocationdimensionid-put-openapi.md
- name: plentymarkets REST-API - Edit the purpose and status for a group of storage
    locations
  x-api-slug: restwarehouseslocationsgroup-put
  description: Edits the purpose and status for a group of storage locations by passing
    the group storage location ID (can be sent as mass assignment)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restwarehouseslocationsgroup-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restwarehouseslocationsgroup-put-openapi.md
- name: plentymarkets REST-API - Create a warehouse location level
  x-api-slug: restwarehouseslocationslevels-post
  description: Creates a warehouse location level.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restwarehouseslocationslevels-post-openapi.md
- name: plentymarkets REST-API - Delete a warehouse location level
  x-api-slug: restwarehouseslocationslevelswarehouselocationlevelid-delete
  description: Deletes a warehouse location level
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restwarehouseslocationslevelswarehouselocationlevelid-delete-openapi.md
- name: plentymarkets REST-API - Get a warehouse location level
  x-api-slug: restwarehouseslocationslevelswarehouselocationlevelid-get
  description: Gets a warehouse location level by ID. The warehouse location ID is
    required.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restwarehouseslocationslevelswarehouselocationlevelid-get-openapi.md
- name: plentymarkets REST-API - Update a warehouse location level
  x-api-slug: restwarehouseslocationslevelswarehouselocationlevelid-put
  description: Updates a warehouse location level
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restwarehouseslocationslevelswarehouselocationlevelid-put-openapi.md
- name: plentymarkets REST-API - Create multiple warehouse location dimensions
  x-api-slug: restwarehouseslocationsmultiple-dimensions-post
  description: Creates multiple warehouse location dimension.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restwarehouseslocationsmultiple-dimensions-post-openapi.md
- name: plentymarkets REST-API - Generate warehouse location preview and saves it
  x-api-slug: restwarehouseslocationspreviews-post
  description: Generates warehouse location preview and saves it
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restwarehouseslocationspreviews-post-openapi.md
- name: plentymarkets REST-API - Generate the warehouse location label
  x-api-slug: restwarehouseslocationswarehouseidlabel-get
  description: Generates the warehouse location label
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restwarehouseslocationswarehouseidlabel-get-openapi.md
- name: plentymarkets REST-API - Delete a warehouse location
  x-api-slug: restwarehouseslocationswarehouselocationid-delete
  description: Deletes a warehouse location
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restwarehouseslocationswarehouselocationid-delete-openapi.md
- name: plentymarkets REST-API - Get a warehouse location
  x-api-slug: restwarehouseslocationswarehouselocationid-get
  description: Gets a warehouse location by ID. The warehouse location ID is required.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restwarehouseslocationswarehouselocationid-get-openapi.md
- name: plentymarkets REST-API - Update a warehouse location
  x-api-slug: restwarehouseslocationswarehouselocationid-put
  description: Updates a warehouse location
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restwarehouseslocationswarehouselocationid-put-openapi.md
- name: plentymarkets REST-API - Get a warehouse location structure
  x-api-slug: restwarehousesstructurewarehouseid-get
  description: Gets a warehouse location structure by warehouse ID. The warehouse
    ID is required.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restwarehousesstructurewarehouseid-get-openapi.md
- name: plentymarkets REST-API - List warehouse locations
  x-api-slug: restwarehouseswarehouseidlocations-get
  description: Lists all warehouse locations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restwarehouseswarehouseidlocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restwarehouseswarehouseidlocations-get-openapi.md
- name: plentymarkets REST-API - List warehouse location dimensions
  x-api-slug: restwarehouseswarehouseidlocationsdimensions-get
  description: Lists all warehouse location dimensions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restwarehouseswarehouseidlocationsdimensions-get-openapi.md
- name: plentymarkets REST-API - List warehouse location levels
  x-api-slug: restwarehouseswarehouseidlocationslevels-get
  description: Lists all warehouse location levels.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restwarehouseswarehouseidlocationslevels-get-openapi.md
- name: plentymarkets REST-API - List clients (stores)
  x-api-slug: restwebstores-get
  description: List clients (stores).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restwebstores-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restwebstores-get-openapi.md
- name: 'plentymarkets REST-API - '
  x-api-slug: restwebstoreswebstoreidplugin-set-get
  description: .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restwebstoreswebstoreidplugin-set-get-openapi.md
- name: 'plentymarkets REST-API - '
  x-api-slug: restwebstoreswebstoreidplugin-set-post
  description: .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/plentymarkets/master/_listings/plentymarkets/restwebstoreswebstoreidplugin-set-post-openapi.md
x-common:
- type: x-blog-rss
  url: https://www.plentymarkets.co.uk/?ActionCall=WebActionRSS&rrss_id=1
- type: x-github
  url: https://github.com/plentymarkets
- type: x-twitter
  url: https://twitter.com/plentymarketsuk
- type: x-website
  url: http://www.plentymarkets.co.uk
- type: x-api-gallery
  url: http://pivotal.tracker.api.gallery.streamdata.io
- type: x-api-stack
  url: http://plentymarkets.stack.network
- type: x-blog
  url: https://www.plentymarkets.co.uk/blog/
- type: x-pricing
  url: https://www.plentymarkets.co.uk/prices/
- type: x-website
  url: https://www.plentymarkets.co.uk
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---