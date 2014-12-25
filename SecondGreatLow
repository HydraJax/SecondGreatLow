function SecondGreatLow(arr) { 
  var solution = [];
  var arrSorted = arr.sort(function(a, b){ return a-b; });
  for ( var i= 0; i < arrSorted.length; i++ ) {
    if ( arrSorted.length === 2 && arrSorted[ 0 ] === arrSorted[ 1 ]) return arrSorted[0] + " " + arrSorted[1];
    if ( arrSorted[0] === arrSorted[1] ) arrSorted.shift();
    if ( arrSorted[arrSorted.length-1 ] === arr[arr.length-2] ) arrSorted.pop();
  }
  solution = solution + ( arrSorted[ 1 ] + " " + arrSorted[ arr.length-2 ] );
  return solution;
}
numArr = [80,80];
SecondGreatLow(numArr);