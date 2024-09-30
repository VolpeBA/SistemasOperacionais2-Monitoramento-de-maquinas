# Sistemas Operacionais II
- Projeto desenvolvido com o objetivo de conclusão da matéria de "Sistemas Operacionais II" no curso de Análise e desenvolvimento de sistemas e para portfólio pessoal.

# Sobre o projeto
- Este é um programa que busca muitas informações do sistema de arquivos virtual Linux, como temperatura da CPU, uso de memória RAM, tráfego de rede, além de chamar alguns comandos bash como 'who' e 'ps'. Em seguida, grava todas as informações no InfluxDB para que o Grafana possa renderizar alguns gráficos legais com tudo isso.

<div align="center">
<image src="/Dashboard.png" width="1000px" center>
</div>

# Dependências
- Python 3
- influxdb-python [Github link](https://github.com/influxdata/influxdb-python)
- InfluxDB [Offical website](https://www.influxdata.com/get-influxdb/)
- Grafana [Official website](https://grafana.com/get)
- Docker [Official website](https://www.docker.com/)

## Instalação

1. Instale todas as dependências acima.
2. Habilite os serviços InfluxDB e Grafana
3. Clone ou baixe este repositório.

## Uso
1. Execute medidas.py

```bash
$ python3 medidas.py
```

2. Por padrão, o Grafana pode ser acessado por um navegador em ‘localhost:3000’.
3. Importe o dashboard disponível neste repositório.

# Cronologia do projeto

# Semana 1
Estudando o projeto e analisando.

# Semana 2
Iniciando os trabalhos e instalando as dependências.

# Semana 3
Codificando e iniciando configuração.

# Semana 4
Corrigindo bugs no codigo, na proxima semana irei configurar uma maquina linux para rodar o projeto na apresentação.
