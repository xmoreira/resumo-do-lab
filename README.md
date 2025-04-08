# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

Entendendo a relação entre SLA e a inatividade de um recurso nativo, fica claro que se eu crio este recurso e ele fica por mais tempo inativo do que o SLA contratado a Microsoft terá que ressarcir o valor.
É importante saber o tempo de inatividade para cada modelo de SLA, pois, quanto maior o SLA, menos tempo de inatividade, porém mais caro e quanto mais mais noves na porcentagem do SLA, menos tempo de inatividade.
Quando vamos criar uma máquina virtual, temos as "Opções de Disponibilidade", onde podemos selecionar a forma de disponibilidade e em zona de disponibilidade, selecionamos as zonas em que queremos que a máquina virtual seja criada.
Em "Opções de Disponibilidade" é apresentado também outras estratégias que podemos usar para criar as máquinas virtuais, como "Conjunto de Dimensionamento de Máquinas Virtuais", "Conjunto de Disponibilidade" além da própria "Zona de disponibilidade", que assim para cada opção existe o SLA respectivo.
Em "Redundância" podemos selecionar qual será a estratégia de replicação como: LRS, GRS, ZRS e GZRS, que siginifica que estaremos replicando este dado entre data centers ou regiões, influenciando assim no SLA.
Quanto mais o recurso é replicado, menos tempo de indisponibilidade, pois o dado estará replicado em mais data centers, ajudando assim no caso de um desastre e na disponibilidade de uma informação, pois após o registro dos dados, eles são copiados para uma segunda região ou zona, influenciando do SLA como também nos custos.
Por isso então a importância do profissional arquiteto entender o propósito da criação do recurso, se é para produção ou se é para teste ou se é para ver se funciona, pois este não entendimento poderá acarretar em um alto custo, e entendo melhor a finalidade do recurso poderá ser acertivo nas melhoras para este recurso.
