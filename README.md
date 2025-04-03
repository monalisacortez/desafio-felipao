let nomeHeroi = "Batmona"
let XP = 11000

switch (XP) {
    case XP<1000:
        console.log("Seu nível é Ferro");
        break;
    case XP>1001 && XP<2000:
        console.log("Seu nível é Bronze");
        break;
    case XP>2001 && XP<5000:
        console.log("Seu nível é Prata");
        break;
    case XP>6001 && XP<7000:
        console.log("Seu nível é Ouro");
        break;
    case XP>7001 && XP<8000:
        console.log("Seu nível é Platina");
        break;
    case XP>8001 && XP<9000:
        console.log("Seu nível é Ascendente");
        break;
    case XP>9001 && XP<10000:
        console.log("Seu nível é Imortal");
        break;
    case XP>=10001:
        console.log("Seu nível é Radiante");
}

console.log(", parabéns " + nomeHeroi + "!")
