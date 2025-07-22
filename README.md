# zcsfilter_auto
Bash Scripts for automate the creation of filter rules in Zimbra&reg;

[Zimbra&reg; Documentation Mail Filters](https://wiki.zimbra.com/wiki/Zimbra_Web_Client_Mail_Filters)

[Zimbra&reg; zmmailbox Documentation](https://wiki.zimbra.com/wiki/Zmmailbox)

## Requirements
* Create a COS ( Class of Service ) without preferences options for users
* Create a file with accounts to apply rules (users)
* Create a file with keywords to usage in rules (keywords)
* Account for forward mesages ( account_redirect@domain.com )

## Example:
### Adding rules
add_filter_zimbra_acc users keywords NAME_RULE account_redirect@domain.com
### Delete rules
del_filter_zimbra_acc users NAME_RULE default
