Kafka设计用来处理大量实时数据：
- 具有高吞吐量处理大量的事件流。例如实时的日志聚合
- 可以优雅的处理大量数据的积压，以支持周期性的从离线系统加载数据
- 可以给消息处理器低延时的发送消息，来处理传统的消息处理系统的场景
- 支持分区，分布式，实时的处理这些消息以及派生的消息。这激发了我们创造[[分区模型]]和[[消费者模型]]
- 在给其他外部系统提供数据流的场景下，在机器故障出现时，系统需要具备容错性。