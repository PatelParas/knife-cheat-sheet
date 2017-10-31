# knife-cheat-sheet
Knife Short Commands which make your life easy

##Cookbooks

### How do I create a new cookbook?
```
cd ~/chef-repo
knife cookbook create <cookbook-name> -C "Paras Patel" -m "paras.patel@hotmail.com" 
```
### How do I upload my new cookbook to the chef server so I can use it?
```
knife cookbook upload <cookbookname> 
```
### How do I download existing recipes from the Chef Community?
```
knife cookbook site install awsclient
```
