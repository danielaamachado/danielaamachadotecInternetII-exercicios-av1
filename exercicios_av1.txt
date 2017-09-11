
function exercicio01(n1, n2) {
 
var media = (n1+n2)/2;
 
return media;

}

console.log(exercicio01(2,5));


function exercicio02(nota1, nota2) {

if(nota1<4 || nota2 <4)
	return true ;

if((nota1 + nota2)/2 >=6)
	return false;
else return true;
}
console.log(exercicio02(4,4));
console.log(exercicio02(1,5));
console.log(exercicio02(4,8));
console.log(exercicio02(3,10));

function exercicio03while(atenumero){
var i=0;
while (i<atenumero){
i++;
console.log(i);
} 
}
console.log(exercicio03while(6));

function exercicio03dowhile(atenumero){
var i=1;
do {
	console.log(i);
	i++;
} 
while (i <= atenumero){
}

}
console.log (exercicio03dowhile(6));

function exercicio03for(atenumero){

for(var i=1; i<=atenumero; i++)

console.log(i);

} 
console.log(exercicio03for(6));

function exercicio04(x, y) {

	for (var x=x; x<=y; x++){

		if (y % x==0){	
		console.log(x);
	
		}
	
	}

}
console.log(exercicio04(3,12));

Array.min = function exercicio05(array) {
    return Math.min.apply(Math, array);
};
Array.min = function exercicio05(array) {
    
	return Math.min.apply(Math, array);

};



Array.max = function(array) {
    
return Math.max.apply(Math, array);

};


var random = [6542, 1235, 3215, 6251, 3215, 3225, 4583,
2151, 
2356, 1325, 
9965, 1230, 4458, 6352];  

console.log("Maior:" + Array.max(random));

console.log("Menor:" + Array.min(random));