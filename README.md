# tempCNMAC1

Padrão LaTeX para submissão de trabalho/resumo na categoria 1 do CNMAC.

## Como compilar

	pdflatex resumo
	biber resumo
	pdflatex resumo
	pdflatex resumo

### Linux

Alternativamente, em sistema operacional Linux ou compatível, pode-se compilar com

	$ make

Para mais informações, consulte o arquivo `Makefile`.

## Arquivos

Os dois arquivos que você precisará editar são:

- `resumo.tex`: arquivo principal contendo o código-fonte LaTeX do trabalho/resumo.

- `ref.bib`: arquivo formato BibTeX/BibLaTeX contendo os dados das referências bibliográficas.

O arquivo `pssbmac.cls` contém as definições da classe do documento padrão a ser gerado. __Este arquivo deve ser utilizado como tal, não devendo ser alterado__.

Os demais arquivos são auxiliares:

- `resumo.pdf`: exemplo do PDF a ser gerado.

- `ex_fig.jpg`: arquivo de imagem utilizada como exemplo.

- `Makefile`: Makefile para geração do arquivo em terminal Linux ou compatível.

## Créditos

Elaborado para SBMAC - Sociedade de Matemática Aplicada e Computacional (https://www.sbmac.org.br/).

## Licença

Este trabalho está licenciado sob a Licença Creative Commons Atribuição-CompartilhaIgual 4.0 Internacional. Para ver uma cópia desta licença, visite http://creativecommons.org/licenses/by-sa/4.0/ ou envie uma carta para Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.


