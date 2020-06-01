# advpl-excel
Classe em ADVPL para gerar planilhas do excel no formato xlsx com menor consumo de memória e mais otimizado.

# Recursos disponíveis
* Definir células String,Numérica,data,DateTime,Logica,formula
* Adicionar novas planilhas(Nome,Cor)
* Cor de preenchimento(simples,efeito de preenchimento)
* Alinhamento(Horizontal,Vertical,Reduzir para Caber,Quebra Texto,Angulo de Rotação)
* Formato da célula
* Mesclar células
* Auto Filtro
* Congelar painéis(colunas e linhas)
* Definir tamanho da coluna
* Definir tamanho da linha
* Formatar numeros(casas decimais)
* Letra: Fonte,Tamanho,Cor,Negrito,Italico,Sublinhado,Tachado
* Bordas: (Left,Right,Top,Bottom),Cor,Estilo
* Formatação condicional:(operador,formula)(font,fundo,bordas)
* Formatar como tabela(Estilos Predefinidos,Filtros,Totalizadores)
* Cria nome para referência de célula ou intervalo
* Agrupamento de linha
* Imagens
* Exibir/Oculta linhas de Grade
* Definir linha para repetir na impressão

* Leitura simples dos dados

# Testes
Arquivo excel gerado: [pasta2.xlsx](exemplo/pasta2.xlsx)

![Exemplo1](/exemplo/excel1.png)

Auto Filtros,Congelar painéis,Agrupar linhas:

![Exemplo2](/exemplo/excel2.png)

Formatar como tabela:

![Exemplo2](/exemplo/excel3.png)

Exemplo de uso:

[tstyexcel.prw](exemplo/tstyexcel.prw)<br>
[Olá Mundo](https://github.com/saulogm/advpl-excel/wiki/Ol%C3%A1-Mundo)

# Instalação
1. Compilar Fontes da pasta src

Pronto para usar a classe YExcel!

### Dúvidas
- Email: saulomax@gmail.com
- GitHub: https://github.com/saulogm


# Observação
Caso a build seja inferior a 7.00.131227 - 13.2.3.17 é necessario instalar o 7-Zip.
Instalar o 7-Zip (http://www.7-zip.org/)
Configurar o appserver.ini com o caminho do 7-Zip.
```
[GENERAL]
LOCAL7ZIP=C:\Program Files\7-Zip\7z.exe
```

# Agradecimentos
[Samuel Gomes Martins] (https://github.com/samuelgmartins)
