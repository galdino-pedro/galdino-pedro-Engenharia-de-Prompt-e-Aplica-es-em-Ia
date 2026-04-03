1. O Problema Escolhido

Necessidade: Documentar uma função simples em Python que calcula a média de notas de um aluno e diz se ele foi aprovado.

2. Primeira Iteração (Instrução Vaga)
Prompt:

"Explica esse código de média em Python pra mim."

Documentação da Resposta Ruim:
A IA provavelmente entregará uma resposta genérica, talvez apenas comentando as linhas do código ou dando uma explicação técnica demais para um iniciante, sem contexto sobre boas práticas ou organização.
def calcular_media(nota1, nota2):

Código de média em Python

    # Processamento dos dados
    media_final = (nota1 + nota2) / 2
    
    # Estrutura de decisão (Controle de Fluxo)
    if media_final >= 7:
        return "Aprovado"
    else:
        return "Reprovado"
<img width="787" height="638" alt="image" src="https://github.com/user-attachments/assets/e0d4462a-b2f8-4baf-8762-ab6e276eef80" />

3. Aplicando a Equação do Prompt
Vou estruturar a solicitação usando a fórmula: Persona + Contexto + Restrições + Formato.

Persona: Professor de programação sênior, paciente e didático.

Contexto: Estou criando um tutorial para alunos do primeiro semestre de ADS (Análise e Desenvolvimento de Sistemas).

Restrições: Não use termos técnicos excessivos sem explicá-los. O código deve seguir o padrão PEP8. A explicação deve ser curta e objetiva.

Formato: Tabela para os conceitos e Markdown para o código.

# PERSONA
Atue como um Professor de Programação Sênior especializado em didática para iniciantes.

# CONTEXTO
Estou produzindo um material de apoio para estudantes de tecnologia que nunca viram código antes. Preciso que você documente e explique a função de cálculo de média abaixo.

# TAREFA
1. Refatore o código para seguir as melhores práticas (PEP8).
2. Explique o que cada bloco faz de forma analógica.
3. Crie uma tabela de variáveis explicando o papel de cada uma.

# RESTRIÇÕES
- Use linguagem simples e acolhedora.
- O código deve ser em Python.
- Saída obrigatória em formato Markdown estruturado.

# CÓDIGO BASE
def media(n1, n2):
  m = (n1 + n2) / 2
  if m >= 7:
    return "aprovado"
  else:
    return "reprovado"
