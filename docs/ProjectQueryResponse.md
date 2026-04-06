# ProjectQueryResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Items** | [**[]ProjectOut**](ProjectOut.md) |  | 
**Total** | **int32** |  | 
**Page** | **int32** |  | 
**Resultsperpage** | **int32** |  | 

## Methods

### NewProjectQueryResponse

`func NewProjectQueryResponse(items []ProjectOut, total int32, page int32, resultsperpage int32, ) *ProjectQueryResponse`

NewProjectQueryResponse instantiates a new ProjectQueryResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectQueryResponseWithDefaults

`func NewProjectQueryResponseWithDefaults() *ProjectQueryResponse`

NewProjectQueryResponseWithDefaults instantiates a new ProjectQueryResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetItems

`func (o *ProjectQueryResponse) GetItems() []ProjectOut`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *ProjectQueryResponse) GetItemsOk() (*[]ProjectOut, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *ProjectQueryResponse) SetItems(v []ProjectOut)`

SetItems sets Items field to given value.


### GetTotal

`func (o *ProjectQueryResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *ProjectQueryResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *ProjectQueryResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetPage

`func (o *ProjectQueryResponse) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *ProjectQueryResponse) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *ProjectQueryResponse) SetPage(v int32)`

SetPage sets Page field to given value.


### GetResultsperpage

`func (o *ProjectQueryResponse) GetResultsperpage() int32`

GetResultsperpage returns the Resultsperpage field if non-nil, zero value otherwise.

### GetResultsperpageOk

`func (o *ProjectQueryResponse) GetResultsperpageOk() (*int32, bool)`

GetResultsperpageOk returns a tuple with the Resultsperpage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResultsperpage

`func (o *ProjectQueryResponse) SetResultsperpage(v int32)`

SetResultsperpage sets Resultsperpage field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


