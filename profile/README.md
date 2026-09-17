<p align="center">
  <img src="./PRP - sem fundo 1.png" alt="Logo PRP Soluções" width="200"/>
</p>

# Controle de Versões de Sistemas

## 1.Objetivo
Definir o padrão de versionamento das aplicações, garantindo:

- Rastreabilidade das alterações realizadas;
- Controle das liberações em produção;
- Histórico de evoluções e correções;
- Facilidade de comunicação entre equipes técnicas e usuários.

## 2. Padrão de Versionamento

Será adotado o padrão MAJOR.MINOR.PATCH.

### Descrição
MAJOR:	Alterações significativas ou que impactem funcionalidades existentes  
MINOR:	Inclusão de novas funcionalidades sem quebrar compatibilidade  
PATCH:	Correções de erros e pequenos ajustes  

### Exemplos
|Versão|Descrição|
|------|---------|
|1.0.0 |Primeira versão oficial|
|1.1.0 |Nova funcionalidade adicionada|
|1.1.1 |Correção de erro|
|2.0.0 |Grande reformulação do sistema|

## 3. Registro das Alterações

Toda alteração deve ser registrada em um histórico de mudanças (Changelog).

### Modelo
|Versão|Descrição|
|------|---------|
|1.0.0 |Implantação inicial|
|1.1.0 |Inclusão de relatório|
|1.1.1 |Correção de erro de cálculo|
