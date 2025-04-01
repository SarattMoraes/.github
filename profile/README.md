<div align="center">


<br>
  
  ![Banner](https://saratt.com.br/wp-content/uploads/2021/08/logo-topo-saratt.png)



<br>

## 🗃️ Nomenclatura de repositórios
</div>



   ```
   <Categoria>_<NomeProjeto>_<Descricao>_<Versao>
   ```
   ##### Onde:
   - **Categoria**: RPA, DAG, ETL, AUTO, WEB, etc.
   - **NomeProjeto**: Nome simples e único, identificando a finalidade do projeto.
   - **Descricao** (opcional): Descrição curta para detalhar mais o que o repositório faz.
   - **Versao** (opcional): Se aplicável, pode incluir versões, como "_v1", "_v2".

<br>

##### Exemplo:

   - **RPA**: `RPA_Processamento_Faturas_v1`
   - **ETL**: `ETL_Integracao_API_Clientes`
   - **AUTO**: `AUTO_Atualizacao_Dados_Usuarios_v2`
   - **WEB**: `WEB_dashboard_financeiro`
   - **DAG**: `DAG_Orquestracao_Tarefas_Agendadas`
   - **TEMPLATE**: `TEMPLATE_Workflow_Orquestracao_Airflow`




<div align="center">

## 📦 Nomenclatura de DAGS

</div>

   ```
   <Categoria>_<NomeProjeto>_<Descricao>_<Versao>
   ```

##### Onde:
- **DAG_Categoria**: RPA, ETL, AUTO, WEB, etc. (indica a categoria principal da DAG).
- **NomeProjeto**: Nome do projeto relacionado à DAG.
- **Descricao** (opcional): Descrição curta sobre o que a DAG faz.
- **Versao** (opcional): Versão da DAG, caso aplicável.

As **tags** devem ser usadas para refletir funcionalidades e responsabilidades da DAG, como **"RPA", "SQL", "HTTP".** facilitando o filtro e a organização no Apache Airflow. Também podemos usar palavras chaves que representam um projeto que possui várias dags como **"Protocolos"**

Exemplo de tags:
- **RPA**
- **Teste**
- **Email**
- **HTTP**
- **Protocolos**
- **SQL**

### Exemplo de DAG ID e tags:

- **DAG ID**: `DAG_Orquestracao_Protocolos_v1`
- **Tags**: `Protocolos, HTTP, SQL`





