# Cases 


## Case 1: Vamos imaginar que em um processo seletivo existe o valor base salarial de R$ 2000.00 e o salario pretendito pelo candidato. Vamos elaborar um controle de fluxo onde: 
    - Se o valor salario base for maior que o salario pretentido, imprima : ligar para o candidato;
    - Senão Se o valor salario base for igual ao valor salario pretendido, imprima: ligar para o candidato com contra proposta;
    - Senão imprima: Aguardando Resultado demais candidatos;

    - Veja no arquivo processo ProcessoSeletivo.java;

## Case 2: Foi solicitado que nosso sistema garanta que diante das inúmeras candidaturas sejam selecionados apenas 5 candidatos para entrevista onde o salaário pretendido seja menor ou igual ao salário base.

    // Array com a lista de candidatos

String [] candidatos = {"FELIPE", "MARCIA", "JULIA", "PAULO", "AUGUSTO", "MONICA", "FABRICIO", "MIRELA", "DANIELA", "JORGE"}

    // Método que simula o valor pretendido

import java.util.concurrent.ThreadLocalRandom;
static double valorPretendido() {
    return ThreadLocalRandom.current().nextDouble(1800, 2200);
}

## Case 3: Agora é hora de imprimir a lista dos candidatos selecionados para disponibilizar para o RH entrar em contato.

## Case 4: O RH deverá realizar uma ligação com no máximo 03 tentativas para cada candidato selecionado e caso o candidato atenda, deve-se imprimir: 
    -"CONSEGUIMOS CONTATO COM [CANDIDATO] APÓS [TENTATIVA] TENTATIVA(S)"
    - do contrário imprima: "NÃO CONSEGUIMOS CONTATO COM O [CANDIDATO] "