 //ES6 function
function orderReUpdate(array,pointer,value,newObj){
    let obj = array.find(x => x[pointer] === value);
    let index = array.indexOf(obj);
    Object.keys(newObj).forEach(key =>array.fill(obj[key]=newObj[key], index, index++));
    return array
}
//some datas
let array = [{
        "userId": "5e000834756d5c5ceb65fe66",
        "fee": 0.3,
        "ctype": "eur",
        "transfer": 28500,
        "currency": 100000,
        "sabitAlisEmri": false,
        "percent": -5,
        "date": "2020-03-11T12:57:39.599Z"
    },
    {
        "userId": "5e000834756d5c5ceb65fe66",
        "fee": 0.2,
        "ctype": "eur",
        "transfer": 19000,
        "currency": 100000,
        "sabitAlisEmri": false,
        "percent": -5,
        "cache": false,
        "date": "2020-03-11T15:11:31.147Z"
    }]

orderReUpdate(array,'fee',0.3,{'fee':8,'userId':'Cudi Cumhur','currency':500});
console.log(array);
//output
[
   {
      "userId":"Cudi Cumhur",
      "fee":8,
      "ctype":"eur",
      "transfer":28500,
      "currency":500,
      "sabitAlisEmri":false,
      "percent":-5,
      "date":"2020-03-11T12:57:39.599Z"
   },
   {
      "userId":"5e000834756d5c5ceb65fe66",
      "fee":0.2,
      "ctype":"eur",
      "transfer":19000,
      "currency":100000,
      "sabitAlisEmri":false,
      "percent":-5,
      "cache":false,
      "date":"2020-03-11T15:11:31.147Z"
   }
]
