# GERENCIADOR DE TAREFAS E HÁBITOS


## O QUE QUERO?
Um sistema para gerenciamento de tarefas, que permitirá que o usuário faça inclusão, alteração, consulta e exclusão de tarefas e hábitos. 
Consultas avaçadas como por exemplo, filtrar as tarefas e hábitos. O programa também terá interface gráfica Java Swing e persistência de dados. 
O sistema precisa que tenha herança, interfaces e polimorfismo.


## CLASSES
- Atividade(Classe abstrata)
  - id : int
  - nome : String
  - descrição(explicação mais detalhada da tarefa ou hábito) : String
  - categoria : String
  - status : boolean(True - Iniciado / False - Pendente)
  - prioridade(baixa, média, alta) : int
  - data criação : Date
  - frequência : String
    - 
    - Tarefa extends Atividade
      - data final : String
    - Hábito extends Atividade
      - Meta : int (quanto tempo terá para fazer o hábito) 


## INTERFACES
- controlar atividade
  - criarAtividade()
  - consultarAtividade()
  - atualizarAtividade()
  - deletarAtividade()
  - listarTodasAtiviades()