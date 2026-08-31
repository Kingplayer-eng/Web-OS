<!DOCTYPE html>
<html>
  <body style="background-color: #d8b4fe; color: #473b3b; font-weight: 500">
    <div>
      <div class="desktop-icons">
        <div class="icon" onclick="openWindow('app-notes')">
          <span>📝</span>
          <p>Notes</p>
        </div>
        <div class="icon" onclick="openWindow('app-settings')">
          <span>⚙️</span>
          <p>Settings</p>
        </div>
      </div> 
    </div>

    <div id="welcome-screen">
      <h1>WELCOME TO MY OS</h1>
      <p>System status: Online and Ready!</p>
      <h2>Introduction </h2>
      <p>Hello World!</p>
      
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTsMsa9VGxbry9wgm3XhWfSHv76QUrEHRufOWEr13ZEIg&s=10" alt="Welcome Image" style="border-radius: 8px;">
      
      <br><br>
      <button onclick="startSystem()">Start System</button>
    </div>

    <script>
      function startSystem() {
        document.getElementById('welcome-screen').style.display = 'none';
      }

      function openWindow(id) {
        alert('Opening ' + id);
      }
    </script>
  </body>
</html>
