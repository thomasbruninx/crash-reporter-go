# InstanceQueryResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Items** | [**[]InstanceOut**](InstanceOut.md) |  | 
**Total** | **int32** |  | 
**Page** | **int32** |  | 
**Resultsperpage** | **int32** |  | 

## Methods

### NewInstanceQueryResponse

`func NewInstanceQueryResponse(items []InstanceOut, total int32, page int32, resultsperpage int32, ) *InstanceQueryResponse`

NewInstanceQueryResponse instantiates a new InstanceQueryResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInstanceQueryResponseWithDefaults

`func NewInstanceQueryResponseWithDefaults() *InstanceQueryResponse`

NewInstanceQueryResponseWithDefaults instantiates a new InstanceQueryResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetItems

`func (o *InstanceQueryResponse) GetItems() []InstanceOut`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *InstanceQueryResponse) GetItemsOk() (*[]InstanceOut, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *InstanceQueryResponse) SetItems(v []InstanceOut)`

SetItems sets Items field to given value.


### GetTotal

`func (o *InstanceQueryResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *InstanceQueryResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *InstanceQueryResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetPage

`func (o *InstanceQueryResponse) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *InstanceQueryResponse) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *InstanceQueryResponse) SetPage(v int32)`

SetPage sets Page field to given value.


### GetResultsperpage

`func (o *InstanceQueryResponse) GetResultsperpage() int32`

GetResultsperpage returns the Resultsperpage field if non-nil, zero value otherwise.

### GetResultsperpageOk

`func (o *InstanceQueryResponse) GetResultsperpageOk() (*int32, bool)`

GetResultsperpageOk returns a tuple with the Resultsperpage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResultsperpage

`func (o *InstanceQueryResponse) SetResultsperpage(v int32)`

SetResultsperpage sets Resultsperpage field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


