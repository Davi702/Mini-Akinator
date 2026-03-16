# Projeto Mini-Akinator: Árvore de Decisão
Este projeto é um sistema de adivinhação inspirado no jogo Akinator, desenvolvido para a disciplina de Estrutura de Dados Avançada. O software utiliza uma estrutura de Árvore Binária de Decisão para chegar a uma resposta final através de perguntas de "Sim" ou "Não".

# 🚀 Funcionalidades
Adivinhação Inteligente: O sistema percorre a árvore baseando-se nas respostas do usuário.

Aprendizado Incremental (Extensão): Caso o sistema erre, ele solicita a resposta correta e uma pergunta diferenciadora, expandindo a árvore dinamicamente em tempo de execução.

Demonstração Técnica: Implementação e visualização dos percursos BFS (Busca em Largura) e DFS (Busca em Profundidade).

# 📂 Estrutura de Arquivos
src/main.py: Ponto de entrada que orquestra o menu e as execuções.

src/tree_models.py: Definição da classe Node e construção da árvore inicial.

src/algorithms.py: Implementação dos algoritmos de percurso BFS e DFS.

src/game_logic.py: Lógica principal do jogo e funções de aprendizado.
