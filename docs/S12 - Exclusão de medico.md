![12 - Exclusão de Médico](.img/s12_exclusao_de_medico.jpg)

# S12 - Exclusão de Médico

Foi criado um controller deleteDoctor.js
Foi atualizado o arquivo doctorRoutes.js
A busca é feita pelo identificador do médico e retorna mensagem de erro se não for encontrado.

- **URL**: `DELETE /api/doctor/:ID`

O endpoint ficou : `http://localhost:6666/doctor/:ID`

Não precisa informar nada no corpo da requisição

# Não há resposta de sucesso

# Possíveis respostas de erro

````

{ message: "Doctor not found" }

{ message: "Failed to delete doctor", error: error.message }
````

### final do Projeto S12 - Exclusão de Médico
