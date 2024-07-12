# Projeto de Engenharia de Dados - PUCRJ
## 👋 Olá meu nome é Greter!
Este é o projeto de engenheria de dados da Pós-graduação da PUC-RJ. Usei a nuvem de GCP para criar meu workflow usando as seguintes ferramentas: Google Cloud Storage para guardar os dados, Bigquery como datawarehouse, o workbench de VertexAi para criar meu notebook e rodar minhas transformações de dados e análises.

Para rodar o projecto:
- Entra na consola de Google Cloud e cria um projeto novo ([Ver aqui como criar um projeto](https://developers.google.com/workspace/guides/create-project))
- Cria um bucket onde serão guardados os dados do projeto, para saber como criar um bucket você pode consultar o seguinte [Ver aqui como criar um bucket](https://cloud.google.com/storage/docs/discover-object-storage-console?hl=pt-br&_gl=1*1lv84jq*_up*MQ..&gclid=ea8123583b8613985a2d45c9bab12a0e&gclsrc=3p.ds).
- Descargas os arquivos .csv do repositório e sube para o buckets ([Ver aqui como subir arquivos ao bucket](https://cloud.google.com/storage/docs/discover-object-storage-console?hl=pt-br&_gl=1*1lv84jq*_up*MQ..&gclid=ea8123583b8613985a2d45c9bab12a0e&gclsrc=3p.ds#upload_an_object_into_the_bucket))
- Entra no VertexAI e cria um notebook gerenciado pelo usuário ([Ver aqui como criar no workbench do VertexAI um notebook](https://cloud.google.com/vertex-ai/docs/workbench/user-managed/create-user-managed-notebooks-instance-console-quickstart?hl=pt-br))
- Clonar o repo de Git e fazer uma cópia no Workbench de VertexAI ([Ver aqui como clonar o código do repo](https://cloud.google.com/vertex-ai/docs/workbench/instances/save-to-github?hl=pt-br#clone-a-repo))
- Modificar os nomes das seguintes variáveis para os nomes corretos que você irá usar no seu projeto:
    - bucket_name
    - file_path_tabela_hotel 
    - file_path_tabela_reserva
    - project_id 
    - dataset_id 
    - table_hotel_id 
    - table_reserva_id
- Rodar o notebook!
