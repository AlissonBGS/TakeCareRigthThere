# TakeCareRigthThere

DESCRIÇÃO DO PROJETO
    
   Aplicativo Android/Web para monitoramento de incidentes através de relatos dos usuários.

   Incidentes possíveis de denunciar:
        Acidente de trânsito
        Assalto
        Tiroteio
        Tempestade forte
        Deslizamento
        Queda de árvores
        Movimentação suspeita

RELATO:

   A interface permitirá que o usuário iniciasse o relato de forma rápida, portanto, no
menu inicial (tela pós login) já existiria um botão “Relatar”, onde o usuário preencheria um
relatório simples, com informação sobre o incidente relatado, como por exemplo:
    
   --> Incidente: um campo de escolha única para um dos incidentes disponíveis para relato.
   --> Local: Poderia ser pego pelo local do usuário através do gps ou escolhido pelo usuário
(caso já tenha saído do local do incidente).
    --> Horário: Pode ser pego pelo horário do celular ou escolhido pelo usuário (caso ja tenha
passado um tempo do incidente)
    --> Descrição: Detalhes sobre o incidente, descrição melhor do local, de já estão lidando com
a situação, se é uma denuncia grave ou não, urgência. Talvez possa ser dividida em outros
campos de formulário.
    --> Urgência/Importância: Nível de urgência do relato (nível de 0 a 5 ou por escala de
palavras), por motivos de alertas mais importantes e estatísticas sobre as regiões.

ALERTAS

No momento em que uma denúncia é feita e aprovada, é emitido um alerta para os
celulares que possuem o aplicativo instalado, conexão com internet e gps ligado, e que
estão localizadas na mesma região do incidente.
O alerta seria um notificação da aplicação, que através do relato possui um grau de
urgência, ou seja, se está acontecendo um tiroteio na região onde o usuário se localiza, a
urgência é grande, caso seja apenas um acidente de trânsito, a urgência é menor, pois a
questão é só encontrar uma rota alternativa.
Além da notificação em tempo real, é possível visualizar os incidentes de um região,
inserindo a mesma numa caixa de busca, não sendo necessário a utilização do gps.

BANCO DE DADOS

O banco de dados será povoado pelos próprios usuário em questões de relatos, portanto,
haverá uma análise de dados que dirá qual região possui mais incidentes de determinado
tipo, que seriam as partes de estatísticas retiradas dos relatos.

Questões a serem analisadas:
    Relatos falsos: É necessário verificar a veracidade do relato, portanto é muito difícil
(principalmente em grande escala) verificar cada relato, portanto é um ponto que deve ser
bastante discutido. Uma solução é existir um sistema de votos entre os usuários, para que
os próprios usuários possam dizer se o relato é verídico ou não.
    Questão de identidade do usuário: Talvez, dependendo do relato, pessoas irão querer
anonimato, portanto é uma questão complicada de discutir, pois existem muitas vertentes
que influenciam na eficiência do aplicativo (relatos falsos).
