# git setup
RSP: https://sourabhbajaj.com/mac-setup/Git/
RSP: Reasonable starting point.



## 1password
- https://support.1password.com/command-line-getting-started/

### cli
```
eval $(op signin xxxxx.1password.com noreply@someemail.com __SECRET_KEY__)

opt='op get item __uuids__ --fields token'

optotp='op get totp __uuid__'```
