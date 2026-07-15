# Atividade-intro-tech-5---vetores
O presente projeto consiste na conclusão de uma atividade do bootcamp da Generation. 

Atividade 1 – Ordenação de Vetor

Aqui foi possível desenvolver com ajuda das aulas um algoritmo no Portugol para ler 10 números inteiros, e coloca-los em um vetor e ordenar em ordem decrescente. Foi solicitado que fosse utilizado os vetores, laços de repetição e estruturas condicionais para ordenar cada um dos elementos.

programa
{
    funcao inicio()
    {
        inteiro vetor[10]
        inteiro i, j, aux

                para(i = 0; i < 10; i++) // input dos dados
        {
            escreva("Digite o ", i + 1, "º número: ")
            leia(vetor[i])
            limpa()
            
        }

                para(i = 0; i < 9; i++) // process em ordem decrescente
        {
            para(j = i + 1; j < 10; j++)
            {
                se(vetor[i] < vetor[j])
                {
                    aux = vetor[i]
                    vetor[i] = vetor[j]
                    vetor[j] = aux
                }
            }
        }

               escreva("Ordem decrescente: ")  // output dos dados

        para(i = 0; i < 10; i++)
        {
            escreva(vetor[i], " ")
        }
    }
}

Atividade 2 – Operações com Vetores

Neste outro exercício foi desenvolvido algoritmo no Portugol para ler 10 números inteiros e coloca-los dentro de um vetor. Ao depurar o programa imprimi os elementos localizados em números pares do vetor, calcula a soma de todos os números e a média , aplicando os conceitos de vetores, estruturas condicionais e laços de repetição como é solicitado na atividade.
