Minecraft-Mods
==============

Coding 
IMPORTANT Computer craft mod
//Code
redstone.setOutput("left", true)
correctpassword = "HetIsNiels"
write("What is the password?   ")
 
password = read()
 
if password == (correctpassword) then
 write("Password correct!")
 redstone.setOutput("back", true)
 sleep(5)
 os.shutdown()
elseif password == "edit" then
 write("Starting computer modus...")
 write("")
 redstone.setOutput("left", false)
else
 write("Incorrect password! Shuting down the computer...")
 sleep(5)
 os.shutdown()
end
