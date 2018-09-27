# Ansible-Azure-SecGroup


This Repo Creates Azure Security Group. Azure Credentials is managed by Tower or AWX so it is not required as part of this Playbook. Just make sure you have the credentials selected as part fo the template.


## Required Variables

```javascript
{
Azure_Resource_Group: ''
Azure_SG_Name: ''
Azure_SG_Rules: 'Array'
}
```