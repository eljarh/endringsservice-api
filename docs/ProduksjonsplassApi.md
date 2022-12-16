# \ProduksjonsplassApi

All URIs are relative to *https://raw.githubusercontent.com/eljarh/api-spec/main/https*

Method | HTTP request | Description
------------- | ------------- | -------------
[**PostProduksjonsplass**](ProduksjonsplassApi.md#PostProduksjonsplass) | **Post** /produksjonsplass | les inn en produksjonsplass



## PostProduksjonsplass

> Produksjonsplass PostProduksjonsplass(ctx).Produksjonsplass(produksjonsplass).Execute()

les inn en produksjonsplass



### Example

```go
package main

import (
    "context"
    "fmt"
    "os"
    openapiclient "./openapi"
)

func main() {
    produksjonsplass := *openapiclient.NewProduksjonsplass("123123", "1") // Produksjonsplass | 

    configuration := openapiclient.NewConfiguration()
    apiClient := openapiclient.NewAPIClient(configuration)
    resp, r, err := apiClient.ProduksjonsplassApi.PostProduksjonsplass(context.Background()).Produksjonsplass(produksjonsplass).Execute()
    if err != nil {
        fmt.Fprintf(os.Stderr, "Error when calling `ProduksjonsplassApi.PostProduksjonsplass``: %v\n", err)
        fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
    }
    // response from `PostProduksjonsplass`: Produksjonsplass
    fmt.Fprintf(os.Stdout, "Response from `ProduksjonsplassApi.PostProduksjonsplass`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPostProduksjonsplassRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **produksjonsplass** | [**Produksjonsplass**](Produksjonsplass.md) |  | 

### Return type

[**Produksjonsplass**](Produksjonsplass.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

