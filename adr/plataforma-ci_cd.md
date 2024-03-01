# Plataforma Frontend

**Data:** 22/02/2024

## Contexto
Plataforma de ci/cd para automação do processo de entrega do produto.

## Decisão
Será utilizado o Github Actions para criação das pipelines de CI/CD

- **Integração Nativa com o GitHub:** GitHub Actions é nativamente integrado ao GitHub, proporcionando uma experiência de usuário mais fluida e uma configuração simplificada para projetos hospedados no GitHub. A configuração do fluxo de trabalho pode ser definida diretamente nos arquivos do repositório.
- **Modelo de Preços:** GitHub Actions oferece um modelo de preços competitivo, especialmente para projetos de código aberto e pequenas equipes. Ele inclui uma quantidade generosa de 2.000 minutos gratuitos para a execução de workflows, tornando-o atraente para projetos com orçamentos limitados.
- **Workflow Configurado como Código:** Os workflows do GitHub Actions são definidos usando arquivos YAML que residem no repositório. Isso facilita a compreensão, versionamento e colaboração em fluxos de trabalho, além de permitir uma integração contínua e entrega contínua declarativas.

## Consequências

- **Limites de Tempo de Execução:**
O GitHub Actions impõe limites de tempo de execução para os workflows. Se um workflow exceder esses limites, pode ser necessário ajustar a lógica ou dividir o trabalho em etapas menores. Isso pode ser uma desvantagem para projetos que requerem execuções prolongadas.
- **Limites Gratuitos para Repositórios Privados:**
Embora o GitHub Actions ofereça uma quantidade generosa de minutos gratuitos para execução de workflows em repositórios públicos, há limites mais restritos para repositórios privados, o que pode afetar projetos maiores ou equipes com necessidades intensivas de CI/CD.
