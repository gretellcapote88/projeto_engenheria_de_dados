# Projeto de Engenharia de Dados - PUCRJ
## 👋 Olá meu nome é Greter!
Este é o projeto de engenheria de dados da Pós-graduação da PUC-RJ

Para rodar o projecto:
- Entra na consola de Google Cloud e cria um projeto novo
- Cria um bucket onde serão guardados os dados do projeto, para saber como criar um bucket você pode consultar o seguinte [link](https://cloud.google.com/storage/docs/discover-object-storage-console?hl=pt-br&_gl=1*1lv84jq*_up*MQ..&gclid=ea8123583b8613985a2d45c9bab12a0e&gclsrc=3p.ds).
- Descargas os arquivos .csv do repositório e sube para o buckets ([Ver aqui como subir arquivos ao bucket](https://cloud.google.com/storage/docs/discover-object-storage-console?hl=pt-br&_gl=1*1lv84jq*_up*MQ..&gclid=ea8123583b8613985a2d45c9bab12a0e&gclsrc=3p.ds#upload_an_object_into_the_bucket))
- Entra no VertexAI e cria um notebook gerenciado pelo usuário ([Ver aqui como criar no workbench do VertexAI um notebook](https://cloud.google.com/vertex-ai/docs/workbench/user-managed/create-user-managed-notebooks-instance-console-quickstart?hl=pt-br))
- Clonar o repo de Git e fazer uma cópia no Workbench de VertexAI ([Ver aqui como clonar o código do repo](https://cloud.google.com/vertex-ai/docs/workbench/instances/save-to-github?hl=pt-br#clone-a-repo))
- Modificar os nomes das seguintes variáveis para os nomes corretos que você irá usar no seu projeto:
    - bucket_name = 'dadosprojetopucrj'
    - file_path_tabela_hotel = 'Yerevan-Hotels.csv'
    - file_path_tabela_reserva = 'reservas.csv'
    - project_id = PROJECT_ID
    - dataset_id = 'datasethotels'
    - table_hotel_id = 'hotels'
    - table_reserva_id = 'reserva'
