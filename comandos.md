git checkout -b <<nome da branch>>

-- Cria uma branch nova à partir da branch em que o usuário está.

git pull origin <<nome da branch>>

-- Faz a mesclagem das branchs, sem necessidade de commit apenas atualiza o que está na branch <<>> e joga na branch atual, não mantem a rastreabilidade de que houve o merge

git merge --no-ff <<nome da branch>>
-- Faz a mesclagem das branchs, mas informa que houve uma mesclagem através de um commit de merge