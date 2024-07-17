# vvdev
JavaScript library for iplookup.vvdev.ru
# main
```js
async function main(){
    const {vvdev} = require('./vvdev');
    const ip= new vvdev();
    let req=await ip.my_ip()
    console.log(req)
}
main()
```
