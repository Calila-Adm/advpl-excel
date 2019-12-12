# advpl-excel
Classe em ADVPL para gerar planilhas do excel no formato xlsx com menor consumo de mem�ria e mais otimizado.

# Recursos dispon�veis
* Definir c�lulas String,Num�rica,data,DateTime,Logica,formula
* Adicionar novas planilhas(Nome,Cor)
* Cor de preenchimento(simples,efeito de preenchimento)
* Alinhamento(Horizontal,Vertical,Reduzir para Caber,Quebra Texto,Angulo de Rota��o)
* Formato da c�lula
* Mesclar c�lulas
* Auto Filtro
* Congelar pain�is(colunas e linhas)
* Definir tamanho da coluna
* Definir tamanho da linha
* Formatar numeros(casas decimais)
* Letra: Fonte,Tamanho,Cor,Negrito,Italico,Sublinhado,Tachado
* Bordas: (Left,Right,Top,Bottom),Cor,Estilo
* Formata��o condicional:(operador,formula)(font,fundo,bordas)
* Formatar como tabela(Estilos Predefinidos,Filtros,Totalizadores)
* Cria nome para refer�ncia de c�lula ou intervalo
* Agrupamento de linha
* Imagens
* Exibir/Oculta linhas de Grade
* Definir linha para repetir na impress�o

* Leitura simples dos dados

# Testes
Arquivo excel gerado: [pasta2.xlsx](exemplo/pasta2.xlsx)

![Exemplo1](/exemplo/excel1.png)

Auto Filtros,Congelar pain�is,Agrupar linhas:

![Exemplo2](/exemplo/excel2.png)

Formatar como tabela:

![Exemplo2](/exemplo/excel3.png)

Exemplo de uso:

[tstyexcel.prw](exemplo/tstyexcel.prw)

# Instala��o
1. Compilar Fontes da pasta src

Pronto para usar a classe YExcel!

### D�vidas
- Email: saulomax@gmail.com
- GitHub: https://github.com/saulogm


# Observa��o
Caso a build seja inferior a 7.00.131227 - 13.2.3.17 � necessario instalar o 7-Zip.
Instalar o 7-Zip (http://www.7-zip.org/)
Configurar o appserver.ini com o caminho do 7-Zip.
```
[GENERAL]
LOCAL7ZIP=C:\Program Files\7-Zip\7z.exe
```

# Agradecimentos
[Samuel Gomes Martins] (https://github.com/samuelgmartins)