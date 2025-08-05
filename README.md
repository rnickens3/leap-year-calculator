# leap-year-calculator
Function that checks if a year is a leap year, then returns result.

## Summary
This function takes in a year and goes through three checks: 
- If the year is divisible by 4, then it is a leap year.
- Unless the year is also divisible by 100, then it is not a leap year.
- Unless the year is also divisible by 400, then it is a leap year.

It will return the result.

```javascript
function isLeapYear(year) {
  if ((year % 4 === 0 && year % 100 !== 0) || (year % 400 === 0 )) {
    return `${year} is a leap year.`; 
  } else {
    return `${year} is not a leap year.`;
  }
} 
