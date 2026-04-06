# \DefaultAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateInstanceApiV1InstancePost**](DefaultAPI.md#CreateInstanceApiV1InstancePost) | **Post** /api/v1/instance | Create Instance
[**CreateReportApiV1ReportPost**](DefaultAPI.md#CreateReportApiV1ReportPost) | **Post** /api/v1/report | Create Report



## CreateInstanceApiV1InstancePost

> InstanceCreateResponse CreateInstanceApiV1InstancePost(ctx).InstanceCreate(instanceCreate).Execute()

Create Instance

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/crash-reporter/crash-reporter-go"
)

func main() {
	instanceCreate := *openapiclient.NewInstanceCreate("ProjectId_example") // InstanceCreate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.CreateInstanceApiV1InstancePost(context.Background()).InstanceCreate(instanceCreate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.CreateInstanceApiV1InstancePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateInstanceApiV1InstancePost`: InstanceCreateResponse
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.CreateInstanceApiV1InstancePost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateInstanceApiV1InstancePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **instanceCreate** | [**InstanceCreate**](InstanceCreate.md) |  | 

### Return type

[**InstanceCreateResponse**](InstanceCreateResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateReportApiV1ReportPost

> ReportOut CreateReportApiV1ReportPost(ctx).ReportCreate(reportCreate).Execute()

Create Report

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/crash-reporter/crash-reporter-go"
)

func main() {
	reportCreate := *openapiclient.NewReportCreate("InstanceUuid_example", "Severity_example") // ReportCreate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.CreateReportApiV1ReportPost(context.Background()).ReportCreate(reportCreate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.CreateReportApiV1ReportPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateReportApiV1ReportPost`: ReportOut
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.CreateReportApiV1ReportPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateReportApiV1ReportPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **reportCreate** | [**ReportCreate**](ReportCreate.md) |  | 

### Return type

[**ReportOut**](ReportOut.md)

### Authorization

[HTTPBearer](../README.md#HTTPBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

