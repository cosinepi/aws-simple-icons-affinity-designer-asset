# AWS Simple Icons Affinity Designer Asset
An asset file for Affinity Designer that contains Amazon AWS simple icons from https://aws.amazon.com/architecture/icons/

## Download
For the impatient:
1. Download [the asset](https://github.com/cosinepi/aws-simple-icons-affinity-designer-asset/blob/master/Asset/AWS_Simple_Icons_EPS-SVG_v16.2.22.afassets).
2. Open Affinity Designer, View -> Studio -> Assets (if not checked).
3. Use Import Assets... to import your downloaded file.

## Production Notes

Aside from a little scripting, this asset file was essentially created by hand.

I wrote a simple Python script to transform the asset file names to exclude repetitive parts. For instance, a file named `On-Demand-Workforce_AmazonMechanicalTurk_assignmenttask.svg` inside the `On-Demand Workforce` folder is simply renamed to `AmazonMechanicalTurk_assignmenttask.svg`, and added to the `On-Demand Workforce` subcategory of the asset. The script also deletes the `.png` and `.eps` versions of the same graphics. The `.svg` versions are very well supported by Affinity Designer.

Then comes the laborious work. I manually opened each file in Affinity Designer, grouped the graphics, put in the name to the group, and added the graphics to the subcategory of the asset, corresponding to the folder where the original `.svg` is in.  The renaming is necessary so that next time you drag the graphics out of the asset into your drawing, it is properly named.

I didn't manage to automate the process because Affinity Designer currently does not support automation very well, though this is something on their road map. If you have better idea to automate the whole process, 

## Tips

1. In each subcategory, the graphics are strictly sorted by the original filename of the graphics, including the `.svg` extension. That's why you'll see, for instance, that `AmazonDynamoDB_table` comes before `AmazonDynamoDB`, because `AmazonDynamoDB_table.svg` comes before `AmazonDynamoDB.svg`. 
2. In case you cannot find a graphics you need, try the search box inside the asset panel. That works very well.

## List of Assets

- Analytics
    - AWSDataPipeline
    - AmazonEMR
    - AmazonEMR_EMRengine
    - AmazonEMR_EMRengineMapRM3
    - AmazonEMR_EMRengineMapRM5
    - AmazonEMR_EMRengineMapRM7
    - AmazonEMR_HDFScluster
    - AmazonEMR_cluster
    - AmazonElasticsearchService
    - AmazonKinesis
    - AmazonKinesis_AmazonKinesis-enabledapp
    - AmazonKinesis_AmazonKinesisAnalytics
    - AmazonKinesis_AmazonKinesisFirehose
    - AmazonKinesis_AmazonKinesisStreams
    - AmazonMachineLearning
    - AmazonQuickSight
- Application Services
    - AmazonAPIGateway
    - AmazonAppStream
    - AmazonCloudSearch
    - AmazonCloudSearch_SDFmetadata
    - AmazonElasticTranscoder
    - AmazonSES
    - AmazonSES_email
    - AmazonSQS
    - AmazonSQS_message
    - AmazonSQS_queue
    - AmazonSWF
    - AmazonSWF_decider
    - AmazonSWF_worker
- Compute
    - AWSElasticBeanstalk
    - AWSElasticBeanstalk_application
    - AWSElasticBeanstalk_deployment
    - AWSLambda
    - AmazonEC2
    - AmazonEC2_AMI
    - AmazonEC2_AutoScaling
    - AmazonEC2_DBoninstance
    - AmazonEC2_ElasticIP
    - AmazonEC2_Spotfleet
    - AmazonEC2_Spotinstance
    - AmazonEC2_instance
    - AmazonEC2_instances
    - AmazonEC2_instancewithCloudWatch
    - AmazonEC2_optimizedinstance
    - AmazonECR
    - AmazonECS
    - ElasticLoadBalancing
- Database
    - AWSDatabaseMigrationService
    - AmazonDynamoDB
    - AmazonDynamoDB_attribute
    - AmazonDynamoDB_attributes
    - AmazonDynamoDB_globalsecondaryindex
    - AmazonDynamoDB_item
    - AmazonDynamoDB_items
    - AmazonDynamoDB_table
    - AmazonElasticCache
    - AmazonElasticCache_Memcached
    - AmazonElasticCache_Redis
    - AmazonElasticCache_cachenode
    - AmazonRDS
    - AmazonRDS_MSSQLinstance
    - AmazonRDS_MSSQLinstancealternate
    - AmazonRDS_MySQLDBinstance
    - AmazonRDS_MySQLinstancealternate
    - AmazonRDS_OracleDBinstance
    - AmazonRDS_OracleDBinstancealternate
    - AmazonRDS_PIOP
    - AmazonRDS_PostgreSQLinstance
    - AmazonRDS_RDSDBinstance
    - AmazonRDS_RDSDBinstancereadreplica
    - AmazonRDS_RDSDBinstancestandby
    - AmazonRDS_SQLmaster
    - AmazonRDS_SQLslave
    - AmazonRedshift
    - AmazonRedshift_densecomputenode
    - AmazonRedshift_densestoragenode
- Developer Tools
    - AWSCodeCommit
    - AWSCodeDeploy
    - AWSCodePipeline
- Enterprise Applications
    - AmazonWorkDocs
    - AmazonWorkMail
    - AmazonWorkSpaces
- Game Development
    - AmazonGameLift
- General
    - AWSManagementConsole
    - AWScloud
    - Internet
    - client
    - corporatedatacenter
    - disk
    - forums
    - genericdatabase
    - mobileclient
    - multimedia
    - tapestorage
    - traditionalserver
    - user
    - users
    - virtualprivatecloud
- Internet of Things
    - AWSIoT
    - AWSIoT_HTTP2protocol
    - AWSIoT_HTTPprotocol
    - AWSIoT_MQTTprotocol
    - AWSIoT_action
    - AWSIoT_actuator
    - AWSIoT_certificate
    - AWSIoT_desiredstate
    - AWSIoT_hardwareboard
    - AWSIoT_policy
    - AWSIoT_reportedstate
    - AWSIoT_rule
    - AWSIoT_sensor
    - AWSIoT_servo
    - AWSIoT_shadow
    - AWSIoT_simulator
    - AWSIoT_thingbank
    - AWSIoT_thingbicycle
    - AWSIoT_thingcamera
    - AWSIoT_thingcar
    - AWSIoT_thingcart
    - AWSIoT_thingcoffeepot
    - AWSIoT_thingdoorlock
    - AWSIoT_thingfactory
    - AWSIoT_thinggeneric
    - AWSIoT_thinghouse
    - AWSIoT_thinglightbulb
    - AWSIoT_thingmedicalemergency
    - AWSIoT_thingpoliceemergency
    - AWSIoT_thingthermostat
    - AWSIoT_thingtravel
    - AWSIoT_thingutility
    - AWSIoT_thingwindfarm
    - AWSIoT_topic
- Management Tools
    - AWSCloudFormation
    - AWSCloudFormation_stack
    - AWSCloudFormation_template
    - AWSCloudTrail
    - AWSConfig
    - AWSOpsWorks
    - AWSOpsWorks_apps
    - AWSOpsWorks_deployments
    - AWSOpsWorks_instances
    - AWSOpsWorks_layers
    - AWSOpsWorks_monitoring
    - AWSOpsWorks_permissions
    - AWSOpsWorks_resources
    - AWSOpsWorks_stack
    - AWSServiceCatalog
    - AWSTrustedAdvisor
    - AmazonCloudWatch
    - AmazonCloudWatch_alarm
- Mobile Services
    - AWSDeviceFarm
    - AWSMobileHub
    - AmazonCognito
    - AmazonMobileAnalytics
    - AmazonSNS
    - AmazonSNS_HTTPnotification
    - AmazonSNS_emailnotification
    - AmazonSNS_topic
- Networking
    - AWSDirectConnect
    - AmazonRoute53
    - AmazonRoute53_AmazonRoute53
    - AmazonRoute53_hostedzone
    - AmazonRoute53_routetable
    - AmazonVPC
    - AmazonVPC_VPCNATgateway
    - AmazonVPC_VPCpeering
    - AmazonVPC_VPNconnection
    - AmazonVPC_VPNgateway
    - AmazonVPC_customergateway
    - AmazonVPC_endpoints
    - AmazonVPC_flowlogs
    - AmazonVPC_internetgateway
    - AmazonVPC_router
- On-Demand Workforce
    - AmazonMechanicalTurk
    - AmazonMechanicalTurk_assignmenttask
    - AmazonMechanicalTurk_humanintelligencetasks
    - AmazonMechanicalTurk_requester
    - AmazonMechanicalTurk_workers
- SDK
    - AWSCLI
    - AWSToolkitForEclipse
    - AWSToolkitForVisualStudio
    - AWSToolsForWindowsPowerShell
    - Android
    - Java
    - JavaScript
    - Net
    - Nodejs
    - PHP
    - Python
    - Ruby
    - Xamarin
    - iOS
- Security & Identity
    - ACM
    - ACM_certificate-manager
    - AWSCloudHSM
    - AWSDirectoryService
    - AWSIAM
    - AWSIAM_AWSSTS-2
    - AWSIAM_AWSSTS
    - AWSIAM_MFAtoken
    - AWSIAM_addon
    - AWSIAM_dataencryptionkey
    - AWSIAM_encrypteddata
    - AWSIAM_long-termsecuritycredential
    - AWSIAM_permissions
    - AWSIAM_role
    - AWSIAM_temporarysecuritycredential
    - AWSKMS
    - AWSWAF
    - AmazonInspector
- Storage & Content Delivery
    - AWSImportExportSnowball
    - AWSImportExportSnowball_importexport
    - AWSStorageGateway
    - AWSStorageGateway_cachedvolume
    - AWSStorageGateway_non-cachedvolume
    - AWSStorageGateway_virtualtapelibrary
    - AmazonCloudFront
    - AmazonCloudFront_downloaddistribution
    - AmazonCloudFront_edgelocation
    - AmazonCloudFront_streamingdistribution
    - AmazonEBS
    - AmazonEFS
    - AmazonGlacier
    - AmazonGlacier_archive
    - AmazonGlacier_vault
    - AmazonS3
    - AmazonS3_bucket
    - AmazonS3_bucketwithobjects
    - AmazonS3_object
    - snapshot
    - volume

## License

This is an asset provided by good will. Find more on license info on https://aws.amazon.com/architecture/icons/

## Feedback

I'd be happy to know if it is possible to fully automate the process of creating the asset for Affinity Designer. If you have a good idea, please let me know.

I created this asset file when I was watching the 2016 US president election live stream. There is no promise of no mistakes made. Please let me know if you find any.
