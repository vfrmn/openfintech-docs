
# Kyivstar (contract) (service) 
![kyivstar_contract_number_uah](https://static.openfintech.io/payout_methods/kyivstar_contract_number_uah/logo.svg?w=400&c=v0.59.26#w24)  

## General 
 
**Code:** `kyivstar_contract_number_uah` 
 
**Method:** `kyivstar_contract_number` [show -->](/payout-methods/kyivstar_contract_number/) 
 
**Currency:** `UAH` [show -->](/currencies/UAH/) 
 
**Name:** 
 
:	[EN] Kyivstar (contract) 
:	[RU] Киевстар (контракт) 
:	[UK] Київстар (контракт) 
 
**Amount limits:** from `100` to `499900` UAH 

## Fields 

### Overview 

|Key|Required|Type|Regexp| 
|:---:|:---:|:---:|:---:| 
|`client_id`|✔|`string`|`/^\d{1,128}$/`| 
 

### Details 
 
1. **`client_id`** 
 
	Type: `string` 
 
	Regexp: `/^\d{1,128}$/` 
 
	Required: `1` 
 
	Label:  
	: [EN] Kyivstar contract № 
	: [UK] № контракту Київстар 
	: [RU] № контракта Киевстар 
 
	Hint:  
	: [EN] Enter kyivstar contract № 
	: [UK] Введіть № контракту київстар 
	: [RU] Введите № контракта киевстар 
 

## JSON Object 

```json
{
  "code":"kyivstar_contract_number_uah",
  "method":"kyivstar_contract_number",
  "currency":"UAH",
  "fields":[
    {
      "key":"client_id",
      "type":"string",
      "label":{
        "en":"Kyivstar contract \u2116",
        "uk":"\u2116 \u043a\u043e\u043d\u0442\u0440\u0430\u043a\u0442\u0443 \u041a\u0438\u0457\u0432\u0441\u0442\u0430\u0440",
        "ru":"\u2116 \u043a\u043e\u043d\u0442\u0440\u0430\u043a\u0442\u0430 \u041a\u0438\u0435\u0432\u0441\u0442\u0430\u0440"
      },
      "regexp":"\/^\\d{1,128}$\/",
      "required":true,
      "position":1,
      "hint":{
        "en":"Enter kyivstar contract \u2116",
        "uk":"\u0412\u0432\u0435\u0434\u0456\u0442\u044c \u2116 \u043a\u043e\u043d\u0442\u0440\u0430\u043a\u0442\u0443 \u043a\u0438\u0457\u0432\u0441\u0442\u0430\u0440",
        "ru":"\u0412\u0432\u0435\u0434\u0438\u0442\u0435 \u2116 \u043a\u043e\u043d\u0442\u0440\u0430\u043a\u0442\u0430 \u043a\u0438\u0435\u0432\u0441\u0442\u0430\u0440"
      },
      "example":"5028283"
    }
  ],
  "amount_min":"100",
  "amount_max":"499900"
}
```  
