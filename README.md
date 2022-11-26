Quickstart code from Microsoft Azure documentation to read messages from Service Bus queue, and help diagnose connection issues.

Source: https://learn.microsoft.com/en-us/azure/service-bus-messaging/service-bus-dotnet-get-started-with-queues?tabs=passwordless

Transport Type can be changed line #23.

```powershell
$env:NAMESPACE_CONNECTION_STRING = "Endpoint=sb://xxx.servicebus.windows.net/;SharedAccessKeyName=xxx;SharedAccessKey=xxx"
$env:QUEUE_NAME = "xxx"

dotnet run
```


