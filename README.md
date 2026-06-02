#Faculdate Estacio de Sá RJ (Unesa)
## Projeto extensionista  do curso Tópicos de Big Data em Python
- Aluno: José Roberto Duarte Hegendorne
- Matrícula: 202502214154
- Curso Presencial
- Professora: Simone Gama
- Período: 1ª semestre 2026

## Dados do Sistema de Bilhetagem Eletrônica

- URL dos dados analizados: 
  https://dadosabertos.rj.gov.br/dataset/setram_sbe




## Repositório de dados baixados: 
   https://dadosabertos.rj.gov.br/dataset/setram_sbe
## link do repósitorio do drive é: 
   https://drive.google.com/drive/folders/1486i6aBSUVuyrD6bISm0qYGZs-eIhK71?usp=sharing

    Os arquivos são distribuidos com a movimentação diaria do bilhete unico.

# Dicionario de Dados dos arquivos originais: 
## Cartão Hash: 
   Sequência única de caracteres gerada a partir do Nº Cartão. 
## Data da Transação:
   Data e hora do processamento da transação.
## Data do Processamento:  
   Data e hora do processamento da transação.
## Descrição da Aplicação:  :    
   - Código da aplicação do cartão 
   - 100 - Expresso
   - 114 - Siga Viagem Supervia, 
   - 115 - Siga Viagem Metrô, 
   - 400 - Vale-transporte, 
   - 450 - Empresarial, 
   - 820 - Gratuidade de Morador de Paquetá/Ilha Grande, 
   - 80 QRCode Unitário
        
## Linha - 
     Número e nome da Linha.
## Nº Carro:
    Número da estação ou do carro onde a transação foi realizada.
## Nº Cartão:
    Número externo do cartão do usuário. Informação anonimizada para atender a LGPD, conforme exemplo a seguir: 1091xxxxxx713.
## Nº Validador:
    Número do validador utilizado na transação.
## Operadora:
    Nome da Operadora de transporte. Informação anonimizada para as Vans para atender a LGPD, conforme exemplo a seguir: VAN560001-LUISA MAxxxxxxxx
## Sentido:
    Código do sentido da linha (0 - não informado, 1 - ida, 2 - volta).
## Sindicato:
    Nome do sindicato
## Vl Linha
    Valor da linha da operadora de transporte.
## Vl Subsídio
    Valor do subsídio.
## Vl Trans
    Valor descontado no cartão do usuário.

# Bibliotecas utilizadas no código    
   - Pandas
   - Numpy
   - sklearn
   - seaborn
   - matplotLib 


## Classificação das Variáveis

### Variáveis Numéricas

- Vl_Linha
- Vl_Trans
- Vl_Subsidio

### Variáveis Categóricas

- Descricao_da_Aplicacao
- Operadora
- Linha
- Sindicato
- Sentido

### Variáveis Temporais

- Data_da_Transacao
- Data_do_Processamento  
 
 # Variaveis declaradas:
   - Pd - pandas 
   - Bu_total - data frame que recebe o CSV sem tratamento
   - Bu - data frame com Csv tratado
   - colunas - lista os campos que irei utilizar 
   - X - Variave de valor independente
   - Y - Variavel de valor dependente


       
