# Controle de Níveis de Água - Monitoramento de Reservatório

Projeto desenvolvido em Python para simular o monitoramento de um reservatório de água em ambiente de terminal, utilizando cores dinâmicas para indicar níveis de risco.

##  Tecnologias e Conceitos Utilizados
- **Python 3.x**
- **Estruturas de Dados:** Listas de dicionários para armazenar os níveis e alertas.
- **Funções:** Organização modular do código.
- **Biblioteca Colorama:** Aplicação de cores e restauração automática do estilo padrão do terminal.

##  Níveis de Alerta Monitorados
1. **Nível 1:** Muito baixo (crítico) -> Vermelho
2. **Nível 2:** Baixo -> Amarelo
3. **Nível 3:** Médio -> Verde
4. **Nível 4:** Alto -> Ciano
5. **Nível 5:** Muito alto (alerta) -> Azul

## Como Executar
1. Instale a biblioteca colorama:
   ```bash
   pip install colorama
