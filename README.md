# Iniciativa Kubernets - Mar/2022

Repositorio para o desafio da aula 01 da Iniciativa Kubernets

## Como usar?

### Pré requisitos:

1. Ter o docker instalado
2. Ter o GIT instalado

### Criando a imagem:

1. **Clonar o repositorio :**
```
git clone https://github.com/GleitonCampos/conversao-temperatura.git
```
2. **Fazer o build da imagem no Docker:**
```
docker image build -t NOME_DA_IMAGEM .
```
3. **Executar o container:**
```
docker container run -d -p 8080:8080 NOME_DA_IMAGEM
```
4. **Acessar o docker host na porta selecionada e verificar:**

![image](https://user-images.githubusercontent.com/7107690/161099798-604b42e0-699a-4218-b780-1716df480ab0.png)
