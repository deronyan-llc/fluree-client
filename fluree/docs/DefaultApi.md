# \DefaultApi

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**FlureeCreatePost**](DefaultApi.md#FlureeCreatePost) | **Post** /fluree/create | Endpoint for creating new ledgers
[**FlureeHistoryGet**](DefaultApi.md#FlureeHistoryGet) | **Get** /fluree/history | Endpoint for submitting history queries
[**FlureeHistoryPost**](DefaultApi.md#FlureeHistoryPost) | **Post** /fluree/history | Endpoint for submitting history queries
[**FlureeQueryGet**](DefaultApi.md#FlureeQueryGet) | **Get** /fluree/query | Endpoint for submitting queries
[**FlureeQueryPost**](DefaultApi.md#FlureeQueryPost) | **Post** /fluree/query | Endpoint for submitting queries
[**FlureeRemoteResourcePost**](DefaultApi.md#FlureeRemoteResourcePost) | **Post** /fluree/remoteResource | Remote connection resource read
[**FlureeTransactPost**](DefaultApi.md#FlureeTransactPost) | **Post** /fluree/transact | Endpoint for submitting transactions


# **FlureeCreatePost**
> map[string]interface{} FlureeCreatePost(ctx, body)
Endpoint for creating new ledgers

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | **interface{}**|  | 

### Return type

**map[string]interface{}**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json, application/sparql-query, application/transit+msgpack, application/transit+json, application/edn
 - **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **FlureeHistoryGet**
> []interface{} FlureeHistoryGet(ctx, body)
Endpoint for submitting history queries

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | **interface{}**|  | 

### Return type

**[]interface{}**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json, application/sparql-query, application/transit+msgpack, application/transit+json, application/edn
 - **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **FlureeHistoryPost**
> []interface{} FlureeHistoryPost(ctx, body)
Endpoint for submitting history queries

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | **interface{}**|  | 

### Return type

**[]interface{}**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json, application/sparql-query, application/transit+msgpack, application/transit+json, application/edn
 - **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **FlureeQueryGet**
> interface{} FlureeQueryGet(ctx, body)
Endpoint for submitting queries

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**Body**](Body.md)|  | 

### Return type

**interface{}**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json, application/sparql-query, application/transit+msgpack, application/transit+json, application/edn
 - **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **FlureeQueryPost**
> interface{} FlureeQueryPost(ctx, body)
Endpoint for submitting queries

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | [**Body1**](Body1.md)|  | 

### Return type

**interface{}**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json, application/sparql-query, application/transit+msgpack, application/transit+json, application/edn
 - **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **FlureeRemoteResourcePost**
> FlureeRemoteResourcePost(ctx, body)
Remote connection resource read

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | **interface{}**|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json, application/sparql-query, application/transit+msgpack, application/transit+json, application/edn
 - **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **FlureeTransactPost**
> map[string]interface{} FlureeTransactPost(ctx, body)
Endpoint for submitting transactions

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **body** | **interface{}**|  | 

### Return type

**map[string]interface{}**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json, application/sparql-query, application/transit+msgpack, application/transit+json, application/edn
 - **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

