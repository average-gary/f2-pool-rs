# \DefaultApi

All URIs are relative to *https://api.f2pool.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**v2_assets_balance_post**](DefaultApi.md#v2_assets_balance_post) | **POST** /v2/assets/balance | Fetch current user's asset details
[**v2_assets_settle_mode_switch_post**](DefaultApi.md#v2_assets_settle_mode_switch_post) | **POST** /v2/assets/settle_mode/switch | Switch settlement mode
[**v2_assets_transactions_list_post**](DefaultApi.md#v2_assets_transactions_list_post) | **POST** /v2/assets/transactions/list | Fetch bill list
[**v2_blocks_date_range_post**](DefaultApi.md#v2_blocks_date_range_post) | **POST** /v2/blocks/date_range | Get blocks list within a date range
[**v2_blocks_paging_post**](DefaultApi.md#v2_blocks_paging_post) | **POST** /v2/blocks/paging | Get blocks list with pagination
[**v2_hash_rate_distribute_post**](DefaultApi.md#v2_hash_rate_distribute_post) | **POST** /v2/hash_rate/distribute | Distribute hashrate to an f2pool account
[**v2_hash_rate_distribution_info_post**](DefaultApi.md#v2_hash_rate_distribution_info_post) | **POST** /v2/hash_rate/distribution/info | Hashrate distribution information
[**v2_hash_rate_distribution_orders_post**](DefaultApi.md#v2_hash_rate_distribution_orders_post) | **POST** /v2/hash_rate/distribution/orders | List of all orders of hashrate distribution
[**v2_hash_rate_distribution_settlements_post**](DefaultApi.md#v2_hash_rate_distribution_settlements_post) | **POST** /v2/hash_rate/distribution/settlements | List of all settlements of hashrate distribution
[**v2_hash_rate_distribution_terminate_post**](DefaultApi.md#v2_hash_rate_distribution_terminate_post) | **POST** /v2/hash_rate/distribution/terminate | Terminate hashrate distribution order
[**v2_hash_rate_history_post**](DefaultApi.md#v2_hash_rate_history_post) | **POST** /v2/hash_rate/history | Fetch hashrate historical data
[**v2_hash_rate_info_list_post**](DefaultApi.md#v2_hash_rate_info_list_post) | **POST** /v2/hash_rate/info_list | Fetch hashrate information of multiple accounts
[**v2_hash_rate_info_post**](DefaultApi.md#v2_hash_rate_info_post) | **POST** /v2/hash_rate/info | Fetch hashrate information
[**v2_hash_rate_worker_history_post**](DefaultApi.md#v2_hash_rate_worker_history_post) | **POST** /v2/hash_rate/worker/history | Fetch hashrate historical data of a worker
[**v2_hash_rate_worker_list_post**](DefaultApi.md#v2_hash_rate_worker_list_post) | **POST** /v2/hash_rate/worker/list | Fetch worker list
[**v2_mining_user_add_post**](DefaultApi.md#v2_mining_user_add_post) | **POST** /v2/mining_user/add | Add new mining account
[**v2_mining_user_balance_withdraw_post**](DefaultApi.md#v2_mining_user_balance_withdraw_post) | **POST** /v2/mining_user/balance/withdraw | Manual withdrawal
[**v2_mining_user_get_post**](DefaultApi.md#v2_mining_user_get_post) | **POST** /v2/mining_user/get | Fetch account information
[**v2_mining_user_list_post**](DefaultApi.md#v2_mining_user_list_post) | **POST** /v2/mining_user/list | List all mining accounts
[**v2_mining_user_payment_pause_post**](DefaultApi.md#v2_mining_user_payment_pause_post) | **POST** /v2/mining_user/payment/pause | Pause payment
[**v2_mining_user_payment_resume_post**](DefaultApi.md#v2_mining_user_payment_resume_post) | **POST** /v2/mining_user/payment/resume | Resume payment
[**v2_mining_user_read_only_page_add_post**](DefaultApi.md#v2_mining_user_read_only_page_add_post) | **POST** /v2/mining_user/read_only_page/add | Create read-only page
[**v2_mining_user_read_only_page_delete_post**](DefaultApi.md#v2_mining_user_read_only_page_delete_post) | **POST** /v2/mining_user/read_only_page/delete | Delete read-only page
[**v2_mining_user_threshold_update_post**](DefaultApi.md#v2_mining_user_threshold_update_post) | **POST** /v2/mining_user/threshold/update | Change payout threshold
[**v2_mining_user_wallet_update_post**](DefaultApi.md#v2_mining_user_wallet_update_post) | **POST** /v2/mining_user/wallet/update | Modify wallet address
[**v2_revenue_distribution_add_post**](DefaultApi.md#v2_revenue_distribution_add_post) | **POST** /v2/revenue/distribution/add | Distribute revenue to an f2pool account
[**v2_revenue_distribution_delete_post**](DefaultApi.md#v2_revenue_distribution_delete_post) | **POST** /v2/revenue/distribution/delete | Terminate revenue distribution record
[**v2_revenue_distribution_info_post**](DefaultApi.md#v2_revenue_distribution_info_post) | **POST** /v2/revenue/distribution/info | Get revenue distribution information



## v2_assets_balance_post

> models::V2AssetsBalancePost200Response v2_assets_balance_post(v2_assets_balance_post_request)
Fetch current user's asset details

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**v2_assets_balance_post_request** | [**V2AssetsBalancePostRequest**](V2AssetsBalancePostRequest.md) |  | [required] |

### Return type

[**models::V2AssetsBalancePost200Response**](_v2_assets_balance_post_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## v2_assets_settle_mode_switch_post

> models::V2AssetsSettleModeSwitchPost200Response v2_assets_settle_mode_switch_post(v2_assets_settle_mode_switch_post_request)
Switch settlement mode

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**v2_assets_settle_mode_switch_post_request** | [**V2AssetsSettleModeSwitchPostRequest**](V2AssetsSettleModeSwitchPostRequest.md) |  | [required] |

### Return type

[**models::V2AssetsSettleModeSwitchPost200Response**](_v2_assets_settle_mode_switch_post_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## v2_assets_transactions_list_post

> models::V2AssetsTransactionsListPost200Response v2_assets_transactions_list_post(v2_assets_transactions_list_post_request)
Fetch bill list

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**v2_assets_transactions_list_post_request** | [**V2AssetsTransactionsListPostRequest**](V2AssetsTransactionsListPostRequest.md) |  | [required] |

### Return type

[**models::V2AssetsTransactionsListPost200Response**](_v2_assets_transactions_list_post_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## v2_blocks_date_range_post

> models::V2BlocksPagingPost200Response v2_blocks_date_range_post(v2_blocks_date_range_post_request)
Get blocks list within a date range

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**v2_blocks_date_range_post_request** | [**V2BlocksDateRangePostRequest**](V2BlocksDateRangePostRequest.md) |  | [required] |

### Return type

[**models::V2BlocksPagingPost200Response**](_v2_blocks_paging_post_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## v2_blocks_paging_post

> models::V2BlocksPagingPost200Response v2_blocks_paging_post(v2_blocks_paging_post_request)
Get blocks list with pagination

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**v2_blocks_paging_post_request** | [**V2BlocksPagingPostRequest**](V2BlocksPagingPostRequest.md) |  | [required] |

### Return type

[**models::V2BlocksPagingPost200Response**](_v2_blocks_paging_post_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## v2_hash_rate_distribute_post

> models::HashRateDistributionOrder v2_hash_rate_distribute_post(v2_hash_rate_distribution_info_post_request)
Distribute hashrate to an f2pool account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**v2_hash_rate_distribution_info_post_request** | [**V2HashRateDistributionInfoPostRequest**](V2HashRateDistributionInfoPostRequest.md) |  | [required] |

### Return type

[**models::HashRateDistributionOrder**](HashRateDistributionOrder.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## v2_hash_rate_distribution_info_post

> models::V2HashRateDistributionInfoPost200Response v2_hash_rate_distribution_info_post(v2_hash_rate_distribution_info_post_request)
Hashrate distribution information

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**v2_hash_rate_distribution_info_post_request** | [**V2HashRateDistributionInfoPostRequest**](V2HashRateDistributionInfoPostRequest.md) |  | [required] |

### Return type

[**models::V2HashRateDistributionInfoPost200Response**](_v2_hash_rate_distribution_info_post_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## v2_hash_rate_distribution_orders_post

> models::V2HashRateDistributionOrdersPost200Response v2_hash_rate_distribution_orders_post(v2_hash_rate_distribution_orders_post_request)
List of all orders of hashrate distribution

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**v2_hash_rate_distribution_orders_post_request** | [**V2HashRateDistributionOrdersPostRequest**](V2HashRateDistributionOrdersPostRequest.md) |  | [required] |

### Return type

[**models::V2HashRateDistributionOrdersPost200Response**](_v2_hash_rate_distribution_orders_post_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## v2_hash_rate_distribution_settlements_post

> models::V2HashRateDistributionSettlementsPost200Response v2_hash_rate_distribution_settlements_post(v2_hash_rate_distribution_orders_post_request)
List of all settlements of hashrate distribution

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**v2_hash_rate_distribution_orders_post_request** | [**V2HashRateDistributionOrdersPostRequest**](V2HashRateDistributionOrdersPostRequest.md) |  | [required] |

### Return type

[**models::V2HashRateDistributionSettlementsPost200Response**](_v2_hash_rate_distribution_settlements_post_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## v2_hash_rate_distribution_terminate_post

> models::V2HashRateDistributionTerminatePost200Response v2_hash_rate_distribution_terminate_post(v2_hash_rate_distribution_terminate_post_request)
Terminate hashrate distribution order

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**v2_hash_rate_distribution_terminate_post_request** | [**V2HashRateDistributionTerminatePostRequest**](V2HashRateDistributionTerminatePostRequest.md) |  | [required] |

### Return type

[**models::V2HashRateDistributionTerminatePost200Response**](_v2_hash_rate_distribution_terminate_post_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## v2_hash_rate_history_post

> models::V2HashRateHistoryPost200Response v2_hash_rate_history_post(v2_hash_rate_history_post_request)
Fetch hashrate historical data

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**v2_hash_rate_history_post_request** | [**V2HashRateHistoryPostRequest**](V2HashRateHistoryPostRequest.md) |  | [required] |

### Return type

[**models::V2HashRateHistoryPost200Response**](_v2_hash_rate_history_post_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## v2_hash_rate_info_list_post

> models::V2HashRateInfoListPost200Response v2_hash_rate_info_list_post(v2_hash_rate_info_list_post_request)
Fetch hashrate information of multiple accounts

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**v2_hash_rate_info_list_post_request** | [**V2HashRateInfoListPostRequest**](V2HashRateInfoListPostRequest.md) |  | [required] |

### Return type

[**models::V2HashRateInfoListPost200Response**](_v2_hash_rate_info_list_post_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## v2_hash_rate_info_post

> models::V2HashRateInfoPost200Response v2_hash_rate_info_post(v2_hash_rate_info_post_request)
Fetch hashrate information

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**v2_hash_rate_info_post_request** | [**V2HashRateInfoPostRequest**](V2HashRateInfoPostRequest.md) |  | [required] |

### Return type

[**models::V2HashRateInfoPost200Response**](_v2_hash_rate_info_post_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## v2_hash_rate_worker_history_post

> models::V2HashRateHistoryPost200Response v2_hash_rate_worker_history_post(v2_hash_rate_worker_history_post_request)
Fetch hashrate historical data of a worker

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**v2_hash_rate_worker_history_post_request** | [**V2HashRateWorkerHistoryPostRequest**](V2HashRateWorkerHistoryPostRequest.md) |  | [required] |

### Return type

[**models::V2HashRateHistoryPost200Response**](_v2_hash_rate_history_post_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## v2_hash_rate_worker_list_post

> models::V2HashRateWorkerListPost200Response v2_hash_rate_worker_list_post(v2_hash_rate_info_post_request)
Fetch worker list

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**v2_hash_rate_info_post_request** | [**V2HashRateInfoPostRequest**](V2HashRateInfoPostRequest.md) |  | [required] |

### Return type

[**models::V2HashRateWorkerListPost200Response**](_v2_hash_rate_worker_list_post_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## v2_mining_user_add_post

> models::V2MiningUserAddPost200Response v2_mining_user_add_post(v2_mining_user_add_post_request)
Add new mining account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**v2_mining_user_add_post_request** | [**V2MiningUserAddPostRequest**](V2MiningUserAddPostRequest.md) |  | [required] |

### Return type

[**models::V2MiningUserAddPost200Response**](_v2_mining_user_add_post_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## v2_mining_user_balance_withdraw_post

> models::V2MiningUserBalanceWithdrawPost200Response v2_mining_user_balance_withdraw_post(v2_mining_user_balance_withdraw_post_request)
Manual withdrawal

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**v2_mining_user_balance_withdraw_post_request** | [**V2MiningUserBalanceWithdrawPostRequest**](V2MiningUserBalanceWithdrawPostRequest.md) |  | [required] |

### Return type

[**models::V2MiningUserBalanceWithdrawPost200Response**](_v2_mining_user_balance_withdraw_post_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## v2_mining_user_get_post

> models::V2MiningUserGetPost200Response v2_mining_user_get_post(v2_mining_user_get_post_request)
Fetch account information

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**v2_mining_user_get_post_request** | [**V2MiningUserGetPostRequest**](V2MiningUserGetPostRequest.md) |  | [required] |

### Return type

[**models::V2MiningUserGetPost200Response**](_v2_mining_user_get_post_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## v2_mining_user_list_post

> models::V2MiningUserListPost200Response v2_mining_user_list_post()
List all mining accounts

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::V2MiningUserListPost200Response**](_v2_mining_user_list_post_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## v2_mining_user_payment_pause_post

> models::V2MiningUserWalletUpdatePost200Response v2_mining_user_payment_pause_post(v2_mining_user_payment_pause_post_request)
Pause payment

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**v2_mining_user_payment_pause_post_request** | [**V2MiningUserPaymentPausePostRequest**](V2MiningUserPaymentPausePostRequest.md) |  | [required] |

### Return type

[**models::V2MiningUserWalletUpdatePost200Response**](_v2_mining_user_wallet_update_post_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## v2_mining_user_payment_resume_post

> models::V2MiningUserWalletUpdatePost200Response v2_mining_user_payment_resume_post(v2_mining_user_payment_pause_post_request)
Resume payment

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**v2_mining_user_payment_pause_post_request** | [**V2MiningUserPaymentPausePostRequest**](V2MiningUserPaymentPausePostRequest.md) |  | [required] |

### Return type

[**models::V2MiningUserWalletUpdatePost200Response**](_v2_mining_user_wallet_update_post_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## v2_mining_user_read_only_page_add_post

> models::V2MiningUserReadOnlyPageAddPost200Response v2_mining_user_read_only_page_add_post(v2_mining_user_read_only_page_add_post_request)
Create read-only page

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**v2_mining_user_read_only_page_add_post_request** | [**V2MiningUserReadOnlyPageAddPostRequest**](V2MiningUserReadOnlyPageAddPostRequest.md) |  | [required] |

### Return type

[**models::V2MiningUserReadOnlyPageAddPost200Response**](_v2_mining_user_read_only_page_add_post_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## v2_mining_user_read_only_page_delete_post

> models::V2MiningUserGetPostRequest v2_mining_user_read_only_page_delete_post(v2_mining_user_read_only_page_delete_post_request)
Delete read-only page

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**v2_mining_user_read_only_page_delete_post_request** | [**V2MiningUserReadOnlyPageDeletePostRequest**](V2MiningUserReadOnlyPageDeletePostRequest.md) |  | [required] |

### Return type

[**models::V2MiningUserGetPostRequest**](_v2_mining_user_get_post_request.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## v2_mining_user_threshold_update_post

> models::V2MiningUserThresholdUpdatePost200Response v2_mining_user_threshold_update_post(v2_mining_user_threshold_update_post_request)
Change payout threshold

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**v2_mining_user_threshold_update_post_request** | [**V2MiningUserThresholdUpdatePostRequest**](V2MiningUserThresholdUpdatePostRequest.md) |  | [required] |

### Return type

[**models::V2MiningUserThresholdUpdatePost200Response**](_v2_mining_user_threshold_update_post_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## v2_mining_user_wallet_update_post

> models::V2MiningUserWalletUpdatePost200Response v2_mining_user_wallet_update_post(v2_mining_user_wallet_update_post_request)
Modify wallet address

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**v2_mining_user_wallet_update_post_request** | [**V2MiningUserWalletUpdatePostRequest**](V2MiningUserWalletUpdatePostRequest.md) |  | [required] |

### Return type

[**models::V2MiningUserWalletUpdatePost200Response**](_v2_mining_user_wallet_update_post_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## v2_revenue_distribution_add_post

> models::V2RevenueDistributionAddPost200Response v2_revenue_distribution_add_post(v2_revenue_distribution_add_post_request)
Distribute revenue to an f2pool account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**v2_revenue_distribution_add_post_request** | [**V2RevenueDistributionAddPostRequest**](V2RevenueDistributionAddPostRequest.md) |  | [required] |

### Return type

[**models::V2RevenueDistributionAddPost200Response**](_v2_revenue_distribution_add_post_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## v2_revenue_distribution_delete_post

> models::V2HashRateDistributionTerminatePost200Response v2_revenue_distribution_delete_post(v2_revenue_distribution_delete_post_request)
Terminate revenue distribution record

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**v2_revenue_distribution_delete_post_request** | [**V2RevenueDistributionDeletePostRequest**](V2RevenueDistributionDeletePostRequest.md) |  | [required] |

### Return type

[**models::V2HashRateDistributionTerminatePost200Response**](_v2_hash_rate_distribution_terminate_post_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## v2_revenue_distribution_info_post

> models::V2RevenueDistributionInfoPost200Response v2_revenue_distribution_info_post(v2_revenue_distribution_info_post_request)
Get revenue distribution information

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**v2_revenue_distribution_info_post_request** | [**V2RevenueDistributionInfoPostRequest**](V2RevenueDistributionInfoPostRequest.md) |  | [required] |

### Return type

[**models::V2RevenueDistributionInfoPost200Response**](_v2_revenue_distribution_info_post_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

