<p align="center">
  <img src="https://github.com/juuwes/mjv-java-school/assets/93749428/2717ad8f-53e4-47e5-9425-72f2fc1bfbb0" alt="Sublime's custom image" width="400"/>
</p>

<h1 align="center">CONTRATE.me - Projeto Final da MJV School Java</h1>

<p align="justify"> <b>CONTRATE.me</b> é uma plataforma que simplifica o recrutamento e seleção de talentos na área de tecnologia. É um repositório centralizado onde profissionais podem armazenar suas informações pessoais e profissionais, destacando suas experiências e habilidades. As empresas podem usar a plataforma para encontrar candidatos qualificados, realizando pesquisas avançadas e entrando em contato diretamente com os profissionais. É uma solução eficiente para conectar talentos e oportunidades de emprego na tecnologia. </p>

## Documentação 📝

A API conta com uma documentação detalhada disponível no <i>Swagger</i>, que pode ser acessada pelo link: [Contrata.me](http://localhost:8080/swagger-ui/index.html#/)

## Tecnologias e Ferramentas ⚙️

<p align="justify"> Foi utilizado <i>Spring Data JPA</i> para implementar a camada de persistência da dados.

**Linguagem:** Java (<i>versão: 11</i>)

**Framework:** Spring Boot (<i>versão: 2.7.9</i>)
      
- <i>Dependências do Spring</i> : DataJPA | Validation |  Starter WEB | DevTools | Lombok | MySQL | Swagger | ModelMapper

**Banco de Dados:** MySQL

**Plataforma de API:** Postman

**Documentação da API:** Swagger

**IDE:** IntelliJ IDEA

**Modelagem UML:** Lucidchart
</p>

## Diagrama UML 📈

  <img src="https://github.com/juuwes/mjv-java-school/assets/93749428/f469b28f-e831-4879-80f0-a86b508a7f14" alt="Sublime's custom image" width="550"/>

## Estrutura e Pacotes 🗂️

- configs
- DTOs
- enums
- exceptions
- models
- repositories
- resources
- services

## Schemas - JSON 📋

**PROFISSÕES**

```json
{
  "nome": "Desenvolvedor de Sistemas Java Jr"
}
```

__________________________

**HABILIDADES** 

```json
{
  "nome": "Java"
}
```
  
__________________________

**CIDADES**
```json
{
  "nome": "Curitiba",
  "estado": "Paraná",
  "sigla": "PR"
}
```

__________________________

**CANDIDATOS**

```json
{
  "nome": "Maria Silva",
  "cpf": "441.570.480-83",
  "dataNascimento": "12/05/1990",
  "sexo": "FEMININO",
  "email": "maria.silva@gmail.com",
  "profissao": 1,
  "telefoneCelular": {
    "numero": "5511987654321",
    "whatsapp": true
  },
  "telefoneFixo": "551112345678",
  "endereco": {
    "bairro": "Centro",
    "cep": "12345000",
    "cidade": 17,
    "logradouro": "Rua das Flores",
    "numeroEndereco": "123",
    "complemento": "Apartamento 456"
  },
  "pretensaoSalarial": {
    "valorMaximo": 4000.00,
    "valorMinimo": 2500.00
  },
  "habilidades": [1, 2, 3, 4],
  "experiencias": [
    {
      "dataContratacao": "01/03/2010",
      "empregoAtual": false,
      "empresa": "ABC Comércio",
      "profissao": 3,
      "regimeContratacao": "CLT",
      "salario": 3500.00,
      "dataDesligamento": "31/12/2019"
    },
    {
      "dataContratacao": "01/01/2020",
      "empregoAtual": true,
      "empresa": "XYZ Indústria",
      "profissao": 3,
      "regimeContratacao": "CLT",
      "salario": 4200.00,
      "dataDesligamento": ""
    }
  ]
}
```

## Rotas 🧭

**PROFISSÃO**

<img src="https://github.com/juuwes/mjv-java-school/assets/93749428/0f42460d-05be-420c-b212-9cd1465c74c6" alt="Sublime's custom image" width="900"/>

_____________________________

**HABILIDADE**

<img src="https://github.com/juuwes/mjv-java-school/assets/93749428/2a48fea2-752e-4d44-b2c1-a88c7c7604d4" alt="Sublime's custom image" width="900"/>

_____________________________

**CIDADE**

<img src="https://github.com/juuwes/mjv-java-school/assets/93749428/a6c2610c-b6a2-40fc-b3e3-efa7f6be2aef" alt="Sublime's custom image" width="450"/>

_______________________________

**CANDIDATO**

<img src="https://github.com/juuwes/mjv-java-school/assets/93749428/c716ce3b-5bd1-45eb-aed1-5de65c54673c" alt="Sublime's custom image" width="900"/>

<img src="https://github.com/juuwes/mjv-java-school/assets/93749428/6fceb9c9-b8de-472a-9387-0d34da3b3ea9" alt="Sublime's custom image" width="900"/>

## Colaboradores 💻

- <a href="https://github.com/EriksonsSilva"> Erikson Silva </a>
- <a href="https://github.com/fabiopenha"> Fábio Penha </a>
- <a href="https://github.com/JonathanZapotosczny"> Jonathan Zapotosczny </a>
- <a href="https://github.com/Juuwes"> Juliana Gonçalves </a>
- <a href="https://github.com/JulioDinis"> Julio Dinis </a>
- <a href="https://github.com/KaylaDeodato"> Kayla Deodato </a>
- <a href="https://github.com/VictorAlmeida98"> Victor Almeida </a>
