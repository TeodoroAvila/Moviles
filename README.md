### Tareas Aplicaciones moviles

let arraySum = function (array: number[]):number{
    let safer:number=0;
    for (let index=0; index<array.length; index++){
            safer=safer+array[index];
    }
    console.log(safer);
    return(safer);
}
arraySum([20,2,5]);
