
Got it! Here's a clean, professional documentation based on the steps you've provided:

---

# Minecraft Server Setup and Connection Guide

## **<span style="color:rgb(128, 255, 82)">1.</span> <span style="color:rgb(128, 255, 82)">Setting Up Your Own Minecraft Server</span>**

### **Step 1: Download the Server**
- Visit [Forge Download Page](https://files.minecraftforge.net/net/minecraftforge/forge/).
- Select the version of the server you need (for Fabric or OptiFine, ensure you download the correct version).
- ![[Pasted image 20250427110107.png]]
  
### **Step 2: Install the Server**
- Once the file is downloaded, run the installer and choose the **Server** option.
- Select a separate folder (other than the default Minecraft or TLauncher folder) to install the server. This helps keep the server files organized.
- ![[Pasted image 20250427110229.png]]

### **Step 3: Download Java**
- Download the latest version of Java (currently Java 18) from Oracle’s official site: [Java Downloads](https://www.oracle.com/in/java/technologies/downloads/#jdk24-windows).
- ![[Pasted image 20250427110304.png]]

### **Step 4: Run the Server**
- Go to the folder where you installed the server.
- Open the `run.bat` file. This will start the installation of the required server resources.
- ![[Pasted image 20250427110455.png]]

### **Step 5: Accept the EULA**
- After the server finishes setting up, open the `eula.txt` file.
- Change `eula=false` to `eula=true`. This step is similar to accepting the terms during software installations.
- ![[Pasted image 20250427110515.png]]

### **Step 6: Add Mods (Optional)**
- If you want to add mods to your server, place them in the `mods` folder located in the server directory.
- ![[Pasted image 20250427110548.png]]

### **Step 7: Start the Server**
- Run the `run.bat` file again to start the server.
- The server should now be up and running.

### **Step 8: Join Your Server**
- Open Minecraft (Forge-OptiFine) and ensure you are using the same version (e.g., 1.20.1).
- ![[Pasted image 20250427110650.png]]
- In the **Multiplayer** section, enter `127.0.0.1` as the server address and join the game.
- ![[Pasted image 20250427110749.png]]

---

## **<span style="color:rgb(128, 255, 82)">2. Allowing Friends to Join Your Server</span>**

### **Step 1: Edit Server Properties**
- Navigate to the server folder and open the `server.properties` file.
- ![[Pasted image 20250427111021.png]]
- Locate the line `online-mode=true` and change it to `online-mode=false`.
- ![[Pasted image 20250427111048.png]]
  - This allows cracked players (like those using TLauncher) to join your server.

### **Step 2: Create an Account on PlayIt.gg**
- Go to [PlayIt.gg](https://playit.gg/), and create an account or log in if you already have one.

### **Step 3: Download PlayIt**
- Download `playit-windows-x86_64-signed.exe` from PlayIt.gg and place it in the same folder where your Minecraft server is located to keep things organized.
- ![[Pasted image 20250427111134.png]]
- ![[Pasted image 20250427111148.png]]

### **Step 4: Run PlayIt**
- Open PlayIt and follow the four setup steps on the website.
- ![[Pasted image 20250427111222.png]]

### **Step 5: Create a Tunnel**
- Click on **Create Tunnel**.
- ![[Pasted image 20250427111239.png]]
- Set the **Tunnel Type** to **Minecraft Java** and leave the rest of the settings as default.
- ![[Pasted image 20250427111312.png]]
- Press **Add Tunnel**.

### **Step 6: Share the Server IP**
- Once the tunnel is created, you will see an IP address at the top of the PlayIt window.
  any one of them both copy it 
- ![[Pasted image 20250427111408.png]]
- Copy this IP address and share it with the friend you want to play with.

### **Step 7: Friend Joins the Server**
- Your friend needs to download **TLauncher** and ensure they have the same **Forge-OptiFine version** (e.g., 1.20.1) installed.
- If you added mods to your server, your friend should also place the same mods in their TLauncher mods folder.
- In Minecraft, go to **Multiplayer** >  and paste the IP you shared.
- ![[Pasted image 20250427111539.png]]
- Your friend should now be able to join the server.

---

## **<span style="color:rgb(128, 255, 82)">3. Playing a Single Player World with Your Friend</span>**

### **Step 1: Ensure Same Mods**
- Both the host and the friend should have the same mods installed in their TLauncher folder, and both should use the same version (e.g., Forge-OptiFine 1.20.1).

### **Step 2: Host Starts the Single Player World**
- The host should start their single-player world in Minecraft.
- Once the world is loaded, press **Esc**, go to **Open to LAN**, and set the LAN port to `25565`.
- ![[Pasted image 20250427111821.png]]
- ![[Pasted image 20250427111844.png]]

### **Step 3: Set Up PlayIt for Single Player**
- The host should open PlayIt and follow the same steps to create a Minecraft Java tunnel as described in the previous section.

### **Step 4: Friend Joins the World**
- The host will provide the generated PlayIt IP to their friend.
- The friend should launch **TLauncher**, ensure they are using the same version and mods, and go to **Multiplayer** > **Direct Connection**.
- ![[Pasted image 20250427111921.png]]
- The friend enters the host's IP and clicks **Join Server**.
- ![[Pasted image 20250427111942.png]]

### **Step 5: Enjoy Playing Together!**
- Your friend should now be in your single-player world and you can both enjoy the game together.

---

### **Conclusion**

This guide has walked you through setting up a Minecraft server on your own machine, allowing friends to join, and even playing together using a single-player world. By following these steps, you can easily create a multiplayer experience on your local machine and invite friends to play with you!

Happy gaming! 🎮