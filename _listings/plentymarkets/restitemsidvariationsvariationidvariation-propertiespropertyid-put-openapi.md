---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Update a property value
  description: Update the data of a property value linked to a variation.
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
  /rest/boards/{boardId}/columns/{columnId}/tasks/{taskId}/position:
    put:
      summary: Updates the position of a task.
      description: Updates the position of a task..
      operationId: putRestBoardsBoardColumnsColumnTasksTaskPosition
      x-api-path-slug: restboardsboardidcolumnscolumnidtaskstaskidposition-put
      parameters:
      - in: path
        name: boardId
      - in: path
        name: columnId
      - in: query
        name: position
        description: The new position of the task
      - in: path
        name: taskId
      responses:
        200:
          description: OK
      tags:
      - S
      - Position
      - Of
      - Task
  /rest/boards/{boardId}/columns/{columnId}/tasks/{taskId}/references:
    post:
      summary: Creates a new reference from a given task to a contact or a ticket.
      description: Creates a new reference from a given task to a contact or a ticket..
      operationId: postRestBoardsBoardColumnsColumnTasksTaskReferences
      x-api-path-slug: restboardsboardidcolumnscolumnidtaskstaskidreferences-post
      parameters:
      - in: path
        name: boardId
      - in: path
        name: columnId
      - in: query
        name: referenceValue
        description: Reference type followed by foreign ID of the referenced object
      - in: path
        name: taskId
      responses:
        200:
          description: OK
      tags:
      - Creates
      - New
      - Reference
      - From
      - Given
      - Task
      - To
      - Contact
      - Ticket
  /rest/boards/{boardId}/columns/{columnId}/tasks/{taskId}/references/{referenceId}:
    delete:
      summary: Deletes a reference from a given task.
      description: Deletes a reference from a given task..
      operationId: deleteRestBoardsBoardColumnsColumnTasksTaskReferencesReference
      x-api-path-slug: restboardsboardidcolumnscolumnidtaskstaskidreferencesreferenceid-delete
      parameters:
      - in: path
        name: boardId
      - in: path
        name: columnId
      - in: path
        name: referenceId
      - in: path
        name: taskId
      responses:
        200:
          description: OK
      tags:
      - S
      - Reference
      - From
      - Given
      - Task
  /rest/boards/{boardId}/columns/{columnId}/tasks/{taskId}/references/{referenceType}/{referenceKey}:
    get:
      summary: ""
      description: .
      operationId: getRestBoardsBoardColumnsColumnTasksTaskReferencesReferencetypeReferencekey
      x-api-path-slug: restboardsboardidcolumnscolumnidtaskstaskidreferencesreferencetypereferencekey-get
      parameters:
      - in: path
        name: boardId
      - in: path
        name: columnId
      - in: path
        name: referenceKey
      - in: path
        name: referenceType
      - in: path
        name: taskId
      responses:
        200:
          description: OK
      tags:
      - ""
  /rest/categories:
    get:
      summary: List categories
      description: List categories.
      operationId: getRestCategories
      x-api-path-slug: restcategories-get
      parameters:
      - in: query
        name: categoryId
        description: The ID of the category
      - in: query
        name: itemsPerPage
        description: The number of results per page
      - in: query
        name: lang
        description: The languages of the category detail information
      - in: query
        name: level
        description: The level of the category
      - in: query
        name: linklist
        description: Filter for the linklist of categories
      - in: query
        name: name
        description: The name of the category
      - in: query
        name: page
        description: The requested page of results
      - in: query
        name: parentId
        description: The unique ID of the parent category
      - in: query
        name: plentyId
        description: The unique plenty ID of the client (store)
      - in: query
        name: type
        description: The category type
      - in: query
        name: updatedAt
        description: Filter restricts the list of results to items updated after the
          specified date
      - in: query
        name: with
        description: Includes the detail information, the active clients (stores)
          list of the category and/or the linked Elmar category for each client
      responses:
        200:
          description: OK
      tags:
      - List
      - Categories
    post:
      summary: Creates new categories
      description: Creates new categories.
      operationId: postRestCategories
      x-api-path-slug: restcategories-post
      parameters:
      - in: body
        name: /rest/categories
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Creates
      - New
      - Categories
    put:
      summary: Updates categories
      description: Updates categories.
      operationId: putRestCategories
      x-api-path-slug: restcategories-put
      parameters:
      - in: body
        name: /rest/categories
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - S
      - Categories
  /rest/categories/{categoryId}/documents:
    get:
      summary: List documents of a category
      description: Lists the documents of a category. The ID of the category must
        be specified.
      operationId: getRestCategoriesCategoryDocuments
      x-api-path-slug: restcategoriescategoryiddocuments-get
      parameters:
      - in: path
        name: categoryId
      responses:
        200:
          description: OK
      tags:
      - List
      - Documents
      - Of
      - Category
    post:
      summary: Upload category documents
      description: Uploads documents to a category. The ID of the category must be
        specified.
      operationId: postRestCategoriesCategoryDocuments
      x-api-path-slug: restcategoriescategoryiddocuments-post
      parameters:
      - in: body
        name: /rest/categories/{categoryId}/documents
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: categoryId
      - in: query
        name: directoryId
        description: The directory ID
      - in: query
        name: displayDate
        description: The date displayed on the document
      - in: query
        name: documents
        description: The array with the category documents
      - in: query
        name: number
        description: The document number
      - in: query
        name: numberWithPrefix
        description: Number with prefix
      responses:
        200:
          description: OK
      tags:
      - Upload
      - Category
      - Documents
  /rest/categories/{categoryId}/documents/downloads:
    get:
      summary: Download category documents
      description: Downloads the documents of a category as a zip file. The ID of
        the category must be specified.
      operationId: getRestCategoriesCategoryDocumentsDownloads
      x-api-path-slug: restcategoriescategoryiddocumentsdownloads-get
      parameters:
      - in: path
        name: categoryId
      responses:
        200:
          description: OK
      tags:
      - Download
      - Category
      - Documents
  /rest/categories/{categoryId}/documents/{documentId}:
    delete:
      summary: Deletes a category document. The ID of the document must be specified.
      description: Deletes a category document. the id of the document must be specified..
      operationId: deleteRestCategoriesCategoryDocumentsDocument
      x-api-path-slug: restcategoriescategoryiddocumentsdocumentid-delete
      parameters:
      - in: path
        name: categoryId
      - in: path
        name: documentId
      responses:
        200:
          description: OK
      tags:
      - S
      - Category
      - Document
      - ""
      - ID
      - Of
      - Document
      - Must
      - Be
      - Specified
  /rest/categories/{id}:
    delete:
      summary: Deletes a category
      description: Deletes a category. The ID of the category must be specified.
      operationId: deleteRestCategories
      x-api-path-slug: restcategoriesid-delete
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - S
      - Category
    get:
      summary: List categories
      description: List categories.
      operationId: getRestCategories
      x-api-path-slug: restcategoriesid-get
      parameters:
      - in: query
        name: categoryId
        description: The ID of the category
      - in: path
        name: id
      - in: query
        name: itemsPerPage
        description: The number of results per page
      - in: query
        name: lang
        description: The languages of the category detail information
      - in: query
        name: level
        description: The level of the category
      - in: query
        name: linklist
        description: Filter for the linklist of categories
      - in: query
        name: name
        description: The name of the category
      - in: query
        name: page
        description: The requested page of results
      - in: query
        name: parentId
        description: The unique ID of the parent category
      - in: query
        name: plentyId
        description: The unique plenty ID of the client (store)
      - in: query
        name: type
        description: The category type
      - in: query
        name: updatedAt
        description: Filter restricts the list of results to items updated after the
          specified date
      - in: query
        name: with
        description: Includes the detail information, the active clients (stores)
          list of the category and/or the linked Elmar category for each client
      responses:
        200:
          description: OK
      tags:
      - List
      - Categories
    put:
      summary: Updates one category
      description: Updates an existing category. The ID of the category must be specified.
      operationId: putRestCategories
      x-api-path-slug: restcategoriesid-put
      parameters:
      - in: body
        name: /rest/categories/{id}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - S
      - Category
  /rest/categories/{id}/clients:
    delete:
      summary: Deactivate availability for clients
      description: Deactivate availability for clients.
      operationId: deleteRestCategoriesClients
      x-api-path-slug: restcategoriesidclients-delete
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Deactivate
      - Availabilityclients
  /rest/categories/{id}/details:
    delete:
      summary: Delete category details for the specified languages
      description: Delete category details for the specified languages.
      operationId: deleteRestCategoriesDetails
      x-api-path-slug: restcategoriesiddetails-delete
      parameters:
      - in: body
        name: /rest/categories/{id}/details
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Category
      - Detailsthe
      - Specified
      - Languages
  /rest/categories/{id}/templates:
    delete:
      summary: Delete a category template
      description: Deletes a category template. The ID of the category, the plenty
        ID of the client (store) and the language must be specified.
      operationId: deleteRestCategoriesTemplates
      x-api-path-slug: restcategoriesidtemplates-delete
      parameters:
      - in: body
        name: /rest/categories/{id}/templates
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Category
      - Template
    get:
      summary: Get a category template
      description: Gets a category template. The ID of the category, the plenty ID
        of the client (store) and the language must be specified.
      operationId: getRestCategoriesTemplates
      x-api-path-slug: restcategoriesidtemplates-get
      parameters:
      - in: body
        name: /rest/categories/{id}/templates
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: query
        name: lang
        description: The language of the template
      - in: query
        name: plentyId
        description: The unique plenty ID of the client (store)
      responses:
        200:
          description: OK
      tags:
      - Category
      - Template
    put:
      summary: Update a category template
      description: Updates a category template. The ID of the category, the plenty
        ID of the client (store) and the language must be specified.
      operationId: putRestCategoriesTemplates
      x-api-path-slug: restcategoriesidtemplates-put
      parameters:
      - in: body
        name: /rest/categories/{id}/templates
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Category
      - Template
  /rest/category_branches:
    get:
      summary: Get category trees
      description: Get category trees.
      operationId: getRestCategoryBranches
      x-api-path-slug: restcategory-branches-get
      parameters:
      - in: query
        name: itemsPerPage
        description: The number of results per page
      - in: query
        name: page
        description: The requested page of results
      - in: query
        name: type
        description: The category type
      responses:
        200:
          description: OK
      tags:
      - Category
      - Trees
  /rest/category_branches/{id}:
    get:
      summary: Get category tree
      description: Gets the category tree of a category. The ID of the category must
        be specified.
      operationId: getRestCategoryBranches
      x-api-path-slug: restcategory-branchesid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Category
      - Tree
  /rest/comments:
    post:
      summary: Create a comment
      description: Creates a comment.
      operationId: postRestComments
      x-api-path-slug: restcomments-post
      parameters:
      - in: body
        name: /rest/comments
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Comment
  /rest/comments/{commentId}:
    delete:
      summary: Delete a comment
      description: Deletes a comment. The ID of the comment must be specified.
      operationId: deleteRestCommentsComment
      x-api-path-slug: restcommentscommentid-delete
      parameters:
      - in: path
        name: commentId
      responses:
        200:
          description: OK
      tags:
      - Comment
    get:
      summary: Get a comment
      description: Gets a comment. The ID of the comment must be specified.
      operationId: getRestCommentsComment
      x-api-path-slug: restcommentscommentid-get
      parameters:
      - in: path
        name: commentId
      responses:
        200:
          description: OK
      tags:
      - Comment
    put:
      summary: ""
      description: .
      operationId: putRestCommentsComment
      x-api-path-slug: restcommentscommentid-put
      parameters:
      - in: path
        name: commentId
      - in: query
        name: isVisibleForContact
        description: If true, the comment is visible for the associated contact
      - in: query
        name: referenceType
        description: The reference type
      - in: query
        name: referenceValue
        description: The reference value
      - in: query
        name: userId
        description: The ID of the user the comment belongs to
      responses:
        200:
          description: OK
      tags:
      - ""
  /rest/comments/{referenceType}/{referenceValue}:
    get:
      summary: List comments
      description: Lists comments. The reference type and the reference value must
        be specified (e.g. the reference type is 'order' and the reference value is
        the ID of the order).
      operationId: getRestCommentsReferencetypeReferencevalue
      x-api-path-slug: restcommentsreferencetypereferencevalue-get
      parameters:
      - in: query
        name: isVisibleForContact
        description: If true, the comment is visible for the associated contact
      - in: path
        name: referenceType
      - in: path
        name: referenceValue
      - in: query
        name: userId
        description: The ID of the user the comment belongs to
      responses:
        200:
          description: OK
      tags:
      - List
      - Comments
  /rest/customer_contracts:
    get:
      summary: List contracts
      description: List contracts.
      operationId: getRestCustomerContracts
      x-api-path-slug: restcustomer-contracts-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Contracts
    post:
      summary: Creates a new contract
      description: Creates a new contract.
      operationId: postRestCustomerContracts
      x-api-path-slug: restcustomer-contracts-post
      responses:
        200:
          description: OK
      tags:
      - Creates
      - New
      - Contract
  /rest/customer_contracts/{contractId}:
    get:
      summary: Returns a single contract
      description: Returns a single contract.
      operationId: getRestCustomerContractsContract
      x-api-path-slug: restcustomer-contractscontractid-get
      parameters:
      - in: path
        name: contractId
      responses:
        200:
          description: OK
      tags:
      - Returns
      - Single
      - Contract
  /rest/customer_contracts/{contractId}/document:
    get:
      summary: Starts download of contract document
      description: Starts download of contract document.
      operationId: getRestCustomerContractsContractDocument
      x-api-path-slug: restcustomer-contractscontractiddocument-get
      parameters:
      - in: path
        name: contractId
      responses:
        200:
          description: OK
      tags:
      - Starts
      - Download
      - Of
      - Contract
      - Document
  /rest/customer_contracts/{contractId}/sign:
    get:
      summary: Returns signing of a contract
      description: Returns signing of a contract.
      operationId: getRestCustomerContractsContractSign
      x-api-path-slug: restcustomer-contractscontractidsign-get
      parameters:
      - in: path
        name: contractId
      responses:
        200:
          description: OK
      tags:
      - Returns
      - Signing
      - Of
      - Contract
    post:
      summary: Sign a contract
      description: Sign a contract.
      operationId: postRestCustomerContractsContractSign
      x-api-path-slug: restcustomer-contractscontractidsign-post
      parameters:
      - in: path
        name: contractId
      responses:
        200:
          description: OK
      tags:
      - Sign
      - Contract
  /rest/customer_contracts/{contractId}/sign/document:
    get:
      summary: Starts download of signed contract document
      description: Starts download of signed contract document.
      operationId: getRestCustomerContractsContractSignDocument
      x-api-path-slug: restcustomer-contractscontractidsigndocument-get
      parameters:
      - in: path
        name: contractId
      responses:
        200:
          description: OK
      tags:
      - Starts
      - Download
      - Of
      - Signed
      - Contract
      - Document
  /rest/delete_log:
    get:
      summary: Search the delete log
      description: Searches the delete log.
      operationId: getRestDeleteLog
      x-api-path-slug: restdelete-log-get
      parameters:
      - in: query
        name: itemsPerPage
        description: The number of items to list per page
      - in: query
        name: page
        description: The page of results to search for
      - in: query
        name: referenceType
        description: The type of deleted record
      - in: query
        name: updatedBetween
        description: Filter restricts the list of results to deleteLogs updated during
          the specified period
      - in: query
        name: userId
        description: The ID of the user who deleted the record
      responses:
        200:
          description: OK
      tags:
      - Search
      - Delete
      - Log
  /rest/documents/{documentId}:
    get:
      summary: Download the content of a document
      description: Downloads the content of a document. The ID of the document must
        be specified.
      operationId: getRestDocumentsDocument
      x-api-path-slug: restdocumentsdocumentid-get
      parameters:
      - in: path
        name: documentId
      responses:
        200:
          description: OK
      tags:
      - Download
      - Content
      - Of
      - Document
  /rest/exports:
    get:
      summary: List elastic exports
      description: Lists elastic exports.
      operationId: getRestExports
      x-api-path-slug: restexports-get
      parameters:
      - in: query
        name: formatKey
        description: The format of the export
      - in: query
        name: id
        description: The ID of the export
      - in: query
        name: itemsPerPage
        description: The number of items to list per page
      - in: query
        name: name
        description: The name of the export
      - in: query
        name: page
        description: The page of results to search for
      - in: query
        name: type
        description: The type of the export
      responses:
        200:
          description: OK
      tags:
      - List
      - Elastic
      - Exports
    post:
      summary: Create an export
      description: Creates an export.
      operationId: postRestExports
      x-api-path-slug: restexports-post
      parameters:
      - in: body
        name: /rest/exports
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Export
  /rest/exports/format_keys:
    get:
      summary: Get format keys
      description: Shows all format keys registered by plugins in production state
      operationId: getRestExportsFormatKeys
      x-api-path-slug: restexportsformat-keys-get
      responses:
        200:
          description: OK
      tags:
      - Format
      - Keys
  /rest/exports/format_keys/{type}:
    get:
      summary: Get format keys
      description: Shows all format keys registered by plugins in production state
      operationId: getRestExportsFormatKeysType
      x-api-path-slug: restexportsformat-keystype-get
      parameters:
      - in: path
        name: type
      responses:
        200:
          description: OK
      tags:
      - Format
      - Keys
  /rest/exports/generate_token:
    get:
      summary: Generate a token
      description: Creates a new token which can be used as <code>OutputParam</code>
        entry.
      operationId: getRestExportsGenerateToken
      x-api-path-slug: restexportsgenerate-token-get
      responses:
        200:
          description: OK
      tags:
      - Generate
      - Token
  /rest/exports/{exportId}:
    delete:
      summary: Delete export
      description: Deletes an export. The ID of the export must be specified.
      operationId: deleteRestExportsExport
      x-api-path-slug: restexportsexportid-delete
      parameters:
      - in: path
        name: exportId
      responses:
        200:
          description: OK
      tags:
      - Export
    get:
      summary: Get export
      description: Gets detailed information about an export. The ID of the export
        must be specified.
      operationId: getRestExportsExport
      x-api-path-slug: restexportsexportid-get
      parameters:
      - in: path
        name: exportId
      responses:
        200:
          description: OK
      tags:
      - Export
    put:
      summary: Update an export
      description: Updates an export. The ID of the export must be specified.
      operationId: putRestExportsExport
      x-api-path-slug: restexportsexportid-put
      parameters:
      - in: body
        name: /rest/exports/{exportId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: exportId
      responses:
        200:
          description: OK
      tags:
      - Export
  /rest/exports/{exportId}/filters/{filterId}:
    delete:
      summary: ""
      description: .
      operationId: deleteRestExportsExportFiltersFilter
      x-api-path-slug: restexportsexportidfiltersfilterid-delete
      responses:
        200:
          description: OK
      tags:
      - ""
  /rest/exports/{exportId}/filters/{key}:
    delete:
      summary: ""
      description: .
      operationId: deleteRestExportsExportFiltersKey
      x-api-path-slug: restexportsexportidfilterskey-delete
      parameters:
      - in: path
        name: exportId
      - in: path
        name: key
      responses:
        200:
          description: OK
      tags:
      - ""
  /rest/feedbacks/comment:
    post:
      summary: Create a feedback comment
      description: Creates a feedback comment.
      operationId: postRestFeedbacksComment
      x-api-path-slug: restfeedbackscomment-post
      parameters:
      - in: query
        name: commentRelationTargetId
        description: The ID of the comments target
      - in: query
        name: commentRelationTargetTypeId
        description: The type ID of the comments target
      - in: query
        name: message
        description: Feedback comment message
      responses:
        200:
          description: OK
      tags:
      - Feedback
      - Comment
  /rest/feedbacks/comment/{commentId}:
    delete:
      summary: Delete a feedback comment
      description: Deletes a feedback comment. The ID of the feedback comment must
        be specified.
      operationId: deleteRestFeedbacksCommentComment
      x-api-path-slug: restfeedbackscommentcommentid-delete
      parameters:
      - in: path
        name: commentId
      - in: query
        name: feedbackCommentId
        description: The ID of the feedback comment
      responses:
        200:
          description: OK
      tags:
      - Feedback
      - Comment
    get:
      summary: Get a feedback comment
      description: Gets a feedback comment. The ID of the feedback comment must be
        specified.
      operationId: getRestFeedbacksCommentComment
      x-api-path-slug: restfeedbackscommentcommentid-get
      parameters:
      - in: path
        name: commentId
      - in: query
        name: feedbackCommentId
        description: The ID of the feedback comment
      responses:
        200:
          description: OK
      tags:
      - Feedback
      - Comment
    put:
      summary: ""
      description: .
      operationId: putRestFeedbacksCommentComment
      x-api-path-slug: restfeedbackscommentcommentid-put
      responses:
        200:
          description: OK
      tags:
      - ""
  /rest/feedbacks/comments:
    get:
      summary: List feedback comments
      description: Lists feedback comments.
      operationId: getRestFeedbacksComments
      x-api-path-slug: restfeedbackscomments-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Feedback
      - Comments
  /rest/feedbacks/delete_feedbacks/{feedbackIds}:
    delete:
      summary: Delete multiple feedbacks
      description: Deletes multiple feedbacks. A list with IDs of feedbacks must be
        specified.
      operationId: deleteRestFeedbacksDeleteFeedbacksFeedbacks
      x-api-path-slug: restfeedbacksdelete-feedbacksfeedbackids-delete
      parameters:
      - in: path
        name: feedbackIds
      responses:
        200:
          description: OK
      tags:
      - Multiple
      - Feedbacks
  /rest/feedbacks/feedback:
    post:
      summary: Create a feedback
      description: Creates a feedback.
      operationId: postRestFeedbacksFeedback
      x-api-path-slug: restfeedbacksfeedback-post
      parameters:
      - in: query
        name: feedbackRelationSourceTypeId
        description: The type ID of the feedbacks source
      - in: query
        name: feedbackRelationTargetId
        description: The ID of the feedbacks target
      - in: query
        name: feedbackRelationTargetTypeId
        description: The type ID of the feedbacks target
      - in: query
        name: title
        description: Feedback title
      responses:
        200:
          description: OK
      tags:
      - Feedback
  /rest/feedbacks/feedback/replies/{feedbackId}:
    get:
      summary: List feedback replies
      description: Lists feedback replies. The ID of the feedback must be specified.
      operationId: getRestFeedbacksFeedbackRepliesFeedback
      x-api-path-slug: restfeedbacksfeedbackrepliesfeedbackid-get
      parameters:
      - in: path
        name: feedbackId
      responses:
        200:
          description: OK
      tags:
      - List
      - Feedback
      - Replies
  /rest/feedbacks/feedback/{feedbackId}:
    delete:
      summary: Delete a feedback
      description: Deletes a feedback. The ID of the feedback must be specified.
      operationId: deleteRestFeedbacksFeedbackFeedback
      x-api-path-slug: restfeedbacksfeedbackfeedbackid-delete
      parameters:
      - in: path
        name: feedbackId
      responses:
        200:
          description: OK
      tags:
      - Feedback
    get:
      summary: Get a feedback
      description: Gets a feedback. The ID of the feedback must be specified.
      operationId: getRestFeedbacksFeedbackFeedback
      x-api-path-slug: restfeedbacksfeedbackfeedbackid-get
      parameters:
      - in: path
        name: feedbackId
      responses:
        200:
          description: OK
      tags:
      - Feedback
    put:
      summary: Update a feedback
      description: Updates a feedback. The ID of the feedback must be specified.
      operationId: putRestFeedbacksFeedbackFeedback
      x-api-path-slug: restfeedbacksfeedbackfeedbackid-put
      parameters:
      - in: path
        name: feedbackId
      responses:
        200:
          description: OK
      tags:
      - Feedback
  /rest/feedbacks/feedbacks:
    get:
      summary: List feedbacks
      description: Lists feedbacks. The reference type and the reference value must
        be specified (e.g. the reference type is 'order' and the reference value is
        the ID of the order).
      operationId: getRestFeedbacksFeedbacks
      x-api-path-slug: restfeedbacksfeedbacks-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Feedbacks
  /rest/feedbacks/feedbacks_visibility:
    put:
      summary: Update the visibility of multiple feedbacks
      description: Updates the visibility of multiple feedbacks. A list with IDs of
        feedbacks must be specified.
      operationId: putRestFeedbacksFeedbacksVisibility
      x-api-path-slug: restfeedbacksfeedbacks-visibility-put
      parameters:
      - in: query
        name: feedbackIds
        description: The list of feedback IDs, separated by commas
      - in: query
        name: isVisible
        description: The visibility value
      responses:
        200:
          description: OK
      tags:
      - Visibility
      - Of
      - Multiple
      - Feedbacks
  /rest/feedbacks/migrate:
    post:
      summary: Migrate legacy feedbacks
      description: Migrate legacy feedbacks.
      operationId: postRestFeedbacksMigrate
      x-api-path-slug: restfeedbacksmigrate-post
      responses:
        200:
          description: OK
      tags:
      - Migrate
      - Legacy
      - Feedbacks
  /rest/feedbacks/rating:
    post:
      summary: Create a feedback rating
      description: Creates a feedback rating.
      operationId: postRestFeedbacksRating
      x-api-path-slug: restfeedbacksrating-post
      parameters:
      - in: query
        name: ratingRelationTargetId
        description: The ID of the ratings target
      - in: query
        name: ratingRelationTargetTypeId
        description: The type ID of the ratings target
      - in: query
        name: ratingValue
        description: The feedbacks comment message
      responses:
        200:
          description: OK
      tags:
      - Feedback
      - Rating
  /rest/feedbacks/rating/{ratingId}:
    delete:
      summary: Delete a feedback rating
      description: Deletes a feedback rating. The ID of the feedback rating must be
        specified.
      operationId: deleteRestFeedbacksRatingRating
      x-api-path-slug: restfeedbacksratingratingid-delete
      parameters:
      - in: query
        name: feedbackRatingId
        description: The ID of the feedback rating
      - in: path
        name: ratingId
      responses:
        200:
          description: OK
      tags:
      - Feedback
      - Rating
    get:
      summary: Get a feedback rating
      description: Gets a feedback rating. The ID of the feedback rating must be specified.
      operationId: getRestFeedbacksRatingRating
      x-api-path-slug: restfeedbacksratingratingid-get
      parameters:
      - in: query
        name: feedbackRatingId
        description: The ID of the feedback rating
      - in: path
        name: ratingId
      responses:
        200:
          description: OK
      tags:
      - Feedback
      - Rating
    put:
      summary: ""
      description: .
      operationId: putRestFeedbacksRatingRating
      x-api-path-slug: restfeedbacksratingratingid-put
      responses:
        200:
          description: OK
      tags:
      - ""
  /rest/feedbacks/ratings:
    get:
      summary: List feedback ratings
      description: Lists feedback ratings.
      operationId: getRestFeedbacksRatings
      x-api-path-slug: restfeedbacksratings-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Feedback
      - Ratings
  /rest/item_sets:
    delete:
      summary: Delete item sets
      description: Delete item sets.
      operationId: deleteRestItemSets
      x-api-path-slug: restitem-sets-delete
      responses:
        200:
          description: OK
      tags:
      - Item
      - Sets
    get:
      summary: List item sets
      description: Lists all item sets.
      operationId: getRestItemSets
      x-api-path-slug: restitem-sets-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Item
      - Sets
    post:
      summary: Create item sets
      description: Create item sets.
      operationId: postRestItemSets
      x-api-path-slug: restitem-sets-post
      parameters:
      - in: query
        name: params
        description: includes the item sets that have to be created
      responses:
        200:
          description: OK
      tags:
      - Item
      - Sets
    put:
      summary: Update item sets
      description: Update item sets.
      operationId: putRestItemSets
      x-api-path-slug: restitem-sets-put
      responses:
        200:
          description: OK
      tags:
      - Item
      - Sets
  /rest/item_sets/{id}:
    delete:
      summary: Delete an item set
      description: Deletes an item set. The item ID of the item set must be specified.
      operationId: deleteRestItemSets
      x-api-path-slug: restitem-setsid-delete
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Item
      - Set
    get:
      summary: Get an item set
      description: Gets the configuration of an item set. The item ID of the item
        set must be specified.
      operationId: getRestItemSets
      x-api-path-slug: restitem-setsid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Item
      - Set
    put:
      summary: Update an item set
      description: Updates an item set. The item ID of the item set must be specified.
      operationId: putRestItemSets
      x-api-path-slug: restitem-setsid-put
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Item
      - Set
  /rest/item_sets/{setId}/components:
    delete:
      summary: Delete item set components
      description: Delete item set components.
      operationId: deleteRestItemSetsSetComponents
      x-api-path-slug: restitem-setssetidcomponents-delete
      parameters:
      - in: path
        name: setId
      responses:
        200:
          description: OK
      tags:
      - Item
      - Set
      - Components
    get:
      summary: List item set components of an item set
      description: Lists the item set components of an item set. The ID of the item
        set must be specified.
      operationId: getRestItemSetsSetComponents
      x-api-path-slug: restitem-setssetidcomponents-get
      parameters:
      - in: path
        name: setId
      responses:
        200:
          description: OK
      tags:
      - List
      - Item
      - Set
      - Components
      - Of
      - Item
      - Set
    post:
      summary: Create item set components
      description: Create item set components.
      operationId: postRestItemSetsSetComponents
      x-api-path-slug: restitem-setssetidcomponents-post
      parameters:
      - in: path
        name: setId
      responses:
        200:
          description: OK
      tags:
      - Item
      - Set
      - Components
    put:
      summary: Update item set components
      description: Update item set components.
      operationId: putRestItemSetsSetComponents
      x-api-path-slug: restitem-setssetidcomponents-put
      parameters:
      - in: path
        name: setId
      responses:
        200:
          description: OK
      tags:
      - Item
      - Set
      - Components
  /rest/item_sets/{setId}/components/{id}:
    delete:
      summary: Delete an item set component
      description: Deletes an item set component. The item set component ID of the
        item set component must be specified.
      operationId: deleteRestItemSetsSetComponents
      x-api-path-slug: restitem-setssetidcomponentsid-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: setId
      responses:
        200:
          description: OK
      tags:
      - Item
      - Set
      - Component
    get:
      summary: Get an item set component
      description: Get an item set component.
      operationId: getRestItemSetsSetComponents
      x-api-path-slug: restitem-setssetidcomponentsid-get
      parameters:
      - in: path
        name: id
      - in: path
        name: setId
      responses:
        200:
          description: OK
      tags:
      - Item
      - Set
      - Component
    put:
      summary: Update an item set component
      description: Update an item set component.
      operationId: putRestItemSetsSetComponents
      x-api-path-slug: restitem-setssetidcomponentsid-put
      parameters:
      - in: path
        name: id
      - in: path
        name: setId
      responses:
        200:
          description: OK
      tags:
      - Item
      - Set
      - Component
  /rest/item_sets/{setId}/config:
    get:
      summary: Get the item set configuration of an item set
      description: Get the item set configuration of an item set.
      operationId: getRestItemSetsSetConfig
      x-api-path-slug: restitem-setssetidconfig-get
      parameters:
      - in: path
        name: setId
      responses:
        200:
          description: OK
      tags:
      - Item
      - Set
      - Configuration
      - Of
      - Item
      - Set
    put:
      summary: Update an item set configuration
      description: Update an item set configuration.
      operationId: putRestItemSetsSetConfig
      x-api-path-slug: restitem-setssetidconfig-put
      parameters:
      - in: path
        name: setId
      responses:
        200:
          description: OK
      tags:
      - Item
      - Set
      - Configuration
  /rest/items:
    get:
      summary: Search item
      description: Search item.
      operationId: getRestItems
      x-api-path-slug: restitems-get
      parameters:
      - in: query
        name: flagOne
        description: Filter restricts the list of results to items with the specified
          flagOne
      - in: query
        name: flagTwo
        description: Filter restricts the list of results to items with the specified
          flagTwo
      - in: query
        name: itemsPerPage
        description: Limits the number of results listed per page to a specific number
      - in: query
        name: lang
        description: The language of the variation information
      - in: query
        name: manufacturerId
        description: Filter restricts the list of results to items with the specified
          manufacturerId
      - in: query
        name: name
        description: Filter restricts the list of results to items with the specified
          item name
      - in: query
        name: page
        description: Limits the results to a specific page
      - in: query
        name: tagId
        description: Filter restricts the list of results to items with the specified
          tagId
      - in: query
        name: updatedBetween
        description: Filter restricts the list of results to items updated during
          the specified period
      - in: query
        name: variationRelatedUpdatedBetween
        description: Filter restricts the list of results to items with variations
          for which related information was updated during the specified period
      - in: query
        name: variationUpdatedBetween
        description: Filter restricts the list of results to items with variations
          that were updated during the specified period
      - in: query
        name: with
        description: Includes the specified variation information in the results
      responses:
        200:
          description: OK
      tags:
      - Search
      - Item
    post:
      summary: Create new item
      description: Create new item.
      operationId: postRestItems
      x-api-path-slug: restitems-post
      parameters:
      - in: body
        name: /rest/items
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - New
      - Item
  /rest/items/attribute_values/{valueId}/names:
    get:
      summary: Get name and language for an attribute value ID
      description: Gets name and language for an attribute value ID. The attribute
        value ID must be specified.
      operationId: getRestItemsAttributeValuesValueNames
      x-api-path-slug: restitemsattribute-valuesvalueidnames-get
      parameters:
      - in: path
        name: valueId
      responses:
        200:
          description: OK
      tags:
      - Name
      - Languagean
      - Attribute
      - Value
      - ID
    post:
      summary: Create an attribute value name
      description: Creates an attribute value name.
      operationId: postRestItemsAttributeValuesValueNames
      x-api-path-slug: restitemsattribute-valuesvalueidnames-post
      parameters:
      - in: body
        name: /rest/items/attribute_values/{valueId}/names
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: valueId
      responses:
        200:
          description: OK
      tags:
      - Attribute
      - Value
      - Name
  /rest/items/attribute_values/{valueId}/names/{lang}:
    delete:
      summary: Delete an attribute value name
      description: Deletes an attribute value name. The attribute value ID and language
        must be specified.
      operationId: deleteRestItemsAttributeValuesValueNamesLang
      x-api-path-slug: restitemsattribute-valuesvalueidnameslang-delete
      parameters:
      - in: path
        name: lang
      - in: path
        name: valueId
      responses:
        200:
          description: OK
      tags:
      - Attribute
      - Value
      - Name
    get:
      summary: Get an attribute value name
      description: Gets the attribute value name. The attribute value ID and language
        must be specified.
      operationId: getRestItemsAttributeValuesValueNamesLang
      x-api-path-slug: restitemsattribute-valuesvalueidnameslang-get
      parameters:
      - in: path
        name: lang
      - in: path
        name: valueId
      responses:
        200:
          description: OK
      tags:
      - Attribute
      - Value
      - Name
    put:
      summary: Update an attribute value name
      description: Updates an attribute value name.
      operationId: putRestItemsAttributeValuesValueNamesLang
      x-api-path-slug: restitemsattribute-valuesvalueidnameslang-put
      parameters:
      - in: body
        name: /rest/items/attribute_values/{valueId}/names/{lang}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: lang
      - in: path
        name: valueId
      responses:
        200:
          description: OK
      tags:
      - Attribute
      - Value
      - Name
  /rest/items/attributes:
    get:
      summary: List attributes
      description: Lists all attributes.
      operationId: getRestItemsAttributes
      x-api-path-slug: restitemsattributes-get
      parameters:
      - in: query
        name: updatedAt
        description: Filter restricts the list of results to items updated after the
          specified date
      - in: query
        name: with
        description: Includes the specified attribute information in the results
      responses:
        200:
          description: OK
      tags:
      - List
      - Attributes
    post:
      summary: Create an attribute
      description: Creates an attribute.
      operationId: postRestItemsAttributes
      x-api-path-slug: restitemsattributes-post
      parameters:
      - in: body
        name: /rest/items/attributes
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Attribute
  /rest/items/attributes/maps:
    get:
      summary: Lists all attribute maps.
      description: Lists all attribute maps..
      operationId: getRestItemsAttributesMaps
      x-api-path-slug: restitemsattributesmaps-get
      responses:
        200:
          description: OK
      tags:
      - Lists
      - ""
      - Attribute
      - Maps
  /rest/items/attributes/markets/maps:
    post:
      summary: Creates a new attribute map.
      description: Creates a new attribute map..
      operationId: postRestItemsAttributesMarketsMaps
      x-api-path-slug: restitemsattributesmarketsmaps-post
      parameters:
      - in: body
        name: /rest/items/attributes/markets/maps
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Creates
      - New
      - Attribute
      - Map
  /rest/items/attributes/values/maps:
    get:
      summary: Lists all attribute value maps.
      description: Lists all attribute value maps..
      operationId: getRestItemsAttributesValuesMaps
      x-api-path-slug: restitemsattributesvaluesmaps-get
      responses:
        200:
          description: OK
      tags:
      - Lists
      - ""
      - Attribute
      - Value
      - Maps
  /rest/items/attributes/values/markets/maps:
    post:
      summary: Creates a new attribute value map.
      description: Creates a new attribute value map..
      operationId: postRestItemsAttributesValuesMarketsMaps
      x-api-path-slug: restitemsattributesvaluesmarketsmaps-post
      parameters:
      - in: body
        name: /rest/items/attributes/values/markets/maps
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Creates
      - New
      - Attribute
      - Value
      - Map
  /rest/items/attributes/{attributeId}/markets/{marketId}/maps:
    delete:
      summary: Deletes an attribute map.
      description: Deletes an attribute map. The ID of the attribute and the ID of
        the market must be specified.
      operationId: deleteRestItemsAttributesAttributeMarketsMarketMaps
      x-api-path-slug: restitemsattributesattributeidmarketsmarketidmaps-delete
      parameters:
      - in: path
        name: attributeId
      - in: path
        name: marketId
      responses:
        200:
          description: OK
      tags:
      - S
      - Attribute
      - Map
    get:
      summary: Gets an attribute map.
      description: Gets an attribute map. The ID of the attribute and the ID of the
        market must be specified.
      operationId: getRestItemsAttributesAttributeMarketsMarketMaps
      x-api-path-slug: restitemsattributesattributeidmarketsmarketidmaps-get
      parameters:
      - in: path
        name: attributeId
      - in: path
        name: marketId
      responses:
        200:
          description: OK
      tags:
      - S
      - Attribute
      - Map
    put:
      summary: Updates an attribute map.
      description: Updates an attribute map. The ID of the attribute and the ID of
        the market must be specified.
      operationId: putRestItemsAttributesAttributeMarketsMarketMaps
      x-api-path-slug: restitemsattributesattributeidmarketsmarketidmaps-put
      parameters:
      - in: path
        name: attributeId
      - in: path
        name: marketId
      responses:
        200:
          description: OK
      tags:
      - S
      - Attribute
      - Map
  /rest/items/attributes/{attributeId}/names:
    get:
      summary: Get an attribute name
      description: Gets the attribute name in the specified language. The language
        code must be specified.
      operationId: getRestItemsAttributesAttributeNames
      x-api-path-slug: restitemsattributesattributeidnames-get
      parameters:
      - in: path
        name: attributeId
      responses:
        200:
          description: OK
      tags:
      - Attribute
      - Name
    post:
      summary: Create an attribute name
      description: Creates an attribute name in the specified language. The language
        code must be specified.
      operationId: postRestItemsAttributesAttributeNames
      x-api-path-slug: restitemsattributesattributeidnames-post
      parameters:
      - in: body
        name: /rest/items/attributes/{attributeId}/names
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: attributeId
      responses:
        200:
          description: OK
      tags:
      - Attribute
      - Name
  /rest/items/attributes/{attributeId}/names/{lang}:
    delete:
      summary: Delete an attribute name
      description: Deletes the attribute name in the specified language. The language
        code and attribute name must be specified.
      operationId: deleteRestItemsAttributesAttributeNamesLang
      x-api-path-slug: restitemsattributesattributeidnameslang-delete
      parameters:
      - in: path
        name: attributeId
      - in: path
        name: lang
      responses:
        200:
          description: OK
      tags:
      - Attribute
      - Name
    get:
      summary: List attribute names
      description: Lists the attribute names of an attribute.
      operationId: getRestItemsAttributesAttributeNamesLang
      x-api-path-slug: restitemsattributesattributeidnameslang-get
      parameters:
      - in: path
        name: attributeId
      - in: path
        name: lang
      responses:
        200:
          description: OK
      tags:
      - List
      - Attribute
      - Names
    put:
      summary: Update an attribute name
      description: Updates the attribute name in the specified language. The language
        code and attribute name must be specified.
      operationId: putRestItemsAttributesAttributeNamesLang
      x-api-path-slug: restitemsattributesattributeidnameslang-put
      parameters:
      - in: body
        name: /rest/items/attributes/{attributeId}/names/{lang}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: attributeId
      - in: path
        name: lang
      responses:
        200:
          description: OK
      tags:
      - Attribute
      - Name
  /rest/items/attributes/{attributeId}/value_market_names:
    get:
      summary: Search attribute value market names
      description: Search attribute value market names.
      operationId: getRestItemsAttributesAttributeValueMarketNames
      x-api-path-slug: restitemsattributesattributeidvalue-market-names-get
      parameters:
      - in: path
        name: attributeId
      - in: query
        name: itemsPerPage
        description: The number of items to list per page
      - in: query
        name: lang
      - in: query
        name: page
        description: The page of results to search for
      - in: query
        name: referenceType
      responses:
        200:
          description: OK
      tags:
      - Search
      - Attribute
      - Value
      - Market
      - Names
    post:
      summary: Create an attribute value market name
      description: Creates an attribute value market name.
      operationId: postRestItemsAttributesAttributeValueMarketNames
      x-api-path-slug: restitemsattributesattributeidvalue-market-names-post
      parameters:
      - in: body
        name: /rest/items/attributes/{attributeId}/value_market_names
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: attributeId
      responses:
        200:
          description: OK
      tags:
      - Attribute
      - Value
      - Market
      - Name
  /rest/items/attributes/{attributeId}/value_market_names/{valueId}/{lang}/{referenceType}:
    delete:
      summary: Delete an attribute value market name
      description: Deletes an attribute value market name. The attribute value ID
        and language must be specified.
      operationId: deleteRestItemsAttributesAttributeValueMarketNamesValueLangReferencetype
      x-api-path-slug: restitemsattributesattributeidvalue-market-namesvalueidlangreferencetype-delete
      parameters:
      - in: path
        name: attributeId
      - in: path
        name: lang
      - in: path
        name: referenceType
      - in: path
        name: valueId
      responses:
        200:
          description: OK
      tags:
      - Attribute
      - Value
      - Market
      - Name
    put:
      summary: Update an attribute value market name
      description: Updates an attribute value market name. The attribute value ID
        and language must be specified.
      operationId: putRestItemsAttributesAttributeValueMarketNamesValueLangReferencetype
      x-api-path-slug: restitemsattributesattributeidvalue-market-namesvalueidlangreferencetype-put
      parameters:
      - in: body
        name: /rest/items/attributes/{attributeId}/value_market_names/{valueId}/{lang}/{referenceType}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: attributeId
      - in: path
        name: lang
      - in: path
        name: referenceType
      - in: path
        name: valueId
      responses:
        200:
          description: OK
      tags:
      - Attribute
      - Value
      - Market
      - Name
  /rest/items/attributes/{attributeId}/values:
    get:
      summary: List attribute values
      description: Lists the attribute values for an attribute. The attribute ID must
        be specified.
      operationId: getRestItemsAttributesAttributeValues
      x-api-path-slug: restitemsattributesattributeidvalues-get
      parameters:
      - in: path
        name: attributeId
      - in: query
        name: updatedAt
        description: Filter restricts the list of results to items updated after the
          specified date
      - in: query
        name: with
        description: Includes the specified attribute value information in the results
      responses:
        200:
          description: OK
      tags:
      - List
      - Attribute
      - Values
    post:
      summary: Create an attribute value
      description: Creates an attribute value.
      operationId: postRestItemsAttributesAttributeValues
      x-api-path-slug: restitemsattributesattributeidvalues-post
      parameters:
      - in: body
        name: /rest/items/attributes/{attributeId}/values
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: attributeId
      responses:
        200:
          description: OK
      tags:
      - Attribute
      - Value
  /rest/items/attributes/{attributeId}/values/{attributeValueId}/markets/{marketId}/maps:
    delete:
      summary: Deletes an attribute value map.
      description: Deletes an attribute value map. The ID of the attribute, the ID
        of the attribute value and the ID of the market must be specified.
      operationId: deleteRestItemsAttributesAttributeValuesAttributevalueMarketsMarketMaps
      x-api-path-slug: restitemsattributesattributeidvaluesattributevalueidmarketsmarketidmaps-delete
      parameters:
      - in: path
        name: attributeId
      - in: path
        name: attributeValueId
      - in: path
        name: marketId
      responses:
        200:
          description: OK
      tags:
      - S
      - Attribute
      - Value
      - Map
    get:
      summary: Gets an attribute value map.
      description: Gets an attribute value map. The ID of the attribute, the ID of
        the attribute value and the ID of the market must be specified.
      operationId: getRestItemsAttributesAttributeValuesAttributevalueMarketsMarketMaps
      x-api-path-slug: restitemsattributesattributeidvaluesattributevalueidmarketsmarketidmaps-get
      parameters:
      - in: path
        name: attributeId
      - in: path
        name: attributeValueId
      - in: path
        name: marketId
      responses:
        200:
          description: OK
      tags:
      - S
      - Attribute
      - Value
      - Map
    put:
      summary: Updates an attribute value map.
      description: Updates an attribute value map. The ID of the attribute, the ID
        of the attribute value and the ID of the market must be specified.
      operationId: putRestItemsAttributesAttributeValuesAttributevalueMarketsMarketMaps
      x-api-path-slug: restitemsattributesattributeidvaluesattributevalueidmarketsmarketidmaps-put
      parameters:
      - in: path
        name: attributeId
      - in: path
        name: attributeValueId
      - in: path
        name: marketId
      responses:
        200:
          description: OK
      tags:
      - S
      - Attribute
      - Value
      - Map
  /rest/items/attributes/{attributeId}/values/{id}:
    delete:
      summary: Delete an attribute value
      description: Deletes an attribute value. The attribute ID must be specified.
      operationId: deleteRestItemsAttributesAttributeValues
      x-api-path-slug: restitemsattributesattributeidvaluesid-delete
      parameters:
      - in: path
        name: attributeId
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Attribute
      - Value
    get:
      summary: Get an attribute value
      description: Get an attribute value. The ID of the attribute value must be specified.
      operationId: getRestItemsAttributesAttributeValues
      x-api-path-slug: restitemsattributesattributeidvaluesid-get
      parameters:
      - in: path
        name: attributeId
      - in: path
        name: id
      - in: query
        name: with
        description: Includes the specified attribute value information in the results
      responses:
        200:
          description: OK
      tags:
      - Attribute
      - Value
    put:
      summary: Update an attribute value
      description: Updates an attribute value. The attribute value must be specified.
      operationId: putRestItemsAttributesAttributeValues
      x-api-path-slug: restitemsattributesattributeidvaluesid-put
      parameters:
      - in: body
        name: /rest/items/attributes/{attributeId}/values/{id}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: attributeId
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Attribute
      - Value
  /rest/items/attributes/{id}:
    delete:
      summary: Delete an attribute
      description: Deletes an attribute. The ID of the attribute must be specified.
      operationId: deleteRestItemsAttributes
      x-api-path-slug: restitemsattributesid-delete
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Attribute
    get:
      summary: Get an attribute
      description: Gets an attribute. The ID of the attribute must be specified.
      operationId: getRestItemsAttributes
      x-api-path-slug: restitemsattributesid-get
      parameters:
      - in: path
        name: id
      - in: query
        name: with
        description: Includes the specified attribute information in the results
      responses:
        200:
          description: OK
      tags:
      - Attribute
    put:
      summary: Update an attribute
      description: Updates an attribute. The ID of the attribute must be specified.
      operationId: putRestItemsAttributes
      x-api-path-slug: restitemsattributesid-put
      parameters:
      - in: body
        name: /rest/items/attributes/{id}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Attribute
  /rest/items/barcodes:
    get:
      summary: List barcodes
      description: Lists all barcodes.
      operationId: getRestItemsBarcodes
      x-api-path-slug: restitemsbarcodes-get
      parameters:
      - in: query
        name: updatedAt
        description: Filter restricts the list of results to items updated after the
          specified date
      responses:
        200:
          description: OK
      tags:
      - List
      - Barcodes
    post:
      summary: Create a barcode
      description: Creates a barcode.
      operationId: postRestItemsBarcodes
      x-api-path-slug: restitemsbarcodes-post
      parameters:
      - in: body
        name: /rest/items/barcodes
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Barcode
  /rest/items/barcodes/referrer/{referrerId}:
    get:
      summary: List barcodes by referrer
      description: Lists barcodes linked to the specified referrer. The ID of the
        referrer must be specified.
      operationId: getRestItemsBarcodesReferrerReferrer
      x-api-path-slug: restitemsbarcodesreferrerreferrerid-get
      parameters:
      - in: path
        name: referrerId
      responses:
        200:
          description: OK
      tags:
      - List
      - Barcodes
      - By
      - Referrer
  /rest/items/barcodes/type/{type}:
    get:
      summary: List barcodes by type
      description: Lists all barcodes of a specific type. The type must be specified.
      operationId: getRestItemsBarcodesTypeType
      x-api-path-slug: restitemsbarcodestypetype-get
      parameters:
      - in: path
        name: type
      responses:
        200:
          description: OK
      tags:
      - List
      - Barcodes
      - By
      - Type
  /rest/items/barcodes/{barcodeId}:
    delete:
      summary: Delete a barcode
      description: Deletes a barcode. The ID of the barcode must be specified.
      operationId: deleteRestItemsBarcodesBarcode
      x-api-path-slug: restitemsbarcodesbarcodeid-delete
      parameters:
      - in: path
        name: barcodeId
      responses:
        200:
          description: OK
      tags:
      - Barcode
    get:
      summary: Get a barcode
      description: Gets a barcode. The ID of the barcode must be specified.
      operationId: getRestItemsBarcodesBarcode
      x-api-path-slug: restitemsbarcodesbarcodeid-get
      parameters:
      - in: path
        name: barcodeId
      responses:
        200:
          description: OK
      tags:
      - Barcode
    put:
      summary: Update a barcode
      description: Updates a barcode. The ID of the barcode must be specified.
      operationId: putRestItemsBarcodesBarcode
      x-api-path-slug: restitemsbarcodesbarcodeid-put
      parameters:
      - in: body
        name: /rest/items/barcodes/{barcodeId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: barcodeId
      responses:
        200:
          description: OK
      tags:
      - Barcode
  /rest/items/barcodes/{barcodeId}/referrer:
    post:
      summary: Activate a referrer
      description: Activate a referrer for a barcode.
      operationId: postRestItemsBarcodesBarcodeReferrer
      x-api-path-slug: restitemsbarcodesbarcodeidreferrer-post
      parameters:
      - in: path
        name: barcodeId
      responses:
        200:
          description: OK
      tags:
      - Activate
      - Referrer
  /rest/items/barcodes/{barcodeId}/referrer/{referrerId}:
    delete:
      summary: Deactivate a referrer
      description: Deactivate a referrer for a barcode. The ID of the barcode and
        the ID of the referrer must be specified.
      operationId: deleteRestItemsBarcodesBarcodeReferrerReferrer
      x-api-path-slug: restitemsbarcodesbarcodeidreferrerreferrerid-delete
      parameters:
      - in: path
        name: barcodeId
      - in: path
        name: referrerId
      responses:
        200:
          description: OK
      tags:
      - Deactivate
      - Referrer
  /rest/items/item_shipping_profiles:
    get:
      summary: List all shipping profiles of all items
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
      operationId: getRestItemsItemShippingProfiles
      x-api-path-slug: restitemsitem-shipping-profiles-get
      responses:
        200:
          description: OK
      tags:
      - List
      - ""
      - Shipping
      - Profiles
      - Of
      - ""
      - Items
    post:
      summary: Bulk activate shipping profiles
      description: Activates up to 50 shipping profiles for items
      operationId: postRestItemsItemShippingProfiles
      x-api-path-slug: restitemsitem-shipping-profiles-post
      responses:
        200:
          description: OK
      tags:
      - Bulk
      - Activate
      - Shipping
      - Profiles
  /rest/items/labels:
    get:
      summary: List item label templates
      description: Lists the ID and name of all item label templates saved in the
        system.
      operationId: getRestItemsLabels
      x-api-path-slug: restitemslabels-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Item
      - Label
      - Templates
  /rest/items/manufacturers:
    get:
      summary: List manufacturers
      description: |-
        Lists all manufacturers in the system.

        Display a listing of the resource.
      operationId: getRestItemsManufacturers
      x-api-path-slug: restitemsmanufacturers-get
      parameters:
      - in: query
        name: name
        description: Filter restricts the list of results to records with specified
          name
      - in: query
        name: updatedAt
        description: Filter restricts the list of results to records updated after
          the specified date
      responses:
        200:
          description: OK
      tags:
      - List
      - Manufacturers
    post:
      summary: Create a manufacturer
      description: Creates a manufacturer.
      operationId: postRestItemsManufacturers
      x-api-path-slug: restitemsmanufacturers-post
      responses:
        200:
          description: OK
      tags:
      - Manufacturer
  /rest/items/manufacturers/{id}:
    delete:
      summary: Delete a manufacturer
      description: Deletes a manufacturer. The ID of the manufacturer must be specified.
      operationId: deleteRestItemsManufacturers
      x-api-path-slug: restitemsmanufacturersid-delete
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Manufacturer
    get:
      summary: Get a manufacturer
      description: Gets a manufacturer. The ID of the manufacturer must be specified.
      operationId: getRestItemsManufacturers
      x-api-path-slug: restitemsmanufacturersid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Manufacturer
    put:
      summary: Update a manufacturer
      description: Updates a manufacturer. The ID of the manufacturer must be specified.
      operationId: putRestItemsManufacturers
      x-api-path-slug: restitemsmanufacturersid-put
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Manufacturer
  /rest/items/manufacturers/{id}/commissions:
    get:
      summary: List commissions
      description: Lists all commissions associated with a manufacturer. The ID of
        the manufacturer must be specified.
      operationId: getRestItemsManufacturersCommissions
      x-api-path-slug: restitemsmanufacturersidcommissions-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - List
      - Commissions
    post:
      summary: Create a commission
      description: Creates a commission for a manufacturer. The ID of the manufacturer
        must be specified.
      operationId: postRestItemsManufacturersCommissions
      x-api-path-slug: restitemsmanufacturersidcommissions-post
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Commission
  /rest/items/manufacturers/{id}/commissions/{manufacturerId}:
    delete:
      summary: Delete a commission
      description: Delete a commission. The ID of the commission must be specified.
      operationId: deleteRestItemsManufacturersCommissionsManufacturer
      x-api-path-slug: restitemsmanufacturersidcommissionsmanufacturerid-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: manufacturerId
      responses:
        200:
          description: OK
      tags:
      - Commission
    get:
      summary: Get a commission
      description: Gets a commission for a manufacturer. The ID of the commission
        must be specified.
      operationId: getRestItemsManufacturersCommissionsManufacturer
      x-api-path-slug: restitemsmanufacturersidcommissionsmanufacturerid-get
      parameters:
      - in: path
        name: id
      - in: path
        name: manufacturerId
      responses:
        200:
          description: OK
      tags:
      - Commission
    put:
      summary: Update a commission
      description: Updates a commission. The ID of the commission must be specified.
      operationId: putRestItemsManufacturersCommissionsManufacturer
      x-api-path-slug: restitemsmanufacturersidcommissionsmanufacturerid-put
      parameters:
      - in: path
        name: id
      - in: path
        name: manufacturerId
      responses:
        200:
          description: OK
      tags:
      - Commission
  /rest/items/properties:
    get:
      summary: List properties
      description: Lists all properties.
      operationId: getRestItemsProperties
      x-api-path-slug: restitemsproperties-get
      parameters:
      - in: query
        name: groupId
        description: Filter restricts the list of results to items linked to a specified
          property group
      - in: query
        name: updatedAt
        description: Filter restricts the list of results to items updated after the
          specified date
      - in: query
        name: with
        description: Includes the specified property information in the results
      responses:
        200:
          description: OK
      tags:
      - List
      - Properties
    post:
      summary: Create a property
      description: Creates a property.
      operationId: postRestItemsProperties
      x-api-path-slug: restitemsproperties-post
      parameters:
      - in: body
        name: /rest/items/properties
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Property
  /rest/items/properties/{id}:
    delete:
      summary: Delete a property
      description: Deletes a property. The ID of the property must be specified.
      operationId: deleteRestItemsProperties
      x-api-path-slug: restitemspropertiesid-delete
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Property
    get:
      summary: Get a property
      description: Gets a property. The ID of the property must be specified.
      operationId: getRestItemsProperties
      x-api-path-slug: restitemspropertiesid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Property
    put:
      summary: Update a property
      description: Updates a property. The ID of the property must be specified.
      operationId: putRestItemsProperties
      x-api-path-slug: restitemspropertiesid-put
      parameters:
      - in: body
        name: /rest/items/properties/{id}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Property
  /rest/items/properties/{id}/market_references:
    get:
      summary: List property market references
      description: Lists the property market references of a property. The ID of the
        property must be specified.
      operationId: getRestItemsPropertiesMarketReferences
      x-api-path-slug: restitemspropertiesidmarket-references-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - List
      - Property
      - Market
      - References
    post:
      summary: Create a property market reference
      description: Creates a property market reference.
      operationId: postRestItemsPropertiesMarketReferences
      x-api-path-slug: restitemspropertiesidmarket-references-post
      parameters:
      - in: body
        name: /rest/items/properties/{id}/market_references
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Property
      - Market
      - Reference
  /rest/items/properties/{id}/market_references/{marketId}:
    delete:
      summary: Delete a property market reference
      description: Deletes a property market reference. The ID of the property and
        the ID of the market must be specified.
      operationId: deleteRestItemsPropertiesMarketReferencesMarket
      x-api-path-slug: restitemspropertiesidmarket-referencesmarketid-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: marketId
      responses:
        200:
          description: OK
      tags:
      - Property
      - Market
      - Reference
    get:
      summary: Get a property market reference
      description: Gets a property market reference. The market ID and the property
        ID must be specified.
      operationId: getRestItemsPropertiesMarketReferencesMarket
      x-api-path-slug: restitemspropertiesidmarket-referencesmarketid-get
      parameters:
      - in: path
        name: id
      - in: path
        name: marketId
      responses:
        200:
          description: OK
      tags:
      - Property
      - Market
      - Reference
    put:
      summary: Update a property market reference
      description: Updates a property market reference.
      operationId: putRestItemsPropertiesMarketReferencesMarket
      x-api-path-slug: restitemspropertiesidmarket-referencesmarketid-put
      parameters:
      - in: body
        name: /rest/items/properties/{id}/market_references/{marketId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: path
        name: marketId
      responses:
        200:
          description: OK
      tags:
      - Property
      - Market
      - Reference
  /rest/items/properties/{id}/names:
    get:
      summary: List the property names
      description: Lists the names of a property in all languages. The ID of the property
        must be specified.
      operationId: getRestItemsPropertiesNames
      x-api-path-slug: restitemspropertiesidnames-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - List
      - Property
      - Names
    post:
      summary: Create a property name
      description: Creates a property name. The ID of the property must be specified.
      operationId: postRestItemsPropertiesNames
      x-api-path-slug: restitemspropertiesidnames-post
      parameters:
      - in: body
        name: /rest/items/properties/{id}/names
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Property
      - Name
  /rest/items/properties/{id}/names/{lang}:
    delete:
      summary: Delete a property name
      description: Deletes a property name. The ID of the property must be specified.
      operationId: deleteRestItemsPropertiesNamesLang
      x-api-path-slug: restitemspropertiesidnameslang-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: lang
      responses:
        200:
          description: OK
      tags:
      - Property
      - Name
    get:
      summary: Get a property name
      description: Gets a property name in a specified language. The ID of the property
        and the language code must be specified.
      operationId: getRestItemsPropertiesNamesLang
      x-api-path-slug: restitemspropertiesidnameslang-get
      parameters:
      - in: path
        name: id
      - in: path
        name: lang
      responses:
        200:
          description: OK
      tags:
      - Property
      - Name
    put:
      summary: Update a property name
      description: Updates a property name. The ID of the property and the language
        code must be specified.
      operationId: putRestItemsPropertiesNamesLang
      x-api-path-slug: restitemspropertiesidnameslang-put
      parameters:
      - in: body
        name: /rest/items/properties/{id}/names/{lang}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: path
        name: lang
      responses:
        200:
          description: OK
      tags:
      - Property
      - Name
  /rest/items/properties/{propertyId}/selections:
    get:
      summary: List property selections
      description: Lists the property selections of a property. The ID of the property
        must be specified.
      operationId: getRestItemsPropertiesPropertySelections
      x-api-path-slug: restitemspropertiespropertyidselections-get
      parameters:
      - in: path
        name: propertyId
      responses:
        200:
          description: OK
      tags:
      - List
      - Property
      - Selections
    post:
      summary: Create a property selection
      description: Creates a property selection.
      operationId: postRestItemsPropertiesPropertySelections
      x-api-path-slug: restitemspropertiespropertyidselections-post
      parameters:
      - in: body
        name: /rest/items/properties/{propertyId}/selections
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: propertyId
      responses:
        200:
          description: OK
      tags:
      - Property
      - Selection
  /rest/items/properties/{propertyId}/selections/{id}:
    delete:
      summary: Delete a property selection
      description: Deletes a property selection. The ID of the property must be specified.
      operationId: deleteRestItemsPropertiesPropertySelections
      x-api-path-slug: restitemspropertiespropertyidselectionsid-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: propertyId
      responses:
        200:
          description: OK
      tags:
      - Property
      - Selection
    get:
      summary: Get a property selection
      description: Gets a property selection of a property.
      operationId: getRestItemsPropertiesPropertySelections
      x-api-path-slug: restitemspropertiespropertyidselectionsid-get
      parameters:
      - in: path
        name: id
      - in: path
        name: propertyId
      responses:
        200:
          description: OK
      tags:
      - Property
      - Selection
    post:
      summary: Creates a property selection lang
      description: Creates a property selection lang.
      operationId: postRestItemsPropertiesPropertySelections
      x-api-path-slug: restitemspropertiespropertyidselectionsid-post
      parameters:
      - in: body
        name: /rest/items/properties/{propertyId}/selections/{id}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: path
        name: propertyId
      responses:
        200:
          description: OK
      tags:
      - Creates
      - Property
      - Selection
      - Lang
  /rest/items/properties/{propertyId}/selections/{id}/{lang}:
    delete:
      summary: Delete a property selection language
      description: Deletes a property selection language. The ID of the selection
        and the language must be specified.
      operationId: deleteRestItemsPropertiesPropertySelectionsLang
      x-api-path-slug: restitemspropertiespropertyidselectionsidlang-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: lang
      - in: path
        name: propertyId
      responses:
        200:
          description: OK
      tags:
      - Property
      - Selection
      - Language
    get:
      summary: List property selections by language
      description: Lists the property selections of a property for a specific language.
        The ID and language of the property must be specified.
      operationId: getRestItemsPropertiesPropertySelectionsLang
      x-api-path-slug: restitemspropertiespropertyidselectionsidlang-get
      parameters:
      - in: path
        name: id
      - in: path
        name: lang
      - in: path
        name: propertyId
      responses:
        200:
          description: OK
      tags:
      - List
      - Property
      - Selections
      - By
      - Language
    put:
      summary: Update a property selection
      description: Updates a property selection.
      operationId: putRestItemsPropertiesPropertySelectionsLang
      x-api-path-slug: restitemspropertiespropertyidselectionsidlang-put
      parameters:
      - in: body
        name: /rest/items/properties/{propertyId}/selections/{id}/{lang}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: path
        name: lang
      - in: path
        name: propertyId
      responses:
        200:
          description: OK
      tags:
      - Property
      - Selection
  /rest/items/properties/{propertyId}/selections/{lang}:
    get:
      summary: List property selections
      description: Lists the property selections of a property. The ID of the property
        must be specified.
      operationId: getRestItemsPropertiesPropertySelectionsLang
      x-api-path-slug: restitemspropertiespropertyidselectionslang-get
      parameters:
      - in: path
        name: lang
      - in: path
        name: propertyId
      responses:
        200:
          description: OK
      tags:
      - List
      - Property
      - Selections
  /rest/items/property_groups:
    get:
      summary: List property groups
      description: Lists the property groups.
      operationId: getRestItemsPropertyGroups
      x-api-path-slug: restitemsproperty-groups-get
      parameters:
      - in: query
        name: with
        description: Includes the specified property group information in the results
      responses:
        200:
          description: OK
      tags:
      - List
      - Property
      - Groups
    post:
      summary: Create a property group
      description: Creates a property group.
      operationId: postRestItemsPropertyGroups
      x-api-path-slug: restitemsproperty-groups-post
      parameters:
      - in: body
        name: /rest/items/property_groups
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Property
      - Group
  /rest/items/property_groups/{id}:
    delete:
      summary: Delete a property group
      description: Deletes a property group. The ID of the property group must be
        specified.
      operationId: deleteRestItemsPropertyGroups
      x-api-path-slug: restitemsproperty-groupsid-delete
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Property
      - Group
    get:
      summary: Get a property group
      description: Gets a property group. The ID of the property group must be specified.
      operationId: getRestItemsPropertyGroups
      x-api-path-slug: restitemsproperty-groupsid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Property
      - Group
    put:
      summary: Update a property group
      description: Updates an existing property group.
      operationId: putRestItemsPropertyGroups
      x-api-path-slug: restitemsproperty-groupsid-put
      parameters:
      - in: body
        name: /rest/items/property_groups/{id}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Property
      - Group
  /rest/items/property_groups/{id}/names:
    get:
      summary: List the property group names of a property group
      description: Lists the property group names of a property group in all languages.
        The ID of the property group must be specified.
      operationId: getRestItemsPropertyGroupsNames
      x-api-path-slug: restitemsproperty-groupsidnames-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - List
      - Property
      - Group
      - Names
      - Of
      - Property
      - Group
    post:
      summary: Create a property group name
      description: Creates a property group name. The ID of the property group must
        be specified.
      operationId: postRestItemsPropertyGroupsNames
      x-api-path-slug: restitemsproperty-groupsidnames-post
      parameters:
      - in: body
        name: /rest/items/property_groups/{id}/names
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Property
      - Group
      - Name
  /rest/items/property_groups/{id}/names/{lang}:
    delete:
      summary: Delete a property group name
      description: Deletes a property group name. The ID of the property group must
        be specified.
      operationId: deleteRestItemsPropertyGroupsNamesLang
      x-api-path-slug: restitemsproperty-groupsidnameslang-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: lang
      responses:
        200:
          description: OK
      tags:
      - Property
      - Group
      - Name
    get:
      summary: Get a property group name in a language
      description: Gets a property group name in the specified language. The ID of
        the property group name and the language code must be specified.
      operationId: getRestItemsPropertyGroupsNamesLang
      x-api-path-slug: restitemsproperty-groupsidnameslang-get
      parameters:
      - in: path
        name: id
      - in: path
        name: lang
      responses:
        200:
          description: OK
      tags:
      - Property
      - Group
      - Name
      - In
      - Language
    put:
      summary: Update a property group name
      description: Updates a property group name. The ID of the property group and
        the language must be specified.
      operationId: putRestItemsPropertyGroupsNamesLang
      x-api-path-slug: restitemsproperty-groupsidnameslang-put
      parameters:
      - in: body
        name: /rest/items/property_groups/{id}/names/{lang}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: path
        name: lang
      responses:
        200:
          description: OK
      tags:
      - Property
      - Group
      - Name
  /rest/items/sales_prices:
    get:
      summary: List sales prices
      description: Lists all sales prices.
      operationId: getRestItemsSalesPrices
      x-api-path-slug: restitemssales-prices-get
      parameters:
      - in: query
        name: updatedAt
        description: Filter restricts the list of results to items updated after the
          specified date
      responses:
        200:
          description: OK
      tags:
      - List
      - Sales
      - Prices
    post:
      summary: Create a sales price
      description: Creates a sales price.
      operationId: postRestItemsSalesPrices
      x-api-path-slug: restitemssales-prices-post
      parameters:
      - in: body
        name: /rest/items/sales_prices
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Sales
      - Price
  /rest/items/sales_prices/{id}:
    delete:
      summary: Delete a sales price
      description: |-
        Deletes a sales price. The ID of the sales price must be specified.

        Delete salesPrice
      operationId: deleteRestItemsSalesPrices
      x-api-path-slug: restitemssales-pricesid-delete
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Sales
      - Price
    get:
      summary: Get a sales price
      description: Gets the data for a specific sales price. The ID of the sales price
        must be specified.
      operationId: getRestItemsSalesPrices
      x-api-path-slug: restitemssales-pricesid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Sales
      - Price
    put:
      summary: Update a sales price
      description: Updates a sales price.
      operationId: putRestItemsSalesPrices
      x-api-path-slug: restitemssales-pricesid-put
      parameters:
      - in: body
        name: /rest/items/sales_prices/{id}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Sales
      - Price
  /rest/items/sales_prices/{id}/accounts:
    get:
      summary: List referrer accounts
      description: Lists all activated referrer accounts of a sales price.
      operationId: getRestItemsSalesPricesAccounts
      x-api-path-slug: restitemssales-pricesidaccounts-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - List
      - Referrer
      - Accounts
    post:
      summary: Activate a referrer account
      description: Activates a referrer account for a sales price.
      operationId: postRestItemsSalesPricesAccounts
      x-api-path-slug: restitemssales-pricesidaccounts-post
      parameters:
      - in: body
        name: /rest/items/sales_prices/{id}/accounts
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Activate
      - Referrer
      - Account
  /rest/items/sales_prices/{id}/accounts/{accountType}/{accountId}:
    delete:
      summary: Deactivate a referrer account
      description: Deactivates a referrer account for a sales price.
      operationId: deleteRestItemsSalesPricesAccountsAccounttypeAccount
      x-api-path-slug: restitemssales-pricesidaccountsaccounttypeaccountid-delete
      parameters:
      - in: path
        name: accountId
      - in: path
        name: accountType
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Deactivate
      - Referrer
      - Account
  /rest/items/sales_prices/{id}/countries:
    get:
      summary: List countries by sales price
      description: Lists active countries for a sales price. The ID of the sales price
        must be specified.
      operationId: getRestItemsSalesPricesCountries
      x-api-path-slug: restitemssales-pricesidcountries-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - List
      - Countries
      - By
      - Sales
      - Price
    post:
      summary: Activate a country
      description: Activates a country for a sales price.
      operationId: postRestItemsSalesPricesCountries
      x-api-path-slug: restitemssales-pricesidcountries-post
      parameters:
      - in: body
        name: /rest/items/sales_prices/{id}/countries
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Activate
      - Country
  /rest/items/sales_prices/{id}/countries/{countryId}:
    delete:
      summary: Deactivate a country
      description: Deactivates a country for a sales price.
      operationId: deleteRestItemsSalesPricesCountriesCountry
      x-api-path-slug: restitemssales-pricesidcountriescountryid-delete
      parameters:
      - in: path
        name: countryId
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Deactivate
      - Country
  /rest/items/sales_prices/{id}/currencies:
    get:
      summary: List activated currencies
      description: List all currencies activated for a sales price. The ID of the
        sales price must be specified.
      operationId: getRestItemsSalesPricesCurrencies
      x-api-path-slug: restitemssales-pricesidcurrencies-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - List
      - Activated
      - Currencies
    post:
      summary: Activate a currency
      description: Activates a currency for a sales price. The ID of the sales price
        must be specified.
      operationId: postRestItemsSalesPricesCurrencies
      x-api-path-slug: restitemssales-pricesidcurrencies-post
      parameters:
      - in: body
        name: /rest/items/sales_prices/{id}/currencies
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Activate
      - Currency
  /rest/items/sales_prices/{id}/currencies/{currency}:
    delete:
      summary: Deactivate a currency
      description: Deactivate a currency for a sales price. The ID of the sales price
        and the ISO code of the currency must be specified.
      operationId: deleteRestItemsSalesPricesCurrenciesCurrency
      x-api-path-slug: restitemssales-pricesidcurrenciescurrency-delete
      parameters:
      - in: path
        name: currency
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Deactivate
      - Currency
  /rest/items/sales_prices/{id}/customer_classes:
    get:
      summary: List activated customer classes
      description: Lists the activated customer classes for a sales price. The ID
        of the sales price must be specified.
      operationId: getRestItemsSalesPricesCustomerClasses
      x-api-path-slug: restitemssales-pricesidcustomer-classes-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - List
      - Activated
      - Customer
      - Classes
    post:
      summary: Activate a customer class
      description: Activates a customer class for a sales price. The ID of the sales
        price and the ID of the customer class must be specified.
      operationId: postRestItemsSalesPricesCustomerClasses
      x-api-path-slug: restitemssales-pricesidcustomer-classes-post
      parameters:
      - in: body
        name: /rest/items/sales_prices/{id}/customer_classes
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Activate
      - Customer
      - Class
  /rest/items/sales_prices/{id}/customer_classes/{customerClassId}:
    delete:
      summary: Activate a customer class
      description: Activates a customer class for a sales price. The ID of the sales
        price and the ID of the customer class must be specified.
      operationId: deleteRestItemsSalesPricesCustomerClassesCustomerclass
      x-api-path-slug: restitemssales-pricesidcustomer-classescustomerclassid-delete
      parameters:
      - in: path
        name: customerClassId
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Activate
      - Customer
      - Class
  /rest/items/sales_prices/{id}/names:
    get:
      summary: List names of a sales price
      description: Lists the names of a sales price in all languages. The ID of the
        sales price must be specified.
      operationId: getRestItemsSalesPricesNames
      x-api-path-slug: restitemssales-pricesidnames-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - List
      - Names
      - Of
      - Sales
      - Price
    post:
      summary: Create a sales price name
      description: Creates a name for a sales price in the specified language. The
        ID of the sales price must be specified.
      operationId: postRestItemsSalesPricesNames
      x-api-path-slug: restitemssales-pricesidnames-post
      parameters:
      - in: body
        name: /rest/items/sales_prices/{id}/names
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Sales
      - Price
      - Name
  /rest/items/sales_prices/{id}/names/{lang}:
    delete:
      summary: Delete a sales price name
      description: Deletes the name of a sales price in the specified language. The
        ID of the sales price and the language code must be specified.
      operationId: deleteRestItemsSalesPricesNamesLang
      x-api-path-slug: restitemssales-pricesidnameslang-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: lang
      responses:
        200:
          description: OK
      tags:
      - Sales
      - Price
      - Name
    get:
      summary: Gets a sales price name
      description: Gets the sales price name of a sales price in the specified langauge.
        The ID of the sales price and the language code must be specified.
      operationId: getRestItemsSalesPricesNamesLang
      x-api-path-slug: restitemssales-pricesidnameslang-get
      parameters:
      - in: path
        name: id
      - in: path
        name: lang
      responses:
        200:
          description: OK
      tags:
      - S
      - Sales
      - Price
      - Name
    put:
      summary: Update a sales price name
      description: Updates a sales price name in the specified language. The ID of
        the sales price and the language code must be specified.
      operationId: putRestItemsSalesPricesNamesLang
      x-api-path-slug: restitemssales-pricesidnameslang-put
      parameters:
      - in: body
        name: /rest/items/sales_prices/{id}/names/{lang}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: path
        name: lang
      responses:
        200:
          description: OK
      tags:
      - Sales
      - Price
      - Name
  /rest/items/sales_prices/{id}/online_stores:
    get:
      summary: List activated clients (stores)
      description: Lists all activated clients (stores) for a sales price. The ID
        of the sales price must be specified.
      operationId: getRestItemsSalesPricesOnlineStores
      x-api-path-slug: restitemssales-pricesidonline-stores-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - List
      - Activated
      - Clients
      - (stores)
    post:
      summary: Activate a client (store)
      description: Activates a client (store) for a sales price. The ID of the sales
        price must be specified.
      operationId: postRestItemsSalesPricesOnlineStores
      x-api-path-slug: restitemssales-pricesidonline-stores-post
      parameters:
      - in: body
        name: /rest/items/sales_prices/{id}/online_stores
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Activate
      - Client
      - (store)
  /rest/items/sales_prices/{id}/online_stores/{webstoreId}:
    delete:
      summary: Deactivate a client (store)
      description: Deactivates a client (store) for a sales price. The ID of the sales
        price and the ID of the client (store) must be specified.
      operationId: deleteRestItemsSalesPricesOnlineStoresWebstore
      x-api-path-slug: restitemssales-pricesidonline-storeswebstoreid-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: webstoreId
      responses:
        200:
          description: OK
      tags:
      - Deactivate
      - Client
      - (store)
  /rest/items/sales_prices/{id}/referrers:
    get:
      summary: List activated referrers
      description: Lists all activated referrers for a sales price. The ID of the
        sales price must be specified.
      operationId: getRestItemsSalesPricesReferrers
      x-api-path-slug: restitemssales-pricesidreferrers-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - List
      - Activated
      - Referrers
    post:
      summary: Activate a referrer
      description: Activates a referrer for a sales price. The ID of the sales price
        must be specified.
      operationId: postRestItemsSalesPricesReferrers
      x-api-path-slug: restitemssales-pricesidreferrers-post
      parameters:
      - in: body
        name: /rest/items/sales_prices/{id}/referrers
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Activate
      - Referrer
  /rest/items/sales_prices/{id}/referrers/{referrerId}:
    delete:
      summary: Deactivates a referrer
      description: Deactivates a referrer for a sales price. The ID of the sales price
        and the ID of the referrer must be specified.
      operationId: deleteRestItemsSalesPricesReferrersReferrer
      x-api-path-slug: restitemssales-pricesidreferrersreferrerid-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: referrerId
      responses:
        200:
          description: OK
      tags:
      - Deactivates
      - Referrer
  /rest/items/units:
    get:
      summary: List units
      description: Lists all units.
      operationId: getRestItemsUnits
      x-api-path-slug: restitemsunits-get
      parameters:
      - in: query
        name: updatedAt
        description: Filter restricts the list of results to items updated after the
          specified date
      responses:
        200:
          description: OK
      tags:
      - List
      - Units
    post:
      summary: Create a unit
      description: Creates a unit.
      operationId: postRestItemsUnits
      x-api-path-slug: restitemsunits-post
      parameters:
      - in: body
        name: /rest/items/units
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Unit
  /rest/items/units/{id}:
    delete:
      summary: Delete a unit
      description: Deletes a unit. The ID of the unit must be specified.
      operationId: deleteRestItemsUnits
      x-api-path-slug: restitemsunitsid-delete
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Unit
    get:
      summary: Get a unit
      description: Gets a unit. The ID of the unit must be specified.
      operationId: getRestItemsUnits
      x-api-path-slug: restitemsunitsid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Unit
    put:
      summary: Update a unit
      description: Updates a unit. The ID of the unit must be specified.
      operationId: putRestItemsUnits
      x-api-path-slug: restitemsunitsid-put
      parameters:
      - in: body
        name: /rest/items/units/{id}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Unit
  /rest/items/units/{id}/names:
    get:
      summary: List unit names
      description: Lists the unit names of a unit. The ID of the unit must be specified.
      operationId: getRestItemsUnitsNames
      x-api-path-slug: restitemsunitsidnames-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - List
      - Unit
      - Names
    post:
      summary: Create a unit name
      description: Creates a unit name. The ID of the unit and the language must be
        specified.
      operationId: postRestItemsUnitsNames
      x-api-path-slug: restitemsunitsidnames-post
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Unit
      - Name
  /rest/items/units/{id}/names/{lang}:
    delete:
      summary: Delete a unit name
      description: Deletes a unit name. The ID of the unit and the language must be
        specified.
      operationId: deleteRestItemsUnitsNamesLang
      x-api-path-slug: restitemsunitsidnameslang-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: lang
      responses:
        200:
          description: OK
      tags:
      - Unit
      - Name
    get:
      summary: Get a unit name
      description: Gets a unit name. The ID of the unit and the language must be specified.
      operationId: getRestItemsUnitsNamesLang
      x-api-path-slug: restitemsunitsidnameslang-get
      parameters:
      - in: path
        name: id
      - in: path
        name: lang
      responses:
        200:
          description: OK
      tags:
      - Unit
      - Name
    put:
      summary: Update a unit name
      description: Updates a unit name. The ID of the unit and the language must be
        specified.
      operationId: putRestItemsUnitsNamesLang
      x-api-path-slug: restitemsunitsidnameslang-put
      parameters:
      - in: path
        name: id
      - in: path
        name: lang
      responses:
        200:
          description: OK
      tags:
      - Unit
      - Name
  /rest/items/variations:
    get:
      summary: Search variations
      description: Search variations by different filters
      operationId: getRestItemsVariations
      x-api-path-slug: restitemsvariations-get
      parameters:
      - in: query
        name: barcode
        description: Filter restricts the list of results to variations with the specified
          barcode
      - in: query
        name: categoryId
        description: Filter restricts the list of results to variations with the specified
          category id
      - in: query
        name: createdBetween
        description: Filter restricts the list of results to variations created during
          the specified period
      - in: query
        name: flagOne
        description: Filter restricts the list of results to variations of items with
          the flag one
      - in: query
        name: flagTwo
        description: Filter restricts the list of results to variations of items with
          the flag two
      - in: query
        name: id
        description: Filter restricts the list of results to variations with the specified
          variation ID
      - in: query
        name: isActive
        description: Filter restricts the list of results to variations that are active
      - in: query
        name: isBundle
        description: Filter restricts the list of results to variations to which variations
          were added to create a bundle
      - in: query
        name: isMain
        description: Filter restricts the list of results to variations that are main
          variations
      - in: query
        name: itemId
        description: Filter restricts the list of results to variations with the specified
          item ID
      - in: query
        name: itemName
        description: Filter restricts the list of results to variations with the specified
          item name
      - in: query
        name: itemsPerPage
        description: Limits the number of results listed per page to a specific number
      - in: query
        name: itemTagId
        description: Filter restricts the list of results to variations with the specified
          tag ID
      - in: query
        name: lang
        description: The language of the variation information
      - in: query
        name: manufacturerId
        description: Filter restricts the list of results to variations with the specified
          manufacturer ID
      - in: query
        name: numberExact
        description: Filter restricts the list of results to the variation with the
          variation number specified
      - in: query
        name: numberFuzzy
        description: Filter restricts the list of results to variations with numbers
          that contain the variation number specified (SQL LIKE operator)
      - in: query
        name: page
        description: Limits the results to a specific page
      - in: query
        name: plentyId
        description: Filter restricts the list of results to variations to which variations
          were visible in specific Clients
      - in: query
        name: relatedUpdatedBetween
        description: Filter restricts the list of results to those variations for
          which related information was updated during the specified period
      - in: query
        name: sku
        description: Filter restricts the list of results to variations with the specified
          SKU
      - in: query
        name: storeSpecial
        description: Filter restricts the list of results to variations of items with
          the specified store special
      - in: query
        name: supplierNumber
        description: Filter restricts the list of results to variations with the specified
          supplier number
      - in: query
        name: updatedBetween
        description: Filter restricts the list of results to variations updated during
          the specified period
      - in: query
        name: with
        description: Includes the specified variation information in the results
      responses:
        200:
          description: OK
      tags:
      - Search
      - Variations
  /rest/items/variations/variation_categories:
    post:
      summary: Bulk create category links
      description: Creates up to 50 links between variations and categories. The ID
        of the variations and the ID of the categories must be specified.
      operationId: postRestItemsVariationsVariationCategories
      x-api-path-slug: restitemsvariationsvariation-categories-post
      parameters:
      - in: body
        name: /rest/items/variations/variation_categories
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Bulk
      - Create
      - Category
      - Links
    put:
      summary: Bulk update category links
      description: Updates up to 50 links between variations and categories. The ID
        of the variations and the ID of the categories must be specified.
      operationId: putRestItemsVariationsVariationCategories
      x-api-path-slug: restitemsvariationsvariation-categories-put
      parameters:
      - in: body
        name: /rest/items/variations/variation_categories
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Bulk
      - Update
      - Category
      - Links
  /rest/items/variations/variation_markets:
    get:
      summary: List all links between variations and markets
      description: |-
        Lists all links between variations and markets.
        Results can be filtered by the ID of the variation and by the ID of the market, e.g. "variationId=1030"
        lists all links of the variation with the ID 1030.
      operationId: getRestItemsVariationsVariationMarkets
      x-api-path-slug: restitemsvariationsvariation-markets-get
      responses:
        200:
          description: OK
      tags:
      - List
      - ""
      - Links
      - Between
      - Variations
      - Markets
    post:
      summary: Create up to 50 links between variations and markets
      description: Creates up to 50 links between variations and markets. The ID of
        the variation and the ID of the market must be specified.
      operationId: postRestItemsVariationsVariationMarkets
      x-api-path-slug: restitemsvariationsvariation-markets-post
      parameters:
      - in: body
        name: /rest/items/variations/variation_markets
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Up
      - To
      - "50"
      - Links
      - Between
      - Variations
      - Markets
  /rest/items/variations/variation_properties:
    post:
      summary: Bulk update properties
      description: Creates up to 50 properties of variations.
      operationId: postRestItemsVariationsVariationProperties
      x-api-path-slug: restitemsvariationsvariation-properties-post
      parameters:
      - in: body
        name: /rest/items/variations/variation_properties
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Bulk
      - Update
      - Properties
    put:
      summary: Bulk update properties
      description: Updates up to 50 properties of variations.
      operationId: putRestItemsVariationsVariationProperties
      x-api-path-slug: restitemsvariationsvariation-properties-put
      parameters:
      - in: body
        name: /rest/items/variations/variation_properties
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Bulk
      - Update
      - Properties
  /rest/items/variations/variation_sales_prices:
    get:
      summary: Get all sales price relations
      description: Gets all links between variations and sales prices including sales
        price data.
      operationId: getRestItemsVariationsVariationSalesPrices
      x-api-path-slug: restitemsvariationsvariation-sales-prices-get
      parameters:
      - in: query
        name: salesPriceId
        description: Filter that restricts the search result to the sales price data
          of variations linked to a specific sales price
      - in: query
        name: updatedAt
        description: Filter that restricts the search result to links between variations
          and sales prices updated after a specific point in time
      - in: query
        name: variationId
        description: Filter that restricts the search result to the sales price data
          of a specific variation
      responses:
        200:
          description: OK
      tags:
      - Sales
      - Price
      - Relations
    post:
      summary: Bulk create prices
      description: Creates up to 50 prices of variations. The ID of the variation,
        the ID of the sales price and a price must be specified.
      operationId: postRestItemsVariationsVariationSalesPrices
      x-api-path-slug: restitemsvariationsvariation-sales-prices-post
      parameters:
      - in: body
        name: /rest/items/variations/variation_sales_prices
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Bulk
      - Create
      - Prices
    put:
      summary: Bulk update prices
      description: Updates up to 50 prices of variations. The ID of the variation,
        the ID of the sales price and a price must be specified.
      operationId: putRestItemsVariationsVariationSalesPrices
      x-api-path-slug: restitemsvariationsvariation-sales-prices-put
      parameters:
      - in: body
        name: /rest/items/variations/variation_sales_prices
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Bulk
      - Update
      - Prices
  /rest/items/{id}/images:
    get:
      summary: List images of an item
      description: Lists all images of an item. The item ID must be specified.
      operationId: getRestItemsImages
      x-api-path-slug: restitemsidimages-get
      parameters:
      - in: path
        name: id
      - in: query
        name: updatedAt
        description: Filter restricts the list of results to items updated after the
          specified date
      responses:
        200:
          description: OK
      tags:
      - List
      - Images
      - Of
      - Item
  /rest/items/{id}/images/attribute_value_markets:
    get:
      summary: List attribute value image link
      description: Lists the images linked to an attribute value.
      operationId: getRestItemsImagesAttributeValueMarkets
      x-api-path-slug: restitemsidimagesattribute-value-markets-get
      parameters:
      - in: query
        name: attributeId
        description: The unique ID of the attribute
      - in: path
        name: id
      - in: query
        name: imageId
        description: The unique ID of the image
      - in: query
        name: itemId
        description: The unique ID of the item
      - in: query
        name: valueId
        description: The unique ID of the attribute value
      responses:
        200:
          description: OK
      tags:
      - List
      - Attribute
      - Value
      - Image
      - Link
  /rest/items/{id}/images/upload:
    post:
      summary: Upload a new image
      description: Uploads an image. The item ID must be specified.
      operationId: postRestItemsImagesUpload
      x-api-path-slug: restitemsidimagesupload-post
      parameters:
      - in: body
        name: /rest/items/{id}/images/upload
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Upload
      - New
      - Image
  /rest/items/{id}/images/{imageId}:
    delete:
      summary: Delete an image
      description: Delete an image. The ID of the image must be specified.
      operationId: deleteRestItemsImagesImage
      x-api-path-slug: restitemsidimagesimageid-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: imageId
      responses:
        200:
          description: OK
      tags:
      - Image
    get:
      summary: Get an image
      description: Gets an image. The ID of the image must be specified.
      operationId: getRestItemsImagesImage
      x-api-path-slug: restitemsidimagesimageid-get
      parameters:
      - in: path
        name: id
      - in: path
        name: imageId
      responses:
        200:
          description: OK
      tags:
      - Image
    put:
      summary: Update an image
      description: Updates an image. The ID of the image must be specified.
      operationId: putRestItemsImagesImage
      x-api-path-slug: restitemsidimagesimageid-put
      parameters:
      - in: body
        name: /rest/items/{id}/images/{imageId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: path
        name: imageId
      responses:
        200:
          description: OK
      tags:
      - Image
  /rest/items/{id}/images/{imageId}/attribute_value_markets:
    post:
      summary: Create an attribute value image link
      description: Creates a link between an image and an attribute value.
      operationId: postRestItemsImagesImageAttributeValueMarkets
      x-api-path-slug: restitemsidimagesimageidattribute-value-markets-post
      parameters:
      - in: body
        name: /rest/items/{id}/images/{imageId}/attribute_value_markets
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: path
        name: imageId
      responses:
        200:
          description: OK
      tags:
      - Attribute
      - Value
      - Image
      - Link
  /rest/items/{id}/images/{imageId}/attribute_value_markets/{valueId}:
    delete:
      summary: Delete an attribute value image link
      description: Deletes the link between an image and an attribute value. The attribute
        ID must be specified.
      operationId: deleteRestItemsImagesImageAttributeValueMarketsValue
      x-api-path-slug: restitemsidimagesimageidattribute-value-marketsvalueid-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: imageId
      - in: query
        name: itemId
        description: The unique ID of the item
      - in: path
        name: valueId
      responses:
        200:
          description: OK
      tags:
      - Attribute
      - Value
      - Image
      - Link
    get:
      summary: Get an attribute value image link
      description: 'Gets an attribute value image link. The following IDs must be
        specified: image ID, item ID and value ID.'
      operationId: getRestItemsImagesImageAttributeValueMarketsValue
      x-api-path-slug: restitemsidimagesimageidattribute-value-marketsvalueid-get
      parameters:
      - in: path
        name: id
      - in: path
        name: imageId
      - in: query
        name: itemId
        description: The unique ID of the item
      - in: path
        name: valueId
      responses:
        200:
          description: OK
      tags:
      - Attribute
      - Value
      - Image
      - Link
    put:
      summary: Update an attribute value image link
      description: 'Updates the link between an image and an attribute value. The
        following IDs must be specified: image ID, item ID and value ID.'
      operationId: putRestItemsImagesImageAttributeValueMarketsValue
      x-api-path-slug: restitemsidimagesimageidattribute-value-marketsvalueid-put
      parameters:
      - in: body
        name: /rest/items/{id}/images/{imageId}/attribute_value_markets/{valueId}
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: attributeId
        description: The unique ID of the attribute
      - in: path
        name: id
      - in: path
        name: imageId
      - in: query
        name: itemId
        description: The unique ID of the item
      - in: path
        name: valueId
      responses:
        200:
          description: OK
      tags:
      - Attribute
      - Value
      - Image
      - Link
  /rest/items/{id}/images/{imageId}/availabilities:
    delete:
      summary: Delete an availability
      description: Delete an availability for a specified value.
      operationId: deleteRestItemsImagesImageAvailabilities
      x-api-path-slug: restitemsidimagesimageidavailabilities-delete
      parameters:
      - in: body
        name: /rest/items/{id}/images/{imageId}/availabilities
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: path
        name: imageId
      responses:
        200:
          description: OK
      tags:
      - Availability
    get:
      summary: List availabilities
      description: List all availabilities of an image. The image ID must be specified.
      operationId: getRestItemsImagesImageAvailabilities
      x-api-path-slug: restitemsidimagesimageidavailabilities-get
      parameters:
      - in: path
        name: id
      - in: path
        name: imageId
      responses:
        200:
          description: OK
      tags:
      - List
      - Availabilities
    post:
      summary: Create an availability
      description: Create an availability. The image ID must be specified.
      operationId: postRestItemsImagesImageAvailabilities
      x-api-path-slug: restitemsidimagesimageidavailabilities-post
      parameters:
      - in: body
        name: /rest/items/{id}/images/{imageId}/availabilities
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: path
        name: imageId
      responses:
        200:
          description: OK
      tags:
      - Availability
  /rest/items/{id}/images/{imageId}/names:
    get:
      summary: List names of an image
      description: Lists all names of an image. The image ID must be specified.
      operationId: getRestItemsImagesImageNames
      x-api-path-slug: restitemsidimagesimageidnames-get
      parameters:
      - in: path
        name: id
      - in: path
        name: imageId
      responses:
        200:
          description: OK
      tags:
      - List
      - Names
      - Of
      - Image
    post:
      summary: Create an image name
      description: Create an image name. The ID, language and name of the image must
        be specified.
      operationId: postRestItemsImagesImageNames
      x-api-path-slug: restitemsidimagesimageidnames-post
      parameters:
      - in: body
        name: /rest/items/{id}/images/{imageId}/names
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: path
        name: imageId
      responses:
        200:
          description: OK
      tags:
      - Image
      - Name
  /rest/items/{id}/images/{imageId}/names/{lang}:
    delete:
      summary: Delete an image name
      description: Delete an image name. The ID and language of the image must be
        specified.
      operationId: deleteRestItemsImagesImageNamesLang
      x-api-path-slug: restitemsidimagesimageidnameslang-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: imageId
      - in: path
        name: lang
      responses:
        200:
          description: OK
      tags:
      - Image
      - Name
    get:
      summary: Get an image name
      description: Gets an image name. The image ID and language must be specified.
      operationId: getRestItemsImagesImageNamesLang
      x-api-path-slug: restitemsidimagesimageidnameslang-get
      parameters:
      - in: path
        name: id
      - in: path
        name: imageId
      - in: path
        name: lang
      responses:
        200:
          description: OK
      tags:
      - Image
      - Name
    put:
      summary: Update an image name
      description: Update an image name. The ID, language and name of the image must
        be specified.
      operationId: putRestItemsImagesImageNamesLang
      x-api-path-slug: restitemsidimagesimageidnameslang-put
      parameters:
      - in: body
        name: /rest/items/{id}/images/{imageId}/names/{lang}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: path
        name: imageId
      - in: path
        name: lang
      responses:
        200:
          description: OK
      tags:
      - Image
      - Name
  /rest/items/{id}/images/{imageId}/variation_images:
    get:
      summary: List image links of an image
      description: Lists all variations linked to an image. The image ID must be specified.
      operationId: getRestItemsImagesImageVariationImages
      x-api-path-slug: restitemsidimagesimageidvariation-images-get
      parameters:
      - in: path
        name: id
      - in: path
        name: imageId
      responses:
        200:
          description: OK
      tags:
      - List
      - Image
      - Links
      - Of
      - Image
  /rest/items/{id}/item_cross_selling:
    get:
      summary: List cross-selling links
      description: Lists all cross-selling items linked to an item. The ID of the
        item must be specified.
      operationId: getRestItemsItemCrossSelling
      x-api-path-slug: restitemsiditem-cross-selling-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - List
      - Cross-selling
      - Links
    post:
      summary: Create a cross-selling link
      description: Creates a cross-selling link.
      operationId: postRestItemsItemCrossSelling
      x-api-path-slug: restitemsiditem-cross-selling-post
      parameters:
      - in: body
        name: /rest/items/{id}/item_cross_selling
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Cross-selling
      - Link
  /rest/items/{id}/item_cross_selling/{crossItemId}:
    delete:
      summary: Delete a cross-selling link
      description: Deletes a cross-selling link. The ID of the item and the ID of
        the cross-selling item must be specified.
      operationId: deleteRestItemsItemCrossSellingCrossitem
      x-api-path-slug: restitemsiditem-cross-sellingcrossitemid-delete
      parameters:
      - in: path
        name: crossItemId
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Cross-selling
      - Link
  /rest/items/{id}/variation_images:
    get:
      summary: List image links of an item
      description: Lists all images linked to an item. The item ID must be specified.
      operationId: getRestItemsVariationImages
      x-api-path-slug: restitemsidvariation-images-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - List
      - Image
      - Links
      - Of
      - Item
  /rest/items/{id}/variations/{variationId}/descriptions:
    get:
      summary: List texts
      description: Lists the texts for an item in all available languages. The ID
        of the variation must be specified.
      operationId: getRestItemsVariationsVariationDescriptions
      x-api-path-slug: restitemsidvariationsvariationiddescriptions-get
      parameters:
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - List
      - Texts
    post:
      summary: Create texts
      description: Creates texts for an item. The ID of the variation and the language
        code must be specified.
      operationId: postRestItemsVariationsVariationDescriptions
      x-api-path-slug: restitemsidvariationsvariationiddescriptions-post
      parameters:
      - in: body
        name: /rest/items/{id}/variations/{variationId}/descriptions
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Texts
  /rest/items/{id}/variations/{variationId}/descriptions/{lang}:
    delete:
      summary: Delete texts
      description: Deletes texts for an item in the specified language. The ID of
        the variation and the language code must be specified.
      operationId: deleteRestItemsVariationsVariationDescriptionsLang
      x-api-path-slug: restitemsidvariationsvariationiddescriptionslang-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: lang
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Texts
    get:
      summary: Get texts
      description: Gets the texts for an item in the specified language. The ID of
        the variation and the language code must be specified.
      operationId: getRestItemsVariationsVariationDescriptionsLang
      x-api-path-slug: restitemsidvariationsvariationiddescriptionslang-get
      parameters:
      - in: path
        name: id
      - in: path
        name: lang
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Texts
    put:
      summary: Update texts
      description: Updates texts for an item in the specified language. The ID of
        the variation and the language code must be specified.
      operationId: putRestItemsVariationsVariationDescriptionsLang
      x-api-path-slug: restitemsidvariationsvariationiddescriptionslang-put
      parameters:
      - in: body
        name: /rest/items/{id}/variations/{variationId}/descriptions/{lang}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: path
        name: lang
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Texts
  /rest/items/{id}/variations/{variationId}/images:
    get:
      summary: List images of a variation
      description: Lists all images of a variation. The variation ID must be specified.
      operationId: getRestItemsVariationsVariationImages
      x-api-path-slug: restitemsidvariationsvariationidimages-get
      parameters:
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - List
      - Images
      - Of
      - Variation
  /rest/items/{id}/variations/{variationId}/labels:
    post:
      summary: Get a variation label
      description: Gets a base64 encoded label for the specified variation ID. The
        labelId of the label template must be specified.
      operationId: postRestItemsVariationsVariationLabels
      x-api-path-slug: restitemsidvariationsvariationidlabels-post
      parameters:
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Variation
      - Label
  /rest/items/{id}/variations/{variationId}/market_ident_numbers:
    get:
      summary: List ident number of a variation
      description: Lists the ident number (ASIN/ePID) of a variation. The ID of the
        item and the ID of the variation must be specified.
      operationId: getRestItemsVariationsVariationMarketEntNumbers
      x-api-path-slug: restitemsidvariationsvariationidmarket-ident-numbers-get
      parameters:
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - List
      - Ident
      - Number
      - Of
      - Variation
    post:
      summary: Create a market ident number
      description: Creates a market ident number (ASIN/ePID) for a variation.
      operationId: postRestItemsVariationsVariationMarketEntNumbers
      x-api-path-slug: restitemsidvariationsvariationidmarket-ident-numbers-post
      parameters:
      - in: body
        name: /rest/items/{id}/variations/{variationId}/market_ident_numbers
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Market
      - Ident
      - Number
  /rest/items/{id}/variations/{variationId}/market_ident_numbers/{marketIdentNumberId}:
    delete:
      summary: Deletes a market ident number
      description: Deletes a market ident number (ASIN/ePID) of a variation.
      operationId: deleteRestItemsVariationsVariationMarketEntNumbersMarketentnumber
      x-api-path-slug: restitemsidvariationsvariationidmarket-ident-numbersmarketidentnumberid-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: marketIdentNumberId
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - S
      - Market
      - Ident
      - Number
    get:
      summary: Get a market ident number
      description: Gets a market ident number (ASIN/ePID) of a variation.
      operationId: getRestItemsVariationsVariationMarketEntNumbersMarketentnumber
      x-api-path-slug: restitemsidvariationsvariationidmarket-ident-numbersmarketidentnumberid-get
      parameters:
      - in: path
        name: id
      - in: path
        name: marketIdentNumberId
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Market
      - Ident
      - Number
    put:
      summary: Updates a market ident number
      description: Updates a market ident number (ASIN/ePID) of a variation.
      operationId: putRestItemsVariationsVariationMarketEntNumbersMarketentnumber
      x-api-path-slug: restitemsidvariationsvariationidmarket-ident-numbersmarketidentnumberid-put
      parameters:
      - in: body
        name: /rest/items/{id}/variations/{variationId}/market_ident_numbers/{marketIdentNumberId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: path
        name: marketIdentNumberId
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - S
      - Market
      - Ident
      - Number
  /rest/items/{id}/variations/{variationId}/stock:
    get:
      summary: List stock of a variation per warehouse
      description: Lists stock of a variation per warehouse. The ID of the item and
        the ID of the variation must be specified.
      operationId: getRestItemsVariationsVariationStock
      x-api-path-slug: restitemsidvariationsvariationidstock-get
      parameters:
      - in: query
        name: columns
        description: The properties to be loaded
      - in: path
        name: id
      - in: query
        name: itemId
        description: The ID of the item
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - List
      - Stock
      - Of
      - Variation
      - Per
      - Warehouse
  /rest/items/{id}/variations/{variationId}/stock/bookIncomingItems:
    put:
      summary: Book incoming stock
      description: Books incoming stock for a variation. The incoming stock will be
        added to the existing stock. The ID of the item and the ID of the variation
        must be specified.
      operationId: putRestItemsVariationsVariationStockBookincomingitems
      x-api-path-slug: restitemsidvariationsvariationidstockbookincomingitems-put
      parameters:
      - in: body
        name: /rest/items/{id}/variations/{variationId}/stock/bookIncomingItems
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: query
        name: itemId
        description: The ID of the item
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Book
      - Incoming
      - Stock
  /rest/items/{id}/variations/{variationId}/stock/correction:
    put:
      summary: Correct stock
      description: Corrects stock. The item ID and the variation ID must be specified.
      operationId: putRestItemsVariationsVariationStockCorrection
      x-api-path-slug: restitemsidvariationsvariationidstockcorrection-put
      parameters:
      - in: body
        name: /rest/items/{id}/variations/{variationId}/stock/correction
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: query
        name: itemId
        description: The ID of the item
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Correct
      - Stock
  /rest/items/{id}/variations/{variationId}/stock/movements:
    get:
      summary: List stock movements
      description: |-
        Lists stock movements for a variation. The ID of the item and the ID of the variation must be specified. To get movements older than 3 months, set the 'year' parameter.
        NOTE: You can either get archive entries or non-archive entries. You can not get entries for the current year that are younger and older than 3 months with one request. You need separate requests to get entries older and younger than 3 months. To get all entries younger than 3 month you do not need to specify a year or any createdAt parameter.
      operationId: getRestItemsVariationsVariationStockMovements
      x-api-path-slug: restitemsidvariationsvariationidstockmovements-get
      parameters:
      - in: query
        name: columns
        description: The properties to be loaded
      - in: query
        name: createdAtFrom
        description: Get entries with createdAt date after this date
      - in: query
        name: createdAtTo
        description: Get entries with createdAt date before this date
      - in: path
        name: id
      - in: query
        name: itemId
        description: The ID of the item
      - in: query
        name: itemsPerPage
        description: The number of items per page
      - in: query
        name: page
        description: The requested page
      - in: path
        name: variationId
      - in: query
        name: warehouseId
        description: The ID of the warehouse
      - in: query
        name: year
        description: Get entries from the archive for the given year
      responses:
        200:
          description: OK
      tags:
      - List
      - Stock
      - Movements
  /rest/items/{id}/variations/{variationId}/stock/redistribute:
    put:
      summary: Redistribute stock
      description: Redistributes the stock of one storage location among one or more
        storage locations. The item ID and the variation ID need to be specified.
      operationId: putRestItemsVariationsVariationStockRedistribute
      x-api-path-slug: restitemsidvariationsvariationidstockredistribute-put
      parameters:
      - in: body
        name: /rest/items/{id}/variations/{variationId}/stock/redistribute
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: query
        name: itemId
        description: The ID of the item
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Redistribute
      - Stock
  /rest/items/{id}/variations/{variationId}/stock/storageLocations:
    get:
      summary: List stock of a variation per storage locations
      description: Lists stock of a variation per storage location. The ID of the
        item and the ID of the variation must be specified.
      operationId: getRestItemsVariationsVariationStockStoragelocations
      x-api-path-slug: restitemsidvariationsvariationidstockstoragelocations-get
      parameters:
      - in: query
        name: columns
        description: The properties to be loaded
      - in: path
        name: id
      - in: query
        name: itemId
        description: The ID of the item
      - in: query
        name: itemsPerPage
        description: The number of items per page
      - in: query
        name: page
        description: The requested page
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - List
      - Stock
      - Of
      - Variation
      - Per
      - Storage
      - Locations
  /rest/items/{id}/variations/{variationId}/variation_additional_skus:
    get:
      summary: List additional SKUs
      description: Lists the additional SKUs of a variation. Filters must be specified.
      operationId: getRestItemsVariationsVariationVariationAdditionalSkus
      x-api-path-slug: restitemsidvariationsvariationidvariation-additional-skus-get
      parameters:
      - in: body
        name: /rest/items/{id}/variations/{variationId}/variation_additional_skus
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - List
      - Additional
      - SKUs
    post:
      summary: Create an additional SKU
      description: Creates an additional SKU. The ID of the variation must be specified.
      operationId: postRestItemsVariationsVariationVariationAdditionalSkus
      x-api-path-slug: restitemsidvariationsvariationidvariation-additional-skus-post
      parameters:
      - in: body
        name: /rest/items/{id}/variations/{variationId}/variation_additional_skus
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Additional
      - SKU
  /rest/items/{id}/variations/{variationId}/variation_additional_skus/{additionalSkuId}:
    delete:
      summary: Delete an additional SKU
      description: Deletes an additional SKU. The ID of the additional SKU must be
        specified.
      operationId: deleteRestItemsVariationsVariationVariationAdditionalSkusAdditionalsku
      x-api-path-slug: restitemsidvariationsvariationidvariation-additional-skusadditionalskuid-delete
      parameters:
      - in: path
        name: additionalSkuId
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Additional
      - SKU
    get:
      summary: Gets an additional SKU
      description: Gets an additional SKU. The ID of the additional SKU must be specified.
      operationId: getRestItemsVariationsVariationVariationAdditionalSkusAdditionalsku
      x-api-path-slug: restitemsidvariationsvariationidvariation-additional-skusadditionalskuid-get
      parameters:
      - in: path
        name: additionalSkuId
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - S
      - Additional
      - SKU
    put:
      summary: Update an additional SKU
      description: Updates an additional SKU. The ID of the additional SKU must be
        specified.
      operationId: putRestItemsVariationsVariationVariationAdditionalSkusAdditionalsku
      x-api-path-slug: restitemsidvariationsvariationidvariation-additional-skusadditionalskuid-put
      parameters:
      - in: body
        name: /rest/items/{id}/variations/{variationId}/variation_additional_skus/{additionalSkuId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: additionalSkuId
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Additional
      - SKU
  /rest/items/{id}/variations/{variationId}/variation_barcodes:
    get:
      summary: List variation barcodes
      description: Lists all barcodes of a variation. The ID of the item and the ID
        of the variation must be specified.
      operationId: getRestItemsVariationsVariationVariationBarcodes
      x-api-path-slug: restitemsidvariationsvariationidvariation-barcodes-get
      parameters:
      - in: path
        name: id
      - in: path
        name: variationId
      - in: query
        name: with
        description: Includes the specified variation barcode information in the results
      responses:
        200:
          description: OK
      tags:
      - List
      - Variation
      - Barcodes
    post:
      summary: Create a variation barcode
      description: Creates a variation barcode. The ID of the item, the ID of the
        variation, the ID of the barcode and the code must be specified.
      operationId: postRestItemsVariationsVariationVariationBarcodes
      x-api-path-slug: restitemsidvariationsvariationidvariation-barcodes-post
      parameters:
      - in: body
        name: /rest/items/{id}/variations/{variationId}/variation_barcodes
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Variation
      - Barcode
  /rest/items/{id}/variations/{variationId}/variation_barcodes/{barcodeId}:
    delete:
      summary: Delete a variation barcode
      description: Deletes a variation barcode. Unlinks the barcode from the variation
        and deletes the code saved for the variation.
      operationId: deleteRestItemsVariationsVariationVariationBarcodesBarcode
      x-api-path-slug: restitemsidvariationsvariationidvariation-barcodesbarcodeid-delete
      parameters:
      - in: path
        name: barcodeId
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Variation
      - Barcode
    get:
      summary: Get a variation barcode
      description: Get a specific variation barcode. The ID of the item, the ID of
        the variation and the ID of the barcode must be specified.
      operationId: getRestItemsVariationsVariationVariationBarcodesBarcode
      x-api-path-slug: restitemsidvariationsvariationidvariation-barcodesbarcodeid-get
      parameters:
      - in: path
        name: barcodeId
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Variation
      - Barcode
    put:
      summary: Update a variation barcode
      description: Updates a variation barcode. The ID of the item, the ID of the
        variation, the ID of the barcode and the code must be specified.
      operationId: putRestItemsVariationsVariationVariationBarcodesBarcode
      x-api-path-slug: restitemsidvariationsvariationidvariation-barcodesbarcodeid-put
      parameters:
      - in: body
        name: /rest/items/{id}/variations/{variationId}/variation_barcodes/{barcodeId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: barcodeId
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Variation
      - Barcode
  /rest/items/{id}/variations/{variationId}/variation_bundles:
    get:
      summary: List bundle components
      description: List all components of a bundle. The ID of the item and the ID
        of the variation to which bundle components were added must be specified.
      operationId: getRestItemsVariationsVariationVariationBundles
      x-api-path-slug: restitemsidvariationsvariationidvariation-bundles-get
      parameters:
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - List
      - Bundle
      - Components
    post:
      summary: Add a variation to a bundle
      description: Adds a variation to a bundle variation as a bundle component.
      operationId: postRestItemsVariationsVariationVariationBundles
      x-api-path-slug: restitemsidvariationsvariationidvariation-bundles-post
      parameters:
      - in: body
        name: /rest/items/{id}/variations/{variationId}/variation_bundles
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Variation
      - To
      - Bundle
  /rest/items/{id}/variations/{variationId}/variation_bundles/{bundleId}:
    delete:
      summary: Remove a bundle component
      description: Removes a component from a bundle. The bundle ID must be specified.
      operationId: deleteRestItemsVariationsVariationVariationBundlesBundle
      x-api-path-slug: restitemsidvariationsvariationidvariation-bundlesbundleid-delete
      parameters:
      - in: path
        name: bundleId
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Remove
      - Bundle
      - Component
    get:
      summary: Get a variation bundle
      description: Gets the bundle information for a specific bundle component.
      operationId: getRestItemsVariationsVariationVariationBundlesBundle
      x-api-path-slug: restitemsidvariationsvariationidvariation-bundlesbundleid-get
      parameters:
      - in: path
        name: bundleId
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Variation
      - Bundle
    put:
      summary: Update a variation bundle
      description: Updates a variation bundle component.
      operationId: putRestItemsVariationsVariationVariationBundlesBundle
      x-api-path-slug: restitemsidvariationsvariationidvariation-bundlesbundleid-put
      parameters:
      - in: body
        name: /rest/items/{id}/variations/{variationId}/variation_bundles/{bundleId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: bundleId
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Variation
      - Bundle
  /rest/items/{id}/variations/{variationId}/variation_categories:
    get:
      summary: List categories linked to a variation
      description: Lists all categories linked to a variation.
      operationId: getRestItemsVariationsVariationVariationCategories
      x-api-path-slug: restitemsidvariationsvariationidvariation-categories-get
      parameters:
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - List
      - Categories
      - Linked
      - To
      - Variation
    post:
      summary: Link a category to a variation
      description: Creates a link between a category and a variation.
      operationId: postRestItemsVariationsVariationVariationCategories
      x-api-path-slug: restitemsidvariationsvariationidvariation-categories-post
      parameters:
      - in: body
        name: /rest/items/{id}/variations/{variationId}/variation_categories
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Link
      - Category
      - To
      - Variation
  /rest/items/{id}/variations/{variationId}/variation_categories/{catId}:
    delete:
      summary: Remove a category from a variation
      description: Deletes the link between a category and a variation.
      operationId: deleteRestItemsVariationsVariationVariationCategoriesCat
      x-api-path-slug: restitemsidvariationsvariationidvariation-categoriescatid-delete
      parameters:
      - in: path
        name: catId
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Remove
      - Category
      - From
      - Variation
    get:
      summary: Get link between category and variation
      description: Gets the link between a category and a variation.
      operationId: getRestItemsVariationsVariationVariationCategoriesCat
      x-api-path-slug: restitemsidvariationsvariationidvariation-categoriescatid-get
      parameters:
      - in: path
        name: catId
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Link
      - Between
      - Category
      - Variation
    put:
      summary: Update variation category link
      description: Updates the link between a category and a variation.
      operationId: putRestItemsVariationsVariationVariationCategoriesCat
      x-api-path-slug: restitemsidvariationsvariationidvariation-categoriescatid-put
      parameters:
      - in: body
        name: /rest/items/{id}/variations/{variationId}/variation_categories/{catId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: catId
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Variation
      - Category
      - Link
  /rest/items/{id}/variations/{variationId}/variation_clients:
    get:
      summary: List clients linked to a variation
      description: Lists all clients (stores) linked to a variation. The ID of the
        variation must be specified.
      operationId: getRestItemsVariationsVariationVariationClients
      x-api-path-slug: restitemsidvariationsvariationidvariation-clients-get
      parameters:
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - List
      - Clients
      - Linked
      - To
      - Variation
    post:
      summary: Link a client to a variation
      description: Creates a link between a client (store) and a variation.
      operationId: postRestItemsVariationsVariationVariationClients
      x-api-path-slug: restitemsidvariationsvariationidvariation-clients-post
      parameters:
      - in: body
        name: /rest/items/{id}/variations/{variationId}/variation_clients
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Link
      - Client
      - To
      - Variation
  /rest/items/{id}/variations/{variationId}/variation_clients/{plentyId}:
    delete:
      summary: Unlink a client from a variation
      description: Deletes the link between a client (store) and a variation.
      operationId: deleteRestItemsVariationsVariationVariationClientsPlenty
      x-api-path-slug: restitemsidvariationsvariationidvariation-clientsplentyid-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: plentyId
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Unlink
      - Client
      - From
      - Variation
  /rest/items/{id}/variations/{variationId}/variation_default_categories:
    get:
      summary: List default category links
      description: Lists the default category of a variation for all clients (stores).
        The ID of the item and the ID of the variation must be specified.
      operationId: getRestItemsVariationsVariationVariationDefaultCategories
      x-api-path-slug: restitemsidvariationsvariationidvariation-default-categories-get
      parameters:
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - List
      - Default
      - Category
      - Links
    post:
      summary: Create a default category link
      description: Creates a link between a variation and a category that designates
        the category as the default category.
      operationId: postRestItemsVariationsVariationVariationDefaultCategories
      x-api-path-slug: restitemsidvariationsvariationidvariation-default-categories-post
      parameters:
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Default
      - Category
      - Link
  /rest/items/{id}/variations/{variationId}/variation_default_categories/{plentyId}:
    delete:
      summary: Delete a default category link
      description: Deletes a link between a variation and a category that designates
        this category as the default category.
      operationId: deleteRestItemsVariationsVariationVariationDefaultCategoriesPlenty
      x-api-path-slug: restitemsidvariationsvariationidvariation-default-categoriesplentyid-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: plentyId
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Default
      - Category
      - Link
    get:
      summary: Gets a default category link
      description: Gets the default category linked to a variation for the specified
        client (store). The ID of the item, the ID of the variation and the ID of
        the client (store) must be specified.
      operationId: getRestItemsVariationsVariationVariationDefaultCategoriesPlenty
      x-api-path-slug: restitemsidvariationsvariationidvariation-default-categoriesplentyid-get
      parameters:
      - in: path
        name: id
      - in: path
        name: plentyId
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - S
      - Default
      - Category
      - Link
  /rest/items/{id}/variations/{variationId}/variation_images:
    get:
      summary: List image links of a variation
      description: Lists all images linked to a variation. The variation ID must be
        specified.
      operationId: getRestItemsVariationsVariationVariationImages
      x-api-path-slug: restitemsidvariationsvariationidvariation-images-get
      parameters:
      - in: path
        name: id
      - in: query
        name: updatedAt
        description: Filter restricts the list of results to variation images updated
          after the specified date
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - List
      - Image
      - Links
      - Of
      - Variation
    post:
      summary: Create an image link
      description: Creates a link between an image and a variation.
      operationId: postRestItemsVariationsVariationVariationImages
      x-api-path-slug: restitemsidvariationsvariationidvariation-images-post
      parameters:
      - in: body
        name: /rest/items/{id}/variations/{variationId}/variation_images
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Image
      - Link
  /rest/items/{id}/variations/{variationId}/variation_images/{imageId}:
    delete:
      summary: Delete an image link
      description: Deletes a link between an image and a variation.
      operationId: deleteRestItemsVariationsVariationVariationImagesImage
      x-api-path-slug: restitemsidvariationsvariationidvariation-imagesimageid-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: imageId
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Image
      - Link
  /rest/items/{id}/variations/{variationId}/variation_markets:
    delete:
      summary: Delete all market links of one variation
      description: Deletes all links of one variation. The ID of the variation must
        be specified.
      operationId: deleteRestItemsVariationsVariationVariationMarkets
      x-api-path-slug: restitemsidvariationsvariationidvariation-markets-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Market
      - Links
      - Of
      - Variation
    get:
      summary: List markets linked to a variation
      description: Lists all markets linked to a variation. The ID of the item and
        the ID of the variation must be specified.
      operationId: getRestItemsVariationsVariationVariationMarkets
      x-api-path-slug: restitemsidvariationsvariationidvariation-markets-get
      parameters:
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - List
      - Markets
      - Linked
      - To
      - Variation
    post:
      summary: Create link between variation and market
      description: Creates a link between a variation and a market. The ID of the
        item, the ID of the variation and the ID of the market must be specified.
      operationId: postRestItemsVariationsVariationVariationMarkets
      x-api-path-slug: restitemsidvariationsvariationidvariation-markets-post
      parameters:
      - in: body
        name: /rest/items/{id}/variations/{variationId}/variation_markets
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Link
      - Between
      - Variation
      - Market
  /rest/items/{id}/variations/{variationId}/variation_markets/{marketplaceId}:
    delete:
      summary: Delete link between variation and market
      description: Deletes a link between a variation and a market. The ID of the
        item, the ID of the variation and the ID of the market must be specified.
      operationId: deleteRestItemsVariationsVariationVariationMarketsMarketplace
      x-api-path-slug: restitemsidvariationsvariationidvariation-marketsmarketplaceid-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: marketplaceId
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Link
      - Between
      - Variation
      - Market
  /rest/items/{id}/variations/{variationId}/variation_properties:
    delete:
      summary: Deletes all links between a variation and its property values
      description: Deletes all links between a variation and its property values.
        The ID of the variation must be specified.
      operationId: deleteRestItemsVariationsVariationVariationProperties
      x-api-path-slug: restitemsidvariationsvariationidvariation-properties-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - S
      - ""
      - Links
      - Between
      - Variation
      - Its
      - Property
      - Values
    get:
      summary: List property values linked to a variation
      description: Lists the property values linked to a variation. The ID of the
        item and the ID of the variation must be specified.
      operationId: getRestItemsVariationsVariationVariationProperties
      x-api-path-slug: restitemsidvariationsvariationidvariation-properties-get
      parameters:
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - List
      - Property
      - Values
      - Linked
      - To
      - Variation
    post:
      summary: Create link between variation and property value
      description: Creates a link between a variation and a property value.
      operationId: postRestItemsVariationsVariationVariationProperties
      x-api-path-slug: restitemsidvariationsvariationidvariation-properties-post
      parameters:
      - in: body
        name: /rest/items/{id}/variations/{variationId}/variation_properties
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Link
      - Between
      - Variation
      - Property
      - Value
  /rest/items/{id}/variations/{variationId}/variation_properties/{propertyId}:
    delete:
      summary: Delete link between variation and property value
      description: Delete a link between a variation and a property value. The ID
        of the item, the ID of the variation and the ID of the property must be specified.
      operationId: deleteRestItemsVariationsVariationVariationPropertiesProperty
      x-api-path-slug: restitemsidvariationsvariationidvariation-propertiespropertyid-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: propertyId
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Link
      - Between
      - Variation
      - Property
      - Value
    get:
      summary: Get a property value
      description: Gets a property value linked to a variation.
      operationId: getRestItemsVariationsVariationVariationPropertiesProperty
      x-api-path-slug: restitemsidvariationsvariationidvariation-propertiespropertyid-get
      parameters:
      - in: path
        name: id
      - in: path
        name: propertyId
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Property
      - Value
    put:
      summary: Update a property value
      description: Update the data of a property value linked to a variation.
      operationId: putRestItemsVariationsVariationVariationPropertiesProperty
      x-api-path-slug: restitemsidvariationsvariationidvariation-propertiespropertyid-put
      parameters:
      - in: body
        name: /rest/items/{id}/variations/{variationId}/variation_properties/{propertyId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: path
        name: propertyId
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Property
      - Value
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