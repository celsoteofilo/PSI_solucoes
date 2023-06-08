# Padrão do Projeto

Com base nos requisitos fornecidos, podemos relacionar os padrões de criação mencionados anteriormente aos requisitos do software para a clínica de psicologia da seguinte forma:

Factory Method (Método de Fábrica):

Requisito relacionado: [RF007] O Software deve realizar cadastro de novos funcionários.
Descrição: O Factory Method pode ser aplicado para permitir que a clínica crie diferentes tipos de funcionários (psicólogos, assistentes, administrativos) por meio de uma interface comum. Cada tipo de funcionário seria uma subclasse que implementa a interface e decide qual classe concreta instanciar.
Singleton:

Requisito relacionado: [RF010] O Software deverá disponibilizar localização da clínica e filiais.
Descrição: O Singleton pode ser utilizado para garantir que a classe responsável pela localização da clínica seja uma instância única acessível globalmente. Isso permitiria o compartilhamento dos dados de localização entre diferentes partes do sistema.
Builder (Construtor):

Requisito relacionado: [RF008] O Software deve realizar inpute de novos dados sobre cada paciente durante as consultas realizando um update em seu usuário.
Descrição: O Builder pode ser empregado para separar a construção do objeto "paciente" de sua representação final. Durante as consultas, o software pode coletar informações sobre o paciente passo a passo e, ao final, utilizar um builder para criar um objeto paciente com base nessas informações coletadas.
É importante ressaltar que essas são apenas sugestões de aplicação dos padrões de criação com base nos requisitos fornecidos. A escolha final dependerá da arquitetura e das necessidades específicas do projeto. É recomendado analisar cuidadosamente cada requisito e considerar como os padrões podem ser aplicados de forma efetiva para atender aos objetivos do software da clínica de psicologia. 
