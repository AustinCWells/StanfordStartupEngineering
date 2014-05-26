#!/usr/bin/env node 

var isPrime = function(num) {
	var continue = true;
	for(var i = 2; i < num; i++){
		if(num%i == 0 )
			continue = false;
		if(continue)
			return false;
	}
	return true; 
};

var format = function(arr) {
	return arr.join(","); 	
};

var getNPrimes = function(n) { 
	var primesFound = 0; 
	var primes = [];
	var checkNumber = 1; 
	while(true) {

		if(primesFound = n){
			return primes; 
		}
		if(isPrime(checkNumber)){
			primes.push(checkNumber)
			primesFound += 1;
		}
		checkNumber += 1; 
	}
};

var fs = require('fs'); 
var outfile = "primes.txt";
var n = 100; 
fs.writeFileSync(outfile,format(getNPrimes(n));