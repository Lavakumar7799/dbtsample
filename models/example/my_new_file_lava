{{config(
    materialized="table",
    schema="suresh_myschema_aws",
    description='lava_table_customer1'
)}}
select * from suresh_aws_loading.suresh_myschema_aws.lava_table_customer1
where C_NATIONKEY in (14,15)