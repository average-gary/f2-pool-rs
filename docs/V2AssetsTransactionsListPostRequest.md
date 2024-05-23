# V2AssetsTransactionsListPostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**currency** | Option<**String**> | Required | [optional]
**mining_user_name** | Option<**String**> | Account name (Only one of mining_user_name and address should be used) | [optional]
**address** | Option<**String**> | Wallet address | [optional]
**r#type** | Option<**String**> | Multiple types are separated by ',' (all, revenue, reward, dividend, flash_exchange, payout) | [optional]
**start_time** | Option<**i64**> | Start timestamp | [optional]
**end_time** | Option<**i64**> | End timestamp, must be later than start timestamp | [optional]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


