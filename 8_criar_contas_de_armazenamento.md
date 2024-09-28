# Criar contas de armazenamento

1. Acesse o portal.
2. Acesse no menu esquerdo "Todos os serviços".
3. Na caixa de busca, informe "contas de armazenamento".
4. Clique em "Contas de armazenamento".
5. Clique em "Criar".
6. Informe Assinatura e Grupo de recursos.
7. Informe o "Nome da conta de armazenamento". Deverá conter apenas números e letras minúsculas, e deverá ser um identificador único (ninguém poderá estar usando a mesma combinação).
8. Informe uma Região.
9. Informe o "Desempenho". O "standard" é o mais comum, sendo "premium" fazendo sentido apenas casos em que a demanda de desempenho é muito alta.
Obs: premium cobra a alocação total, mesmo que não esteja utilizando.
10. Selecione a redundância desejada:
- LRS (redundância local): 3 cópias no mesmo datacenter.
- GRS (redundância geográfica): 3 cópias no mesmo datacenter mais 3 cópias em um datacenter de uma região diferente.
- ZRS (redundância de zona): 3 cópias em diferentes datacenters da mesma região.
- GZRS (redundância geográfica e de zona): 3 cópias em diferentes datacenters da mesma região mais 3 cópias de diferentes datacenters de uma segunda região.
Escolha LRS apenas para ambientes de testes e fique com GRS ou ZRS para a maioria dos casos.

![](https://raw.githubusercontent.com/henriquebjr/az900-dio/main/resources/criar_conta_armazenamento.png)

11. Clique em próximo.
12. Na aba "Avançado" informe as preferências de Segurança, Protocolos de Acesso, Armazenamento de Blobs e Arquivos do Azure. Note que em "Camada de Acesso" há as opções de Quente ou Frio, sendo quente mais indicado para usos normal de aplicação e frio para backups.
13. Clique em próximo.
14. Em "Rede" configure as preferências de acesso. Pode manter as configurações sugeridas.
15. Clique em próximo.
16. Em "Proteção de dados" talvez seja uma boa opção desmarcar as opções "Habilitar a exclusão temporária para blobs" e "Habilitar a exclusão temporária para contêineres", caso não seja um ambiente de produção.
17. Clique em próximo.
18. Configurações de criptografia pode deixar as configurações sugeridas.
19. Clique em próximo.
20. Adicione as marcas (tags) desejadas.
21. Clique em avançar.
22. Caso esteja tudo correto, clique em Criar.