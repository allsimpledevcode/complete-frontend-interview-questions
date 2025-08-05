# Implement coupons filter 


Implement a javascript function filter a copons based on value on the creteria greater than and exact match

Data
``` javascript
const data = [
    {
        id: 1,
        coupon: 'NEW40',
        created_at: 1754365319843,
        value: 2
    }, {
        id: 2,
        coupon: 'NEW40',
        created_at: 1754365319843,
        value: 2
    }, {
        id: 3,
        coupon: 'NEW40',
        created_at: 1754365319843,
        value: 3
    }, {
        id: 4,
        coupon: 'NEW40',
        created_at: 1754365319843,
        value: 4
    }, {
        id: 5,
        coupon: 'NEW40',
        created_at: 1754365319843,
        value: 12
    }
]
```

Example 1
``` javascript
function coponsFilters(coupons, value) {
    // code here
}

//Input
const result = coponsFilters(data, { greaterThan: 2 })
//Ouput: 
[
    {
        id: 3,
        coupon: 'NEW40',
        created_at: 1754365319843,
        value: 3
    }, {
        id: 4,
        coupon: 'NEW40',
        created_at: 1754365319843,
        value: 4
    }, {
        id: 5,
        coupon: 'NEW40',
        created_at: 1754365319843,
        value: 12
    }
]
```

Example 2
``` javascript
function coponsFilters(coupons, value) {
    // code here
}

//Input
const result = coponsFilters(data, { isEqual: 2 })
//Ouput: 
[
    {
        id: 1,
        coupon: 'NEW40',
        created_at: 1754365319843,
        value: 2
    }, {
        id: 2,
        coupon: 'NEW40',
        created_at: 1754365319843,
        value: 2
    }
]
```