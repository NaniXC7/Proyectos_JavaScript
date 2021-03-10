let rm = Math.floor(Math.random()*3);
let rm1 = Math.floor(Math.random()*3);
            
if(rm === 0 && rm1 === 0){
    console.log("Jugador 1 saca: piedra \t\t jugador 2 saca: piedra");
    console.log("\t\tHa sido un empate");
}
if(rm === 1 && rm1 === 1){
    console.log("Jugador 1 saca papel: \t\t jugador 2 saca: papel");
    console.log("\t\tHa sido un empate");
}
if(rm === 2 && rm1 === 2){
    console.log("Jugador 1 saca tijera: \t\t jugador 2 saca: tijera");
    console.log("\t\tHa sido un empate");
}
if(rm === 0 && rm1 === 1){
    console.log("Jugador 1 saca: piedra \t\t jugador 2 saca: papel");
    console.log("\t\tGana: jugador 2");
}
if(rm === 1 && rm1 === 0){
    console.log("Jugador 1 saca: papel \t\t jugador 2 saca: piedra");
    console.log("\t\tGana: jugador 1");
}
if(rm === 0 && rm1 === 2){
    console.log("Jugador 1 saca: piedra \t\t jugador 2 saca: tijera");
    console.log("\t\tGana: jugador 1");
}
if(rm === 2 && rm1 === 0){
    console.log("Jugador 1 saca: tijera \t\t jugador 2 saca: piedra");
    console.log("\t\tGana: jugador 2");
}
if(rm === 2 && rm1 === 1){
    console.log("Jugador 1 saca: tijera \t\t jugador 2 saca: papel");
    console.log("\t\tGana: jugador 1");
}
if(rm === 1 && rm1 === 2){
    console.log("Jugador 1 saca: papel \t\t jugador 2 saca: tijera");
    console.log("\t\tGana: jugador 2");
}
