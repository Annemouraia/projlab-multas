# Projlab · Controle de Multas e Frotas

Aplicativo web para controle de multas, gestão de frota e documentações (veículos e motoristas) da Projlab.

## Como acessar

Depois de ativar o GitHub Pages nas configurações deste repositório, o link fica no formato:
`https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`

Também é possível abrir o arquivo `index.html` direto no navegador, sem internet.

## Funcionalidades

- Dashboard com indicadores de multas e alerta de documentos vencendo
- Registro de multas com indicação de motorista
- Gestão de frota (veículos, responsáveis, status)
- Documentação dos veículos (CRLV, Seguro, IPVA, Revisão, Inspeção)
- Documentação dos motoristas (CNH, RG, CPF, Exame Toxicológico)
- Ranking de motoristas por número de infrações
- Relatórios com exportação em CSV e backup completo em JSON

## Sobre o armazenamento de dados

Os dados ficam salvos no navegador (localStorage) do dispositivo usado para acessar o app. Isso significa:

- O histórico continua lá da próxima vez que você abrir o mesmo link, no mesmo navegador
- Não há sincronização automática entre computadores, navegadores ou celulares diferentes
- Para levar os dados de um dispositivo para outro, use o botão de backup em JSON na aba **Relatórios**
