# Tabela CFOP em SQL
Script que gera a tabela de CFOPs em SQL para implementação em banco de dados

### Instruções:
- Alterar a linha 8 com os dados da tabela usada no BD
- Alterar a linha 17 caso deseja que a descrição não esteja em caixa alta
```
sql += "('%s', '%s'), " % (cfop, descricao.upper())
```
para
```
sql += "('%s', '%s'), " % (cfop, descricao)
```
- O campo ```descricao``` deverá ser um varchar com tamanho maior que 300, sugiro 350.
- Executar o script com Python 3
