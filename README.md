# Projeto prático

- Nesta atividade será desenvolvida uma atividade básica com git visando a aplicação dos seguintes passos:
    - Criação de repositório via github;
    - Clone do repositório localmente;
    - Criação de uma branch **feature/{identificador}**;
    - Commit inical;
    - Criação de um **Pull Request**;
    - Aceitar o **Pull Request**;
    - Alteração do README.md;
    - Envio das informações alteradas no README.md para a main;

# Versionamento Semântico

- Versionamento semântico nada mais é que um conjunto de praticas adotadas para estruturar e guiar a manutenção das versões de um projeto. Este por sua vez utiliza como base um conjunto de principios, como:
    - Estrutura de versões major.minor.patch, por exemplo, 1.0.0. 
        - A ideia por trás desta estrutura é organizar versões maiores e mais importantes representadas pela **major**, esta versão geralmente irá representar um ponto fixo no desenvolvimento e as features seguintes irão depender desta, exemplo, **1**.0.0, **2**.0.0 ou **3**.0.0;
        - A **minor**, por outro lado lida, com as atualizações menores dentro da major, tratando algumas mudanças de menor escala que não seriam signativas o suficiente para formatar uma nova versão **major**, exemplo 1.**1**.0 ou 1.**2**.0;
        - Os patches corrigem bugs ou funcionalidades com inconsistencias menores e menos significantes, exemplo 1.1.**2**, 1.3.**4**;
- Além desta também existem outros principios que podem ser seguidos em versionamento semantico, tendo como foco evitar que as atualizações do software quebrem o que já está no ar;  