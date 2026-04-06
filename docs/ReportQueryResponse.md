# ReportQueryResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Items** | [**[]ReportOut**](ReportOut.md) |  | 
**Total** | **int32** |  | 
**Page** | **int32** |  | 
**Resultsperpage** | **int32** |  | 

## Methods

### NewReportQueryResponse

`func NewReportQueryResponse(items []ReportOut, total int32, page int32, resultsperpage int32, ) *ReportQueryResponse`

NewReportQueryResponse instantiates a new ReportQueryResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReportQueryResponseWithDefaults

`func NewReportQueryResponseWithDefaults() *ReportQueryResponse`

NewReportQueryResponseWithDefaults instantiates a new ReportQueryResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetItems

`func (o *ReportQueryResponse) GetItems() []ReportOut`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *ReportQueryResponse) GetItemsOk() (*[]ReportOut, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *ReportQueryResponse) SetItems(v []ReportOut)`

SetItems sets Items field to given value.


### GetTotal

`func (o *ReportQueryResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *ReportQueryResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *ReportQueryResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetPage

`func (o *ReportQueryResponse) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *ReportQueryResponse) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *ReportQueryResponse) SetPage(v int32)`

SetPage sets Page field to given value.


### GetResultsperpage

`func (o *ReportQueryResponse) GetResultsperpage() int32`

GetResultsperpage returns the Resultsperpage field if non-nil, zero value otherwise.

### GetResultsperpageOk

`func (o *ReportQueryResponse) GetResultsperpageOk() (*int32, bool)`

GetResultsperpageOk returns a tuple with the Resultsperpage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResultsperpage

`func (o *ReportQueryResponse) SetResultsperpage(v int32)`

SetResultsperpage sets Resultsperpage field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


