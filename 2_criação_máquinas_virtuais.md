# Criação de máquinas virtuais na Azure

1. Acesse o portal.
2. Acesse "Todos os recursos".
3. Clique em "Criar".
4. Na tela inicial já deverá aparecer "Máquina Virtual". Caso não apareça, digite na caixa de busca.

![](https://raw.githubusercontent.com/henriquebjr/az900-dio/main/resources/criar_maquina_virtual.png)

5. Escolha a Assinatura e o Grupo de recursos.
6. Informe o nome da instância.
7. Selecione uma Região.
8. Selecione uma "Opção de disponibilidade". Há três opções de redundância. Escolhe a que fizer mais sentido para o seu projeto.

![](https://raw.githubusercontent.com/henriquebjr/az900-dio/main/resources/opções_disponibilidade.png)

9. Escolha uma das "Opções de zona".
10. Caso tenha escolhido "Zona auto-selecionada", será possível indicar as zonas de instância no campo "Zona de disponibilidade".

![](https://raw.githubusercontent.com/henriquebjr/az900-dio/main/resources/zona_disponibilidade.png)

11. Caso em "Opções de disponibilidade" tenha escolhido "Conjunto de dimensionamento de máquinas virtuais", crie um novo conjunto.
12. Informe os demais campos.
13. Clique em próximo.
14. Selecione o tipo de armazenamento.
15. Recomendação: marque a opção "Excluir com VM" para não deixar discos perdidos gerando custos financeiros.
16. Clique em próximo.
17. Selecione uma rede virtual existente ou crie uma nova.
18. Recomendação: marque a opção "Excluir o ip público e a NIC quando a VM for excluída" para não continuar gerando custos quando a VM for excluída.
19. Clique em próximo para acesso passo de "Gerenciamento".
20. Selecione o tipo de autenticação e configuração desligamento automático.
21. Informe se deseja habilitar o backup. Por padrão, o backup é executado uma vez ao dia.
22. Também possível configurar notificações e alertas de monitoramento.
23. Clique em próximo.
24. No passo "Avançado" é possível configurar extensões, como funcionalidades extras.
25. Clique em próximo.
26. No passo "Marcas" é possível informar identificadores para facilitar no manuseio do recursos, principalmente para identificar origem de custos.
27. Clique em "Revisar + criar", e caso esteja tudo certo conforme esperado, clique em "Criar".
