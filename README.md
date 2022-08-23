
static void Main(string[] args)
{
    string webhookUrl = "Webhook URL";
    string data = "{\"content\": \"Webhook Test Message\"}";
​
    HttpRequestService.HttpRequest(webhookUrl, data, "application/json");
}
