---
title: Feilkoder 
description: Feilkoder i Altinn
weight: 900
---

{{< figure src="/docs/images/guides/tjenesteeier/feilkoder.png" title="">}}


|**Feilkode**||**Beskrivelse (eng)**|
|--------|--------|--------|
|**Common Error Codes 1 – 1000**||
|    GeneralError                    |    0      |     Denotes a general error                  |
|    NullObjectReference             |    1      |     Denotes an error caused by a   null reference                   |
|    MissingRight                    |    14     |     Authorization error - Subject   does not have required right    |
|    HookActivationFailed            |    90     |     Error given when hook   activation fails                        |
|    IncorrectLevel                  |    17     |     User is not authenticated on   the correct level                |
|    RequiresLevel1                  |    18     |     Requires   level 1                                              |
|    RequiresLevel2                  |    19     |     Requires   level 2                                              |
|    RequiresLevel3                  |    20     |     Requires   level 3                                              |
|    RequiresLevel4                  |    21     |     Requires   level 4                                              |
|    ExternalSystemAuthentication    |    989    |    External system authentication failed|
|**Common Error Codes 10000 - 20000**|||
|AccessDenied|10000| Database error - Access denied|
|**Hook Error Codes 20001 - 21000**|||
|ServiceCannotBeStarted|20001| Hook error - Service cannot be started|
|ServiceCannotBeStartedForCurrentReporte |20002 | Hook error - Service cannot be started for the current reportee|
|NoValidSubscriptionData |20003||
|NoValidReporteeAgeAndStatus |20004||
|**TUL Error Codes 21001 - 23000**||
|    ServiceEditionCodeAlreadyExists         |    21001     |     TUL Error - Service edition   code exists already                                   |
|    FileNotFound                            |    21002     |     TUL Error - File not found                                                          |
|    DataAreaTypeNotFound                    |    21003     |     TUL Error - Data area type not   found                                              |
|    RootNodeNotFound                        |    21004     |     TUL Error - Root node not found                                                     |
|    DoesNotExists                           |    21005     |     TUL Error - (something) does   not exist                                            |
|    NotImpersonatedOrAuthorised             |    21006     |     TUL Error - User is not   impersonated or authorized                                |
|    EntrySiteDoesNotExists                  |    21007     |     TUL Error - Entry site does not   exist                                             |
|    IDZeroORNegative                        |    21008     |     TUL Error - ID is zero or   negative                                                |
|    ServiceEditionInProduction              |    21009     |     TUL Error - Service edition is   already in production                              |
|    RequiredFieldNotSupplied                |    210010    |     TUL Error - Required field is   not supplied                                        |
|    CannotBeNull                            |    210011    |     TUL Error - (something) cannot   be null                                            |
|    UserNotAuthorized                       |    210012    |     TUL Error - User is not   authorized                                                |
|    IncorrectClientConfiguration            |    210013    |     TUL Error - Incorrect client   configuration                                        |
|    IncorrecctArguement                     |    210014    |     TUL   Error - Incorrect argument                                                    |
|    GetDeploymentPackagesFailed             |    210015    |     TUL   Error - GetDeploymentPackages failed                                          |
|    GetDeploymentPackageFailed              |    210016    |     TUL   Error - GetDeploymentPackage failed                                           |
|    ServiceEditionValidationFailed          |    210017    |     TUL Error - Service edition   validation failed                                     |
|    DeploymentPackageCreationFailed         |    210018    |     TUL Error - Deployment package   creation failed                                    |
|    ServiceEditionMigrationFailed           |    210019    |     TUL Error - Service edition   migration failed                                      |
|    UnableToReachSBLService                 |    210020    |     TUL Error - Unable to reach SBL   service                                           |
|    CallToSBLWCFOperationFailed             |    210021    |     TUL Error - Call to SBL WCF   operation failed                                      |
|    UnexpectedErrorDuringMigration          |    210022    |     TUL Error - Unexpected error   during migration                                     |
|    ValueNotDefinedInEnum                   |    210023    |     TUL Error - Value is not   defined in enum                                          |
|    BEObjectCannotBeNull                    |    210024    |     TUL Error - Business Entity   object cannot be null                                 |
|    XsdNotFoundOrXsnNotUploaded             |    22985     |     TUL Error - XSD not found or   XSN not uploaded                                     |
|    ServiceDoesNotExist                     |    22986     |     TUL Error - Service does not   exist                                                |
|    ServiceHasAlreadyBeenDeleted            |    22987     |     TUL Error - Service has already   been deleted                                      |
|    ServiceEditionHasAlreadyBeenDeleted     |    22988     |     TUL Error - Service edition has   already been deleted                              |
|    ServiceEditionHasBeenDeleted            |    22989     |     TUL Error - Service edition has   been deleted                                      |
|    ServiceHasBeenDeleted                   |    22990     |     TUL Error - Service has been   deleted                                              |
|    ServiceOwnerUrlAlreadyExists            |    22991     |     TUL Error - Service owner URL   already exists                                      |
|    UserDoesNotHaveRightsToCreateSites      |    22992     |     TUL Error - User does not have   rights to create sites                             |
|    UnexpectedErrorInRetrievingGuid         |    22993     |     TUL Error - Unexpected error in   retrieving GUID                                   |
|    DataRetrievalFailed                     |    22994     |     TUL Error - Data retrieval   failed                                                 |
|    UnexpectedErrorInSettingStatus          |    22995     |     TUL Error - Unexpected error in   setting status                                    |
|    SiteCreationFailed                      |    22996     |     TUL Error - Site creation   failed                                                  |
|    SuppliedGuidIsNullOrEmpty               |    22997     |     TUL Error - Supplied GUID is null   or empty                                        |
|    DuplicateXsdInFormSet                   |    22998     |     TUL Error - Duplicate XSD in   formset                                              |
|    ServiceShortNameExists                  |    22999     |     TUL Error - Service short name   already exists                                     |
|    ServiceEditionShortNameAlreadyExists    |    210025    |     TUL Error - Service edition   short name already exists                             |
|    ServiceCodeAlreadyExists                |    210026    |     TUL Error - Service code   already exists                                           |
|    SpecificationDataMissing                |    210027    |     TUL Error - Specification data   missing                                            |
|    NoAuthorizationRulesDefined             |    210028    |     TUL Error - No authorization   rules have been defined for this service edition.    |
|    RoleNameAreadyExists                    |    210029    |     TUL Error - No authorization   rules have been defined for this service edition.    |
|    SBLOperationTimedOut                    |    210030    |    TUL Error - Migration timed out
|**Integration Error Codes 30001 - 31000**||
|    NotAuthorizedForReportee        |    30001    |     Integration error - Not   authorized for reportee        |
|    NotAuthorizedForSignature       |    30002    |     Integration error - Not   authorized for signature       |
|    NotAValidService                |    30003    |     Integration error - Not a valid   service                |
|    ArgumentNullException           |    30004    |     Integration error - Argument is   null                   |
|    NotAValidServiceOwnerCode       |    30005    |     Integration error - Not a valid   service owner code     |
|    InValidServiceEditionVersion    |    30006    |     Integration error - Invalid   service edition version    |
|    FileNotExist                    |    30007    |     Integration error - File does not   exist                |
|**SBL External Error Codes 40001 - 41000**||
|    LanguageCodeCannotBeNull                |    40001    |     SBL External error - Language   code cannot be null                  |
|    MessageBodyCannotBeNull                 |    40002    |     SBL External error - Message   body cannot be null                   |
|    MessageTitleCannotBeNull                |    40003    |     SBL External error - Message   title cannot be null                  |
|    MessageSummaryCannotBeNull              |    40004    |     SBL External error - Message   summary cannot be null                |
|    ExternalReferenceCannotBeNull           |    40005    |     SBL External error - External   reference cannot be null             |
|    ExternalServiceCodeCannotBeNull         |    40006    |     SBL External error - External   service code cannot be null          |
|    ReporteeCannotBeNull                    |    40007    |     SBL External error - Reportee   cannot be null                       |
|    SystemUserCodeCannotBeNull              |    40008    |     SBL External error - System   user code cannot be null               |
|    CorrespondenceCanNotBeDeleted           |    40009    |     SBL External error -   Correspondence cannot be deleted              |
|    ElementCanNotBeDeleted                  |    40010    |     SBL External error - Element   cannot be deleted                     |
|    PersonHasStrictlyConfidentialAddress    |    40011    |     SBL External error - Person has   strictly confidential address      |
|    FormDataIsNotValid                      |    40012    |     SBL External error - Form data   is not valid                        |
|    ServiceIsNotValid                       |    40013    |     SBL External error - Service is   not valid                          |
|    InValidNumberOfReceipents               |    40014    |     SBL External error - Invalid   number of receipients                 |
|    InvalidFormatSmsAndEmail                |    40015    |     SBL External error - Invalid   SMS                                   |
|    InvalidSSN                              |    40016    |     SBL External error - Invalid   SSN                                   |
|    ReceiverAddressNull                     |    40017    |     No   receiver address                                                |
|    ControlWorkflowSentComplete             |    40018    |     Control   Workflow Sent Complete                                     |
|    InvalidServiceType                      |    40019    |     Invalid   Service Type                                               |
|    InvalidEmailAddressForFromAddress       |    40020    |    The From Address must be skipped or contain a valid email address.    |
|**Authorization Error Codes 50001 - 51000**||
|    DelegateRolesBEInputInvalid                |    50001    |     This error code is used when the   party a user wants to delegate a role or right to, does not exist.                                                             |
|    GeoLocationIsMandatory                     |    50002    |     This is used when geo location   has not been supplied                                                                                                            |
|    InvalidGeoLocation                         |    50003    |     This is used when geo location   format is not correct                                                                                                            |
|    CoveredByUserIDRequired                    |    50004    |     This is used when delegation   type is SSN,UserName and CoveredByUserID has not been supplied                                                                     |
|    CoveredByPartyIDRequired                   |    50005    |     This is used when delegation   type is Organization and CoveredByPartyID has not been supplied                                                                    |
|    CannotDelegateToEnterpriseCertifiedUser    |    50006    |    This is used when roles or rights of an enterprise/user not   represented by an enterprise certified user is being delegated to an   enterprise certified user.    |
|    CannotDelegateANonDelegatableRole          |    50007    |     This is used when someone is   trying to delegate a non-delegatable role                                                                                          |
|    InvalidOrgNumber                           |    50008    |     When the OrgNo is not proper or   does not exist                                                                                                                  |
|    InvalidUserDetails                         |    50009    |     When the SSN or Last Name or   UserName are not valid or a user with the combination does not exist                                                               |
|    UserDoesNotHaveProfessionalConsent         |    50010    |     When user does not have   professional consent                                                                                                                    |
|    InvalidGeoLocationFormat                   |    50011    |     Geo location is in incorrect   format                                                                                                                             |
|    CannotDelegateDenyOnOtherResources         |    50012    |     Cannot delegate Deny type right   on resources other than reporteeElement.                                                                                        |
|    RoleTypeNameNotUnique                      |    50013    |     RoleTypeName is not unique                                                                                                                                        |
|    RoleTypeBeenDelegated                      |    50014    |     RoleType   has been Delegated                                                                                                                                     |
|    RoleTypeLanguagesNotValid                  |    50015    |     RoleTypeLanguagesNotValid                                                                                                                                         |
|    DeleteRolesAndRightsFailure                |    50016    |     DeleteRolesAndRightsFailure                                                                                                                                       |
|    SelfDelegationIsNotAllowed                 |    50017    |     Delegation to self is not   allowed                                                                                                                               |
|    RoleTypeCodeNotMigrated                    |    50018    |     RoleTypeCodeNotMigrated                                                                                                                                           |
|    ResourceHasNoRule                          |    50019    |     RuleHasNoRight |
|    **Collaboration Service Error Codes 60001 - 70001**    |             |                                                                                       |
|    InvalidCaseID                                                                     |    60001    |     Invalid   Case ID                                                                 |
|    InvalidCaseIdentifier                                                             |    60002    |     Invalid Service Code and   Service Edition Code Combination and Invalid CaseID    |
|    InvalidLanguage                                                                   |    60003    |     Invalid   Language ID                                                             |
|    ExceededCharacterLimit                                                            |    60004    |     Character Limit Exceeded.                                                         |
|    InvalidReporteeElement                                                            |    60005    |     Invalid   Reportee Element                                                        |
|    UnarchivedCorrespondenceException                                                 |    60006    |     For correspondences services   which have not been archived                       |
|    UnarchivedReportingServicesException                                              |    60007    |     For Form Task services which   have not been archived                             |
|    ReporteeElementInAnotherCase                                                      |    60008    |     For Reportee element is already   associated to another case                      |
|    InvalidServiceInCollaborationServiceSet                                           |    60009    |     For A Service, not available in   Collaboration Service Set                       |
|    InvalidReporteeID                                                                 |    60010    |     Invalid   Reportee ID                                                             |
|    InvalidNoticeTemplateID                                                           |    60011    |     Invalid   NoticeTemplateID                                                        |
|    InvalidReporteeNumber                                                             |    60012    |     Mandatory ReporteeNumber                                                          |
|    ArchivedOrDeletedCaseID                                                           |    60013    |     Case is already archived or   deleted                                             |
|    ArchivedCaseID                                                                    |    60014    |    Case is archived.So no processing allowed.                                         |
|    DeletedCaseID                                                                     |    60015    |    Case is Deleted. So no processing allowed.                                         |
|    InvalidElement                                                                    |    60016    |    The element is unavailable.                                                        |
|    UnassociatedElement                                                               |    60017    |    The element is not associated with any Case.                                       |
|    DeletedElement                                                                    |    60018    |    The element is deleted.                                                            |
|    ArchivedElement                                                                   |    60019    |    The element is archived.                                                           |
|    InvalidNoticeTokenID                                                              |    60020    |    Invalid notice Token                                                               |
|    InvalidNoticeTokenValue                                                           |    60021    |    Invalid notice Token Value                                                         |
|    InvalidEventIdentifier                                                            |    60022    |    Invalid Event Identifiers                                                          |
|    InvalidEventName                                                                  |    60023    |    Invalid Event Name                                                                 |
|    UnauthorizedServiceOwner                                                          |    60024    |    Service Owner is unauthorized                                                      |
|    MissingNoticeTokens                                                               |    60025    |    Missing Notice Tokens                                                              |
|    WorkFlowValidationException                                                       |    60026    |    Received WorkFlow Exception                                                        |
|    WorkFlowInitiationException                                                       |    60027    |    Workflow Initiation Exception                                                      |
|    MissingWorkflowInstance                                                           |    60028    |    Missing Workflow Instance                                                          |
|    WorkFlowGenericException                                                          |    60029    |    WorkFlow Generic Exception                                                         |
|    EventDeliveryFailed                                                               |    60030    |    Event Delivery Failed                                                              |
|    MissingEventName                                                                  |    60031    |    Missing Event Name                                                                 |
|    UnavailableStateMachineEvents                                                     |    60032    |    Unavailable State Machine Events                                                   |
|    **SMDI Error Codes - 70001 - 80001**    |             | |
|    IncorrectService                                                 |    70001    |     Incorrect service details                                              |
|    IncorrectWorkFlow                                                |    70002    |     Incorrect process work flow   details                                  |
|    IncorrectServiceEditionVersion                                   |    70003    |     Incorrect Service Edition   Version details                            |
|    IncorrectEventHook                                               |    70004    |     Incorrect Event Hook details                                           |
|    IncorrectReportingService                                        |    70005    |     Incorrect Reporting Service details                                    |
|    IncorrectCorrespondenceService                                   |    70006    |     Incorrect Correspondence Service details                               |
|    IncorrectLookupService                                           |    70007    |     Incorrect Lookup Service details                                       |
|    IncorrectCollaborationReUse                                      |    70008    |     Incorrect Collaboration Service   - ReUseData details                  |
|    IncorrectFormset                                                 |    70009    |     Incorrect Form Set details                                             |
|    IncorrectLogicalForm                                             |    70010    |     Incorrect Form Set details                                             |
|    IncorrectSplitData                                               |    70011    |     Incorrect Split of data details                                        |
|    IncorrectTranslation                                             |    70012    |     Incorrect Translation details                                          |
|    IncorrectDeployForm                                              |    70013    |     Incorrect FormTemplate uploaded                                        |
|    IncorrectSecurity                                                |    70014    |     Incorrect Roles & Rights details                                       |
|    IncorrectCollaborationServices                                   |    70015    |     Incorrect Collaboration Service   - ServicesInCollaboration details    |
|    IncorrectCollaborationStateMachine                               |    70016    |     Incorrect Collaboration Service   - StateMachine details               |
|    IncorrectStyleSheet                                              |    70017    |     Incorrect StyleSheet details                                           |
|    IncorrectPIImages                                                |    70018    |     Incorrect StyleSheet - Images details                                  |
|    IncorrectPI                                                      |    70019    |     Incorrect PI details |