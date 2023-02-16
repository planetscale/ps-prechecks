PlanetScale Migration Questionnaire
===================================
 
## Architectural Detail - Production

For your current environment, please describe the following details. Feel free to add as much detail as you believe is relevant. Screenshots or diagrams are welcome for added clarity.

#### Total number of database instances and their roles
> For example: 
>> _Main application - 1 primary, 4 replicas (serving reads), 1 replica (serving OLAP queries)_
>> _Secondary application - 1 primary, 2 replicas_

```
Your Answer Here
```

#### Instance sizes and types
> For example:
>>  _r5.4xlarge for all instances_

```
Your Answer Here
```

#### Disk / IOPS allocations
> For example:
>>  _Persistent SSD's, 25000 provisioned IOPS_

```
Your Answer Here
```

#### Cloud Regions / Datacenter locations
> For example:
>>  _Deployed in AWS us-east-1_

```
Your Answer Here
```

#### Application & Database Stack
> Describe your primary development language, frameworks, database connectors/ORM's, as well as relevant caching layers.

```
Your Answer Here
```

#### Downstream Tooling
> For example:
>> _We use Airbyte to capture some of our table's row updates and stream all change events into Snowflake._

```
Your Answer Here
```

## Performance Profile - Production

#### Observed traffic patterns and Peak QPS vs Avg QPS
> For example:
>>  _Following US business hours, especially large peaks during pre-planned events. Averaging around 10k qps during normal days, jumping to 50k during events. See included screenshots._

```
Your Answer Here
```

#### Observed resource utilization
> For example:
>> _CPU/Memory/IO usage during average and peak traffic times._

```
Your Answer Here
```

## Architectural Detail - Development / Staging / QA

#### Infrastructure requirements
> How does your Staging environment compare to Production? Consider hardware resources, as well as data size.

```
Your Answer Here
```

#### Development Pipeline Automation
> How does your development team collaborate and what infrastructure is in place to bring code into production?

```
Your Answer Here
```

## Team & Project

#### Organization Composition & Size
> Consider every role that interacts directly with the database environment, whether as a developer, analyst or as an infrastructure engineer.

```
Your Answer Here
```

#### Desired Outcome
> What is your reason for considering PlanetScale? What business goal could it help you accomplish? How would you measure success? What would happen if you didn't find a solution?

```
Your Answer Here
```

#### Timeline
> When do you need to complete this by? Are there any specific project timelines we should be aware of?

```
Your Answer Here
```

#### Capacity for Change
> What are the main challenges to consider when approaching a potentially large change in the environment? Consider elements like legacy code, the need to minimize downtime, but also whether you are capable of allocating dedicated time for the transition.

```
Your Answer Here
```
