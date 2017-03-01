# zcsfilter_auto
Bash Scripts for automatic filter rules in Zimbra&reg;

##Requirements
* Create a COS ( Class of Service ) without preferences options for users
* Create a file with accounts to apply rules
* Create a file with keywords to usage in rules
* Account for forward mesages ( emails )

## Example:
### Adding rules
add_filter_zimbra_acc users keywords NAME_RULE account_redirect@domain.com
### Delete rules
del_filter_zimbra_acc users NAME_RULE default
