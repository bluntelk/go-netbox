# CreateAvailablePrefixRequest

## Properties

 Name             | Type                                                                                           | Description                                               | Notes      
------------------|------------------------------------------------------------------------------------------------|-----------------------------------------------------------|------------
 **PrefixLength** | **int32**                                                                                      |                                                           |
 **ScopeType**    | Pointer to **NullableString**                                                                  |                                                           | [optional] 
 **ScopeId**      | Pointer to **NullableInt32**                                                                   |                                                           | [optional] 
 **Tenant**       | Pointer to [**NullableASNRangeRequestTenant**](ASNRangeRequestTenant.md)                       |                                                           | [optional] 
 **Vlan**         | Pointer to [**NullableBulkInterfaceRequestUntaggedVlan**](BulkInterfaceRequestUntaggedVlan.md) |                                                           | [optional] 
 **Status**       | Pointer to [**BulkPrefixRequestStatus**](BulkPrefixRequestStatus.md)                           |                                                           | [optional] 
 **Role**         | Pointer to [**NullableASNRequestRole**](ASNRequestRole.md)                                     |                                                           | [optional] 
 **IsPool**       | Pointer to **bool**                                                                            | All IP addresses within this prefix are considered usable | [optional] 
 **MarkUtilized** | Pointer to **bool**                                                                            | Treat as fully utilized                                   | [optional] 
 **Description**  | Pointer to **string**                                                                          |                                                           | [optional] 
 **Owner**        | Pointer to [**NullableASNRangeRequestOwner**](ASNRangeRequestOwner.md)                         |                                                           | [optional] 
 **Comments**     | Pointer to **string**                                                                          |                                                           | [optional] 
 **Tags**         | Pointer to [**[]NestedTagRequest**](NestedTagRequest.md)                                       |                                                           | [optional] 
 **CustomFields** | Pointer to **map[string]interface{}**                                                          |                                                           | [optional] 

## Methods

### NewCreateAvailablePrefixRequest

`func NewCreateAvailablePrefixRequest(prefixLength int32, ) *CreateAvailablePrefixRequest`

NewCreateAvailablePrefixRequest instantiates a new CreateAvailablePrefixRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateAvailablePrefixRequestWithDefaults

`func NewCreateAvailablePrefixRequestWithDefaults() *CreateAvailablePrefixRequest`

NewCreateAvailablePrefixRequestWithDefaults instantiates a new CreateAvailablePrefixRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPrefixLength

`func (o *CreateAvailablePrefixRequest) GetPrefixLength() int32`

GetPrefixLength returns the PrefixLength field if non-nil, zero value otherwise.

### GetPrefixLengthOk

`func (o *CreateAvailablePrefixRequest) GetPrefixLengthOk() (*int32, bool)`

GetPrefixLengthOk returns a tuple with the PrefixLength field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrefixLength

`func (o *CreateAvailablePrefixRequest) SetPrefixLength(v int32)`

SetPrefixLength sets PrefixLength field to given value.

### GetScopeType

`func (o *CreateAvailablePrefixRequest) GetScopeType() string`

GetScopeType returns the ScopeType field if non-nil, zero value otherwise.

### GetScopeTypeOk

`func (o *CreateAvailablePrefixRequest) GetScopeTypeOk() (*string, bool)`

GetScopeTypeOk returns a tuple with the ScopeType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScopeType

`func (o *CreateAvailablePrefixRequest) SetScopeType(v string)`

SetScopeType sets ScopeType field to given value.

### HasScopeType

`func (o *CreateAvailablePrefixRequest) HasScopeType() bool`

HasScopeType returns a boolean if a field has been set.

### SetScopeTypeNil

`func (o *CreateAvailablePrefixRequest) SetScopeTypeNil(b bool)`

SetScopeTypeNil sets the value for ScopeType to be an explicit nil

### UnsetScopeType

`func (o *CreateAvailablePrefixRequest) UnsetScopeType()`

UnsetScopeType ensures that no value is present for ScopeType, not even an explicit nil

### GetScopeId

`func (o *CreateAvailablePrefixRequest) GetScopeId() int32`

GetScopeId returns the ScopeId field if non-nil, zero value otherwise.

### GetScopeIdOk

`func (o *CreateAvailablePrefixRequest) GetScopeIdOk() (*int32, bool)`

GetScopeIdOk returns a tuple with the ScopeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScopeId

`func (o *CreateAvailablePrefixRequest) SetScopeId(v int32)`

SetScopeId sets ScopeId field to given value.

### HasScopeId

`func (o *CreateAvailablePrefixRequest) HasScopeId() bool`

HasScopeId returns a boolean if a field has been set.

### SetScopeIdNil

`func (o *CreateAvailablePrefixRequest) SetScopeIdNil(b bool)`

SetScopeIdNil sets the value for ScopeId to be an explicit nil

### UnsetScopeId

`func (o *CreateAvailablePrefixRequest) UnsetScopeId()`

UnsetScopeId ensures that no value is present for ScopeId, not even an explicit nil

### GetTenant

`func (o *CreateAvailablePrefixRequest) GetTenant() ASNRangeRequestTenant`

GetTenant returns the Tenant field if non-nil, zero value otherwise.

### GetTenantOk

`func (o *CreateAvailablePrefixRequest) GetTenantOk() (*ASNRangeRequestTenant, bool)`

GetTenantOk returns a tuple with the Tenant field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenant

`func (o *CreateAvailablePrefixRequest) SetTenant(v ASNRangeRequestTenant)`

SetTenant sets Tenant field to given value.

### HasTenant

`func (o *CreateAvailablePrefixRequest) HasTenant() bool`

HasTenant returns a boolean if a field has been set.

### SetTenantNil

`func (o *CreateAvailablePrefixRequest) SetTenantNil(b bool)`

SetTenantNil sets the value for Tenant to be an explicit nil

### UnsetTenant

`func (o *CreateAvailablePrefixRequest) UnsetTenant()`

UnsetTenant ensures that no value is present for Tenant, not even an explicit nil

### GetVlan

`func (o *CreateAvailablePrefixRequest) GetVlan() BulkInterfaceRequestUntaggedVlan`

GetVlan returns the Vlan field if non-nil, zero value otherwise.

### GetVlanOk

`func (o *CreateAvailablePrefixRequest) GetVlanOk() (*BulkInterfaceRequestUntaggedVlan, bool)`

GetVlanOk returns a tuple with the Vlan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVlan

`func (o *CreateAvailablePrefixRequest) SetVlan(v BulkInterfaceRequestUntaggedVlan)`

SetVlan sets Vlan field to given value.

### HasVlan

`func (o *CreateAvailablePrefixRequest) HasVlan() bool`

HasVlan returns a boolean if a field has been set.

### SetVlanNil

`func (o *CreateAvailablePrefixRequest) SetVlanNil(b bool)`

SetVlanNil sets the value for Vlan to be an explicit nil

### UnsetVlan

`func (o *CreateAvailablePrefixRequest) UnsetVlan()`

UnsetVlan ensures that no value is present for Vlan, not even an explicit nil

### GetStatus

`func (o *CreateAvailablePrefixRequest) GetStatus() BulkPrefixRequestStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CreateAvailablePrefixRequest) GetStatusOk() (*BulkPrefixRequestStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CreateAvailablePrefixRequest) SetStatus(v BulkPrefixRequestStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *CreateAvailablePrefixRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetRole

`func (o *CreateAvailablePrefixRequest) GetRole() ASNRequestRole`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *CreateAvailablePrefixRequest) GetRoleOk() (*ASNRequestRole, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *CreateAvailablePrefixRequest) SetRole(v ASNRequestRole)`

SetRole sets Role field to given value.

### HasRole

`func (o *CreateAvailablePrefixRequest) HasRole() bool`

HasRole returns a boolean if a field has been set.

### SetRoleNil

`func (o *CreateAvailablePrefixRequest) SetRoleNil(b bool)`

SetRoleNil sets the value for Role to be an explicit nil

### UnsetRole

`func (o *CreateAvailablePrefixRequest) UnsetRole()`

UnsetRole ensures that no value is present for Role, not even an explicit nil

### GetIsPool

`func (o *CreateAvailablePrefixRequest) GetIsPool() bool`

GetIsPool returns the IsPool field if non-nil, zero value otherwise.

### GetIsPoolOk

`func (o *CreateAvailablePrefixRequest) GetIsPoolOk() (*bool, bool)`

GetIsPoolOk returns a tuple with the IsPool field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsPool

`func (o *CreateAvailablePrefixRequest) SetIsPool(v bool)`

SetIsPool sets IsPool field to given value.

### HasIsPool

`func (o *CreateAvailablePrefixRequest) HasIsPool() bool`

HasIsPool returns a boolean if a field has been set.

### GetMarkUtilized

`func (o *CreateAvailablePrefixRequest) GetMarkUtilized() bool`

GetMarkUtilized returns the MarkUtilized field if non-nil, zero value otherwise.

### GetMarkUtilizedOk

`func (o *CreateAvailablePrefixRequest) GetMarkUtilizedOk() (*bool, bool)`

GetMarkUtilizedOk returns a tuple with the MarkUtilized field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMarkUtilized

`func (o *CreateAvailablePrefixRequest) SetMarkUtilized(v bool)`

SetMarkUtilized sets MarkUtilized field to given value.

### HasMarkUtilized

`func (o *CreateAvailablePrefixRequest) HasMarkUtilized() bool`

HasMarkUtilized returns a boolean if a field has been set.

### GetDescription

`func (o *CreateAvailablePrefixRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateAvailablePrefixRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateAvailablePrefixRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CreateAvailablePrefixRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetOwner

`func (o *CreateAvailablePrefixRequest) GetOwner() ASNRangeRequestOwner`

GetOwner returns the Owner field if non-nil, zero value otherwise.

### GetOwnerOk

`func (o *CreateAvailablePrefixRequest) GetOwnerOk() (*ASNRangeRequestOwner, bool)`

GetOwnerOk returns a tuple with the Owner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwner

`func (o *CreateAvailablePrefixRequest) SetOwner(v ASNRangeRequestOwner)`

SetOwner sets Owner field to given value.

### HasOwner

`func (o *CreateAvailablePrefixRequest) HasOwner() bool`

HasOwner returns a boolean if a field has been set.

### SetOwnerNil

`func (o *CreateAvailablePrefixRequest) SetOwnerNil(b bool)`

SetOwnerNil sets the value for Owner to be an explicit nil

### UnsetOwner

`func (o *CreateAvailablePrefixRequest) UnsetOwner()`

UnsetOwner ensures that no value is present for Owner, not even an explicit nil

### GetComments

`func (o *CreateAvailablePrefixRequest) GetComments() string`

GetComments returns the Comments field if non-nil, zero value otherwise.

### GetCommentsOk

`func (o *CreateAvailablePrefixRequest) GetCommentsOk() (*string, bool)`

GetCommentsOk returns a tuple with the Comments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComments

`func (o *CreateAvailablePrefixRequest) SetComments(v string)`

SetComments sets Comments field to given value.

### HasComments

`func (o *CreateAvailablePrefixRequest) HasComments() bool`

HasComments returns a boolean if a field has been set.

### GetTags

`func (o *CreateAvailablePrefixRequest) GetTags() []NestedTagRequest`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *CreateAvailablePrefixRequest) GetTagsOk() (*[]NestedTagRequest, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *CreateAvailablePrefixRequest) SetTags(v []NestedTagRequest)`

SetTags sets Tags field to given value.

### HasTags

`func (o *CreateAvailablePrefixRequest) HasTags() bool`

HasTags returns a boolean if a field has been set.

### GetCustomFields

`func (o *CreateAvailablePrefixRequest) GetCustomFields() map[string]interface{}`

GetCustomFields returns the CustomFields field if non-nil, zero value otherwise.

### GetCustomFieldsOk

`func (o *CreateAvailablePrefixRequest) GetCustomFieldsOk() (*map[string]interface{}, bool)`

GetCustomFieldsOk returns a tuple with the CustomFields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomFields

`func (o *CreateAvailablePrefixRequest) SetCustomFields(v map[string]interface{})`

SetCustomFields sets CustomFields field to given value.

### HasCustomFields

`func (o *CreateAvailablePrefixRequest) HasCustomFields() bool`

HasCustomFields returns a boolean if a field has been set.

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


