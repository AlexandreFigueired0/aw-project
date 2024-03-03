## Decision Drivers

1. Tem apenas a responsabilidade de ler um qr code e identificar o produto associado a esse qr code.
2. É uma parte independente do negócio, sendo uma das principais features da app QRmeat.
3. Apresenta lógica complexa o suficiente para ser atribuido a uma equipa, sendo necessarias implementações a nível das camadas de apresentação (scanner), lógica (processamento e interpretação do código QR) e dados (para aceder aos detalhes do produto associado ao código QR)