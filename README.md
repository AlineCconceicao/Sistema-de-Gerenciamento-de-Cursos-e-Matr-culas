# Sistema-de-Gerenciamento-de-Cursos-e-Matr-culas
Sistema de Gerenciamento de Cursos e Matrículas


Proposta de Projeto 03: Sistema de Gerenciamento de Cursos e Matrículas
Descrição: Este projeto visa criar um sistema básico para gerenciar cursos, alunos e matrículas em uma universidade, utilizando JavaScript (Node.js) com listas e objetos para simular um banco de dados. O sistema será interativo por meio do console, permitindo operações de CRUD (criar, ler, atualizar, excluir) para cursos, alunos e matrículas. O objetivo é ensinar os alunos conceitos de programação com foco em gerenciamento de dados e interação de sistemas por meio de menus e navegação no console.
Objetivos:
Ensinar conceitos básicos de manipulação de dados com listas e objetos em JavaScript.
Implementar um sistema de menus para navegar entre funcionalidades de gestão de cursos, alunos e matrículas.
Aplicar lógica de controle e repetição para manter o sistema rodando e permitir interatividade contínua.
Modularizar o código em funções para realizar operações CRUD e vincular matrículas entre alunos e cursos.
Requisitos do Sistema:
Cadastro de Cursos: Cada curso tem um código único, nome e carga horária.
Cadastro de Alunos: Cada aluno tem um número de matrícula, nome e data de nascimento.
Registro de Matrículas: Cada matrícula deve vincular um aluno a um curso, juntamente com a data da matrícula.
Listar Cursos, Alunos e Matrículas: O sistema deve permitir visualizar todos os registros cadastrados.
Atualizar e Excluir Registros: Permitir a atualização e exclusão de cursos, alunos e matrículas.
Simulação de banco de dados: Utilizar listas e objetos para armazenar temporariamente os dados em memória.
Sistema de menus: Navegação no console via menus com opções interativas.
Lista de Tarefas:
Fase 1: Planejamento e Esboço do Sistema
Desenho do Sistema:
Definir o fluxo de navegação com menus:
Tela inicial com opções para "Gerenciar Cursos", "Gerenciar Alunos" e "Gerenciar Matrículas".
Submenus para cada uma das opções, com operações de CRUD (criar, listar, atualizar, excluir).
Entrega: Esboço com o fluxo dos menus e opções, simulando como o sistema deve se comportar.
Definir a Estrutura de Dados (Listas e Objetos):
Estruturar as classes/objetos Curso, Aluno e Matricula e criar listas para armazenar os dados.
Exemplo de estrutura de dados:
const cursos = []; const alunos = []; const matriculas = [];
Entrega: Código inicial com a estrutura básica de dados (listas e objetos).
Fase 2: Implementação Básica do Sistema
Criar Menu Principal e Sistema de Navegação:
Implementar o menu principal com opções como "Cadastrar Curso", "Cadastrar Aluno", "Registrar Matrícula", "Listar Cursos", "Listar Alunos", "Listar Matrículas", "Sair".
Utilizar switch/case ou if/else para controlar o fluxo de navegação.
Entrega: Sistema de menus com navegação básica funcionando.
Cadastrar Cursos:
Criar uma função para cadastrar novos cursos na lista de cursos.
Solicitar informações como código, nome e carga horária.
Validar entradas (ex.: o código deve ser único, carga horária deve ser numérica).
Entrega: Função de cadastro de cursos funcionando.
Cadastrar Alunos:
Criar uma função para cadastrar alunos na lista de alunos.
Solicitar nome, número de matrícula e data de nascimento.
Validar as entradas (ex.: número de matrícula deve ser único).
Entrega: Função de cadastro de alunos funcionando.
Listar Cursos e Alunos:
Criar funções para listar todos os cursos e alunos cadastrados, exibindo os dados no console.
Entrega: Funções de listagem de cursos e alunos funcionando.
Fase 3: Funcionalidades Avançadas
Registrar Matrícula:
Criar uma função que permita selecionar um aluno e um curso para registrar uma matrícula.
Registrar a data da matrícula e adicionar a matrícula à lista de matrículas.
Entrega: Função de registro de matrículas funcional.
Listar Matrículas:
Criar uma função que exiba todas as matrículas registradas, mostrando o aluno, o curso e a data da matrícula.
Entrega: Função de listagem de matrículas funcional.
Atualizar e Excluir Cursos e Alunos:
Criar funções para editar os dados de cursos e alunos.
Criar funções para excluir cursos e alunos das listas.
Entrega: Funções de atualização e exclusão funcionando corretamente.
Fase 4: Refinamento e Conclusão
Refinar o Sistema:
Revisar o código e testar todas as funcionalidades para garantir que não há erros.
Melhorar a experiência do usuário (ex.: adicionar mensagens de sucesso e erro).
Entrega: Sistema completo e funcional.
Documentar o Projeto:
Escrever uma documentação explicando o funcionamento do sistema, como rodá-lo e o que cada parte do código faz.
Entrega: Documentação finalizada.
Apresentação do Projeto:
Preparar uma apresentação explicando as funcionalidades e como o sistema foi desenvolvido.
Entrega: Apresentação para a turma ou professores.

Ferramentas Necessárias:
Node.js: Para rodar o sistema backend.
Editor de Texto/IDE: VSCode, Sublime, ou qualquer outro editor de preferência.
Terminal/Console: Para rodar e testar o sistema via linha de comando.
Prazos Sugeridos:
Fase 1 - Planejamento e Desenho do Sistema: 1 semana.
Fase 2 - Implementação Básica: 2 semanas.
Fase 3 - Funcionalidades Avançadas: 2 semanas.
Fase 4 - Refinamento e Conclusão: 1 semana.
Total estimado: 6 semanas para a conclusão do projeto.


