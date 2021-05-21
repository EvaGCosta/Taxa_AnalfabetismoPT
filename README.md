# Dados relativos à taxa de analfabetismo em Portugal nos anos de 1900 e 1911

ℹ️ **Fonte dos dados**: 
Censos de 1900 - https://pt.wikipedia.org/wiki/IV_Recenseamento_Geral_da_Popula%C3%A7%C3%A3o_de_Portugal] 
Censos de 1911 - https://pt.wikipedia.org/wiki/V_Recenseamento_Geral_da_Popula%C3%A7%C3%A3o_de_Portugal]

# 🤔 Contexto
Para este trabalho, proposto pelo docente da cadeira de Programação e Algoritmos II, decidimos analisar à taxa de analfabetismo em Portugal do antigamente.
Como 2021 foi o ano em que tornou a haver um novo levantamento de dados através dos Censos pelo Instituito Nacional de Estatística, o grupo de trabalho decidiu analisar os dados antigos relativos à população analfabeta visto que, nos livros de história sempre nos ensinaram que a população dessa época não sabia ler mas estavamos curiosas por saber o quão isso era frave.
Assim surgiu a opurtunidade de matar a curiosidade e pôr os nossos conhecimentos sobre a disciplina à prova.

# 👁️ Questões analisadas
+ Qual o distrito em Portugal com mais pessoas analfabetas?
+ Qual o distrito com menos população analfabeta?
+ Existem mais mulheres ou homens analfabetos?
+ Qual a média da populção anlfabeta em Portugal e a média da população que sabe ler?

# 📔 Dicionário dos dados
Uma explicação do conteúdo em `Censos_1900.csv` e `Censos_1911.csv`.


| Nome da coluna        | Significado           | Tipo de dado  |
| ------------- |:-------------:| -----:|
| `Distrito` | Nome do distrito de Portugal | stirng |
| `População` | Número de pessoas por distrito | int |
| `Homens_Analfabetos` | Nome do distrito de Portugal | object |
| `Homens_sabem_ler` | Nome do distrito de Portugal | object |
| `Mulheres_Analfabetas` | Nome do distrito de Portugal | object |
| `Mulheres_sabem_ler` | Nome do distrito de Portugal | object |
| `Total_Analfabet0s` | Nome do distrito de Portugal | object |
| `Total_sabem_ler` | Nome do distrito de Portugal | object |

# 💡 Problemas durante o trabalho
Durante esta pesquisa obtivemos vários dados, visto que a maioria não era confiável nem adaptável para o trabalho, em primeiro lugar fomos pesquisar em dados.org mas os dados não estavam a funcionar, de seguida obtivemos o json dos dados mas este não funcionou por ser demasiado grande, por fim optamos por fazer dos anos de 1900 e 1911, pelo facto de serem dados confiáveis e exequíveis.
Apesar de serem confiáveis o cabeçalho da tabela não estava bem construído para análise dos dados, por isso tivemos de a reformular passando assim os dados e criando o nosso próprio csv com os dados da wikipedia. Como criámos o nosso próprio csv, não foi necessário fazer a limpeza dos dados.

