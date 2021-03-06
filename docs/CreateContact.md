# SibApiV3Sdk::CreateContact

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**email** | **String** | Email address of the user. Mandatory if &#x60;attributes.sms&#x60; is not passed | [optional] 
**attributes** | **Object** | Values of the attributes to fill. The attributes must exist in you contact database | [optional] 
**email_blacklisted** | **BOOLEAN** | Blacklist the contact for emails (emailBlacklisted &#x3D; true) | [optional] 
**sms_blacklisted** | **BOOLEAN** | Blacklist the contact for SMS (smsBlacklisted &#x3D; true) | [optional] 
**list_ids** | **Array&lt;Integer&gt;** | Ids of the lists to add the contact to | [optional] 
**update_enabled** | **BOOLEAN** | Facilitate to update existing contact in same request (updateEnabled &#x3D; true) | [optional] [default to false]
**smtp_blacklist_sender** | **Array&lt;String&gt;** | SMTP forbidden sender for contact. Use only for email Contact ( only available if updateEnabled &#x3D; true ) | [optional] 


