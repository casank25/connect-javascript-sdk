# SquareConnect.CustomerSort

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**field** | **String** | The field to sort the results on. It could be the total money spent at the merchant, the date of the first visit (etc). See [CustomerSortField](#type-customersortfield) for possible values. Default value: &#x60;DEFAULT&#x60;. | [optional] 
**order** | **String** | Indicates the order in which results should be displayed based on the value of the sort field. String comparisons use standard alphabetic comparison to determine order. Strings representing numbers are sorted as strings. See [SortOrder](#type-sortorder) for possible values. Default value: &#x60;ASC&#x60;. | [optional] 


<a name="FieldEnum"></a>
## Enum: FieldEnum


* `DEFAULT` (value: `"DEFAULT"`)

* `CREATED_AT` (value: `"CREATED_AT"`)




<a name="OrderEnum"></a>
## Enum: OrderEnum


* `DESC` (value: `"DESC"`)

* `ASC` (value: `"ASC"`)




