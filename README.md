# CHECK-IN

## Script automatizado

- [2017-ENG-ESTD](https://github.com/eduardoklosowski/check-in-commiter)


## Como fazer check-in nas aulas usando git/github

1. Clonar repositório do check-in

    ```
    git clone https://github.com/univille-prof-ivan-bosnic/CHECK-IN.git
    ```

2. Criar diretório com nome do seu e-mail (necessário somente para primeiro check-in da disciplina)

    exemplo: `CHECK-IN\2017-BSI-APS\ivanbosnic@univille.br`

3. Criar arquivo referente à aula que será feito check-in, no formato `DD-MM-AAAA.txt`

    exemplo: `20-02-2017.txt` (para dia 20 de fevereiro de 2017)

4. Adicionar alteração, fazer commit e depois push para repositório remoto

    ```
    git add .
    git commit -m "presenca"
    git push
    ```
