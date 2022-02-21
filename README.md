
node app.js

# API End Points

## System Settings

### DATA CONNECTIONS APIs

- Get All Data Source Records:

    **GET** -> http://rm-dataflow-api.pentaknot.com/dataflow/system-settings/data/source

- Get Source Data Record By Id:
    
    **GET** -> http://rm-dataflow-api.pentaknot.com/dataflow/system-settings/data/source/<:connectionId>

- Add Source Data Record:
    
    **POST** -> http://rm-dataflow-api.pentaknot.com/dataflow/system-settings/data/source

- Update Source Data Record
    
    **PUT** -> http://rm-dataflow-api.pentaknot.com/dataflow/system-settings/data/source/<:connectionId>

- Delete Source Data Record
    
    **Delete** -> http://rm-dataflow-api.pentaknot.com/dataflow/system-settings/data/source/<:connectionId>

- Get All Data Source Types Records

    **GET** -> http://rm-dataflow-api.pentaknot.com/dataflow/system-settings/data/source-type

- Get All Target Data Connection Records
    
    **GET** -> http://rm-dataflow-api.pentaknot.com/dataflow/system-settings/data/target

- Get target Data Connection Record By Id
    
    **GET** -> http://rm-dataflow-api.pentaknot.com/dataflow/system-settings/data/target/<:connectionId>

- Add target Data Connection Connection Record

    **POST** -> http://rm-dataflow-api.pentaknot.com/dataflow/system-settings/data/target

- Update target Data Connection Record

    **PUT** -> http://rm-dataflow-api.pentaknot.com/dataflow/system-settings/data/target/<:connectionId>

- Delete Data Connection Record
    
    **Delete** -> http://rm-dataflow-api.pentaknot.com/dataflow/system-settings/data/target/<:connectionId>

### CLUSTER SETUP APIs

- Get All Industry Types:

    **GET** -> http://rm-dataflow-api.pentaknot.com/dataflow/system-settings/cluster/industry-types

- Get All Columns:
    
    **GET** -> http://rm-dataflow-api.pentaknot.com/dataflow/system-settings/cluster/columns

- Get Cluster List By Industry Id:

    **GET** -> http://rm-dataflow-api.pentaknot.com/dataflow/system-settings/cluster/<:industryId>
    
    E.g.: http://rm-dataflow-api.pentaknot.com/dataflow/system-settings/cluster/1

- Add New Cluster:

    **POST** -> http://rm-dataflow-api.pentaknot.com/dataflow/system-settings/cluster/

    POST BODY JSON Structure -> http://rm-dataflow-api.pentaknot.com/dataflow/system-settings/cluster/add-new-cluster