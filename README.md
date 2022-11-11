# Comandos-Git
Repositório que reúne os desafios propostos pelo [#7DaysOfCode](https://7daysofcode.io/?utm_source=ActiveCampaign&utm_medium=email&utm_content=%237DaysOfCode%3A+%F0%9F%91%A9%F0%9F%8F%BD%E2%80%8D%F0%9F%92%BB+Continue+aprofundando+seus+conhecimentos%21&utm_campaign=%5BAlura+%237Days+Of+Code%5D%28GitHub+-+1%C2%AA+Ed+%29+Conclus%C3%A3o+dos+7+dias+de+GitHub) da Alura focado em GitHub

![capa](https://www.hostinger.com.br/tutoriais/wp-content/uploads/sites/12/2019/03/Como-Renomear-um-Branch-do-Git.png)

## Desafios
- [X] **Criar** repositório no GitHub.
- [X] Alterar a descrição do seu **perfil**.
- [X] Escrever um código no GitHub.
- [ ] Fazer o upload de pasta.
- [X] Realizar **commit**.
- [X] **Clonar** o repositório para editá-lo localmente, pela sua IDE.
- [X] **Alterar** arquivo localmente com a IDE.
- [X] **Realizar** o commit dessas alterações.
- [X] **Reverter** o commit.
- [X] Simular um **conflito**
- [ ] Fazer o deploy no Github Pages

## Primeiros Comandos
No Repositório Local podemos ...

### Criar novo repositório

	git init

### Verificar estado dos arquivos/diretórios

	git status

### Adicionar

##### Adicionar um arquivo em específico

	git add arquivo.txt

##### Adicionar um diretório em específico

	git add meu_diretorio

##### Adicionar todos os arquivos/diretórios
	
	git add .

### Comitar arquivo/diretório

##### Comitar um arquivo
	
	git commit meu_arquivo.txt

##### Comitar vários arquivos

	git commit meu_arquivo.txt meu_outro_arquivo.txt
	
##### Comitar informando mensagem

	git commit meuarquivo.txt -m "minha mensagem de commit"

### Visualizar histórico
	
	git log

### Reverter commit
	
	git revert #hashd_do_commit

### Atualizar repositório local com o Remoto
	
	git pull