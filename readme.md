# SOLID

## Interface Segregation Principle (ISP) - Princípio da Segregação de Interface
### "Uma classe não deve ser forçada a implementar interfaces e métodos que não irão utilizar." -- Robert C. Martin

### Temos duas classes que implementam a interface Reajuste, porém na regra de negócio proposto nesse desafio apenas a classe Promocao deve implementar o método valorImpostoDeRenda(), pois o reajuste salarial anual é isento de imposto de renda, ou seja a classe Anuenio não deverá ser forçada a implementar o método valorImpostoDeRenda(), proponha uma solução utilizando o principio ISP.