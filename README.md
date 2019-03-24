# sphinx-soma-teste
Teste de documentação do SOMA usando Sphinx

Para iniciar o default, usei:
`sphinx-quickstart`

O comando acima cria um conjunto de arquivos iniciais com a documentação do projeto.

Para mudar o template, editei o arquivo conf.py, para acrescentar as seguintes linhas:
~~~~
import sphinx_rtd_theme
html_theme = 'sphinx_rtd_theme'
html_theme_path = [sphinx_rtd_theme.get_html_theme_path()]
~~~~

Para gerar a documentação em HTML, no diretório _build:
`make html`
