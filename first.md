```javascript
Vue.prototype.$thousandSeprator = function thousandSeprator(amount) {
    return amount.toString().replace(/\B(?=(\d{3})+(?!\d))/g, ",")
  }
  ```
