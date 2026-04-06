# ReportOut

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | **string** |  | 
**ProjectUuid** | **string** |  | 
**InstanceUuid** | **string** |  | 
**Timestamp** | **time.Time** |  | 
**Severity** | **string** |  | 
**Metadata** | **map[string]interface{}** |  | 

## Methods

### NewReportOut

`func NewReportOut(uuid string, projectUuid string, instanceUuid string, timestamp time.Time, severity string, metadata map[string]interface{}, ) *ReportOut`

NewReportOut instantiates a new ReportOut object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReportOutWithDefaults

`func NewReportOutWithDefaults() *ReportOut`

NewReportOutWithDefaults instantiates a new ReportOut object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *ReportOut) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *ReportOut) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *ReportOut) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetProjectUuid

`func (o *ReportOut) GetProjectUuid() string`

GetProjectUuid returns the ProjectUuid field if non-nil, zero value otherwise.

### GetProjectUuidOk

`func (o *ReportOut) GetProjectUuidOk() (*string, bool)`

GetProjectUuidOk returns a tuple with the ProjectUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectUuid

`func (o *ReportOut) SetProjectUuid(v string)`

SetProjectUuid sets ProjectUuid field to given value.


### GetInstanceUuid

`func (o *ReportOut) GetInstanceUuid() string`

GetInstanceUuid returns the InstanceUuid field if non-nil, zero value otherwise.

### GetInstanceUuidOk

`func (o *ReportOut) GetInstanceUuidOk() (*string, bool)`

GetInstanceUuidOk returns a tuple with the InstanceUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstanceUuid

`func (o *ReportOut) SetInstanceUuid(v string)`

SetInstanceUuid sets InstanceUuid field to given value.


### GetTimestamp

`func (o *ReportOut) GetTimestamp() time.Time`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *ReportOut) GetTimestampOk() (*time.Time, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *ReportOut) SetTimestamp(v time.Time)`

SetTimestamp sets Timestamp field to given value.


### GetSeverity

`func (o *ReportOut) GetSeverity() string`

GetSeverity returns the Severity field if non-nil, zero value otherwise.

### GetSeverityOk

`func (o *ReportOut) GetSeverityOk() (*string, bool)`

GetSeverityOk returns a tuple with the Severity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverity

`func (o *ReportOut) SetSeverity(v string)`

SetSeverity sets Severity field to given value.


### GetMetadata

`func (o *ReportOut) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *ReportOut) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *ReportOut) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


