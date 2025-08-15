# BlackDex-fch
fanchunhui 
using var client = new HttpClient();
var content = new StringContent("{'key':'value'}", Encoding.UTF8, "application/json");
var response = await client.PostAsync("https://api.example.com", content);
var result = await response.Content.ReadAsStringAsync();
