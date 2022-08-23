static void Main(string[] args)
{
    string webhookUrl = "Webhook URL";
    string data = "{\"content\": \"안녕하세요\"}";
​
    HttpRequestService.HttpRequest(webhookUrl, data, "application/json");
}
