# Dashboard de Suprimentos — SE UTE Pilar / LT / SE Rio Largo II

Painel de controle de suprimentos (230 kV), gerado a partir de "1. Controle de Suprimentos.xlsx"
(abas Pré Contrato, MC - UNT COM DIFAL, Checklist Comparativo do Escopo, Controle WEG e
Procurement - Lista Controle R0).

**Repositório privado** — contém preços reais de fornecedores (GE, Siemens, Hubbell, Arteche,
Balteau, Sieyuan, TE Connectivity, WEG, Pfiffner) e não deve ser tornado público.

## Como visualizar

Abra `Dashboard Suprimentos.html` diretamente no navegador (arquivo estático, não precisa de
servidor).

## Como atualizar

Rode `atualizar_dashboard.bat` (na pasta de trabalho do Excel) sempre que quiser subir uma nova
versão do dashboard para este repositório. O script copia o HTML mais recente, comita e envia
para o GitHub — funciona como backup/histórico de versões, não como site publicado.
