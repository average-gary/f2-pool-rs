# TransactionItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | Option<**i64**> | ID of the transaction | [optional]
**r#type** | Option<**String**> | Type of the transaction | [optional]
**changed_balance** | Option<**f64**> | If the changed_balance is greater than 0, it is the income, less than 0, it is the outcome | [optional]
**created_at** | Option<**i64**> | The payout timestamp | [optional]
**mining_extra** | Option<[**models::MiningExtra**](MiningExtra.md)> |  | [optional]
**payout_extra** | Option<[**models::PayoutExtra**](PayoutExtra.md)> |  | [optional]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


