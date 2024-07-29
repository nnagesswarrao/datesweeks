
# Date Generator

## Description

Date Generator is a simple NPM package that generates random dates between a specified "from" and "to" range.
 This can be useful for testing, data generation, and various other purposes where you need random date values.

## Installation
You can install Date Generator using npm:

    npm i date_genarator

## ============STEPS============

## STEP1 
Import Package
var dategenerate = require('date_genarator');

## STEP2
create Object
let dates = new dategenerate()

## STEP3
in date Object dateWeek()  function  pass "from" and "To" dates as arguments
example:
let  from_datate ='2024-02-12';
let  todate =`2024-02-15`;
dates.dateWeek(from_datate, todate);


## Example:

var dategenerate = require('date_genarator');
#
let dates = new dategenerate()
#
let Dates=[]
#
Dates=dates.dateWeek('2024-02-12', '2024-02-15');
#
console.log(Dates)

# 
## output:

[
  {
    date: '2024-02-12',
    dt: 12,
    mnth: 2,
    yr: 2024,
    dy_id: 1,
    weekeDays: 'Monday'
  },
  {
    date: '2024-02-13',
    dt: 13,
    mnth: 2,
    yr: 2024,
    dy_id: 2,
    weekeDays: 'Tuesday'
  },
  {
    date: '2024-02-14',
    dt: 14,
    mnth: 2,
    yr: 2024,
    dy_id: 3,
    weekeDays: 'Wednesday'
  },
  {
    date: '2024-02-15',
    dt: 15,
    mnth: 2,
    yr: 2024,
    dy_id: 4,
    weekeDays: 'Thursday'
  }
]


 

 
