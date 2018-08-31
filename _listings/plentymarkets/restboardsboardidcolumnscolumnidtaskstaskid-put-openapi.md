---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Updates a task.
  description: Updates a task..
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
  /rest/accounting/locations/{webstoreId}/{countryId}/posting_accounts:
    get:
      summary: Get all posting accounts for a country of a webstore
      description: Get all posting accounts for a country of a webstore.
      operationId: getRestAccountingLocationsWebstoreCountryAddingAccounts
      x-api-path-slug: restaccountinglocationswebstoreidcountryidposting-accounts-get
      parameters:
      - in: query
        name: $webstoreId
        description: The ID of the webstore
      - in: path
        name: countryId
      - in: path
        name: webstoreId
      responses:
        200:
          description: OK
      tags:
      - Posting
      - Accountsa
      - Country
      - Of
      - Webstore
  /rest/accounting/stores/locations:
    get:
      summary: List all accounting locations
      description: List all accounting locations.
      operationId: getRestAccountingStoresLocations
      x-api-path-slug: restaccountingstoreslocations-get
      responses:
        200:
          description: OK
      tags:
      - List
      - ""
      - Accounting
      - Locations
  /rest/accounting/stores/{plentyId}/locations:
    get:
      summary: List accounting locations of a client
      description: Lists accounting locations of a client. The plenty ID of the client
        must be specified.
      operationId: getRestAccountingStoresPlentyLocations
      x-api-path-slug: restaccountingstoresplentyidlocations-get
      parameters:
      - in: query
        name: locationId
        description: The plenty ID
      - in: path
        name: plentyId
      responses:
        200:
          description: OK
      tags:
      - List
      - Accounting
      - Locations
      - Of
      - Client
  /rest/accounts:
    get:
      summary: List accounts
      description: List accounts.
      operationId: getRestAccounts
      x-api-path-slug: restaccounts-get
      parameters:
      - in: query
        name: createdAt
        description: Filter that restricts the search result to accounts that were
          created according to given filters
      - in: query
        name: updatedAt
        description: Filter that restricts the search result to accounts that were
          updated according to given filters
      responses:
        200:
          description: OK
      tags:
      - List
      - Accounts
    post:
      summary: Create an account
      description: Create an account.
      operationId: postRestAccounts
      x-api-path-slug: restaccounts-post
      parameters:
      - in: body
        name: /rest/accounts
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Account
  /rest/accounts/addresses:
    post:
      summary: Create an address
      description: Create an address.
      operationId: postRestAccountsAddresses
      x-api-path-slug: restaccountsaddresses-post
      parameters:
      - in: body
        name: /rest/accounts/addresses
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Address
  /rest/accounts/addresses/contact_relations:
    get:
      summary: List address contact relations
      description: List address contact relations.
      operationId: getRestAccountsAddressesContactRelations
      x-api-path-slug: restaccountsaddressescontact-relations-get
      parameters:
      - in: query
        name: addressId
        description: Filter that restricts the search result to addresses with a specific
          ID
      - in: query
        name: contactId
        description: Filter that restricts the search result to contacts with a specific
          ID
      - in: query
        name: id
        description: Filter that restricts the search result to address contact relations
          with a specific ID
      - in: query
        name: isPrimary
        description: Filter that restricts the search result depending on the flag
          used
      - in: query
        name: itemsPerPage
        description: The number of items to list per page
      - in: query
        name: page
        description: The page of results to search for
      - in: query
        name: typeId
        description: Filter that restricts the search result to address types with
          a specific ID
      - in: query
        name: with
        description: Includes the specified address contact relation information in
          the results
      responses:
        200:
          description: OK
      tags:
      - List
      - Address
      - Contact
      - Relations
    post:
      summary: Create address contact relations
      description: Create address contact relations.
      operationId: postRestAccountsAddressesContactRelations
      x-api-path-slug: restaccountsaddressescontact-relations-post
      parameters:
      - in: body
        name: /rest/accounts/addresses/contact_relations
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Address
      - Contact
      - Relations
    put:
      summary: Update address contact relations
      description: Update address contact relations.
      operationId: putRestAccountsAddressesContactRelations
      x-api-path-slug: restaccountsaddressescontact-relations-put
      parameters:
      - in: body
        name: /rest/accounts/addresses/contact_relations
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Address
      - Contact
      - Relations
  /rest/accounts/addresses/contact_relations/{addressContactRelationId}:
    delete:
      summary: Delete an address contact relation
      description: Deletes an address contact relation. The ID of the relation must
        be specified.
      operationId: deleteRestAccountsAddressesContactRelationsAddresscontactrelation
      x-api-path-slug: restaccountsaddressescontact-relationsaddresscontactrelationid-delete
      parameters:
      - in: path
        name: addressContactRelationId
      responses:
        200:
          description: OK
      tags:
      - Address
      - Contact
      - Relation
    get:
      summary: Get an address contact relation
      description: Gets an address contact relation. The ID of the address contact
        relation must be specified.
      operationId: getRestAccountsAddressesContactRelationsAddresscontactrelation
      x-api-path-slug: restaccountsaddressescontact-relationsaddresscontactrelationid-get
      parameters:
      - in: path
        name: addressContactRelationId
      responses:
        200:
          description: OK
      tags:
      - Address
      - Contact
      - Relation
  /rest/accounts/addresses/option_types:
    get:
      summary: List address option types
      description: List address option types.
      operationId: getRestAccountsAddressesOptionTypes
      x-api-path-slug: restaccountsaddressesoption-types-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Address
      - Option
      - Types
    post:
      summary: Create an address option type
      description: Create an address option type.
      operationId: postRestAccountsAddressesOptionTypes
      x-api-path-slug: restaccountsaddressesoption-types-post
      parameters:
      - in: body
        name: /rest/accounts/addresses/option_types
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Address
      - Option
      - Type
  /rest/accounts/addresses/option_types/{optionTypeId}:
    delete:
      summary: Delete an address option type
      description: Deletes an address option type. The ID of the option type must
        be specified.
      operationId: deleteRestAccountsAddressesOptionTypesOptiontype
      x-api-path-slug: restaccountsaddressesoption-typesoptiontypeid-delete
      parameters:
      - in: path
        name: optionTypeId
      responses:
        200:
          description: OK
      tags:
      - Address
      - Option
      - Type
    get:
      summary: Get an address option type
      description: Gets an address option type. The ID of the option type must be
        specified.
      operationId: getRestAccountsAddressesOptionTypesOptiontype
      x-api-path-slug: restaccountsaddressesoption-typesoptiontypeid-get
      parameters:
      - in: path
        name: optionTypeId
      responses:
        200:
          description: OK
      tags:
      - Address
      - Option
      - Type
    put:
      summary: Update an address option type
      description: Updates an address option type. The ID of the option type must
        be specified.
      operationId: putRestAccountsAddressesOptionTypesOptiontype
      x-api-path-slug: restaccountsaddressesoption-typesoptiontypeid-put
      parameters:
      - in: body
        name: /rest/accounts/addresses/option_types/{optionTypeId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: optionTypeId
      responses:
        200:
          description: OK
      tags:
      - Address
      - Option
      - Type
  /rest/accounts/addresses/options/{optionId}:
    delete:
      summary: Delete an address option by the option ID
      description: Deletes an address option. The ID of the option must be specified.
      operationId: deleteRestAccountsAddressesOptionsOption
      x-api-path-slug: restaccountsaddressesoptionsoptionid-delete
      parameters:
      - in: path
        name: optionId
      responses:
        200:
          description: OK
      tags:
      - Address
      - Option
      - By
      - Option
      - ID
    get:
      summary: Get an address option
      description: Gets an address option. The ID of the option must be specified.
      operationId: getRestAccountsAddressesOptionsOption
      x-api-path-slug: restaccountsaddressesoptionsoptionid-get
      parameters:
      - in: path
        name: optionId
      responses:
        200:
          description: OK
      tags:
      - Address
      - Option
    put:
      summary: Update an address option
      description: Updates an address option. The ID of the option must be specified.
      operationId: putRestAccountsAddressesOptionsOption
      x-api-path-slug: restaccountsaddressesoptionsoptionid-put
      parameters:
      - in: path
        name: optionId
      responses:
        200:
          description: OK
      tags:
      - Address
      - Option
  /rest/accounts/addresses/pos_relations:
    get:
      summary: List address POS relations
      description: List address pos relations.
      operationId: getRestAccountsAddressesPosRelations
      x-api-path-slug: restaccountsaddressespos-relations-get
      parameters:
      - in: query
        name: itemsPerPage
        description: items per page
      - in: query
        name: page
        description: page
      - in: query
        name: with
        description: Includes the specified address pos relation information in the
          results
      responses:
        200:
          description: OK
      tags:
      - List
      - Address
      - POS
      - Relations
    post:
      summary: Create an address POS relation
      description: Create an address pos relation.
      operationId: postRestAccountsAddressesPosRelations
      x-api-path-slug: restaccountsaddressespos-relations-post
      responses:
        200:
          description: OK
      tags:
      - Address
      - POS
      - Relation
  /rest/accounts/addresses/pos_relations/{addressPosRelationId}:
    delete:
      summary: Delete an address POS relation
      description: Deletes an address POS relation. The ID of the address POS relation
        must be specified.
      operationId: deleteRestAccountsAddressesPosRelationsAddressposrelation
      x-api-path-slug: restaccountsaddressespos-relationsaddressposrelationid-delete
      parameters:
      - in: path
        name: addressPosRelationId
      responses:
        200:
          description: OK
      tags:
      - Address
      - POS
      - Relation
    get:
      summary: Get an address POS relation
      description: Gets an address POS relation. The ID of the address POS relation
        must be specified.
      operationId: getRestAccountsAddressesPosRelationsAddressposrelation
      x-api-path-slug: restaccountsaddressespos-relationsaddressposrelationid-get
      parameters:
      - in: path
        name: addressPosRelationId
      responses:
        200:
          description: OK
      tags:
      - Address
      - POS
      - Relation
    put:
      summary: Update an address POS relation
      description: Updates an address POS relation. The ID of the address POS relation
        must be specified.
      operationId: putRestAccountsAddressesPosRelationsAddressposrelation
      x-api-path-slug: restaccountsaddressespos-relationsaddressposrelationid-put
      parameters:
      - in: path
        name: addressPosRelationId
      responses:
        200:
          description: OK
      tags:
      - Address
      - POS
      - Relation
  /rest/accounts/addresses/relation_types:
    get:
      summary: List address relation types
      description: List address relation types.
      operationId: getRestAccountsAddressesRelationTypes
      x-api-path-slug: restaccountsaddressesrelation-types-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Address
      - Relation
      - Types
  /rest/accounts/addresses/relations/types/applications/{application}/{lang}:
    get:
      summary: List address relation types
      description: |-
        Lists address relation types. The application and the language must be specified.
        <br>Possible applications:
        <ul>
        <li>contact</li>
        <li>order</li>
        <li>warehouse</li>
        <li>pos</li>
        </ul>
      operationId: getRestAccountsAddressesRelationsTypesApplicationsApplicationLang
      x-api-path-slug: restaccountsaddressesrelationstypesapplicationsapplicationlang-get
      parameters:
      - in: path
        name: application
      - in: path
        name: lang
      responses:
        200:
          description: OK
      tags:
      - List
      - Address
      - Relation
      - Types
  /rest/accounts/addresses/warehouse_relations:
    post:
      summary: Create an address warehouse relation
      description: Create an address warehouse relation.
      operationId: postRestAccountsAddressesWarehouseRelations
      x-api-path-slug: restaccountsaddresseswarehouse-relations-post
      responses:
        200:
          description: OK
      tags:
      - Address
      - Warehouse
      - Relation
  /rest/accounts/addresses/warehouse_relations/{relationId}:
    delete:
      summary: Delete an address warehouse relation
      description: Deletes an address warehouse relation. The ID of the relation must
        be specified.
      operationId: deleteRestAccountsAddressesWarehouseRelationsRelation
      x-api-path-slug: restaccountsaddresseswarehouse-relationsrelationid-delete
      parameters:
      - in: path
        name: relationId
      responses:
        200:
          description: OK
      tags:
      - Address
      - Warehouse
      - Relation
    put:
      summary: Update an address warehouse relation
      description: Updates an address warehouse relation. The ID of the relation must
        be specified.
      operationId: putRestAccountsAddressesWarehouseRelationsRelation
      x-api-path-slug: restaccountsaddresseswarehouse-relationsrelationid-put
      parameters:
      - in: path
        name: relationId
      responses:
        200:
          description: OK
      tags:
      - Address
      - Warehouse
      - Relation
  /rest/accounts/addresses/{addressId}:
    delete:
      summary: Delete an address
      description: Deletes an address. The ID of the address must be specified.
      operationId: deleteRestAccountsAddressesAddress
      x-api-path-slug: restaccountsaddressesaddressid-delete
      parameters:
      - in: path
        name: addressId
      responses:
        200:
          description: OK
      tags:
      - Address
    get:
      summary: Get an address
      description: Gets an address. The ID of the address must be specified.
      operationId: getRestAccountsAddressesAddress
      x-api-path-slug: restaccountsaddressesaddressid-get
      parameters:
      - in: path
        name: addressId
      responses:
        200:
          description: OK
      tags:
      - Address
    put:
      summary: Update an address
      description: Updates an address. The ID of the address must be specified.
      operationId: putRestAccountsAddressesAddress
      x-api-path-slug: restaccountsaddressesaddressid-put
      parameters:
      - in: body
        name: /rest/accounts/addresses/{addressId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: addressId
      responses:
        200:
          description: OK
      tags:
      - Address
  /rest/accounts/addresses/{addressId}/options:
    delete:
      summary: Delete an address option by the address ID
      description: Deletes an address option. The ID of the address must be specified.
      operationId: deleteRestAccountsAddressesAddressOptions
      x-api-path-slug: restaccountsaddressesaddressidoptions-delete
      parameters:
      - in: path
        name: addressId
      responses:
        200:
          description: OK
      tags:
      - Address
      - Option
      - By
      - Address
      - ID
    get:
      summary: List address options
      description: Lists address options. The ID of the address must be specified.
      operationId: getRestAccountsAddressesAddressOptions
      x-api-path-slug: restaccountsaddressesaddressidoptions-get
      parameters:
      - in: path
        name: addressId
      responses:
        200:
          description: OK
      tags:
      - List
      - Address
      - Options
    post:
      summary: Create an address option
      description: Creates an address option. The ID of the address must be specified.
      operationId: postRestAccountsAddressesAddressOptions
      x-api-path-slug: restaccountsaddressesaddressidoptions-post
      parameters:
      - in: path
        name: addressId
      responses:
        200:
          description: OK
      tags:
      - Address
      - Option
    put:
      summary: Update the address options for an address
      description: Update the address options for an address.
      operationId: putRestAccountsAddressesAddressOptions
      x-api-path-slug: restaccountsaddressesaddressidoptions-put
      parameters:
      - in: path
        name: addressId
      responses:
        200:
          description: OK
      tags:
      - Address
      - Optionsan
      - Address
  /rest/accounts/addresses/{addressId}/related_data:
    get:
      summary: Find address data by address id
      description: Find address data by address id.
      operationId: getRestAccountsAddressesAddressRelatedData
      x-api-path-slug: restaccountsaddressesaddressidrelated-data-get
      parameters:
      - in: path
        name: addressId
      responses:
        200:
          description: OK
      tags:
      - Find
      - Address
      - Data
      - By
      - Address
      - Id
  /rest/accounts/contact_relations/{accountContactRelationId}:
    delete:
      summary: Deletes an account contact relation. The ID of the account contact
        relation must be specified.
      description: Deletes an account contact relation. the id of the account contact
        relation must be specified..
      operationId: deleteRestAccountsContactRelationsAccountcontactrelation
      x-api-path-slug: restaccountscontact-relationsaccountcontactrelationid-delete
      parameters:
      - in: path
        name: accountContactRelationId
      responses:
        200:
          description: OK
      tags:
      - S
      - Account
      - Contact
      - Relation
      - ""
      - ID
      - Of
      - Account
      - Contact
      - Relation
      - Must
      - Be
      - Specified
    get:
      summary: Gets an account contact releation. The ID of the account contact relation
        must be specified.
      description: Gets an account contact releation. the id of the account contact
        relation must be specified..
      operationId: getRestAccountsContactRelationsAccountcontactrelation
      x-api-path-slug: restaccountscontact-relationsaccountcontactrelationid-get
      parameters:
      - in: path
        name: accountContactRelationId
      responses:
        200:
          description: OK
      tags:
      - S
      - Account
      - Contact
      - Releation
      - ""
      - ID
      - Of
      - Account
      - Contact
      - Relation
      - Must
      - Be
      - Specified
  /rest/accounts/contacts:
    get:
      summary: List contacts
      description: List contacts.
      operationId: getRestAccountsContacts
      x-api-path-slug: restaccountscontacts-get
      parameters:
      - in: query
        name: billingAddressId
        description: Filter that restricts the search result to contacts with a billing
          address with the id provided
      - in: query
        name: contactAddress
        description: Filter that restricts the search result to contacts with a specific
          address
      - in: query
        name: contactEmail
        description: Filter that restricts the search result to contacts resembling
          to the given email address
      - in: query
        name: contactId
        description: Filter that restricts the search result to a specific contact
      - in: query
        name: countryId
        description: Filter that restricts the search result to contacts with a specific
          country
      - in: query
        name: createdAtAfter
        description: Filter that restricts the search result to contacts that were
          created after a specific date
      - in: query
        name: createdAtBefore
        description: Filter that restricts the search result to contacts that were
          created before a specific date
      - in: query
        name: deliveryAddressId
        description: Filter that restricts the search result to contacts with a delivery
          address with the id provided
      - in: query
        name: email
        description: Filter that restricts the search result to contacts with a specific
          email address
      - in: query
        name: externalId
        description: Filter that restricts the search result to contacts with a specific
          externalId
      - in: query
        name: fullText
        description: Filter for a fulltext search
      - in: query
        name: itemsPerPage
        description: The number of items to list per page
      - in: query
        name: name
        description: Filter that restricts the search result to contacts with a specific
          name
      - in: query
        name: newsletterAllowance
        description: Filter that restricts the search result to contacts who registered
          for the newsletter
      - in: query
        name: newsletterAllowanceAfter
        description: Filter that restricts the search result to contacts who registered
          for the newsletter after a specific date
      - in: query
        name: newsletterAllowanceBefore
        description: Filter that restricts the search result to contacts who registered
          for the newsletter before a specific date
      - in: query
        name: number
        description: Filter that restricts the search result to contacts with a specific
          number
      - in: query
        name: page
        description: The page of results to search for
      - in: query
        name: plentyId
        description: Filter that restricts the search result to contacts with a specific
          plentyId
      - in: query
        name: postalCode
        description: Filter that restricts the search result to contacts with a specific
          postal code
      - in: query
        name: privatePhone
        description: Filter that restricts the search result to contacts with a private
          phone number
      - in: query
        name: referrerId
        description: Filter that restricts the search result to contacts with a specific
          referrer
      - in: query
        name: town
        description: Filter that restricts the search result to contacts with a specific
          town
      - in: query
        name: typeId
        description: Filter that restricts the search result to contacts with a specific
          contact type
      - in: query
        name: updatedAtAfter
        description: Filter that restricts the search result to contacts that were
          updated after a specific date
      - in: query
        name: updatedAtBefore
        description: Filter that restricts the search result to contacts that were
          updated before a specific date
      - in: query
        name: userId
        description: Filter that restricts the search result to contacts with a specific
          user
      - in: query
        name: with
        description: Includes the specified contact information in the results
      responses:
        200:
          description: OK
      tags:
      - List
      - Contacts
    post:
      summary: Create a contact
      description: Create a contact.
      operationId: postRestAccountsContacts
      x-api-path-slug: restaccountscontacts-post
      parameters:
      - in: body
        name: /rest/accounts/contacts
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Contact
  /rest/accounts/contacts/banks:
    post:
      summary: Create a bank account
      description: Create a bank account.
      operationId: postRestAccountsContactsBanks
      x-api-path-slug: restaccountscontactsbanks-post
      parameters:
      - in: body
        name: /rest/accounts/contacts/banks
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Bank
      - Account
  /rest/accounts/contacts/banks/{contactBankId}:
    delete:
      summary: Delete a bank account
      description: Deletes a bank account. The ID of the bank account must be specified.
      operationId: deleteRestAccountsContactsBanksContactbank
      x-api-path-slug: restaccountscontactsbankscontactbankid-delete
      parameters:
      - in: path
        name: contactBankId
      responses:
        200:
          description: OK
      tags:
      - Bank
      - Account
    get:
      summary: Get a bank account
      description: Gets a bank account of the contact. The ID of the bank account
        must be specified.
      operationId: getRestAccountsContactsBanksContactbank
      x-api-path-slug: restaccountscontactsbankscontactbankid-get
      parameters:
      - in: path
        name: contactBankId
      responses:
        200:
          description: OK
      tags:
      - Bank
      - Account
    put:
      summary: Update a bank account
      description: Updates a bank account. The ID of the bank account must be specified.
      operationId: putRestAccountsContactsBanksContactbank
      x-api-path-slug: restaccountscontactsbankscontactbankid-put
      parameters:
      - in: body
        name: /rest/accounts/contacts/banks/{contactBankId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: contactBankId
      responses:
        200:
          description: OK
      tags:
      - Bank
      - Account
  /rest/accounts/contacts/classes:
    get:
      summary: List contact classes
      description: List contact classes.
      operationId: getRestAccountsContactsClasses
      x-api-path-slug: restaccountscontactsclasses-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Contact
      - Classes
  /rest/accounts/contacts/classes/{contactClassId}:
    get:
      summary: Get a contact class
      description: Gets a contact class. The ID of the contact class must be specified.
      operationId: getRestAccountsContactsClassesContactclass
      x-api-path-slug: restaccountscontactsclassescontactclassid-get
      parameters:
      - in: path
        name: contactClassId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Class
  /rest/accounts/contacts/contact_events:
    get:
      summary: List contact events
      description: Lists contact events.
      operationId: getRestAccountsContactsContactEvents
      x-api-path-slug: restaccountscontactscontact-events-get
      parameters:
      - in: query
        name: itemsPerPage
        description: The number of items to list per page
      - in: query
        name: page
        description: The page of results to search for
      responses:
        200:
          description: OK
      tags:
      - List
      - Contact
      - Events
    post:
      summary: Create a contact event
      description: Creates a contact event.
      operationId: postRestAccountsContactsContactEvents
      x-api-path-slug: restaccountscontactscontact-events-post
      parameters:
      - in: body
        name: /rest/accounts/contacts/contact_events
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: itemsPerPage
        description: The number of items to list per page
      - in: query
        name: page
        description: The page of results to search for
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Event
  /rest/accounts/contacts/contact_events/{contactEventId}:
    delete:
      summary: Delete a contact event
      description: Deletes a contact event. The ID of the contact event must be specified.
      operationId: deleteRestAccountsContactsContactEventsContactevent
      x-api-path-slug: restaccountscontactscontact-eventscontacteventid-delete
      parameters:
      - in: path
        name: contactEventId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Event
    put:
      summary: Update a contact event
      description: Updates a contact event. The ID of the contact event must be specified.
      operationId: putRestAccountsContactsContactEventsContactevent
      x-api-path-slug: restaccountscontactscontact-eventscontacteventid-put
      parameters:
      - in: body
        name: /rest/accounts/contacts/contact_events/{contactEventId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: contactEventId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Event
  /rest/accounts/contacts/departments:
    get:
      summary: List contact departments
      description: List contact departments.
      operationId: getRestAccountsContactsDepartments
      x-api-path-slug: restaccountscontactsdepartments-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Contact
      - Departments
    post:
      summary: Create a contact department
      description: Create a contact department.
      operationId: postRestAccountsContactsDepartments
      x-api-path-slug: restaccountscontactsdepartments-post
      parameters:
      - in: body
        name: /rest/accounts/contacts/departments
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Department
  /rest/accounts/contacts/departments/{departmentId}:
    delete:
      summary: Delete a contact department
      description: Deletes a contact department. The ID of the department must be
        specified.
      operationId: deleteRestAccountsContactsDepartmentsDepartment
      x-api-path-slug: restaccountscontactsdepartmentsdepartmentid-delete
      parameters:
      - in: path
        name: departmentId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Department
    get:
      summary: Get a contact department
      description: Gets a contact department. The ID of the department must be specified.
      operationId: getRestAccountsContactsDepartmentsDepartment
      x-api-path-slug: restaccountscontactsdepartmentsdepartmentid-get
      parameters:
      - in: path
        name: departmentId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Department
    put:
      summary: Update a contact department
      description: Updates a contact department. The ID of the department must be
        specified.
      operationId: putRestAccountsContactsDepartmentsDepartment
      x-api-path-slug: restaccountscontactsdepartmentsdepartmentid-put
      parameters:
      - in: body
        name: /rest/accounts/contacts/departments/{departmentId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: departmentId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Department
  /rest/accounts/contacts/group_functions:
    get:
      summary: List all group function related data
      description: Lists all data that is related to the contact group function contents.
      operationId: getRestAccountsContactsGroupFunctions
      x-api-path-slug: restaccountscontactsgroup-functions-get
      responses:
        200:
          description: OK
      tags:
      - List
      - ""
      - Group
      - Function
      - Related
      - Data
    post:
      summary: Apply selected group function options for given contact IDs
      description: Applies selected group function options for given contact IDs.
      operationId: postRestAccountsContactsGroupFunctions
      x-api-path-slug: restaccountscontactsgroup-functions-post
      parameters:
      - in: query
        name: addressLabelTemplate
        description: An address label template ID
      - in: query
        name: contactList
        description: A list of contact IDs
      - in: query
        name: emailTemplate
        description: An email template ID
      - in: query
        name: newsletter
        description: A newsletter folder ID
      responses:
        200:
          description: OK
      tags:
      - Apply
      - Selected
      - Group
      - Function
      - Optionsgiven
      - Contact
      - IDs
  /rest/accounts/contacts/option_sub_types:
    get:
      summary: List contact option sub-types
      description: List contact option sub-types.
      operationId: getRestAccountsContactsOptionSubTypes
      x-api-path-slug: restaccountscontactsoption-sub-types-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Contact
      - Option
      - Sub-types
    post:
      summary: Create a contact option sub-type
      description: Create a contact option sub-type.
      operationId: postRestAccountsContactsOptionSubTypes
      x-api-path-slug: restaccountscontactsoption-sub-types-post
      parameters:
      - in: body
        name: /rest/accounts/contacts/option_sub_types
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Option
      - Sub-type
  /rest/accounts/contacts/option_sub_types/{optionSubTypeId}:
    delete:
      summary: Delete a contact option sub-type
      description: Deletes a contact option sub-type. The ID of the option sub-type
        must be specified.
      operationId: deleteRestAccountsContactsOptionSubTypesOptionsubtype
      x-api-path-slug: restaccountscontactsoption-sub-typesoptionsubtypeid-delete
      parameters:
      - in: path
        name: optionSubTypeId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Option
      - Sub-type
    get:
      summary: Get a contact option sub-type
      description: Gets a contact option sub-type. The ID of the option sub-type must
        be specified.
      operationId: getRestAccountsContactsOptionSubTypesOptionsubtype
      x-api-path-slug: restaccountscontactsoption-sub-typesoptionsubtypeid-get
      parameters:
      - in: path
        name: optionSubTypeId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Option
      - Sub-type
    put:
      summary: Update a contact option sub-type
      description: Updates a contact option sub-type. The ID of the option sub-type
        must be specified.
      operationId: putRestAccountsContactsOptionSubTypesOptionsubtype
      x-api-path-slug: restaccountscontactsoption-sub-typesoptionsubtypeid-put
      parameters:
      - in: body
        name: /rest/accounts/contacts/option_sub_types/{optionSubTypeId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: optionSubTypeId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Option
      - Sub-type
  /rest/accounts/contacts/option_types:
    get:
      summary: List contact option types
      description: List contact option types.
      operationId: getRestAccountsContactsOptionTypes
      x-api-path-slug: restaccountscontactsoption-types-get
      parameters:
      - in: query
        name: with
        description: Lists possible option sub-types for each listed option if the
          parameter subTypes is set
      responses:
        200:
          description: OK
      tags:
      - List
      - Contact
      - Option
      - Types
    post:
      summary: Create a contact option type
      description: Create a contact option type.
      operationId: postRestAccountsContactsOptionTypes
      x-api-path-slug: restaccountscontactsoption-types-post
      parameters:
      - in: body
        name: /rest/accounts/contacts/option_types
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Option
      - Type
  /rest/accounts/contacts/option_types/{optionTypeId}:
    delete:
      summary: Delete a contact option type
      description: Deletes a contact option type. The ID of the option type must be
        specified.
      operationId: deleteRestAccountsContactsOptionTypesOptiontype
      x-api-path-slug: restaccountscontactsoption-typesoptiontypeid-delete
      parameters:
      - in: path
        name: optionTypeId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Option
      - Type
    get:
      summary: Get a contact option type
      description: Gets a contact option type. The ID of the option type must be specified.
      operationId: getRestAccountsContactsOptionTypesOptiontype
      x-api-path-slug: restaccountscontactsoption-typesoptiontypeid-get
      parameters:
      - in: path
        name: optionTypeId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Option
      - Type
    put:
      summary: Update a contact option type
      description: Updates a contact option type. The ID of the option type must be
        specified.
      operationId: putRestAccountsContactsOptionTypesOptiontype
      x-api-path-slug: restaccountscontactsoption-typesoptiontypeid-put
      parameters:
      - in: body
        name: /rest/accounts/contacts/option_types/{optionTypeId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: optionTypeId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Option
      - Type
  /rest/accounts/contacts/options/{optionId}:
    delete:
      summary: Delete a contact option by the option ID
      description: Deletes a contact option. The ID of the option must be specified.
      operationId: deleteRestAccountsContactsOptionsOption
      x-api-path-slug: restaccountscontactsoptionsoptionid-delete
      parameters:
      - in: path
        name: optionId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Option
      - By
      - Option
      - ID
    get:
      summary: Get a contact option by the option ID
      description: Gets a contact option. The ID of the option must be specified.
      operationId: getRestAccountsContactsOptionsOption
      x-api-path-slug: restaccountscontactsoptionsoptionid-get
      parameters:
      - in: path
        name: optionId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Option
      - By
      - Option
      - ID
    put:
      summary: Update a contact option by the option ID
      description: Updates a contact option. The ID of the option must be specified.
      operationId: putRestAccountsContactsOptionsOption
      x-api-path-slug: restaccountscontactsoptionsoptionid-put
      parameters:
      - in: path
        name: optionId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Option
      - By
      - Option
      - ID
  /rest/accounts/contacts/positions:
    get:
      summary: List contact positions
      description: List contact positions.
      operationId: getRestAccountsContactsPositions
      x-api-path-slug: restaccountscontactspositions-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Contact
      - Positions
    post:
      summary: Create a contact position
      description: Create a contact position.
      operationId: postRestAccountsContactsPositions
      x-api-path-slug: restaccountscontactspositions-post
      parameters:
      - in: body
        name: /rest/accounts/contacts/positions
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Position
  /rest/accounts/contacts/positions/{positionId}:
    delete:
      summary: Delete a contact position
      description: Deletes a contact position. The ID of the position must be specified.
      operationId: deleteRestAccountsContactsPositionsPosition
      x-api-path-slug: restaccountscontactspositionspositionid-delete
      parameters:
      - in: path
        name: positionId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Position
    get:
      summary: Get a contact position
      description: Gets a contact position. The ID of the position must be specified.
      operationId: getRestAccountsContactsPositionsPosition
      x-api-path-slug: restaccountscontactspositionspositionid-get
      parameters:
      - in: path
        name: positionId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Position
    put:
      summary: Update a contact position
      description: Updates a contact position. The ID of the position must be specified.
      operationId: putRestAccountsContactsPositionsPosition
      x-api-path-slug: restaccountscontactspositionspositionid-put
      parameters:
      - in: body
        name: /rest/accounts/contacts/positions/{positionId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: positionId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Position
  /rest/accounts/contacts/types:
    get:
      summary: List contact types
      description: List contact types.
      operationId: getRestAccountsContactsTypes
      x-api-path-slug: restaccountscontactstypes-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Contact
      - Types
    post:
      summary: Create a contact type
      description: Create a contact type.
      operationId: postRestAccountsContactsTypes
      x-api-path-slug: restaccountscontactstypes-post
      parameters:
      - in: body
        name: /rest/accounts/contacts/types
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Type
  /rest/accounts/contacts/types/{typeId}:
    delete:
      summary: Delete a contact type
      description: Deletes a contact type. The ID of the contact type must be specified.
      operationId: deleteRestAccountsContactsTypesType
      x-api-path-slug: restaccountscontactstypestypeid-delete
      parameters:
      - in: path
        name: typeId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Type
    get:
      summary: Get a contact type
      description: Gets a contact type. The ID of the contact type must be specified.
      operationId: getRestAccountsContactsTypesType
      x-api-path-slug: restaccountscontactstypestypeid-get
      parameters:
      - in: path
        name: typeId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Type
    put:
      summary: Update a contact type
      description: Updates a contact type. The ID of the contact type must be specified.
      operationId: putRestAccountsContactsTypesType
      x-api-path-slug: restaccountscontactstypestypeid-put
      parameters:
      - in: body
        name: /rest/accounts/contacts/types/{typeId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: typeId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Type
  /rest/accounts/contacts/{contactId}:
    delete:
      summary: Delete a contact
      description: Deletes a contact. The ID of the contact must be specified.
      operationId: deleteRestAccountsContactsContact
      x-api-path-slug: restaccountscontactscontactid-delete
      parameters:
      - in: query
        name: checkExistingOrders
        description: Flag that checks if the contact is linked to orders
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Contact
    get:
      summary: Get a contact
      description: Gets a contact. The ID of the contact must be specified.
      operationId: getRestAccountsContactsContact
      x-api-path-slug: restaccountscontactscontactid-get
      parameters:
      - in: path
        name: contactId
      - in: query
        name: with
        description: Includes the specified contact information in the results
      responses:
        200:
          description: OK
      tags:
      - Contact
    put:
      summary: Update a contact
      description: Updates a contact. The ID of the contact must be specified.
      operationId: putRestAccountsContactsContact
      x-api-path-slug: restaccountscontactscontactid-put
      parameters:
      - in: body
        name: /rest/accounts/contacts/{contactId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Contact
  /rest/accounts/contacts/{contactId}/access_data/login_url:
    get:
      summary: Get the login URL
      description: Gets the URL to login as the given contact. The ID of the contact
        must be specified.
      operationId: getRestAccountsContactsContactAccessDataLoginUrl
      x-api-path-slug: restaccountscontactscontactidaccess-datalogin-url-get
      parameters:
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Login
      - URL
  /rest/accounts/contacts/{contactId}/access_data/new_password:
    put:
      summary: Send password link for a contact
      description: Sends an email to a contact with a link to change the password.
        The ID of the contact must be specified.
      operationId: putRestAccountsContactsContactAccessDataNewPassword
      x-api-path-slug: restaccountscontactscontactidaccess-datanew-password-put
      parameters:
      - in: path
        name: contactId
      - in: query
        name: password
        description: The new password
      responses:
        200:
          description: OK
      tags:
      - Send
      - Password
      - Linka
      - Contact
  /rest/accounts/contacts/{contactId}/access_data/set_password:
    put:
      summary: Update the password for a contact
      description: Updates the password for a contact. The ID of the contact must
        be specified.
      operationId: putRestAccountsContactsContactAccessDataSetPassword
      x-api-path-slug: restaccountscontactscontactidaccess-dataset-password-put
      parameters:
      - in: path
        name: contactId
      - in: query
        name: password
        description: The new password
      responses:
        200:
          description: OK
      tags:
      - Passworda
      - Contact
  /rest/accounts/contacts/{contactId}/access_data/unblock_user:
    put:
      summary: Unblock a contact
      description: Unblocks a contact to allow this contact to log in again. The ID
        of the contact must be specified.
      operationId: putRestAccountsContactsContactAccessDataUnblockUser
      x-api-path-slug: restaccountscontactscontactidaccess-dataunblock-user-put
      parameters:
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Unblock
      - Contact
  /rest/accounts/contacts/{contactId}/accounts:
    post:
      summary: Create an account for existing contact
      description: Creates an account for an existing contact. The ID of the contact
        must be specified.
      operationId: postRestAccountsContactsContactAccounts
      x-api-path-slug: restaccountscontactscontactidaccounts-post
      parameters:
      - in: body
        name: /rest/accounts/contacts/{contactId}/accounts
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Accountexisting
      - Contact
  /rest/accounts/contacts/{contactId}/accounts/{accountId}:
    delete:
      summary: Delete an account of the contact
      description: Deletes an account of the contact. The ID of the contact and the
        ID of the account must be specified.
      operationId: deleteRestAccountsContactsContactAccountsAccount
      x-api-path-slug: restaccountscontactscontactidaccountsaccountid-delete
      parameters:
      - in: path
        name: accountId
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Account
      - Of
      - Contact
    get:
      summary: Get an account of the contact
      description: Gets an account of the contact. The ID of the contact and the ID
        of the account must be specified.
      operationId: getRestAccountsContactsContactAccountsAccount
      x-api-path-slug: restaccountscontactscontactidaccountsaccountid-get
      parameters:
      - in: path
        name: accountId
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Account
      - Of
      - Contact
    put:
      summary: Update an account
      description: Updates an account. The ID of the contact and the ID of the account
        must be specified.
      operationId: putRestAccountsContactsContactAccountsAccount
      x-api-path-slug: restaccountscontactscontactidaccountsaccountid-put
      parameters:
      - in: path
        name: accountId
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Account
  /rest/accounts/contacts/{contactId}/addresses:
    post:
      summary: Create an address for existing contact and type
      description: Creates an address. The ID of the contact must be specified.
      operationId: postRestAccountsContactsContactAddresses
      x-api-path-slug: restaccountscontactscontactidaddresses-post
      parameters:
      - in: body
        name: /rest/accounts/contacts/{contactId}/addresses
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: contactId
      - in: query
        name: isPrimary
        description: Sets a contact address per address type as the primary address
      - in: query
        name: typeId
        description: The type ID of the address
      responses:
        200:
          description: OK
      tags:
      - Addressexisting
      - Contact
      - Type
  /rest/accounts/contacts/{contactId}/addresses/{addressId}:
    delete:
      summary: Delete an address of the contact
      description: Deletes an address of the contact. The ID of the contact and the
        ID of the address must be specified.
      operationId: deleteRestAccountsContactsContactAddressesAddress
      x-api-path-slug: restaccountscontactscontactidaddressesaddressid-delete
      parameters:
      - in: path
        name: addressId
      - in: path
        name: contactId
      - in: query
        name: typeId
        description: The type ID of the address
      responses:
        200:
          description: OK
      tags:
      - Address
      - Of
      - Contact
    put:
      summary: Update an address of the contact
      description: Updates an address of the contact. The ID of the contact and the
        ID of the address must be specified.
      operationId: putRestAccountsContactsContactAddressesAddress
      x-api-path-slug: restaccountscontactscontactidaddressesaddressid-put
      parameters:
      - in: path
        name: addressId
      - in: path
        name: contactId
      - in: query
        name: isPrimary
        description: Sets a contact address per address type as the primary address
      - in: query
        name: typeId
        description: The type ID of the address
      responses:
        200:
          description: OK
      tags:
      - Address
      - Of
      - Contact
  /rest/accounts/contacts/{contactId}/addresses/{addressId}/types/{addressTypeId}/primary:
    put:
      summary: Set a contact address per address type as the primary address
      description: Sets a contact address per address type as the primary address.
        The ID of the contact, the ID of the address and the ID of the address type
        must be specified. A primary address is also definable if you create or update
        a contact address.
      operationId: putRestAccountsContactsContactAddressesAddressTypesAddresstypePrimary
      x-api-path-slug: restaccountscontactscontactidaddressesaddressidtypesaddresstypeidprimary-put
      parameters:
      - in: path
        name: addressId
      - in: path
        name: addressTypeId
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Set
      - Contact
      - Address
      - Per
      - Address
      - Type
      - As
      - Primary
      - Address
  /rest/accounts/contacts/{contactId}/addresses/{addressId}/types/{addressTypeId}/reset_primary:
    put:
      summary: Resets a contact primary address
      description: Resets a contact primary address. The ID of the contact, the ID
        of the address and the ID of the address type must be specified.
      operationId: putRestAccountsContactsContactAddressesAddressTypesAddresstypeResetPrimary
      x-api-path-slug: restaccountscontactscontactidaddressesaddressidtypesaddresstypeidreset-primary-put
      parameters:
      - in: path
        name: addressId
      - in: path
        name: addressTypeId
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Resets
      - Contact
      - Primary
      - Address
  /rest/accounts/contacts/{contactId}/addresses/{addressTypeId?}:
    get:
      summary: List addresses that are linked with contacts
      description: Lists addresses of the contact. The ID of the contact must be specified.
      operationId: getRestAccountsContactsContactAddressesAddresstype
      x-api-path-slug: restaccountscontactscontactidaddressesaddresstypeid-get
      parameters:
      - in: path
        name: addressTypeId?
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - List
      - Addresses
      - That
      - Are
      - Linked
      - Contacts
  /rest/accounts/contacts/{contactId}/anonymize:
    put:
      summary: anonymize Contact
      description: anonymizes the given contact.
      operationId: putRestAccountsContactsContactAnonymize
      x-api-path-slug: restaccountscontactscontactidanonymize-put
      parameters:
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Anonymize
      - Contact
  /rest/accounts/contacts/{contactId}/banks:
    get:
      summary: List bank accounts
      description: Lists bank accounts of the contact. The ID of the contact must
        be specified.
      operationId: getRestAccountsContactsContactBanks
      x-api-path-slug: restaccountscontactscontactidbanks-get
      parameters:
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - List
      - Bank
      - Accounts
  /rest/accounts/contacts/{contactId}/contact_events:
    get:
      summary: List contact events by contact ID
      description: Lists contact events by contact ID. The ID of the contact must
        be specified.
      operationId: getRestAccountsContactsContactContactEvents
      x-api-path-slug: restaccountscontactscontactidcontact-events-get
      parameters:
      - in: path
        name: contactId
      - in: query
        name: itemsPerPage
        description: The number of items to list per page
      - in: query
        name: page
        description: The page of results to search for
      responses:
        200:
          description: OK
      tags:
      - List
      - Contact
      - Events
      - By
      - Contact
      - ID
  /rest/accounts/contacts/{contactId}/document:
    get:
      summary: Get a single storage object from contact documents
      description: Get a single storage object from contact documents.
      operationId: getRestAccountsContactsContactDocument
      x-api-path-slug: restaccountscontactscontactiddocument-get
      parameters:
      - in: path
        name: contactId
      - in: query
        name: key
        description: The storage key of the object to get from contact documents
      responses:
        200:
          description: OK
      tags:
      - Single
      - Storage
      - Object
      - From
      - Contact
      - Documents
    post:
      summary: Upload a document to contact directory
      description: Upload a document to contact directory.
      operationId: postRestAccountsContactsContactDocument
      x-api-path-slug: restaccountscontactscontactiddocument-post
      parameters:
      - in: path
        name: contactId
      - in: query
        name: key
        description: The storage key for the file to upload
      responses:
        200:
          description: OK
      tags:
      - Upload
      - Document
      - To
      - Contact
      - Directory
  /rest/accounts/contacts/{contactId}/document/url:
    get:
      summary: Get a temporary url for a single document
      description: Get a temporary url for a single document.
      operationId: getRestAccountsContactsContactDocumentUrl
      x-api-path-slug: restaccountscontactscontactiddocumenturl-get
      parameters:
      - in: path
        name: contactId
      - in: query
        name: key
        description: The storage key to get temporary url for
      responses:
        200:
          description: OK
      tags:
      - Temporary
      - Urla
      - Single
      - Document
  /rest/accounts/contacts/{contactId}/documents:
    delete:
      summary: Delete files from contact documents
      description: Delete files from contact documents.
      operationId: deleteRestAccountsContactsContactDocuments
      x-api-path-slug: restaccountscontactscontactiddocuments-delete
      parameters:
      - in: path
        name: contactId
      - in: query
        name: keyList
        description: List of storage keys to delete
      responses:
        200:
          description: OK
      tags:
      - Files
      - From
      - Contact
      - Documents
    get:
      summary: List documents for a single contact
      description: List documents for a single contact.
      operationId: getRestAccountsContactsContactDocuments
      x-api-path-slug: restaccountscontactscontactiddocuments-get
      parameters:
      - in: path
        name: contactId
      - in: query
        name: continuationToken
        description: token from previous request to continue listing documents
      responses:
        200:
          description: OK
      tags:
      - List
      - Documentsa
      - Single
      - Contact
  /rest/accounts/contacts/{contactId}/options:
    delete:
      summary: Delete a contact option by the contact ID
      description: Deletes a contact option for an existing contact. The ID of the
        contact must be specified.
      operationId: deleteRestAccountsContactsContactOptions
      x-api-path-slug: restaccountscontactscontactidoptions-delete
      parameters:
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Option
      - By
      - Contact
      - ID
    get:
      summary: List contact options by the contact ID
      description: Lists contact options. The ID of the contact must be specified.
      operationId: getRestAccountsContactsContactOptions
      x-api-path-slug: restaccountscontactscontactidoptions-get
      parameters:
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - List
      - Contact
      - Options
      - By
      - Contact
      - ID
    post:
      summary: Create a contact option by the contact ID
      description: Creates a contact option for an existing contact. The ID of the
        contact must be specified.
      operationId: postRestAccountsContactsContactOptions
      x-api-path-slug: restaccountscontactscontactidoptions-post
      parameters:
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Option
      - By
      - Contact
      - ID
    put:
      summary: Update a contact option by the contact ID
      description: Updates a contact option for an existing contact. The ID of the
        contact must be specified.
      operationId: putRestAccountsContactsContactOptions
      x-api-path-slug: restaccountscontactscontactidoptions-put
      parameters:
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Contact
      - Option
      - By
      - Contact
      - ID
  /rest/accounts/contacts/{contactId}/options/validate:
    get:
      summary: Validate a contact option by a given value
      description: validates a contact option by a given value
      operationId: getRestAccountsContactsContactOptionsValate
      x-api-path-slug: restaccountscontactscontactidoptionsvalidate-get
      parameters:
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Validate
      - Contact
      - Option
      - By
      - Given
      - Value
  /rest/accounts/contacts/{contactId}/related_data:
    get:
      summary: Return all contact related data
      description: Returns all contact related data.
      operationId: getRestAccountsContactsContactRelatedData
      x-api-path-slug: restaccountscontactscontactidrelated-data-get
      parameters:
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Return
      - ""
      - Contact
      - Related
      - Data
  /rest/accounts/contacts/{contactId}/vcard:
    get:
      summary: get a filestream of vcard from customer
      description: Get a filestream of vcard from customer.
      operationId: getRestAccountsContactsContactVcard
      x-api-path-slug: restaccountscontactscontactidvcard-get
      parameters:
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Get
      - Filestream
      - Of
      - Vcard
      - From
      - Customer
  /rest/accounts/order_summaries:
    get:
      summary: List order summaries
      description: List order summaries.
      operationId: getRestAccountsOrderSummaries
      x-api-path-slug: restaccountsorder-summaries-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Order
      - Summaries
    post:
      summary: Create an order summary
      description: Create an order summary.
      operationId: postRestAccountsOrderSummaries
      x-api-path-slug: restaccountsorder-summaries-post
      responses:
        200:
          description: OK
      tags:
      - Order
      - Summary
  /rest/accounts/order_summaries/contacts/{contactId}:
    get:
      summary: Get an order summary by the contact ID
      description: Gets an order summary. The ID of the contact must be specified.
      operationId: getRestAccountsOrderSummariesContactsContact
      x-api-path-slug: restaccountsorder-summariescontactscontactid-get
      parameters:
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Order
      - Summary
      - By
      - Contact
      - ID
  /rest/accounts/order_summaries/orders/{addressId}:
    get:
      summary: Get an order summary by the address ID
      description: Gets an order summary. The ID of the address must be specified.
      operationId: getRestAccountsOrderSummariesOrdersAddress
      x-api-path-slug: restaccountsorder-summariesordersaddressid-get
      parameters:
      - in: path
        name: addressId
      responses:
        200:
          description: OK
      tags:
      - Order
      - Summary
      - By
      - Address
      - ID
  /rest/accounts/order_summaries/{orderSummaryId}:
    delete:
      summary: Delete an order summary
      description: Deletes an order summary. The ID of the order summary must be specified.
      operationId: deleteRestAccountsOrderSummariesOrdersummary
      x-api-path-slug: restaccountsorder-summariesordersummaryid-delete
      parameters:
      - in: path
        name: orderSummaryId
      responses:
        200:
          description: OK
      tags:
      - Order
      - Summary
    get:
      summary: Get an order summary by the order summary ID
      description: Gets an order summary. The ID of the order summary must be specified.
      operationId: getRestAccountsOrderSummariesOrdersummary
      x-api-path-slug: restaccountsorder-summariesordersummaryid-get
      parameters:
      - in: path
        name: orderSummaryId
      responses:
        200:
          description: OK
      tags:
      - Order
      - Summary
      - By
      - Order
      - Summary
      - ID
    put:
      summary: Update an order summary
      description: Updates an order summary. The ID of the order summary must be specified.
      operationId: putRestAccountsOrderSummariesOrdersummary
      x-api-path-slug: restaccountsorder-summariesordersummaryid-put
      parameters:
      - in: path
        name: orderSummaryId
      responses:
        200:
          description: OK
      tags:
      - Order
      - Summary
  /rest/accounts/{accountId}:
    delete:
      summary: Delete an account
      description: Deletes an account. The ID of the account must be specified.
      operationId: deleteRestAccountsAccount
      x-api-path-slug: restaccountsaccountid-delete
      parameters:
      - in: path
        name: accountId
      responses:
        200:
          description: OK
      tags:
      - Account
    get:
      summary: Get an account
      description: Gets an account. The ID of the account must be specified.
      operationId: getRestAccountsAccount
      x-api-path-slug: restaccountsaccountid-get
      parameters:
      - in: path
        name: accountId
      responses:
        200:
          description: OK
      tags:
      - Account
    put:
      summary: Update an account
      description: Updates an account. The ID of the account must be specified.
      operationId: putRestAccountsAccount
      x-api-path-slug: restaccountsaccountid-put
      parameters:
      - in: body
        name: /rest/accounts/{accountId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: accountId
      responses:
        200:
          description: OK
      tags:
      - Account
  /rest/accounts/{accountId}/contacts:
    get:
      summary: List contacts
      description: Lists contacts of the account. The ID of the account must be specified.
      operationId: getRestAccountsAccountContacts
      x-api-path-slug: restaccountsaccountidcontacts-get
      parameters:
      - in: path
        name: accountId
      responses:
        200:
          description: OK
      tags:
      - List
      - Contacts
  /rest/authorized_user:
    get:
      summary: Get authorized user
      description: Gets an authorized user. This call returns a JSON object with information
        about the user after login. This information is used for correctly displaying
        the plentymarkets back end.
      operationId: getRestAuthorizedUser
      x-api-path-slug: restauthorized-user-get
      responses:
        200:
          description: OK
      tags:
      - Authorized
      - User
  /rest/availabilities:
    get:
      summary: List item availabilities
      description: Lists all item availabilities.
      operationId: getRestAvailabilities
      x-api-path-slug: restavailabilities-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Item
      - Availabilities
  /rest/availabilities/{id}:
    get:
      summary: Get an item availability
      description: Gets an item availability. The ID of the availability must be specified.
      operationId: getRestAvailabilities
      x-api-path-slug: restavailabilitiesid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Item
      - Availability
    put:
      summary: Update an item availability
      description: Updates an item availability.
      operationId: putRestAvailabilities
      x-api-path-slug: restavailabilitiesid-put
      parameters:
      - in: body
        name: /rest/availabilities/{id}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Item
      - Availability
  /rest/backend/user/{userId}:
    get:
      summary: ""
      description: .
      operationId: getRestBackendUserUser
      x-api-path-slug: restbackenduseruserid-get
      parameters:
      - in: path
        name: userId
      responses:
        200:
          description: OK
      tags:
      - ""
  /rest/backend/users:
    get:
      summary: ""
      description: .
      operationId: getRestBackendUsers
      x-api-path-slug: restbackendusers-get
      responses:
        200:
          description: OK
      tags:
      - ""
  /rest/backend/users/search_name/{name}:
    get:
      summary: Find all users having a name or username like the given one.
      description: Find all users having a name or username like the given one..
      operationId: getRestBackendUsersSearchNameName
      x-api-path-slug: restbackenduserssearch-namename-get
      parameters:
      - in: path
        name: name
      responses:
        200:
          description: OK
      tags:
      - Find
      - ""
      - Users
      - Having
      - Name
      - Username
      - Like
      - Given
  /rest/basket:
    get:
      summary: Get basket
      description: Gets the shopping cart for the current customer session.
      operationId: getRestBasket
      x-api-path-slug: restbasket-get
      responses:
        200:
          description: OK
      tags:
      - Basket
  /rest/basket/items:
    get:
      summary: List basket items
      description: Lists all items in the shopping cart for the current customer session.
      operationId: getRestBasketItems
      x-api-path-slug: restbasketitems-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Basket
      - Items
    post:
      summary: Add item to basket
      description: Adds a new item to the shopping cart using the request parameters.
      operationId: postRestBasketItems
      x-api-path-slug: restbasketitems-post
      parameters:
      - in: body
        name: /rest/basket/items
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Item
      - To
      - Basket
  /rest/basket/items/{id}:
    get:
      summary: Find a basket item by it's ID
      description: Find a basket item by it's id.
      operationId: getRestBasketItems
      x-api-path-slug: restbasketitemsid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Find
      - Basket
      - Item
      - By
      - Its
      - ID
  /rest/batch:
    get:
      summary: Make batch requests
      description: Pass several operations into a single HTTP request.
      operationId: getRestBatch
      x-api-path-slug: restbatch-get
      parameters:
      - in: body
        name: /rest/batch
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Make
      - Batch
      - Requests
  /rest/boards:
    get:
      summary: Lists all boards.
      description: Lists all boards..
      operationId: getRestBoards
      x-api-path-slug: restboards-get
      responses:
        200:
          description: OK
      tags:
      - Lists
      - ""
      - Boards
    post:
      summary: Creates a new board.
      description: Creates a new board..
      operationId: postRestBoards
      x-api-path-slug: restboards-post
      parameters:
      - in: body
        name: /rest/boards
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Creates
      - New
      - Board
  /rest/boards/{boardId}:
    delete:
      summary: Deletes a specific board.
      description: Deletes a specific board..
      operationId: deleteRestBoardsBoard
      x-api-path-slug: restboardsboardid-delete
      parameters:
      - in: path
        name: boardId
      responses:
        200:
          description: OK
      tags:
      - S
      - Specific
      - Board
    get:
      summary: Gets a single board by its ID
      description: Gets a single board by its id.
      operationId: getRestBoardsBoard
      x-api-path-slug: restboardsboardid-get
      parameters:
      - in: path
        name: boardId
      - in: query
        name: tasksPerPage
        description: Maximum number of tasks to list per column
      responses:
        200:
          description: OK
      tags:
      - S
      - Single
      - Board
      - By
      - Its
      - ID
    post:
      summary: Copies a specific board.
      description: Copies a specific board..
      operationId: postRestBoardsBoard
      x-api-path-slug: restboardsboardid-post
      parameters:
      - in: path
        name: boardId
      responses:
        200:
          description: OK
      tags:
      - Copies
      - Specific
      - Board
    put:
      summary: Updates a specific board.
      description: Updates a specific board..
      operationId: putRestBoardsBoard
      x-api-path-slug: restboardsboardid-put
      parameters:
      - in: body
        name: /rest/boards/{boardId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: boardId
      responses:
        200:
          description: OK
      tags:
      - S
      - Specific
      - Board
  /rest/boards/{boardId}/columns:
    get:
      summary: Lists all columns for a given board
      description: Lists all columns for a given board.
      operationId: getRestBoardsBoardColumns
      x-api-path-slug: restboardsboardidcolumns-get
      parameters:
      - in: path
        name: boardId
      responses:
        200:
          description: OK
      tags:
      - Lists
      - ""
      - Columnsa
      - Given
      - Board
    post:
      summary: Creates a new column and assigns it to a given board
      description: Creates a new column and assigns it to a given board.
      operationId: postRestBoardsBoardColumns
      x-api-path-slug: restboardsboardidcolumns-post
      parameters:
      - in: body
        name: /rest/boards/{boardId}/columns
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: boardId
      responses:
        200:
          description: OK
      tags:
      - Creates
      - New
      - Column
      - Assigns
      - It
      - To
      - Given
      - Board
  /rest/boards/{boardId}/columns/{columnId}:
    delete:
      summary: Deletes a specific column.
      description: Deletes a specific column..
      operationId: deleteRestBoardsBoardColumnsColumn
      x-api-path-slug: restboardsboardidcolumnscolumnid-delete
      parameters:
      - in: path
        name: boardId
      - in: path
        name: columnId
      responses:
        200:
          description: OK
      tags:
      - S
      - Specific
      - Column
    post:
      summary: Copies a specific column.
      description: Copies a specific column..
      operationId: postRestBoardsBoardColumnsColumn
      x-api-path-slug: restboardsboardidcolumnscolumnid-post
      parameters:
      - in: path
        name: boardId
      - in: path
        name: columnId
      responses:
        200:
          description: OK
      tags:
      - Copies
      - Specific
      - Column
    put:
      summary: Updates a specific column.
      description: Updates a specific column..
      operationId: putRestBoardsBoardColumnsColumn
      x-api-path-slug: restboardsboardidcolumnscolumnid-put
      parameters:
      - in: body
        name: /rest/boards/{boardId}/columns/{columnId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: boardId
      - in: path
        name: columnId
      responses:
        200:
          description: OK
      tags:
      - S
      - Specific
      - Column
  /rest/boards/{boardId}/columns/{columnId}/position:
    put:
      summary: Updates the position of a specific column. Also updates the positions
        of all following columns on the same board.
      description: Updates the position of a specific column. also updates the positions
        of all following columns on the same board..
      operationId: putRestBoardsBoardColumnsColumnPosition
      x-api-path-slug: restboardsboardidcolumnscolumnidposition-put
      parameters:
      - in: path
        name: boardId
      - in: path
        name: columnId
      - in: query
        name: position
      responses:
        200:
          description: OK
      tags:
      - S
      - Position
      - Of
      - Specific
      - Column
      - ""
      - Also
      - Updates
      - Positions
      - Of
      - ""
      - Following
      - Columns
      - "On"
      - Same
      - Board
  /rest/boards/{boardId}/columns/{columnId}/tasks:
    get:
      summary: Lists all tasks for a given column.
      description: Lists all tasks for a given column..
      operationId: getRestBoardsBoardColumnsColumnTasks
      x-api-path-slug: restboardsboardidcolumnscolumnidtasks-get
      parameters:
      - in: path
        name: boardId
      - in: path
        name: columnId
      - in: query
        name: startAt
        description: Position of a task to start listing at
      - in: query
        name: tasksPerPage
        description: Number of tasks to list per page
      responses:
        200:
          description: OK
      tags:
      - Lists
      - ""
      - Tasksa
      - Given
      - Column
    post:
      summary: Creates a new tasks on a specified column.
      description: Creates a new tasks on a specified column..
      operationId: postRestBoardsBoardColumnsColumnTasks
      x-api-path-slug: restboardsboardidcolumnscolumnidtasks-post
      parameters:
      - in: body
        name: /rest/boards/{boardId}/columns/{columnId}/tasks
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: boardId
      - in: path
        name: columnId
      responses:
        200:
          description: OK
      tags:
      - Creates
      - New
      - Tasks
      - "On"
      - Specified
      - Column
  /rest/boards/{boardId}/columns/{columnId}/tasks/{taskId}:
    delete:
      summary: Deletes a task.
      description: Deletes a task..
      operationId: deleteRestBoardsBoardColumnsColumnTasksTask
      x-api-path-slug: restboardsboardidcolumnscolumnidtaskstaskid-delete
      parameters:
      - in: path
        name: boardId
      - in: path
        name: columnId
      - in: path
        name: taskId
      responses:
        200:
          description: OK
      tags:
      - S
      - Task
    get:
      summary: Gets a task by its ID.
      description: Gets a task by its id..
      operationId: getRestBoardsBoardColumnsColumnTasksTask
      x-api-path-slug: restboardsboardidcolumnscolumnidtaskstaskid-get
      parameters:
      - in: path
        name: boardId
      - in: path
        name: columnId
      - in: path
        name: taskId
      responses:
        200:
          description: OK
      tags:
      - S
      - Task
      - By
      - Its
      - ID
    post:
      summary: Copies a specific task.
      description: Copies a specific task..
      operationId: postRestBoardsBoardColumnsColumnTasksTask
      x-api-path-slug: restboardsboardidcolumnscolumnidtaskstaskid-post
      parameters:
      - in: path
        name: boardId
      - in: path
        name: columnId
      - in: path
        name: taskId
      responses:
        200:
          description: OK
      tags:
      - Copies
      - Specific
      - Task
    put:
      summary: Updates a task.
      description: Updates a task..
      operationId: putRestBoardsBoardColumnsColumnTasksTask
      x-api-path-slug: restboardsboardidcolumnscolumnidtaskstaskid-put
      parameters:
      - in: body
        name: /rest/boards/{boardId}/columns/{columnId}/tasks/{taskId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: boardId
      - in: path
        name: columnId
      - in: path
        name: taskId
      responses:
        200:
          description: OK
      tags:
      - S
      - Task
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