# 🩺 Projeto Integrador - Front-end

Este repositório contém o front-end do projeto desenvolvido para a disciplina de **Projeto Integrador**, com foco na criação de um sistema voltado para a área médica.

O sistema permite que médicos criem **formulários personalizados** para realização de **pesquisas clínicas**, com o objetivo de **auxiliar na obtenção de diagnósticos mais precisos** para seus pacientes.

Neste sistema, os médicos podem adicionar fórmulas que utilizam dados obtidos por meio do formulário para colaborar com o diagnóstico. Todo o processo é automatizado, ou seja, a partir do momento em que a fórmula é adicionada ao formulário, o próprio sistema realiza o cálculo e devolve o resultado, tornando o diagnóstico mais eficiente.

---

## ⚙️ Requisitos

- [Docker](https://www.docker.com/) instalado

---


## Como Executar em Desenvolvimento

### 1. Clonar este Repositório

```bash
git clone https://seu-repositorio.git
```


### 2. Build dos Contêineres

Para construir o contêiner:

```bash
docker compose build 
```

Caso queira forçar a reconstrução sem usar cache:

```bash
docker compose build --no-cache
```

### 4. Subir o Projeto

Depois de construir, execute:

```bash
docker compose up
```

