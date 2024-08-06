function setup() 
  createCanvas(400, 400);
}

function draw() {
  background(220);
}

function draw() {
    background(220);
    let recomendacao = "A viagem de Chihiro";
    text(recomendacao, width/2, height/2);
}

function draw() {
    background(220);
    let recomendacao = geraRecomendacao();
    text(recomendacao, width/2, height/2);
}

function geraRecomendacao() {
  return "A viagem de Chihiro";
}

function geraRecomendacao(idade) {
    if (idade >= 10) {
        return "As aventuras de Pi";
    } else {
        return "A viagem de Chihiro";
    }
}

function draw() {
    background(220);
    let idade = 15; // exemplo de idade
    let recomendacao = geraRecomendacao(idade);
    text(recomendacao, width/2, height/2);
}

let campoIdade;

function setup() {
    createCanvas(400, 400);
    campoIdade = createInput("15");
}

function draw() {
    background(220);
    let idade = campoIdade.value();
    let recomendacao = geraRecomendacao(idade);
    text(recomendacao, width/2, height/2);
}

function geraRecomendacao(idade) {
    if (idade >= 10) {
        if (idade >= 14) {
            return "O menino que descobriu o vento";
        } else {
            return "As aventuras de Pi";
        }
    } else {
        return "A viagem de Chihiro";
    }
}

let fieldAge;

function setup() {
  createCanvas(400, 400);
  campoIdade = createInput("15");
}

function draw() {
  background(220);
  let idade = 15; // exemplo de idade
  let recomendacao = geraRecomendacao(idade);
  text(recomendacao, width / 2, height / 2);
}

function geraRecomendacao(idade) {
  if (idade >= 10) {
    if (idade >= 14) {
      return "O menino que descobriu o vento";
    } else {
      return "As aventuras de Pi";
    }
  } else {
    return "A viagem de Chihiro";
  }
}

function geraRecomendacao(idade, gostaDeFantasia) {
    if(idade >= 10) {
        if(idade >= 14) {
            return "O menino que descobriu o vento";
        } else {
            if(gostaDeFantasia){
                return "As aventuras de Pi";
            } else {
                return "Depois da chuva";
            }
        }
    } else {
        return "A viagem de Chihiro";
    }
}


function draw() {
    background (220);
    let idade = campoIdade.value();
    let gostaDeFantasia = true;
    let recomendacao = geraRecomendacao(idade, gostaDeFantasia);
    text(recomendacao, width/2, height/2);
}

let fieldage
let fieldFantasy;

function setup() {
    createCanvas(400, 400);
    campoIdade = createInput("15");
    campoFantasia = createCheckbox("Gosta de Fantasia ?");
}

function draw() {
    background(220);
    let idade = campoIdade.value();
    let gostaDeFantasia = campoFantasia.checked();
    let recomendacao = geraRecomendacao(idade, gostaDeFantasia);
    text(recomendacao, width / 2, height / 2);
}

function geraRecomendacao(idade, gostaDeFantasia) {
    if(idade >= 10) {
        if(idade >= 14) {
            return "O menino que descobriu o vento";
        } else {
            if(gostaDeFantasia){
                return "As aventuras de Pi";
            } else {
                return "Depois da chuva";
            }
        }
    } else {
        if(gostaDeFantasia) {
            return "A viagem de Chihiro";
        } else {
            return "O feitiço do tempo";
        }
    }
}

function geraRecomendacao(idade, gostaDeFantasia) {
    if (idade >= 10) {
        if (idade >= 14) {
            return "O menino que descobriu o vento";
        } else {
            if (gostaDeFantasia) {
                return "As aventuras de pi";
            } else {
                return "Depois da chuva";
            }
        }
    } else {
        if (gostaDeFantasia) {
            return "A viagem de chihiro";
        } else {
            return "O feitiço do tempo";
        }
    }
}

function setup() {
    createCanvas(800, 400);
    campoIdade = createInput("5");
    campoFantasia = createCheckbox("Gosta de fantasia?");
}

function draw() {
    background(220);
    let idade = campoIdade.value();
    let gostaDeFantasia = campoFantasia.checked();
    let recomendacao = geraRecomendacao(idade, gostaDeFantasia);

    textAlign(CENTER, CENTER);
    textSize(38);
    text(recomendacao, width / 2, height / 2);
}

function draw() {
    background(220);
    let idade = campoIdade.value();
    let gostaDeFantasia = campoFantasia.checked();
    let recomendacao = geraRecomendacao(idade, gostaDeFantasia);

    fill(color(76, 0, 115)); // Um tom de roxo escuro
    textAlign(CENTER, CENTER);
    textSize(38);
    text(recomendacao, width / 2, height / 2);
}

function draw() {
    background("white");
    let idade = campoIdade.value();
    let gostaDeFantasia = campoFantasia.checked();
    let recomendacao = geraRecomendacao(idade, gostaDeFantasia);

    fill(color(76, 0, 115));
    textAlign(CENTER, CENTER);
    textSize(38);
    text(recomendacao, width / 2, height / 2);
}

function setup() {
    createCanvas(800, 400);
    createSpan("Sua idade:");
    campoIdade = createInput("5");
    campoFantasia = createCheckbox(" Gosta de fantasia?");
}

function setup() {
    createCanvas(800, 400);
    createSpan("Sua idade:");
    campoIdade = createInput("5");
    campoFantasia = createCheckbox(" Gosta de fantasia?");
}

function draw() {
    background("white");
    let idade = campoIdade.value();
    let gostaDeFantasia = campoFantasia.checked();
    let recomendacao = geraRecomendacao(idade, gostaDeFantasia);

    fill(color(76, 0, 115));
    textAlign(CENTER, CENTER);
    textSize(38);
    text(recomendacao, width / 2, height / 2);
}

function geraRecomendacao(idade, gostaDeFantasia) {
    if (idade >= 10) {
        if (idade >= 14) {
            return "O menino que descobriu o vento";
        } else {
            if (gostaDeFantasia) {
                return "As aventuras de pi";
            } else {
                return "Depois da chuva";
            }
        }
    } else {
        if (gostaDeFantasia) {
            return "A viagem de chihiro";
        } else {
            return "O feitiço do tempo";
        }
    }
}

