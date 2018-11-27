https://github.com/facebook/create-react-app/issues/5809

```
# run normal project
yarn start

# run with update that changes a src file as CRA boots
# this gives us a blank page
yarn start:update

# run with update that changes a src file 100s after CRA boots
# this works but of course it's unreliable
yarn start:update:delayed
```
