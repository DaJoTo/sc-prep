# Review Topics

* [ ] AWS
  * [x] DynamoDb - no sql low latency database (used heavily)
    * [x] tables, items & attributes
    * [x] primary keys (simple & composite)
    * [x] secondary indexes (local & global)
    * [x] capacity (RCU/WCU & billing)
    * [x] single-item actions
    * [x] multi-item actions
    * [x] streams
  * [ ] Kinesis data streams (similar to Kafka - streaming vs queueing)
    * [x] Summarised Kafka vs queues
  * [x] API Gateway (central api for services with websocks app for auth)
    * [x] Auth
    * [x] Lambda, Cognito, IAM
    * [x] API Keys (rate limiting)
    * [x] Method Requests (Primarily for Validation)
      * [x] RequestValidator -> Method (simple param/header)
      * [x] Model -> Method -> RequestValidator (request body)
    * [x] Integration Requests (data transformation)
      * [x] Proxies
        * [x] proxy resource (binding from route)
        * [x] proxy integrations (template free forwading)
        * [x] service proxy (forward to AWS service)
      * [x] VTL
      * [x] Passthrough
    * [x] Errors
      * [x] type/status/params/templates
      * [x] minor customisation (codes, details, not full VTL)
    * [x] Integration Responses
      * [x] Lambda/HTTP proxy should provide in required format
      * [x] regex matching for messages/status (depending on source)
      * [x] VTL templates
    * [x] Method Responses
      * [x] Lambda/HTTP proxy n/a again
      * [x] only has 200 OK by default
      * [x] method response must exist to use code in integration response
      * [x] allows for Models useful for SDK (strongly-type langs)
    * [ ] documentation & publishing (used?)
  * [ ] Lambda (compute power for intermittent applications)
  * [ ] CloudFormation (provisioning - infrastructure as code - used heavily)
  * [ ] SQS
  * [ ] ECS (used with EC2 to roll out Docker based services)
  * [ ] Cloudwatch - (all logging but also some metrics)
  * [ ] S3
  * [ ] Route 53 (not critical but no harm in knowing)
* [ ] NodeJS (brushup)
* [ ] Typescript (ES10/ES2019)
* [ ] Yarn (brushup + TS Compilation)
* [ ] React (TS)
* [ ] GoLang (brushup)
* [ ] Cypress
* [ ] Mocha (brushup)
* [ ] Chai (brushup)
* [ ] Sinon (brushup)
