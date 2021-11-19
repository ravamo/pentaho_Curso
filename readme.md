# Recursos y Ejemplos del curso de pentaho para Canarias

En este repositorio vamos a encontrar los recuros y los ejemplos 
Vamos a tener dos carpetas :
* etl donde estan los ejercicos de kettle o pdi. 
* mondrian, recursos para la creacion de cubos.


## etl
├── Chapter01 (primera transformacion simple)
│   ├── fisrt_transformation.ktr
│   ├── hello.ktr
│   └── MiPrimeraETL.ktr
├── Chapter02 (transformacion simple con parametros y varibles)
│   ├── files
│   │   └── Zipssortedbycitystate.csv
│   ├── simple_transformation.ktr
│   ├── simple_transformation_with_named_parameters.ktr
│   └── simple_transformation_with_variables.ktr
├── Chapter03 (transformacion para añadir informacion)
│   ├── combining_datasources.ktr
│   ├── files -> ../Chapter04/files/
│   ├── getting_data_bonus.ktr
│   ├── getting_data_from_a_database.ktr
│   └── reading_plain_files.ktr
├── Chapter04 (añadir informaciòn el flujo como nuevos campos , filtros de información y ordenación)
│   ├── adding_new_fields_II.ktr
│   ├── adding_new_fields.ktr
│   ├── aggregating_data_II.ktr
│   ├── aggregating_data.ktr
│   ├── files
│   │   ├── amsterdam
│   │   │   ├── data.sql
│   │   │   ├── tomslee_airbnb_amsterdam_0025_2014-05-24.csv
│   │   │   ├── tomslee_airbnb_amsterdam_0048_2014-08-30.csv
│   │   │   ├── tomslee_airbnb_amsterdam_0080_2015-01-19.csv
│   │   │   ├── tomslee_airbnb_amsterdam_0106_2015-03-17.csv
│   │   │   ├── tomslee_airbnb_amsterdam_0244_2015-12-16.csv
│   │   │   ├── tomslee_airbnb_amsterdam_0443_2016-05-31.csv
│   │   │   ├── tomslee_airbnb_amsterdam_0509_2016-08-04.csv
│   │   │   ├── tomslee_airbnb_amsterdam_0698_2016-12-15.csv
│   │   │   ├── tomslee_airbnb_amsterdam_0754_2016-12-27.csv
│   │   │   ├── tomslee_airbnb_amsterdam_0807_2017-01-18.csv
│   │   │   ├── tomslee_airbnb_amsterdam_0890_2017-02-17.csv
│   │   │   ├── tomslee_airbnb_amsterdam_0998_2017-03-27.csv
│   │   │   ├── tomslee_airbnb_amsterdam_1144_2017-04-24.csv
│   │   │   ├── tomslee_airbnb_amsterdam_1224_2017-05-12.csv
│   │   │   ├── tomslee_airbnb_amsterdam_1348_2017-06-15.csv
│   │   │   └── tomslee_airbnb_amsterdam_1476_2017-07-22.csv
│   │   ├── cost_of_living_europe.txt
│   │   ├── europe.txt
│   │   ├── injuries.txt
│   │   └── recommended_food.txt
│   ├── filtering_III.ktr
│   ├── filtering_II.ktr
│   ├── filtering.ktr
│   ├── looking_up_db.ktr
│   ├── looking_up.ktr
│   ├── sorting_data_II.ktr
│   ├── sorting_data.ktr
│   ├── splitting_fields_II.ktr
│   └── splitting_fields.ktr
├── Chapter05 (creación de una datamart siemple con sus dimensiones asi como con su tabla de hechos)
│   ├── dim_bodyparts.ktr
│   ├── dim_persons.ktr
│   ├── dim_time.ktr
│   ├── fact_injuries.ktr
│   ├── files
│   │   ├── more_injuries.txt
│   │   └── more_injuries_with_comments.txt
│   ├── inserting_into_table.ktr
│   ├── listing_places.ktr
│   ├── scripts
│   │   └── datamart.sql
│   └── updating_table.ktr
├── Chapter06 (creación de una datamart siemple con sus dimensiones asi como con su tabla de hechos con tranformaciones mas complejas)
│   ├── load_datamart.kjb
│   ├── load_dimensions.kjb
│   ├── load_fact_injuries.kjb
│   ├── sample_job.kjb
│   ├── sample_job_run_upon_conditions.kjb
│   ├── sending_emails.kjb
│   └── transformations
│       ├── dim_bodyparts.ktr
│       ├── dim_persons.ktr
│       ├── fact_injuries.ktr
│       └── set_maxdate.ktr
├── Chapter07 (tranformaciones con mapping y meteda injection para generalizar procesos)
│   ├── mapping
│   │   ├── Mapping - simple mapping.ktr
│   │   └── Mapping - use simple mapping.ktr
│   ├── metadata-injection-example
│   │   ├── data
│   │   │   └── in
│   │   │       ├── supplier1
│   │   │       │   └── data_format_a.xlsx
│   │   │       └── supplier2
│   │   │           └── data_format_b.xlsx
│   │   ├── metadata
│   │   │   ├── metadata_suppliers.xlsx
│   │   │   └── metadata_target.xlsx
│   │   ├── readme.txt
│   │   └── transformations
│   │       ├── 01_process_all_suppliers.ktr
│   │       ├── 02_process_supplier.ktr
│   │       └── 03_process_supplier_file.ktr
│   └── meta-inject
│       ├── read_csv_file.ktr
│       └── use_metainject_step.ktr
├── Chapter08 (Tranformaciones para la carga de datos en base de datos)
│   ├── data
│   │   ├── compras.csv
│   │   ├── produtos.csv
│   │   ├── schema.postgres.sql
│   │   ├── tempo.csv
│   │   ├── vendas.csv
│   │   └── vendedores.csv
│   └── load_data_into_db.ktr
├── Extra
│   └── calculadora.ktr
└── files (ejemplos de varias transformaciones variadas)
    ├── changelog.txt
    ├── closure_input.txt
    ├── coded-data.txt
    ├── customers-100.txt
    ├── customers-100-with-errors.txt
    ├── Denormaliser - 2 series of key-value pairs.txt
    ├── example.xml
    ├── Excel and Row Normaliser - sample data.xls
    ├── GetXMLData - test 1 - simple functionality test.xml
    ├── GetXMLData - test 2 - missing elements.xml
    ├── GetXMLData - test 3 - error handling.xml
    ├── group-denormalize.txt
    ├── hl7_message_01.txt
    ├── hl7_message_02.txt
    ├── hl7_message_wrongCRLF.txt
    ├── hl7_message_ZBE_sample.txt
    ├── Invoice_Statements2.prpt
    ├── Invoice_Statements.prpt
    ├── Invoice.yaml
    ├── item_detail.xml
    ├── job-mail.png
    ├── JSON - read nested fields.js
    ├── jsonfile.js
    ├── merge1_dups.txt
    ├── merge1.txt
    ├── merge2_dups.txt
    ├── merge2.txt
    ├── orders.edi
    ├── Pentaho Translator.png
    ├── process and move files.png
    ├── round_half_even.txt
    ├── round_half_up.txt
    ├── sales_data.csv
    ├── sample-export.xml
    ├── sample-file.ods
    ├── sample-file.xls
    ├── sample-file.xlsx
    ├── Semicolon delimited.txt
    ├── shelltest.cmd
    ├── Spoon Metadata Search.png
    ├── Switch-Case - test data for contains mode.txt
    ├── Territories.txt
    ├── test-job.kjb
    ├── test_xml_file.xml
    ├── Textfile input - fixed length sample data.txt
    ├── Unique Rows by Hashset - basic example.ktr
    ├── WebServicesMovieListingAsHTTP_SOAPRequest.xml
    ├── XBase - dBase sample data.dbf
    ├── XML - flat.xml
    ├── XML Add - creating multi level XML files.xls
    ├── XML file with substitutes.xml
    ├── XML Input Stream (StAX) Test 1 - Basic Tests.xml
    ├── XML Input Stream (StAX) Test 2 - Element Blocks.xml
    ├── XML Input Stream (StAX) Test 3 - Attribute Groups.xml
    ├── XML Input Stream (StAX) Test 4 - Hierarchies.xml
    ├── XML Input Stream (StAX) Test 6 - Namespaces.xml
    ├── XMLOrders.xml
    └── Zipssortedbycitystate.csv
# Mondrian
ejemplo de cubo de mondrian y documentacion
mondrian/ 
├── sample.mondrian.xml
├── Sesion4-OLAP.pdf
└── sport.xml
